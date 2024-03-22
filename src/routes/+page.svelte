<script>
    import {client} from "$lib/elastic-config";
    import {onMount} from "svelte";

    onMount(async ()=>{
        const clientData = await client.info()
        console.log(clientData)
    })

</script>


<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
