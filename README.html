# Resource-RUsh<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#101514">
  <title>RESOURCE RUSH — The Last Signal</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;500;600;700;800;900&family=DM+Mono:wght@400;500&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{color-scheme:dark;--ink:#eff0e8;--muted:#a5a69b;--lime:#d6fa72;--orange:#fb805d;--glass:rgba(14,19,17,.82);--line:rgba(238,238,218,.15)}
    *{box-sizing:border-box}
    html,body{width:100%;height:100%;margin:0;overflow:hidden;background:#101514;color:var(--ink);font-family:Manrope,Arial,sans-serif}
    button{font:inherit}
    #world{position:fixed;inset:0}
    #world canvas{display:block}
    .vignette{position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 35%,rgba(5,9,8,.44) 100%),linear-gradient(0deg,rgba(7,10,9,.47),transparent 35%,rgba(7,10,9,.12))}
    .grain{position:fixed;inset:-50%;pointer-events:none;z-index:3;opacity:.075;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 180 180' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.88' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='.65'/%3E%3C/svg%3E");animation:grain .25s steps(2) infinite}
    @keyframes grain{0%{transform:translate(0,0)}25%{transform:translate(2%,-1%)}50%{transform:translate(-1%,2%)}75%{transform:translate(1%,1%)}}
    .screen{position:fixed;inset:0;z-index:5;display:flex;align-items:center;justify-content:center;padding:24px;background:linear-gradient(90deg,rgba(8,12,11,.87),rgba(8,12,11,.5) 57%,rgba(8,12,11,.18))}
    .screen.hidden{display:none}
    .intro{width:min(1100px,100%);display:grid;grid-template-columns:minmax(0,1.3fr) minmax(290px,.7fr);gap:74px;align-items:center}
    .eyebrow,.micro{font-family:"DM Mono",monospace;letter-spacing:.18em;text-transform:uppercase;font-size:10px;color:var(--lime)}
    .eyebrow{display:flex;gap:12px;align-items:center}
    .eyebrow:before{content:"";width:28px;height:1px;background:var(--lime)}
    h1,h2,p{margin-top:0}
    h1{font-family:"Barlow Condensed",Impact,sans-serif;font-size:clamp(82px,12vw,154px);font-weight:800;line-height:.76;letter-spacing:-.045em;margin:28px 0 19px}
    h1 span{display:block;color:var(--lime)}
    .subtitle{font-family:"Barlow Condensed",sans-serif;font-size:20px;letter-spacing:.19em;color:#dadbd1;text-transform:uppercase}
    .story{max-width:590px;margin:25px 0 28px;font-size:14px;line-height:1.9;color:#c0c2b8}
    .story strong{color:#fff}
    .objective{display:flex;align-items:center;gap:13px;padding:14px 16px;border:1px solid var(--line);background:rgba(255,255,255,.035);max-width:510px}
    .objective-mark{flex:0 0 33px;width:33px;height:33px;border:1px solid rgba(214,250,114,.4);color:var(--lime);display:grid;place-items:center;font-size:16px}
    .objective div:last-child{font-size:11px;line-height:1.65;color:#d0d2c8}
    .objective b{display:block;font-family:"DM Mono",monospace;font-size:10px;color:var(--lime);letter-spacing:.12em;margin-bottom:3px}
    .briefing{border:1px solid rgba(236,237,222,.17);background:rgba(13,18,16,.78);backdrop-filter:blur(18px);padding:25px 24px 23px;box-shadow:0 24px 90px #0005}
    .briefing-head{font-family:"DM Mono",monospace;font-size:10px;letter-spacing:.15em;color:#e1e2d9;text-transform:uppercase;padding-bottom:15px;border-bottom:1px solid var(--line)}
    .control{display:grid;grid-template-columns:92px 1fr;align-items:center;padding:9px 0;border-bottom:1px solid rgba(238,238,218,.07);font-size:11px;color:#bbbeb4}
    .key{font-family:"DM Mono",monospace;font-size:10px;color:var(--lime);letter-spacing:.06em}
    .warning{font-size:10px;line-height:1.75;color:#a8aaa0;margin:15px 0 17px}
    .warning strong{color:#f0a385}
    .start{width:100%;min-height:49px;background:var(--lime);border:0;color:#152011;text-transform:uppercase;letter-spacing:.16em;font-weight:800;font-size:11px;cursor:pointer;transition:background .18s,transform .18s}
    .start:hover{background:#e5ff9b;transform:translateY(-1px)}
    .start span{margin-left:12px}
    .footer{font-family:"DM Mono",monospace;font-size:9px;letter-spacing:.12em;color:#777b72;text-align:center;margin-top:15px;text-transform:uppercase}
    #hud{position:fixed;inset:0;z-index:2;pointer-events:none;display:none}
    #hud.active{display:block}
    .topbar{position:absolute;top:23px;left:26px;right:26px;display:flex;justify-content:space-between;align-items:flex-start}
    .brand{font-family:"Barlow Condensed",sans-serif;font-size:19px;font-weight:800;letter-spacing:.08em}
    .brand span{color:var(--lime)}
    .daybox{text-align:center;padding:9px 19px 8px;background:rgba(11,15,14,.67);border:1px solid var(--line);backdrop-filter:blur(8px)}
    .daybox strong{display:block;font-family:"Barlow Condensed",sans-serif;font-size:20px;letter-spacing:.1em}
    .daybox small{font-family:"DM Mono",monospace;font-size:9px;color:#aeb0a5;letter-spacing:.13em}
    .topright{display:flex;gap:15px;align-items:center}
    .storm-label{font-family:"DM Mono",monospace;color:#dfc1a9;font-size:9px;letter-spacing:.15em;text-align:right}
    .storm-track{width:116px;height:3px;background:#ffffff27;margin-top:7px}
    .storm-fill{height:100%;width:5%;background:var(--orange);transition:width .5s}
    .compass{position:absolute;top:106px;left:50%;transform:translateX(-50%);font-family:"DM Mono",monospace;font-size:9px;letter-spacing:.19em;color:#e2e2d7aa;text-shadow:0 1px 8px #000}
    .leftstats{position:absolute;left:26px;bottom:27px;width:190px;background:var(--glass);border:1px solid var(--line);padding:13px 14px;backdrop-filter:blur(8px)}
    .statrow{display:flex;justify-content:space-between;font-family:"DM Mono",monospace;font-size:9px;letter-spacing:.1em;color:#b9bbb0;margin-bottom:8px}
    .statrow:last-child{margin:0}
    .statrow b{color:#f0f1e9;font-weight:500}
    .meter{height:3px;background:#ffffff20;margin-top:-4px;margin-bottom:10px}
    .meter span{display:block;height:100%;width:100%;background:var(--lime);transition:width .3s}
    .meter.health span{background:var(--orange)}
    .rightstats{position:absolute;right:26px;bottom:27px;display:grid;gap:9px;text-align:right}
    .pill{display:inline-block;background:var(--glass);border:1px solid var(--line);padding:9px 12px;font-family:"DM Mono",monospace;font-size:9px;letter-spacing:.08em;color:#d1d3c8;backdrop-filter:blur(8px)}
    .pill b{color:var(--lime);font-weight:500}
    .crosshair{position:absolute;left:50%;top:50%;width:16px;height:16px;transform:translate(-50%,-50%);opacity:.75}
    .crosshair:before,.crosshair:after{content:"";position:absolute;background:#f2f4e6}
    .crosshair:before{width:1px;height:13px;left:7px;top:1px}
    .crosshair:after{height:1px;width:13px;left:1px;top:7px}
    #prompt{position:absolute;left:50%;top:calc(50% + 35px);transform:translateX(-50%);font-family:"DM Mono",monospace;font-size:10px;letter-spacing:.08em;color:white;text-shadow:0 1px 7px #000;white-space:nowrap}
    #toast{position:absolute;top:20%;left:50%;transform:translate(-50%,-8px);opacity:0;transition:all .22s;background:rgba(13,18,16,.92);border:1px solid #ffffff24;padding:10px 16px;font-family:"DM Mono",monospace;font-size:10px;letter-spacing:.07em;color:var(--lime)}
    #toast.show{opacity:1;transform:translate(-50%,0)}
    .phone{position:fixed;inset:0;z-index:4;display:none;align-items:center;justify-content:center;background:#080d0cdc;backdrop-filter:blur(8px);pointer-events:auto}
    .phone.open{display:flex}
    .phone-shell{width:min(420px,90vw);border:1px solid #d6fa7247;background:#121a16;padding:23px;box-shadow:0 20px 100px #000b}
    .phone-title{display:flex;justify-content:space-between;align-items:center;font-family:"Barlow Condensed",sans-serif;font-weight:700;font-size:24px;letter-spacing:.06em}
    .phone-title em{font-family:"DM Mono",monospace;font-style:normal;font-size:10px;color:var(--lime)}
    .map{position:relative;height:250px;margin:18px 0;background-color:#18221d;background-image:linear-gradient(34deg,transparent 46%,#66735570 47%,#66735570 49%,transparent 50%),linear-gradient(151deg,transparent 48%,#80806350 49%,#80806350 51%,transparent 52%),linear-gradient(90deg,transparent 48%,#75805a40 49%,#75805a40 50%,transparent 51%);border:1px solid var(--line);overflow:hidden}
    .map:before,.map:after{content:"";position:absolute;background:#c0c48d2e}
    .map:before{width:170%;height:1px;top:53%;left:-30%;transform:rotate(-25deg)}
    .map:after{height:170%;width:1px;left:48%;top:-30%;transform:rotate(29deg)}
    .map-point{position:absolute;z-index:1;width:9px;height:9px;border-radius:50%;background:var(--lime);box-shadow:0 0 13px var(--lime)}
    .map-point.you{left:49%;top:53%;background:white;box-shadow:0 0 0 5px #fff3}
    .map-point.beacon{left:73%;top:25%;background:var(--orange);box-shadow:0 0 14px var(--orange)}
    .map-label{position:absolute;z-index:1;font-family:"DM Mono",monospace;font-size:8px;letter-spacing:.08em;color:#e2e4d4}
    .phone-note{font-size:10px;line-height:1.7;color:#aeb2a6}
    .phone-note b{color:var(--lime)}
    #cinematic{position:fixed;inset:0;z-index:8;overflow:hidden;background:linear-gradient(0deg,rgba(5,8,7,.86),transparent 36%,rgba(5,8,7,.12) 72%,rgba(5,8,7,.48));pointer-events:none}
    #cinematic.finished{opacity:0;transition:opacity .65s}
    .film-bar{position:absolute;left:0;right:0;height:7.5vh;background:#050706;box-shadow:0 0 24px #0008}
    .film-bar.top{top:0}.film-bar.bottom{bottom:0}
    .film-top{position:absolute;top:10vh;left:5vw;right:5vw;display:flex;justify-content:space-between;font:10px "DM Mono",monospace;letter-spacing:.17em;color:#f1f1e7bd;text-transform:uppercase}
    .film-mark{color:#ff7056}
    .film-caption{position:absolute;left:50%;bottom:14vh;transform:translateX(-50%);width:min(780px,86vw);text-align:center;text-shadow:0 2px 12px #000;font-size:clamp(13px,1.5vw,18px);line-height:1.75;color:#f3f1e8;letter-spacing:.025em}
    .film-caption strong{font-weight:800;color:var(--lime)}
    .film-credit{position:absolute;left:50%;top:17vh;transform:translateX(-50%);font:10px "DM Mono",monospace;letter-spacing:.28em;text-transform:uppercase;color:#e0e4cfaa}
    .film-title{position:absolute;left:50%;top:32%;transform:translate(-50%,-50%);text-align:center;font:800 clamp(40px,8vw,105px)/.8 "Barlow Condensed",sans-serif;letter-spacing:.06em;text-shadow:0 4px 22px #000}
    .film-title span{display:block;color:var(--lime);font-size:.43em;letter-spacing:.31em;margin-top:20px}
    .film-skip{position:absolute;right:5vw;bottom:10vh;pointer-events:auto;background:#080d0bd9;border:1px solid #ffffff42;padding:10px 14px;color:#f2f1e9;font:9px "DM Mono",monospace;letter-spacing:.14em;text-transform:uppercase;cursor:pointer}
    .film-skip:hover{border-color:var(--lime);color:var(--lime)}
    .film-progress{position:absolute;bottom:7.5vh;left:0;height:2px;width:0;background:var(--lime);box-shadow:0 0 12px var(--lime)}
    #title-screen{display:none}
    #title-screen.ready{display:flex;animation:title-arrive .7s ease both}
    @keyframes title-arrive{from{opacity:0}to{opacity:1}}
    .quest-panel{position:absolute;top:78px;right:26px;width:244px;padding:12px 14px;background:var(--glass);border:1px solid var(--line);backdrop-filter:blur(8px)}
    .quest-heading{font:9px "DM Mono",monospace;letter-spacing:.15em;color:var(--lime);margin-bottom:8px}
    .quest-line{font:9px/1.8 "DM Mono",monospace;color:#d7d8cf}
    .quest-line.done{color:#82897d;text-decoration:line-through}
    .quest-gun{margin-top:9px;padding-top:8px;border-top:1px solid var(--line);font:8px/1.7 "DM Mono",monospace;letter-spacing:.035em;color:#ffc28e}
    .pause{position:fixed;inset:0;z-index:6;display:none;align-items:center;justify-content:center;background:rgba(6,9,8,.76);backdrop-filter:blur(8px);pointer-events:auto}
    .pause.open{display:flex}
    .pause-card{width:min(380px,90vw);text-align:center;border:1px solid var(--line);background:#121916;padding:32px}
    .pause-card h2{font:700 46px "Barlow Condensed",sans-serif;letter-spacing:.06em;margin:0 0 8px}
    .pause-card p{font-size:11px;color:#aeb2a6;margin:0 0 22px}
    .endcard{max-width:520px;text-align:center;padding:45px;border:1px solid var(--line);background:rgba(13,18,16,.91);backdrop-filter:blur(16px)}
    .endcard h2{font:800 clamp(52px,9vw,88px)/.88 "Barlow Condensed",sans-serif;margin:15px 0;color:var(--lime)}
    .endcard.failed h2{color:var(--orange)}
    .endcard p{color:#bfc2b7;font-size:12px;line-height:1.8;margin:17px 0 24px}
    .scoregrid{display:flex;justify-content:center;gap:25px;margin:20px 0 25px}
    .scoregrid div{font-family:"DM Mono",monospace;color:#aeb1a6;font-size:9px;letter-spacing:.1em}
    .scoregrid b{display:block;font-family:"Barlow Condensed",sans-serif;font-size:27px;color:#f4f4ea;margin-bottom:4px}
    @media(max-width:760px){.intro{grid-template-columns:1fr;gap:20px;max-width:520px}.screen{overflow-y:auto;align-items:flex-start;padding:35px 20px;background:rgba(8,12,11,.82)}h1{font-size:82px;margin:20px 0 14px}.story{font-size:12px;margin:17px 0}.briefing{padding:18px}.control{padding:6px 0}.warning{margin:10px 0}.leftstats{left:12px;bottom:13px;width:160px;padding:10px}.rightstats{right:12px;bottom:13px}.topbar{top:13px;left:13px;right:13px}.brand{font-size:16px}.daybox{padding:6px 10px}.storm-track{width:70px}.storm-label{font-size:8px}.compass{top:84px}.pill{padding:7px 8px;font-size:8px}.quest-panel{top:72px;right:12px;width:195px;padding:9px}.quest-line{font-size:8px}.quest-gun{font-size:7px}.film-caption{bottom:13vh}.film-top{top:9vh}}
    @media(max-height:690px) and (min-width:761px){.intro{gap:40px}.briefing{padding:18px}.control{padding:6px 0}.story{margin:17px 0}.warning{margin:10px 0}}
  </style>
</head>
<body>
  <div id="world" aria-hidden="true"></div>
  <div class="vignette"></div><div class="grain"></div>

  <section id="cinematic" aria-label="Story introduction">
    <div class="film-bar top"></div><div class="film-bar bottom"></div>
    <div class="film-top"><span>RESOURCE RUSH STUDIOS</span><span id="film-rec" class="film-mark">● REC&nbsp; 00:00:00</span></div>
    <div id="film-credit" class="film-credit">An ordinary drive · Day zero</div>
    <div id="film-title" class="film-title">GREYWOOD<span>THE LAST SIGNAL</span></div>
    <div id="film-caption" class="film-caption">The road home was quiet. For the first time in weeks, <strong>you let yourself believe things might be okay.</strong></div>
    <div id="film-progress" class="film-progress"></div>
    <button id="skip-film" class="film-skip">Skip story&nbsp; →</button>
  </section>

  <section id="title-screen" class="screen">
    <div class="intro">
      <div class="story-column">
        <div class="eyebrow">A survival story · 10 days to signal</div>
        <h1>RESOURCE<span>RUSH</span></h1>
        <div class="subtitle">The last signal</div>
        <p class="story">You were humming along to the radio, watching the sun fall over the road. Then the dashboard flashed, the engine coughed, and your car rolled to a stop. Beyond the trees: <strong>Greywood</strong>, a village of broken homes and silent streets. The radio catches one clear message—an emergency beacon can still call for rescue. You just have to survive long enough to reach it.</p>
        <div class="objective"><div class="objective-mark">⌁</div><div><b>YOUR OBJECTIVE</b>Search the village. Recover <strong>3 fuses, 2 batteries, and 1 radio core</strong>. Find the rare field rifle. Reach the beacon and transmit before Day 10’s storm closes in.</div></div>
      </div>
      <aside class="briefing">
        <div class="briefing-head">Field briefing / controls</div>
        <div class="control"><span class="key">W A S D</span><span>Move forward, left, back, right</span></div>
        <div class="control"><span class="key">MOUSE</span><span>Look around · aim</span></div>
        <div class="control"><span class="key">SHIFT</span><span>Sprint (uses stamina)</span></div>
        <div class="control"><span class="key">SPACE</span><span>Jump</span></div>
        <div class="control"><span class="key">CTRL</span><span>Crouch · stay quieter</span></div>
        <div class="control"><span class="key">E</span><span>Search · collect · use beacon</span></div>
        <div class="control"><span class="key">CLICK</span><span>Fire rifle · R reload</span></div>
        <div class="control"><span class="key">Q</span><span>Phone map · phone starts at 100%</span></div>
        <div class="control"><span class="key">ESC</span><span>Pause · release mouse</span></div>
        <p class="warning"><strong>10 DAYS. 90 seconds each.</strong> Storms worsen daily and become lethal after Day 10. Zombies hunt by sight and sound. The rare rifle has 6 rounds—reload with R. For the fastest weapon pickup, search the <strong>rusted house northeast of your car</strong>; its rifle glows orange inside. Your phone battery drains while the map is open.</p>
        <button id="start-button" class="start">Enter Greywood <span>→</span></button>
        <div class="footer">Single-player survival · Runs approximately 15 minutes</div>
      </aside>
    </div>
  </section>

  <div id="hud">
    <div class="topbar"><div class="brand">RESOURCE <span>RUSH</span></div><div class="daybox"><strong id="day-label">DAY 01 / 10</strong><small id="clock-label">06:00 · GREYWOOD</small></div><div class="topright"><div><div class="storm-label">STORM THREAT <span id="storm-number">08</span>%</div><div class="storm-track"><div id="storm-fill" class="storm-fill"></div></div></div></div></div>
    <div class="quest-panel"><div class="quest-heading">ACTIVE OBJECTIVES</div><div id="quest-progress" class="quest-line">□ Fuses&nbsp; 0 / 3</div><div id="quest-batteries" class="quest-line">□ Batteries&nbsp; 0 / 2</div><div id="quest-core" class="quest-line">□ Radio core&nbsp; 0 / 1</div><div id="quest-beacon" class="quest-line">□ Reach beacon · NE</div><div class="quest-gun">FAST GUN → NE, ~30 M<br>Rusted house east of road · orange glow inside</div></div>
    <div id="compass" class="compass">N &nbsp; · &nbsp; NE &nbsp; · &nbsp; E &nbsp; · &nbsp; SE &nbsp; · &nbsp; S</div>
    <div class="crosshair"></div><div id="prompt"></div><div id="toast"></div>
    <div class="leftstats">
      <div class="statrow"><span>VITALS</span><b id="health-number">100</b></div><div class="meter health"><span id="health-fill"></span></div>
      <div class="statrow"><span>STAMINA</span><b id="stamina-number">100</b></div><div class="meter"><span id="stamina-fill"></span></div>
      <div class="statrow"><span>PHONE</span><b id="phone-number">100%</b></div>
    </div>
    <div class="rightstats"><div class="pill">PARTS &nbsp;<b id="parts-label">F 0/3 · B 0/2 · C 0/1</b></div><div class="pill">RIFLE &nbsp;<b id="ammo-label">NOT FOUND</b></div><div class="pill">KILLS &nbsp;<b id="kills-label">0</b> &nbsp; · &nbsp; SCORE &nbsp;<b id="score-label">0000</b></div></div>
  </div>

  <section id="phone" class="phone">
    <div class="phone-shell"><div class="phone-title"><span>FIELD DEVICE</span><em id="phone-charge">BATTERY 100%</em></div>    <div class="map"><span id="you-marker" class="map-point you"></span><span id="you-label" class="map-label" style="left:43%;top:57%">YOU</span><span class="map-point beacon"></span><span class="map-label" style="left:76%;top:22%">BEACON</span><span class="map-label" style="left:16%;top:18%">OLD MILL</span><span class="map-label" style="left:21%;top:79%">GREYWOOD</span><span class="map-label" style="left:68%;top:72%">CHAPEL</span></div><p class="phone-note"><b>OBJECTIVE</b> — Find 3 fuses, 2 batteries, and 1 radio core. Beacon is northeast. White marker: you. <b>E</b> to close.</p><button id="close-phone" class="start">Close map</button></div>
  </section>

  <section id="pause-screen" class="pause"><div class="pause-card"><div class="eyebrow" style="justify-content:center">Greywood / field pause</div><h2>HOLD FAST</h2><p>The storm doesn’t stop while you catch your breath.</p><button id="resume-button" class="start">Back to the village <span>→</span></button></div></section>
  <section id="end-screen" class="screen hidden"><div id="endcard" class="endcard"><div id="end-eyebrow" class="eyebrow" style="justify-content:center">Transmission confirmed</div><h2 id="end-title">YOU’RE OUT.</h2><p id="end-copy"></p><div class="scoregrid"><div><b id="end-score">0</b>SCORE</div><div><b id="end-time">0D 0H 0M</b>TIME ALIVE</div><div><b id="end-kills">0</b>INFECTED</div></div><button id="restart-button" class="start">Play again <span>→</span></button></div></section>

  <script type="module">
    import * as THREE from 'https://cdn.jsdelivr.net/npm/three@0.165.0/build/three.module.js';

    const $ = (id) => document.getElementById(id);
    const world = $('world');
    const scene = new THREE.Scene();
    scene.background = new THREE.Color(0x7c877b);
    scene.fog = new THREE.FogExp2(0x7c877b, 0.017);
    const camera = new THREE.PerspectiveCamera(76, innerWidth / innerHeight, 0.08, 155);
    camera.rotation.order = 'YXZ';
    const renderer = new THREE.WebGLRenderer({ antialias: true, powerPreference: 'high-performance' });
    renderer.setPixelRatio(Math.min(devicePixelRatio, 1.6));
    renderer.setSize(innerWidth, innerHeight);
    renderer.shadowMap.enabled = true;
    renderer.shadowMap.type = THREE.PCFSoftShadowMap;
    renderer.toneMapping = THREE.ACESFilmicToneMapping;
    renderer.toneMappingExposure = 1.13;
    world.appendChild(renderer.domElement);

    const hemi = new THREE.HemisphereLight(0xd5ddc0, 0x32352a, 1.55);
    scene.add(hemi);
    const sun = new THREE.DirectionalLight(0xffe4bf, 2.3);
    sun.position.set(-25, 37, 13);
    sun.castShadow = true;
    sun.shadow.mapSize.set(1024, 1024);
    sun.shadow.camera.left = -48; sun.shadow.camera.right = 48;
    sun.shadow.camera.top = 48; sun.shadow.camera.bottom = -48;
    sun.shadow.bias = -0.0004;
    scene.add(sun);

    const mats = {};
    const material = (name, color, roughness = 1, extra = {}) => (mats[name] = new THREE.MeshStandardMaterial({ color, roughness, ...extra }));
    material('ground', 0x454b3b); material('road', 0x373a35); material('stone', 0x77786b);
    material('plaster', 0x857e69); material('plaster2', 0x6c7063); material('wood', 0x493a2e);
    material('floor', 0x514536); material('eyes', 0xff493a, .3, {emissive:0xff1809,emissiveIntensity:4});
    material('blood', 0x542c25, .95);
    material('roof', 0x454843); material('dark', 0x242722); material('bark', 0x42382b);
    material('leaf', 0x364536); material('leaf2', 0x4c583d); material('metal', 0x747b70, .55, { metalness: .55 });
    material('water', 0x273634, .3); material('zskin', 0x71806e); material('coat', 0x494a3d);
    material('glow', 0xcafa78, .4, { emissive: 0x85c247, emissiveIntensity: 1.5 });
    material('beacon', 0xf18761, .35, { emissive: 0xff4930, emissiveIntensity: 2.7 });
    const box = new THREE.BoxGeometry(1, 1, 1);
    const sphere = new THREE.SphereGeometry(1, 9, 7);
    const cylinder = new THREE.CylinderGeometry(1, 1, 1, 8);
    const cone = new THREE.ConeGeometry(1, 1, 7);
    const addMesh = (geo, mat, x, y, z, sx, sy, sz, parent = scene) => {
      const m = new THREE.Mesh(geo, mat);
      m.position.set(x, y, z); m.scale.set(sx, sy, sz);
      m.castShadow = geo !== box || sy > .5; m.receiveShadow = true;
      parent.add(m); return m;
    };

    addMesh(box, mats.ground, 0, -.45, 0, 148, .8, 148);
    addMesh(box, mats.road, 0, -.025, 3, 5.3, .09, 116);
    for (let i = 0; i < 28; i++) {
      const z = -54 + i * 4.2;
      addMesh(box, mats.stone, 0, .025, z, .12, .025, 1.7);
    }

    const houses = [
      {x:-16,z:-15,w:9,d:8,h:5,broken:true},{x:14,z:-21,w:10,d:8,h:5.6,broken:false},
      {x:-18,z:7,w:9,d:8,h:5,broken:false},{x:16,z:4,w:10,d:9,h:5,broken:true},
      {x:-12,z:29,w:11,d:9,h:5.3,broken:true},{x:12,z:31,w:9,d:8,h:5,broken:false},
      {x:-29,z:-34,w:10,d:9,h:5,broken:false},{x:29,z:-39,w:9,d:9,h:5.4,broken:true},
      {x:-28,z:37,w:9,d:8,h:5,broken:true},{x:29,z:39,w:10,d:8,h:5,broken:false}
    ];
    const obstacles = [];
    function addWall(cx,cz,width,depth,height,wallMat){
      addMesh(box,wallMat,cx,height/2,cz,width,height,depth);
      obstacles.push({x:cx,z:cz,rx:width/2+.12,rz:depth/2+.12});
    }
    for (const h of houses) {
      const wallMat = Math.random() > .5 ? mats.plaster : mats.plaster2;
      const front=h.z+h.d/2,back=h.z-h.d/2,doorWidth=1.8,frontWidth=(h.w-doorWidth)/2;
      addMesh(box,mats.floor,h.x,.04,h.z,h.w-.45,.08,h.d-.45);
      addWall(h.x,back,h.w,.4,h.h,wallMat);
      addWall(h.x-h.w/2,h.z,.4,h.d, h.h,wallMat);
      addWall(h.x+h.w/2,h.z,.4,h.d, h.h,wallMat);
      addWall(h.x-(doorWidth+frontWidth)/2,front,frontWidth,.4,h.h,wallMat);
      addWall(h.x+(doorWidth+frontWidth)/2,front,frontWidth,.4,h.h,wallMat);
      addMesh(box,wallMat,h.x,h.h-.4,front,doorWidth,.8,.4);
      addMesh(box,mats.wood,h.x-doorWidth/2+.05,1.05,front-.27,.12,2.1,.12);
      addMesh(box,mats.wood,h.x+doorWidth/2-.05,1.05,front-.27,.12,2.1,.12);
      addMesh(box,mats.wood,h.x,2.12,front-.27,1.95,.12,.12);
      const openDoor=addMesh(box,mats.wood,h.x+doorWidth/2-.18,1.05,front-.3,.09,2.05,1.2);
      openDoor.rotation.y=-.85;
      const windowX=h.x-h.w*.28,windowY=h.h*.58,windowZ=front+.22;
      addMesh(box,mats.dark,windowX,windowY,windowZ,1.05,1.1,.07);
      addMesh(box,mats.dark,h.x+h.w*.28,windowY,windowZ,1.05,1.1,.07);
      for(const wx of [windowX,h.x+h.w*.28]){
        addMesh(box,mats.wood,wx-.55,windowY,windowZ+.05,.08,1.22,.07);
        addMesh(box,mats.wood,wx+.55,windowY,windowZ+.05,.08,1.22,.07);
        addMesh(box,mats.wood,wx,windowY-.56,windowZ+.05,1.16,.08,.07);
        addMesh(box,mats.wood,wx,windowY+.56,windowZ+.05,1.16,.08,.07);
      }
      if(!h.broken||Math.random()>.35){
        for(const side of [-1,1]){
          const roof=addMesh(box,mats.roof,h.x+side*h.w*.22,h.h+.82,h.z,h.w*.59,.3,h.d*1.1);
          roof.rotation.z=side*.37;
        }
      }
      const tableX=h.x-.65,tableZ=h.z-.5;
      addMesh(box,mats.wood,tableX,.95,tableZ,1.65,.13,.82);
      for(const side of [-1,1])for(const end of [-1,1])
        addMesh(box,mats.wood,tableX+side*.68,.47,tableZ+end*.28,.11,.88,.11);
      addMesh(box,mats.dark,h.x+.78,.64,h.z-.9,1.05,1.2,.24);
      for(let shelf=0;shelf<2;shelf++)
        addMesh(box,mats.wood,h.x+.78,.45+shelf*.52,h.z-1.05,1.12,.08,.38);
      if (h.broken) {
        for (let i=0;i<8;i++) {
          const plank=addMesh(box,i%3===0?mats.plaster2:mats.wood,h.x+(Math.random()-.5)*h.w,.13,h.z+(Math.random()-.5)*h.d,1.4,.2,.32);
          plank.rotation.y=Math.random()*Math.PI;
        }
      }
    }

    for (let i=0;i<68;i++) {
      const a = Math.random()*Math.PI*2, r=22+Math.random()*46, x=Math.sin(a)*r, z=Math.cos(a)*r;
      if (Math.abs(x)<5.3 || houses.some(h=>Math.abs(x-h.x)<h.w/2+2&&Math.abs(z-h.z)<h.d/2+2)) continue;
      const height=3.4+Math.random()*3.8;
      if(i%11===0){
        const trunk=addMesh(cylinder,mats.bark,x+.55,.34,z,.43,.68,.43);trunk.rotation.z=.17;
        const fallen=addMesh(cylinder,mats.bark,x+1.9,.36,z-.25,.35,.38,2.8);fallen.rotation.x=.2;fallen.rotation.z=.32;
        continue;
      }
      addMesh(cylinder,mats.bark,x,height*.37,z,.42,height*.75,.42);
      addMesh(cone,i%3===0?mats.leaf2:mats.leaf,x,height*.89,z,2.5+Math.random()*1.4,height*.85,2.5+Math.random()*1.4);
      if(i%7===0) addMesh(cone,mats.leaf,x,height*1.35,z,1.9,height*.7,1.9);
    }
    for(let i=0;i<24;i++){
      const x=(Math.random()-.5)*75,z=(Math.random()-.5)*100;
      if(Math.abs(x)<4||houses.some(h=>Math.abs(x-h.x)<7&&Math.abs(z-h.z)<7))continue;
      const rock=addMesh(sphere,mats.stone,x,.15+Math.random()*.2,z,.35+Math.random()*.7,.25+Math.random()*.38,.35+Math.random()*.6);
      rock.rotation.y=Math.random()*2;
    }

    const car=new THREE.Group();car.position.set(-2.2,0,24);car.rotation.y=.18;scene.add(car);
    addMesh(box,mats.road,0,.72,0,2.35,.75,4.3,car);
    addMesh(box,mats.metal,0,1.36,-.35,1.9,.72,2.05,car);
    addMesh(box,mats.dark,0,1.4,-1.12,1.68,.52,.045,car);
    for(const side of [-1,1])for(const end of [-1,1]){
      const wheel=addMesh(cylinder,mats.dark,side*1.13,.42,end*1.35,.43,.25,.43,car);
      wheel.rotation.z=Math.PI/2;
    }
    addMesh(box,mats.beacon,-.82,.76,-2.14,.32,.16,.08,car);
    addMesh(box,mats.dark,.82,.76,-2.14,.32,.16,.08,car);

    const beaconRoot = new THREE.Group();
    beaconRoot.position.set(31, 0, -49);
    scene.add(beaconRoot);
    addMesh(box,mats.metal,0,2.3,0,.32,4.6,.32,beaconRoot);
    addMesh(box,mats.metal,0,4.55,0,2.4,.12,.12,beaconRoot);
    const beaconLamp=addMesh(sphere,mats.beacon,1.04,4.48,0,.3,.3,.3,beaconRoot);
    const beaconLight=new THREE.PointLight(0xff5138,8,18);beaconLight.position.set(1,4.5,0);beaconRoot.add(beaconLight);
    for(let i=0;i<3;i++){
      const drum=addMesh(cylinder,mats.metal,(i-1)*.8,.35,1.15,.33,.7,.33,beaconRoot);
      drum.rotation.z=Math.PI/2;
    }
    addMesh(box,mats.wood,0,.07,-1.2,3,.14,2,beaconRoot);

    const player = { x:0,z:24,y:1.7,vx:0,vy:0,yaw:0,pitch:0,health:100,stamina:100,phone:100,inventory:{fuse:0,battery:0,core:0},gun:false,ammo:0,kills:0,score:0,crouch:false };
    const loot=[];
    const lootDefinitions=[
      {type:'fuse',count:3,positions:[[-16,-15],[14,-21],[-18,7],[16,4],[-12,29],[12,31],[-29,-34],[29,39]]},
      {type:'battery',count:2,positions:[[-18,7],[16,4],[-12,29],[12,31],[-29,-34],[29,39]]},
      {type:'core',count:1,positions:[[29,-39],[-28,37],[12,31],[-16,-15]]},
      {type:'gun',count:1,positions:[[16,4]]}
    ];
    for(const def of lootDefinitions){
      const picks=[...def.positions].sort(()=>Math.random()-.5).slice(0,def.count);
      for(const [hx,hz] of picks){
        const house=houses.find(h=>h.x===hx&&h.z===hz);
        const x=hx+(Math.random()-.5)*(house.w-2.5);
        const z=hz+(Math.random()-.5)*(house.d-2.5);
        const root=new THREE.Group();root.position.set(x,.85,z);scene.add(root);
        const mesh=def.type==='gun'?addMesh(box,mats.metal,0,0,0,.9,.16,.19,root):addMesh(box,mats.glow,0,0,0,.36,.36,.36,root);
        if(def.type==='gun'){addMesh(box,mats.dark,.4,-.12,0,.36,.2,.22,root);mesh.rotation.y=-.3;}
        const light=new THREE.PointLight(def.type==='gun'?0xff8b3c:0xafff63,def.type==='gun'?3.2:1.8,def.type==='gun'?8:5);light.position.y=.15;root.add(light);
        loot.push({type:def.type,root,baseY:.85,found:false});
      }
    }

    const enemies=[];
    for(const [x,z] of [[-3,-14],[5,-31],[-7,2],[6,19],[-23,23],[23,16],[25,-8],[-35,-18],[4,43]]){
      const g=new THREE.Group();g.position.set(x,0,z);scene.add(g);
      addMesh(box,mats.coat,0,1.08,0,.68,1.08,.43,g);
      const head=addMesh(sphere,mats.zskin,0,1.85,0,.38,.42,.36,g);
      addMesh(box,mats.eyes,-.145,1.9,-.316,.095,.075,.035,g);addMesh(box,mats.eyes,.145,1.9,-.316,.095,.075,.035,g);
      addMesh(box,mats.blood,0,1.65,-.325,.2,.08,.035,g);
      addMesh(box,mats.wood,0,1.48,-.24,.18,.12,.12,g);
      addMesh(box,mats.blood,-.23,1.15,-.23,.16,.34,.035,g);
      const arms=[];
      for(const side of [-1,1]){
        const arm=addMesh(box,mats.zskin,side*.48,1.23,-.05,.23,.82,.24,g);arm.rotation.z=side*.24;
        arms.push(arm);
        addMesh(box,mats.blood,side*.5,.97,-.19,.25,.24,.08,g);
        addMesh(box,mats.zskin,side*.19,.48,0,.2,.7,.22,g);
      }
      enemies.push({group:g,health:3,alive:true,speed:1.12+Math.random()*.35,attack:0,phase:Math.random()*4,head,arms});
    }

    const rainPositions=new Float32Array(280*3);
    for(let i=0;i<280;i++){rainPositions[i*3]=(Math.random()-.5)*100;rainPositions[i*3+1]=Math.random()*26;rainPositions[i*3+2]=(Math.random()-.5)*100;}
    const rainGeometry=new THREE.BufferGeometry();rainGeometry.setAttribute('position',new THREE.BufferAttribute(rainPositions,3));
    const rain=new THREE.Points(rainGeometry,new THREE.PointsMaterial({color:0xcad8dc,size:.09,transparent:true,opacity:0,depthWrite:false}));scene.add(rain);

    let gameStarted=false,gameEnded=false,paused=false,phoneOpen=false,elapsed=0,toastTimer=0,shotCooldown=0;
    let last=performance.now(),locked=false,cinematicActive=true,hudTimer=0;
    const cinematicStarted=performance.now();
    const totalSeconds=900;
    const keys=new Set();
    const clockVector=new THREE.Vector3();
    const dir=new THREE.Vector3();
    const raycaster=new THREE.Raycaster();
    const rayTargets=[];
    for(const e of enemies)rayTargets.push(e.head);
    window.addEventListener('resize',()=>{camera.aspect=innerWidth/innerHeight;camera.updateProjectionMatrix();renderer.setSize(innerWidth,innerHeight);renderer.setPixelRatio(Math.min(devicePixelRatio,1.6));});
    document.addEventListener('keydown',e=>{
      if(['Space','ArrowUp','ArrowDown','ArrowLeft','ArrowRight'].includes(e.code))e.preventDefault();
      keys.add(e.code);
      if(e.repeat)return;
      if(e.code==='KeyQ'&&gameStarted&&!gameEnded)togglePhone();
      if(e.code==='KeyE'&&gameStarted&&!gameEnded){if(phoneOpen)togglePhone(false);else interact();}
      if(e.code==='KeyR'&&player.gun&&player.ammo===0){player.ammo=6;showToast('RIFLE RELOADED · 6 ROUNDS');updateHUD();}
      if(e.code==='Escape'&&gameStarted&&!gameEnded){if(phoneOpen)togglePhone(false);else if(!paused)pauseGame();else resumeGame();}
    });
    document.addEventListener('keyup',e=>keys.delete(e.code));
    document.addEventListener('mousemove',e=>{
      if(!gameStarted||paused||phoneOpen||gameEnded)return;
      player.yaw-=e.movementX*.0021;player.pitch-=e.movementY*.0021;
      player.pitch=THREE.MathUtils.clamp(player.pitch,-1.25,1.25);
    });
    document.addEventListener('pointerlockchange',()=>{const wasLocked=locked;locked=document.pointerLockElement===renderer.domElement;if(wasLocked&&!locked&&gameStarted&&!gameEnded&&!paused&&!phoneOpen)pauseGame();});
    renderer.domElement.addEventListener('click',()=>{if(gameStarted&&!paused&&!phoneOpen&&!locked){renderer.domElement.requestPointerLock();return;}if(locked&&player.gun)shoot();});
    $('start-button').addEventListener('click',()=>{gameStarted=true;$('title-screen').classList.add('hidden');$('hud').classList.add('active');updateHUD();renderer.domElement.requestPointerLock();showToast('GREYWOOD · DAY 1 · FIND SHELTER');});
    $('skip-film').addEventListener('click',endCinematic);
    $('resume-button').addEventListener('click',resumeGame);
    $('close-phone').addEventListener('click',()=>togglePhone(false));
    $('restart-button').addEventListener('click',()=>location.reload());
    function pauseGame(){if(paused)return;paused=true;$('pause-screen').classList.add('open');if(document.pointerLockElement)document.exitPointerLock();}
    function resumeGame(){paused=false;$('pause-screen').classList.remove('open');renderer.domElement.requestPointerLock();}
    function togglePhone(force){phoneOpen=force===undefined?!phoneOpen:force;$('phone').classList.toggle('open',phoneOpen);if(phoneOpen&&document.pointerLockElement)document.exitPointerLock();else if(!phoneOpen&&gameStarted&&!paused&&!gameEnded)renderer.domElement.requestPointerLock();}
    function showToast(text){const el=$('toast');el.textContent=text;el.classList.add('show');toastTimer=2.2;}
    function updateHUD(){
      const day=Math.min(10,Math.floor(elapsed/90)+1),dayProgress=(elapsed%90)/90;
      const minutes=Math.floor(6*60+dayProgress*16*60),hours=Math.floor(minutes/60)%24,mins=minutes%60;
      const storm=Math.min(100,8+(day-1)*8+Math.floor(dayProgress*8));
      $('day-label').textContent=`DAY ${String(day).padStart(2,'0')} / 10`;
      $('clock-label').textContent=`${String(hours).padStart(2,'0')}:${String(mins).padStart(2,'0')} · GREYWOOD`;
      $('storm-number').textContent=String(storm).padStart(2,'0');$('storm-fill').style.width=`${storm}%`;
      $('health-number').textContent=Math.ceil(player.health);$('health-fill').style.width=`${player.health}%`;
      $('stamina-number').textContent=Math.ceil(player.stamina);$('stamina-fill').style.width=`${player.stamina}%`;
      $('phone-number').textContent=`${Math.floor(player.phone)}%`;$('phone-charge').textContent=`BATTERY ${Math.floor(player.phone)}%`;
      $('parts-label').textContent=`F ${player.inventory.fuse}/3 · B ${player.inventory.battery}/2 · C ${player.inventory.core}/1`;
      $('ammo-label').textContent=player.gun?`${player.ammo} / ∞`:'NOT FOUND';$('kills-label').textContent=player.kills;$('score-label').textContent=String(player.score).padStart(4,'0');
      setQuestLine('quest-progress',player.inventory.fuse>=3,`□ Fuses  ${player.inventory.fuse} / 3`);
      setQuestLine('quest-batteries',player.inventory.battery>=2,`□ Batteries  ${player.inventory.battery} / 2`);
      setQuestLine('quest-core',player.inventory.core>=1,`□ Radio core  ${player.inventory.core} / 1`);
      const ready=player.inventory.fuse>=3&&player.inventory.battery>=2&&player.inventory.core>=1;
      setQuestLine('quest-beacon',ready,ready?'□ Reach beacon · NE':'□ Restore beacon · NE');
      const prompt=$('prompt');
      prompt.textContent=getNearestInteraction()||(!locked&&!paused&&!phoneOpen?'CLICK TO LOOK AROUND':'');
      const angle=((player.yaw%(Math.PI*2))+Math.PI*2)%(Math.PI*2),dirs=['N','NE','E','SE','S','SW','W','NW'];
      $('compass').textContent=`${dirs[Math.round(angle/(Math.PI/4))%8]}  ·  ${dirs[(Math.round(angle/(Math.PI/4))+1)%8]}  ·  ${dirs[(Math.round(angle/(Math.PI/4))+2)%8]}`;
      const markerX=THREE.MathUtils.clamp(50+player.x*.48,4,94),markerY=THREE.MathUtils.clamp(50+player.z*.48,5,94);
      $('you-marker').style.left=`${markerX}%`;$('you-marker').style.top=`${markerY}%`;
      $('you-label').style.left=`${markerX-6}%`;$('you-label').style.top=`${markerY+3}%`;
      const night=THREE.MathUtils.smoothstep(dayProgress,.70,.90);
      rain.material.opacity=Math.min(.56,storm/210)*(dayProgress>.48?.45:1);
      scene.fog.density=.014+storm*.000095;
      const shade=1-night*.66;hemi.intensity=1.55*shade;sun.intensity=2.3*shade;
      const sky=new THREE.Color(0x7c877b).lerp(new THREE.Color(0x101722),night*.8);scene.background=sky;scene.fog.color.copy(sky);
    }
    function setQuestLine(id,complete,text){const el=$(id);el.textContent=`${complete?'✓':text.slice(0,1)}${text.slice(1)}`;el.classList.toggle('done',complete);}
    function endCinematic(){
      if(!cinematicActive)return;
      cinematicActive=false;$('cinematic').classList.add('finished');
      setTimeout(()=>{$('cinematic').style.display='none';$('title-screen').classList.add('ready');},650);
    }
    function updateCinematic(now){
      if(!cinematicActive)return;
      const duration=12800,progress=Math.min(1,(now-cinematicStarted)/duration);
      const shots=[
        {time:0,caption:'The road home was quiet. For the first time in weeks, <strong>you let yourself believe things might be okay.</strong>',credit:'An ordinary drive · Day zero',from:[0,2.5,34],to:[-2,1.4,25],look:[-2,1.3,22]},
        {time:.29,caption:'The dashboard flashes. The engine coughs once, twice—then dies. <strong>Your car rolls to a stop.</strong>',credit:'Engine failure · Mile marker 18',from:[1,2.1,29],to:[-2,1.5,23],look:[-2,1.1,24]},
        {time:.54,caption:'Through the trees: an abandoned village, broken houses, and one last <strong>rescue signal.</strong>',credit:'Greywood · Evacuation zone',from:[-8,3,20],to:[-1,2.1,8],look:[2,2.2,-14]},
        {time:.79,caption:'Something moves in the dark. Find the parts. Find a weapon. <strong>Get out before the storm.</strong>',credit:'10 days remaining · No backup',from:[17,4,28],to:[3,2,-2],look:[0,1.7,-23]}
      ];
      let shot=shots[0];for(const candidate of shots)if(progress>=candidate.time)shot=candidate;
      const next=shots[Math.min(shots.indexOf(shot)+1,shots.length-1)];
      const local=Math.min(1,(progress-shot.time)/(next.time-shot.time||1));
      const eased=local*local*(3-2*local);
      const start=shot.from.map((v,i)=>v+(shot.to[i]-v)*Math.min(1,local*.34));
      const end=next.from;
      camera.position.set(...start).lerp(new THREE.Vector3(...end),eased*.32);
      const lookTarget=new THREE.Vector3(...shot.look).lerp(new THREE.Vector3(...next.look),eased);
      camera.lookAt(lookTarget);
      $('film-credit').textContent=shot.credit;$('film-caption').innerHTML=shot.caption;
      $('film-progress').style.width=`${progress*100}%`;
      $('film-rec').textContent=`● REC   00:00:${String(Math.floor(progress*13)).padStart(2,'0')}`;
      if(progress>=1)endCinematic();
    }
    function getNearestInteraction(){
      let nearest=null,best=3.1;
      for(const item of loot){if(item.found)continue;const d=Math.hypot(item.root.position.x-player.x,item.root.position.z-player.z);if(d<best){nearest=item;best=d;}}
      const bd=Math.hypot(beaconRoot.position.x-player.x,beaconRoot.position.z-player.z);
      if(bd<4&&bd<best)return 'E  ·  ACTIVATE RESCUE BEACON';
      if(nearest)return `E  ·  SEARCH ${nearest.type==='gun'?'FIELD RIFLE':nearest.type.toUpperCase()}`;
      return '';
    }
    function interact(){
      const prompt=getNearestInteraction();if(!prompt)return;
      if(prompt.includes('BEACON')){
        const inv=player.inventory;
        if(inv.fuse>=3&&inv.battery>=2&&inv.core>=1)finishGame(true);
        else showToast(`MISSING PARTS · F ${inv.fuse}/3 · B ${inv.battery}/2 · C ${inv.core}/1`);
        return;
      }
      let best=null,dist=3.1;
      for(const item of loot){if(item.found)continue;const d=Math.hypot(item.root.position.x-player.x,item.root.position.z-player.z);if(d<dist){best=item;dist=d;}}
      if(!best)return;best.found=true;best.root.visible=false;
      if(best.type==='gun'){player.gun=true;player.ammo=6;showToast('RARE FIND · FIELD RIFLE · 6 ROUNDS');}
      else{player.inventory[best.type]++;showToast(`${best.type.toUpperCase()} RECOVERED · ${player.inventory[best.type]} FOUND`);}
      updateHUD();
    }
    function shoot(){
      if(shotCooldown>0)return;shotCooldown=.42;
      if(player.ammo<=0){showToast('EMPTY · PRESS R TO RELOAD');return;}
      player.ammo--;raycaster.setFromCamera(new THREE.Vector2(0,0),camera);raycaster.far=42;
      let hit=false;
      for(const e of enemies){if(!e.alive)continue;const hits=raycaster.intersectObject(e.group,true);if(hits.length){e.health--;hit=true;if(e.health<=0){e.alive=false;e.group.visible=false;player.kills++;player.score+=150;showToast('INFECTED NEUTRALIZED · +150');}else showToast('HIT · KEEP MOVING');break;}}
      if(!hit&&player.ammo===0)showToast('LAST ROUND · RELOAD WITH R');updateHUD();
    }
    function finishGame(won){
      gameEnded=true;if(document.pointerLockElement)document.exitPointerLock();
      $('pause-screen').classList.remove('open');$('phone').classList.remove('open');$('end-screen').classList.remove('hidden');
      $('endcard').classList.toggle('failed',!won);
      $('end-eyebrow').textContent=won?'TRANSMISSION CONFIRMED':'GREYWOOD LOST TO THE STORM';
      $('end-title').textContent=won?'YOU’RE OUT.':'SIGNAL LOST.';
      $('end-copy').textContent=won?'The beacon cuts through the storm. A rescue craft answers. Greywood disappears beneath the clouds—but you made it out.':'The storm swallowed the beacon, the village, and your last chance at rescue. Greywood is quiet again.';
      const secs=Math.floor(elapsed),days=Math.floor(secs/90),gameHours=Math.floor((secs%90)/90*16),gameMinutes=Math.floor(((secs%90)/90*16%1)*60);
      $('end-score').textContent=String(player.score+(won?Math.max(0,Math.floor((totalSeconds-elapsed)*2)):0)).padStart(4,'0');
      $('end-time').textContent=`${days}D ${String(gameHours).padStart(2,'0')}H ${String(gameMinutes).padStart(2,'0')}M`;
      $('end-kills').textContent=player.kills;
    }

    function blocked(x,z){
      if(Math.abs(x)>70||Math.abs(z)>70)return true;
      return obstacles.some(o=>Math.abs(x-o.x)<o.rx&&Math.abs(z-o.z)<o.rz);
    }
    function tick(dt){
      if(!gameStarted||paused||gameEnded)return;
      elapsed+=dt;
      if(elapsed>=totalSeconds){finishGame(false);return;}
      if(shotCooldown>0)shotCooldown-=dt;
      if(toastTimer>0){toastTimer-=dt;if(toastTimer<=0)$('toast').classList.remove('show');}
      if(phoneOpen){player.phone=Math.max(0,player.phone-dt*.13);if(player.phone===0){togglePhone(false);showToast('PHONE BATTERY DEPLETED');}}
      const day=Math.floor(elapsed/90)+1;
      if(day>=6){player.health=Math.max(0,player.health-dt*(day>=10?1.05:day>=9?.55:day>=8?.3:day>=7?.16:.07));if(player.health<=0){updateHUD();finishGame(false);return;}}
      const isCrouching=keys.has('ControlLeft')||keys.has('ControlRight');player.crouch=isCrouching;
      const sprint=(keys.has('ShiftLeft')||keys.has('ShiftRight'))&&player.stamina>1&&!isCrouching&&!phoneOpen;
      const forward=phoneOpen?0:(keys.has('KeyW')?1:0)-(keys.has('KeyS')?1:0);
      const strafe=phoneOpen?0:(keys.has('KeyD')?1:0)-(keys.has('KeyA')?1:0);
      dir.set(strafe,0,-forward);
      if(dir.lengthSq()>0){
        dir.normalize().applyAxisAngle(new THREE.Vector3(0,1,0),player.yaw);
        const speed=sprint?7.7:isCrouching?2.1:4.5;
        const nx=player.x+dir.x*speed*dt,nz=player.z+dir.z*speed*dt;
        if(!blocked(nx,player.z))player.x=nx;if(!blocked(player.x,nz))player.z=nz;
        if(sprint)player.stamina=Math.max(0,player.stamina-dt*20);
      }
      if(!sprint)player.stamina=Math.min(100,player.stamina+dt*(isCrouching?13:8));
      if(keys.has('Space')&&player.y<=1.701){player.vy=6.2;keys.delete('Space');}
      player.vy-=18*dt;player.y+=player.vy*dt;if(player.y<1.7){player.y=1.7;player.vy=0;}
      const targetHeight=isCrouching?1.05:1.7;player._eye=THREE.MathUtils.damp(player._eye??1.7,targetHeight,12,dt);
      camera.position.set(player.x,player.y-1.7+player._eye,player.z);
      camera.rotation.set(player.pitch,player.yaw,0,'YXZ');
      const storm=Math.min(1,(elapsed/90/10));
      for(const e of enemies){
        if(!e.alive)continue;e.phase+=dt*4;
        const dx=player.x-e.group.position.x,dz=player.z-e.group.position.z,d=Math.hypot(dx,dz);
        const hearing=isCrouching?7:sprint?28:17;
        if(d<hearing&&d>.9){
          const s=e.speed*(1+storm*.5)*(isCrouching?.68:1);
          const nx=e.group.position.x+dx/d*s*dt,nz=e.group.position.z+dz/d*s*dt;
          if(!blocked(nx,e.group.position.z))e.group.position.x=nx;
          if(!blocked(e.group.position.x,nz))e.group.position.z=nz;
          e.group.rotation.y=Math.atan2(dx,dz);
          e.group.position.y=Math.abs(Math.sin(e.phase))*.045;
          e.arms[0].rotation.x=Math.sin(e.phase)*.34;e.arms[1].rotation.x=-Math.sin(e.phase)*.34;
        }
        if(d<1.45){e.attack-=dt;if(e.attack<=0){player.health-=7+storm*8;e.attack=1.15;showToast('INFECTED ATTACK · KEEP MOVING');if(player.health<=0){player.health=0;updateHUD();finishGame(false);return;}}}
      }
      for(const item of loot)if(!item.found){item.root.position.y=item.baseY+Math.sin(elapsed*2+item.root.position.x)*.1;item.root.rotation.y+=dt*.45;}
      beaconRoot.rotation.y=Math.sin(elapsed*.2)*.09;beaconLight.intensity=7+Math.sin(elapsed*2)*2;
      for(let i=0;i<rainPositions.length/3;i++){rainPositions[i*3+1]-=dt*(7+storm*10);if(rainPositions[i*3+1]<0){rainPositions[i*3+1]=24;rainPositions[i*3]=player.x+(Math.random()-.5)*75;rainPositions[i*3+2]=player.z+(Math.random()-.5)*75;}}
      rainGeometry.attributes.position.needsUpdate=true;rain.position.set(player.x,0,player.z);
      hudTimer+=dt;if(hudTimer>=.12){hudTimer=0;updateHUD();}
    }
    function animate(now){
      requestAnimationFrame(animate);const dt=Math.min((now-last)/1000,.05);last=now;
      updateCinematic(now);tick(dt);renderer.render(scene,camera);
    }
    camera.position.set(player.x,player.y,player.z);
    requestAnimationFrame(animate);
  </script>
</body>
</html>
