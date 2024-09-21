<script>
    import Header from "../lib/components/Header.svelte";
    import Footer from "../lib/components/Footer.svelte";
</script>
<html lang="en">
    <body>
        <Header />
        <slot />
        <Footer />
    </body>
</html>



<style>
    * {
        margin: 0;
        padding: 0;
        color: white;
        background-color: black;
        background: linear-gradient(to right, #d57826, #febf7b);

    }
    html {
        height: 100vh;
    }

    body {
        height: 100%;
        width: 100%;
    }
</style>