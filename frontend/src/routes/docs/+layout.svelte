<script>
import Footer from "../../lib/components/footer.svelte";
import Header from "../../lib/components/header.svelte";
import Sidebar from "../../lib/components/sidebar.svelte";
</script>

<Header/>
<main>
<Sidebar class="sidebar"/>
<div class="content">
    <slot></slot>
</div>
</main>
<Footer/>

<style>

    main{
        display: grid;
        grid-template-columns: 1fr 4fr;
    }

</style>