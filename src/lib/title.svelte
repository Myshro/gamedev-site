<script>

</script>

<div class="title">
    <div class="logo"> 
        <img src="/controller.svg" alt="Game controller">
        <a href="./" class="logo-text">OHS GAMEDEV</a>
    </div>
    <div class="hrefs">
        <a class="members" href="/members">Members</a>
        <a class="socials" href="/socials">Socials</a>
    </div>
</div>

<style>
    * {
        color: #ede9ef;
        white-space: nowrap
    }

    .hrefs, .logo {
        display: flex;
        align-items: center;
        gap: 10px;   
    }

    /* @media screen and (max-width: 600px) {
        .title h1 {
            color: red;
        }
    } */

    img {
        filter: invert(97%) sepia(4%) saturate(203%) hue-rotate(235deg) brightness(97%) contrast(95%);
    }

    .members,.socials {
        font-size: 1.5rem;
    }

    .socials {
        margin-left: 40px;
    }

    .hrefs 
    a:link { text-decoration: none; }
    a:visited { text-decoration: none; }
    a:hover { text-decoration: none; }
    a:active { text-decoration: none; }
    a {
        color: #ede9ef;
    }
    .title {
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 20px 10vw;
        min-width: 600px;
        font-size: 1em;
        width: 100%;
        background-color: transparent;
        top: 0;
        z-index: 10;
    }

    .title img {
        display: inline-block;
        width: 50px;
        height: 50px;
        color: aliceblue;
    }

    .logo-text {
        font-size: 2.5rem;
        margin-left: 20px;
        text-decoration: none;
    }
</style>