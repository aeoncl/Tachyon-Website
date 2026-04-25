<script>
    import "../app.css";
    import logo from "$lib/assets/tachyon-portal.svg";
    import logo2 from "$lib/assets/icon-256.png";
    import screenshot from "$lib/assets/screenshot.png"
    import matrix_logo from "$lib/assets/matrix-logo.svg";
    import bosse_ordi_emote from "$lib/assets/smiley_bosseordi.gif"
    import love_letter_emote from "$lib/assets/opening-a-love-letter-smiley-emoticon.gif"
    import suicide_emoji from "$lib/assets/suicide.gif"
    import laughing_pointing from "$lib/assets/laughing-pointing.gif"

</script>

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
                consulted
                &nbsp;·&nbsp; Out before they fixed Windows Search
                &nbsp;·&nbsp; Written in rust btw ^^ &nbsp;·&nbsp;
                MessengerWuzHere &nbsp;·&nbsp; Still better than MS Teams
                &nbsp;·&nbsp; Zucc-free &nbsp;·&nbsp; Built on hyperfixation and
                caffeine &nbsp;·&nbsp; MDRRRR &nbsp;·&nbsp; Eeeeerm actshually
                it's called Windows Live Messenger &nbsp;·&nbsp; Tachyonized
                &nbsp;·&nbsp; Federated. Encrypted. Unhinged. &nbsp;·&nbsp; No
                splines were harmed &nbsp;·&nbsp; ASL ?
                &nbsp;·&nbsp; Hack the Planet !
                &nbsp;·&nbsp; <a href="https://youtu.be/WtYEvV2a2c8?si=d04VnuwteiXHnvLe" target="_blank">Ce soir c'est wizz</a>
                &nbsp;·&nbsp; Let's circle back and reevaluate in Q2 <img style="display: inline; align-content: center; height: 24px" src={laughing_pointing} alt="lauging pointing" />
            </span>
        </div>
    </div>

<div class="container">

    <div class="content">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="glass-card section-content content-flex">
                <div class="title">
                    <h1>Windows Live Messenger now speaks <img class="matrix-logo" src={matrix_logo} alt="matrix" /></h1>
                    <p>With the help of Tachyon, a small server running on your device, Windows Live Messenger can communicate using Matrix. No trickery involved, the old MSN you know and love has become a real Matrix client.</p>
                </div>
                <img src={screenshot} style="border-radius: 8px;" alt="screenshot" width="248px"/>
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
            <div class="glass-card section-content content-flex">
               
                <img src={screenshot} alt="screenshot" width="200px"/>
                  <div class="title">
                    <h1>Talk with your real friends</h1>
                    <p>Leverage the Matrix ecosystem to talk with your friends from all platforms. Self-host your Matrix homeserver and bridges to show Discord and Instagram what real messaging looks like.</p>
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
            <div class="glass-card section-content content-flex">
                <div class="title">
                    <h1>Peak y2k radness</h1>
                    <p>Windows Live Messenger is full of y2k software secret sauce that give it charm: Nudges, Winks, Custom Emoticons, Animated Display Pictures, ... . They are not all usable as of <em>yet</em> with Tachyon but the goal is to make them all work. <s>i mean i do need to touch grass rn but you got it.</s></p>
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
            <div class="glass-card section-content content-flex">
               
                  <div class="title">
                    <h1>Install</h1>
                    <p>Leverage the Matrix ecosystem to talk with your friends from all platforms. Self-host your server and bridges and show your Instagram contacts what a real secure messaging client looks like.</p>
                </div>
            </div>
        </main>

    </div>

        <div class=" content">
        <aside class="adbar-left">
            <div class="ad"></div>
        </aside>

        <aside class="adbar-right">
            <div class="ad"></div>
        </aside>

        <main>
            <div class="glass-card section-content content-flex">
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
        background: #d9ecf5;
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
        background: rgba(0, 42, 67, 0.75);
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
        justify-content: center;
        gap: 16px;
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

    .glass-card {
        position: relative;
        background:
                linear-gradient(180deg,
                rgba(255, 255, 255, 0.55) 0%,
                rgba(255, 255, 255, 0.25) 50%,
                rgba(255, 255, 255, 0.15) 100%);
        border: 1px solid rgba(255, 255, 255, 0.5);
        border-radius: 24px;
        backdrop-filter: blur(14px);
        -webkit-backdrop-filter: blur(14px);
        box-shadow:
                0 10px 40px rgba(10, 74, 140, 0.25),
                inset 0 1px 0 rgba(255, 255, 255, 0.8);
        overflow: hidden;
    }

    .glass-card::before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        height: 50%;
        background: linear-gradient(
                180deg,
                rgba(255, 255, 255, 0.45) 0%,
                rgba(255, 255, 255, 0.05) 100%
        );
        pointer-events: none;
        border-radius: 24px 24px 0 0;
    }

    .glass-card-dark {
        background:
                linear-gradient(180deg,
                rgba(20, 90, 160, 0.55) 0%,
                rgba(10, 50, 110, 0.45) 50%,
                rgba(8, 40, 90, 0.4) 100%);
        border: 1px solid rgba(120, 200, 255, 0.35);
        box-shadow:
                0 10px 40px rgba(0, 20, 60, 0.5),
                inset 0 1px 0 rgba(180, 220, 255, 0.4);
    }

    .glass-card-dark::before {
        background: linear-gradient(
                180deg,
                rgba(180, 220, 255, 0.18) 0%,
                rgba(180, 220, 255, 0.02) 100%
        );
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
        min-height: 380px;
        padding: 48px 16px 32px;
        gap: 32px;
        position: relative;
        z-index: 10;
    }

    header .brand {
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

    .frutiger-aero-button {
        position: relative;
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
        border-top: 1px solid rgba(255, 255, 255, 0.3);
        border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    }

    .marquee span {
        display: inline-block;
        vertical-align: middle;
        line-height: 1em;
        animation: mq 60s linear infinite;
        font-family: "Comic Sans MS";
        font-size: 18pt;
        color: rgba(228, 248, 255, 0.95);
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
        padding: 48px 16px;
    }

    .content-dark {
    }

    .content-flex {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 48px;
    }
    

    .section-content h1 {
        color: #355a88;
        font-size: clamp(32pt, 4.5vw, 52pt);
        font-family: 'Babylon5 Credits';
        line-height: 1.05;
        filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.3))
        drop-shadow(0 2px 4px rgba(0, 30, 80, 0.2));
    }

    h1 .matrix-logo {
        height: clamp(38pt, 4.5vw, 58pt);
        vertical-align:middle;
        filter: brightness(0) saturate(100%) invert(29%) sepia(66%) saturate(504%) hue-rotate(173deg) brightness(92%) contrast(86%);
    }

    .section-content p {
        margin-top: 36px;
        font-size: 16px;
        line-height: 1.6;
        color: #0a4a8c;
        max-width: 55ch;
        font-family: 'Segoe UI';
    }
    
    .section-content .title {
        max-width: 70%;
    }

    .section-content {
        min-height: 400px;
        padding: 48px 56px;
    }
</style>
