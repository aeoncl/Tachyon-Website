<script>
    import "../app.css";
    import logo from "$lib/assets/tachyon-portal.svg";
    import logo2 from "$lib/assets/icon-256.png";
    import banner from "$lib/assets/tachyon_banner_bigger.png";
    import screenshot from "$lib/assets/image.png"
</script>

<div class="container">



    <div class="navbar prevent-select">
        <div class="brand">
            <img alt="portal logo" src={logo} width="16px" />
            <p class="title">Tachyon</p>
        </div>
        <nav class="nav">
            <ul>
                <li class="glass-button current"><span>Home</span></li>
                <li class="glass-button"><span>Install</span></li>
                <li class="glass-button"><span>FAQ</span></li>
            </ul>
        </nav>
    </div>
    <div class="top-bg">
        
    </div>

    <div class="header-content">
        <header>
            <div class="brand">
                <img alt="portal logo" src={logo2} />
                <div class="title">
                    <p>Tachyon</p>
                    <p class="tagline">
                        A portal to <em>the future we were promised</em>
                    </p>
                </div>
            </div>
            <button class="frutiger-aero-button large">Install</button>
        </header>

        <div class="marquee">
            <span>
                End-to-end encrypted
                &nbsp;·&nbsp; :$$$$ &nbsp;·&nbsp; Powered by Matrix
                &nbsp;·&nbsp; We're so back &nbsp;·&nbsp; No shareholders were
                consulted &nbsp;·&nbsp; Written in rust btw ^^ &nbsp;·&nbsp;
                MessengerWuzHere &nbsp;·&nbsp; Still better than MS Teams
                &nbsp;·&nbsp; Zucc-free &nbsp;·&nbsp; Built on hyperfixation and
                caffeine &nbsp;·&nbsp; MDRRRR &nbsp;·&nbsp; Eeeeerm actshually
                it's called Windows Live Messenger &nbsp;·&nbsp; Tachyonized
                &nbsp;·&nbsp; Federated. Encrypted. Unhinged. &nbsp;·&nbsp; No
                splines were harmed &nbsp;·&nbsp; ASL ?
                &nbsp;·&nbsp; Hack the Planet !
                &nbsp;·&nbsp; I'm out of ideas
            </span>
        </div>
    </div>

    <div class="content">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="section-content content-flex">
                <div class="title">
                    <h1>Windows Live Messenger now speaks Matrix</h1>
                    <p>With the help of Tachyon, a small server running on your device, Windows Live Messenger can communicate using Matrix. No trickery involved, the old MSN you know and love has become a fully fledged Matrix client.</p>
                </div>
                <img src={screenshot} alt="screenshot" width="200px"/>
            </div>
        </main>

    </div>

    <div class="content content-dark">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="section-content content-flex">
               
                <img src={screenshot} alt="screenshot" width="200px"/>
                  <div class="title">
                    <h1>Talk with your real friends</h1>
                    <p>Leverage the Matrix ecosystem to talk with your friends from all platforms. Self-host your server and bridges and show your Discord and Instagram friends what a messaging client that respects your privacy looks like.</p>
                </div>
            </div>
        </main>

    </div>

    <div class="content">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="section-content content-flex">
                <div class="title">
                    <h1>Features</h1>
                    <p>Windows Live Messenger has a lot of quirky features that give it charm. Nudges, Winks, Animated Display Pictures. They are not all usable as of <em>yet</em> but we want to support as much as we can down the line.</p>
                </div>
                <img src={screenshot} alt="screenshot" width="200px"/>
            </div>
        </main>

    </div>

        <div class="content content-dark">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="section-content content-flex">
               
                  <div class="title">
                    <h1>Install</h1>
                    <p>Leverage the Matrix ecosystem to talk with your friends from all platforms. Self-host your server and bridges and show your Instagram contacts what a real secure messaging client looks like.</p>
                </div>
            </div>
        </main>

    </div>

        <div class="content">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="section-content content-flex">
                <div class="title">
                    <h1>Frequently Asked Questions</h1>
                </div>
            </div>
        </main>

    </div>

    <footer>

    </footer>

</div>

<style lang="css">

    .container {
          background: linear-gradient(180deg, #0a4a8c 0%, #1a7acc 15%, #3ab0e8 40%, #7dd4f8 65%, #c8eefa 85%, #e8f8ff 100%);


    }

    .top-bg {
        position: absolute;
        width: 100%;
        height: 90px;
        background-image: url("$lib/assets/tachyon_banner_bigger.png");
        background-position-x: center;
        background-position-y: top;
        background-repeat: repeat-x;
        background-attachment: scroll;
        background-size: auto;
        background-origin: padding-box;
        background-clip: border-box;
    }

    .navbar {
        z-index: 9999;
        position: sticky;
        top: 0;
        overflow: hidden;
        height: 50px;
        background: #044a9e8e;
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        display: grid;
        grid-template:
            "left main right" auto
            / 1fr 4fr 1fr;
    }

    .navbar .brand {
        grid-area: left;
        margin-left: 16px;
        display: flex;
        align-items: center;
    }

    .navbar .brand .title {
        margin-left: -8px;
        font-family: "Babylon5";
        color: white;
    }

    .navbar nav {
        grid-area: main;
    }

    .navbar nav ul {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: center;
        height: 100%;
    }

    .navbar nav ul li {
        display: block;
        font-family: "Babylon5 Credits";
    }

    .navbar nav ul li span {
        filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.6))
            drop-shadow(0 2px 4px rgba(0, 30, 80, 0.5));
    }

    .glass-button {
        border-radius: 10px;
        border: 1px solid rgba(255, 255, 255, 0);

        padding: 8px 24px;
        color: white;
    }

    .glass-button:hover,
    .glass-button.current {
        border: 1px solid rgba(255, 255, 255, 0.2);
        background: rgba(255, 255, 255, 0.1);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border-radius: 8px;
        color: #ffffff;
        cursor: pointer;
        transition: all 0.3s ease;
        box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    }

    .glass-button:active {
        transition: all 0.1s ease;
        background: rgba(255, 255, 255, 0.2);
    }

    .glass-button:disabled {
        opacity: 0.5;
        cursor: not-allowed;
    }

    .prevent-select {
        -webkit-user-select: none; /* Safari */
        -ms-user-select: none; /* IE 10 and IE 11 */
        user-select: none; /* Standard syntax */
    }

    .content {
        
        display: grid;
        grid-template:
            "left main right" auto
            / 1fr 4fr 1fr;
    }

    .header-content {
        background: linear-gradient(
            0deg,
            #7dd0f5 0%,
            #ffffff 100%

        );
        display: grid;
        grid-template:
            ". header ." auto
            "marquee marquee marquee" auto
            / 1fr 4fr 1fr;
    }

    header {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        grid-area: header;
        min-height: 300px;
    }

    header .brand {
        padding: 16px;
        margin-left: 16px;
        display: flex;
        align-items: center;
        width: fit-content;
        margin: 0 auto;
    }

    header .brand img {
        z-index: 1;
    }

    header .brand .title {
        margin-top: 16px;
        font-family: "Babylon5";
        color: white;

        filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.6))
            drop-shadow(0 2px 4px rgba(0, 30, 80, 0.5));
        -webkit-background-clip: text;
        background-clip: text;
        font-size: 96pt;
    }

    header .tagline {
        font-family: "Segoe UI", "Trebuchet MS", sans-serif;
        font-size: 16px;
        font-weight: 300;
        color: rgba(255, 255, 255, 0.85);
        letter-spacing: 0.5px;
        text-shadow: 0 1px 6px rgba(0, 30, 80, 0.5);
        margin-top: 16px;
        text-align: right;
        width: 100%;
    }

    header .tagline em {
        font-style: normal;
        color: white;
        font-weight: 400;
    }

    header button {
        position: absolute;
        top: 338px;
        z-index: 99;
    
    
    }

    .frutiger-aero-button {

        width: fit-content;
        /* OKLCH Color System for accurate colors */
        --hue: 128;
        --sat: 0.8;
        --glow-intensity: 0.2;

        /* Color Variables */
        --fg: oklch(15% calc(var(--sat) * 0.5) var(--hue));
        --bg: oklch(75% var(--sat) var(--hue) / 0.8);
        --bg-dark: oklch(45% var(--sat) var(--hue) / 0.75);
        --bottom-glow: radial-gradient(
            farthest-corner at bottom center,
            rgba(255, 255, 255, var(--glow-intensity)),
            transparent
        );

        /* Base Styling */
        background-color: var(--bg);
        background: var(--bottom-glow),
            linear-gradient(to bottom, var(--bg-dark), var(--bg));

        border: 1px solid var(--bg);
        border-radius: 32px;

        /* Shadows and Effects */
        box-shadow: 0 4px 4px rgba(0, 0, 0, 0.4);

        /* Typography */
        color: var(--fg);
        font-family: "Lucida Grande", "Lucida Sans Unicode", "Segoe UI",
            system-ui, sans-serif;
        font-weight: 700;
        text-shadow: 0 2px 0.5em rgba(0, 0, 0, 0.2);

        /* Layout */
        cursor: pointer;
        transition: all 300ms ease;

        /* Prevent text selection */
        user-select: none;
        -webkit-user-select: none;

        color: white;
    }

    /* Top Highlight Effect */
    .frutiger-aero-button::after {
        content: "";
        position: absolute;
        top: 4%;
        left: 0.75em;
        width: calc(100% - 1.5em);
        height: 40%;
        background: linear-gradient(
            to bottom,
            rgba(255, 255, 255, 0.8),
            rgba(255, 255, 255, 0.1)
        );
        border-radius: inherit;
        transition: background 400ms ease;
        pointer-events: none;
    }

    /* Hover State */
    .frutiger-aero-button:hover,
    .frutiger-aero-button:focus {
        box-shadow: 0 6px 8px rgba(0, 0, 0, 0.4);
        transform: translateY(-1px);
    }

    /* Active State */
    .frutiger-aero-button:active {
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
        transform: translateY(1px);
    }

    /* Size Variations */
    .frutiger-aero-button.small {
        padding: 0.5em 1.5em;
        font-size: 0.875rem;
    }

    .frutiger-aero-button.medium {
        padding: 0.75em 2em;
        font-size: 1rem;
    }

    .frutiger-aero-button.large {
        padding: 1em 3em;
        font-size: 1.125rem;
    }

    .marquee {
        grid-area: marquee;
        background-color: #ffffff23;
        overflow: hidden;
        line-height: 48px;
        white-space: nowrap;
        backdrop-filter: blur(4px);
    }

    .marquee span {
        display: inline-block;
        vertical-align: middle;
        line-height: 1em;
        animation: mq 60s linear infinite;
        font-family: "Babylon5 Credits";
        font-size: 18pt;
        color: rgba(228, 248, 255, 0.877);
        letter-spacing: 0.3px;
    }
    @keyframes mq {
        0% {
            transform: translateX(100vw);
        }
        100% {
            transform: translateX(-100%);
        }
    }

    .adbar-left {
        grid-area: left;
    }

    .adbar-right {
        grid-area: right;
    }

    .ad {
        height: 200px;
        width: 100px;
    }

    main {
        grid-area: main;
        padding: 16px;
    }

    .content-dark {
        background-color: #0a4a8c;
    }

    .content-flex {
        display: flex;
        align-items: center;
        justify-content: space-evenly;

    }
    

    .section-content h1 {
        filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.6))
            drop-shadow(0 2px 4px rgba(0, 30, 80, 0.5));
        -webkit-background-clip: text;
        background-clip: text;
        color: white;
        font-size: 56pt;
        font-family: 'Babylon5 Credits';
    }

    .section-content p {
        margin-top: 48px;
        margin-left: 4px;
        width: 80%;
    filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.6))
            drop-shadow(0 2px 4px rgba(0, 30, 80, 0.5));

        font-family: 'Babylon5 Credits';
    }
    
    .section-content .title {
        max-width: 70%;
    }

    .section-content {
                min-height: 600px;
        padding: 32px;

    }
</style>
