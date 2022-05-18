<script>
	import { setContext } from 'svelte';
    import Test from '../Test.svelte';

    setContext('test', 'example')
</script>

<Test />