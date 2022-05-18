<script>
	import { getContext } from 'svelte';

    function test() {
        console.log(getContext('test'))
        return getContext('test')
    }
</script>

<!-- href is undefined, but the text is the correct value -->
<a href={test()}>{test()}</a>