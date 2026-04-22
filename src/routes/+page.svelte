<script>
    import "../app.css";
    import logo from "$lib/assets/tachyon-portal.svg";
</script>

<div class="container">
    <main>
        <img alt="portal logo" src={logo} width="200px" />
        <h1>tachyon</h1>
        <div class="tagline">
            MSN Messenger is now a <em>Matrix client</em>
        </div>
        <button class="gb gb-p">Install</button>
    </main>
</div>

<style lang="css">
    @keyframes float {
        0% {
            transform: translateY(0px);
        }
        50% {
            transform: translateY(-12px);
        }
        100% {
            transform: translateY(0px);
        }
    }

    @keyframes float2 {
        0% {
            filter: drop-shadow(0 8px 6px rgba(0, 0, 0, 0.2));
        }
        50% {
            filter: drop-shadow(0 20px 12px rgba(0, 0, 0, 0.1));
        }
        100% {
            filter: drop-shadow(0 8px 6px rgba(0, 0, 0, 0.2));
        }
    }

    main img {
        animation: float 4s ease-in-out infinite;
    }

    .container {
        background: linear-gradient(
            180deg,
            #071428 0%,
            #0d2550 25%,
            #1a5a9a 62%,
            #3a9bd5 84%,
            #7dd0f5 100%
        );
        display: flex;
        align-items: center; /* vertical center */
        justify-content: center; /* horizontal center */
        height: 100vh;
    }

    main {
        display: flex;
        flex-direction: column;
        align-items: center; /* center children horizontally */
        gap: 16px;
        text-align: center;
    }

    main h1 {
        animation: float2 4s ease-in-out infinite;
        animation-delay: 0.1s;
        font-family: "Babylon5";
        font-size: 110pt;
        margin: 0;
        color: transparent;
        background: linear-gradient(
            180deg,
            #ffffff 0%,
            #d0eeff 40%,
            #7ac8f8 75%,
            #3a9bd5 100%
        );
        background-clip: text;
        filter: drop-shadow(0 0 20px rgba(80, 180, 255, 0.6))
            drop-shadow(0 2px 4px rgba(0, 30, 80, 0.5));
    }

    main .tagline {
        font-family: "Segoe UI", "Trebuchet MS", sans-serif;
        font-size: 15px;
        font-weight: 300;
        color: rgba(255, 255, 255, 0.85);
        letter-spacing: 0.5px;
        text-shadow: 0 1px 6px rgba(0, 30, 80, 0.5);
        margin-bottom: 28px;
        text-align: right;
        width: 100%;
    }

    main .tagline em {
        font-style: normal;
        color: white;
        font-weight: 400;
    }

    .gb {
        display: inline-block;
        font-size: 18px;
        font-weight: 600;
        padding: 8px 22px;
        border-radius: 5px;
        cursor: pointer;
        position: relative;
        overflow: hidden;
        border: 1px solid;
        font-family: "Segoe UI", sans-serif;
    }
    .gb::before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        height: 50%;
        background: rgba(255, 255, 255, 0.22);
        pointer-events: none;
    }
    .gb-p {
        background: linear-gradient(180deg, #4aabec, #1a7acc 48%, #0f58a8);
        color: white;
        border-color: #0a4080;
        text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
    }
</style>
