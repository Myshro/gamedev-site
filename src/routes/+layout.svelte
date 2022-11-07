<script>
    import Title from '$lib/title.svelte'
</script>

<header>
    <Title />
</header>
<main>
    <slot></slot>
</main>
<footer>
    <!-- <p>Oakton High School</p> -->
</footer>

<style>
    * {
        font-weight: 400;
    }

    header {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #191a1b;
        font-size: 1em;
    }

    footer {
        text-align: center;
    }
</style>