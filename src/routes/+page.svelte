<script>
</script> 

<section class="hero">
    
    
    <img id="unity" src="./unitycrop.png" alt="Unity logo">
    <div class="hero-text rotating">
        <h1>Oakton's only <span class="grad">gamedev</span> club</h1>
        <h3>Come join us in making things!</h3>
        <div class="jump-buttons">
            <button>About</button>
            <button>Tech</button>
            <button>Games</button>
        </div>
    </div>
</section>

<section class="about">
    <div class="custom-shape-divider-top-1667688268">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
        </svg>
    </div>
    <div class="quote">
        "Nobody in this industry knows what they’re doing, we just have a gut assumption."
        <span class="quoter">-Cliff Bleszinski</span>
    </div>
    <hr style="width: 750px; height: 0px;">
    <div class="about-question">
        <h2>Why join?</h2>
        <ul>
            <li>- You get to learn Unity hands on</li>
            <li>- Plenty of officer positions and activities for colleges</li>
            <li>- To have fun!</li>
        </ul>
    </div>
    <div class="about-question">
        <h2 class="about-question">What do we do?</h2>
        <ul>
            <li>- Participate in <span class="grad">game jams</span> together</li>
            <li>- Work on projects with people specializing in all sorts of disciplines</li>
            <li>- Learn more about Unity and how to make fun stuff</li>
        </ul>
    </div>
    <p>We meet on Wednesdays in Mr. Hatchl's room (#1931) in the art hall!</p>
</section>
<section class="technology">
    <div class="custom-shape-divider-top-1667751780">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
        </svg>
    </div>
    <div class="container">
        <div class="language card">
            <img src="./angle-brackets.svg" alt="Angle brackets">
            <div class="contents">
                <h1>Language</h1>
                <p>C#</p>
            </div>
        </div>
        <div class="engine card">
            <img src="./small-cube.svg" alt="Angle brackets">
            <div class="contents">
                <h1>Engine</h1>
                <p>Unity</p>
            </div>
        </div>
        <div class="tools card">
            <img src="wrench.svg" alt="Angle brackets">
            <div class="contents">
                <h1>Tools</h1>
                <p>GitHub</p>
                <p>Trello</p>
                <p>Piskel</p>
            </div>
        </div>
    </div>
</section>
<!-- <section class="games">
    <div class="container">
        <div class="upper">
            <div class="thumbnail">
                <img width="250" height="250" src="./favicon.png">
            </div>
            <div class="thumbnail">
                <img width="250" height="250" src="./favicon.png">
            </div>
        </div>
        <div class="downer">
            <div class="thumbnail">
                <img width="250" height="250" src="./favicon.png">
            </div>
            <div class="thumbnail">
                <img width="250" height="250" src="./favicon.png">
            </div>
        </div>
    </div>
</section> -->

<style>
    :root {
        --white: #f9fcfd;
        --dark: #191a1b;
    }
    * {
        font-weight: 400;
        text-align: center;
        
    }

    .hero {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 550px;
        text-align: center;
        background-color: var(--dark);
        padding: 250px 0 250px 0;
        width: 100vw;
    }
    
    .hero-text {
        background-color: var(--white);
        display: flex;
        flex-direction: column;
        gap: 20px;
        /* min-width: 320px;
        max-width: 320px; */
        width: 320px;
        padding: 20px 0px;
        justify-content: center;
        align-items: center;
        text-align: end;
        border-radius: 20px;
        /* background: url("/inverted.png");
        background-position: center; */
        /* background-size:cover; */
        z-index: 2;
        border: 3px solid black;  
    }

    li > span {
        font-weight: 400;
    }

    #unity {
        position: absolute;
        overflow: hidden;
        animation: rotating 50s linear infinite;
        z-index: 1;
        width: 550px;
        opacity: 1;
        -moz-user-select: none;
-webkit-user-select: none;
user-select: none;
    }

    @keyframes rotating {
    from{
        -webkit-transform: rotate(0deg);
    }
    to{
        -webkit-transform: rotate(360deg);
    }
}

    .jump-buttons > button {
        padding: 5px 20px;
        border-radius: 20px;
        color: #191a1b;
        background-color: #f9fcfd;
        border: 1px solid black;
        transition: .2s;
        font-weight: 600;
    }

    li {
        font-size: 1.5rem;
        font-weight: 400;
        margin: 20px auto 0 auto;
    }

    .jump-buttons > button:hover {
        padding: 5px 20px;
        border-radius: 20px;
        color: #f9fcfd;
        cursor: pointer;
        background-color: #191a1b;
    }

    .grad {
        background: #42D392;
        background: linear-gradient(to left, #42D392 0%, #647eff 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        font-weight: 800;
    }

    .hero h1 {
        font-size: 3.5em;
        font-weight: 800;
    }

    .hero h3 {
        font-size: 1.25em;
        font-weight: 500;
    }

    .about {
        background-color: var(--white);
        position: relative;
        z-index: 100;
        height: 1200px;
        padding: 100px 0 50px 0;
        display: flex;
        flex-direction: column;
        gap: 50px;
    }

    .about-question > h2 {
        font-weight: 700;
        font-size: 3rem;
        margin-bottom: 50px;
    }

    .about p {
        font-weight: 400;
        font-size: 1.25rem;
        margin-bottom: 50px;
        width: 500px;
        margin: 0 auto;
        padding-top: 50px;
    }

    .quote {
        font-size: 3.5rem;
        font-weight: 800;
        max-width: 800px;
        margin: 0 auto;
        text-align: center;
        min-width: 665px;
    }

    .quoter {
        font-size: 2.25rem;
    }

    .technology {
        display: flex;
        justify-content: center;
        position: relative;
        background-color: #42D392;
        padding: 200px 0;
        height: 1000px;
    }

    .card {
        border: 5px solid black;
        border-radius: 20px;
        padding: 20px 50px;
        background-color: var(--white);
        max-width: 450px;
        transition: .2s;
    }

    .card:hover {
        background-color: #647eff;
    }

    .language .contents p {
        font-weight: 700;
        font-size: 10rem;
        margin-bottom: 0px;
    }

    .engine .contents p {
        font-weight: 700;
        font-size: 6rem;
        margin-bottom: 0px;
    }

    .tools .contents p {
        font-weight: 700;
        font-size: 4rem;
        margin-bottom: 0px;
        margin-top: 10px;
    }

    .card h1 {
        font-weight: 700;
        font-size: 3rem;
        margin-bottom: 50px;
    }

    .technology .container {
        display: flex;
        gap: 100px;
    }

    .technology img {
        width: 200px;
        margin-bottom: 20px;
    }

 

    .games {
        display: flex;
        justify-content: center;
    }

    .games > div {
        display: flex;
    }

    

    .custom-shape-divider-top-1667688268 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1667688268 svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 59px;
}

.custom-shape-divider-top-1667688268 .shape-fill {
    fill: #191A1B
}

.custom-shape-divider-top-1667751780 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1667751780 svg {
    position: relative;
    display: block;
    width: calc(129% + 1.3px);
    height: 117px;
}

.custom-shape-divider-top-1667751780 .shape-fill {
    fill: #F9FCFD;
}
</style>