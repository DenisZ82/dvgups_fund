<script>
    import Header from "./Header.svelte";
    import Main from "./Main.svelte";
    import Footer from "./Footer.svelte";
</script>


<Header />
<Main />
<Footer />


<style lang="postcss">
    @reference "tailwindcss";

    :global(html) {
        background-color: #F7F7F7;
    }

    :global(body) {
        font-family: 'Inter', sans-serif;
        color: #181818;
        line-height: 1.6;
        font-size: 16px;
    }

</style>