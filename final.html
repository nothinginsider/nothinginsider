<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nothing Dot Hub // v7.6</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Space+Mono&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg: #ffffff; --text: #000; --glass: rgba(245, 245, 245, 0.45); --dot: #d1d1d1; --accent: #ff2d2d; --border: rgba(0,0,0,0.06);
        }
        [data-theme="dark"] {
            --bg: #000; --text: #fff; --glass: rgba(20, 20, 20, 0.5); --dot: #222; --accent: #ff2d2d; --border: rgba(255,255,255,0.08);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; transition: 0.3s cubic-bezier(0.2, 0.8, 0.2, 1); }
        body { background: var(--bg); color: var(--text); font-family: 'Inter', sans-serif; min-height: 100vh; overflow-x: hidden; }

        body::before {
            content: ""; position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background-image: radial-gradient(var(--dot) 1.5px, transparent 1.5px);
            background-size: 30px 30px; z-index: -1;
        }

        .container { max-width: 450px; margin: auto; padding: 50px 20px 100px 20px; position: relative; z-index: 1; }

        .top-nav { display: flex; justify-content: space-between; align-items: center; margin-bottom: 40px; }
        .theme-ico { 
            width: 45px; height: 45px; background: var(--glass); border: 1px solid var(--border);
            border-radius: 50%; display: grid; place-items: center; cursor: pointer; backdrop-filter: blur(15px);
        }
        h1 { font-size: 2.5rem; font-weight: 900; letter-spacing: -2px; line-height: 1; text-transform: uppercase; }

        .bento { display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px; margin-top: 20px; }
        .box { 
            background: var(--glass); backdrop-filter: blur(25px); -webkit-backdrop-filter: blur(25px);
            border: 1px solid var(--border); border-radius: 30px; padding: 25px; cursor: pointer;
        }
        .full { grid-column: span 2; }
        .box i { font-size: 22px; color: var(--accent); margin-bottom: 12px; display: block; }
        .box h2 { font-size: 16px; font-weight: 800; text-transform: uppercase; }

        /* SUPPORT ICON PULSE */
        .contact-trigger {
            position: fixed; bottom: 30px; right: 30px; width: 60px; height: 60px;
            background: var(--text); color: var(--bg); border-radius: 50%;
            display: grid; place-items: center; cursor: pointer; z-index: 2001;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2); animation: pulse 2s infinite;
        }
        @keyframes pulse { 0% { box-shadow: 0 0 0 0 rgba(255, 45, 45, 0.4); } 70% { box-shadow: 0 0 0 15px rgba(255, 45, 45, 0); } 100% { box-shadow: 0 0 0 0 rgba(255, 45, 45, 0); } }

        .contact-card {
            position: fixed; bottom: 100px; right: 30px; width: 280px;
            background: var(--glass); backdrop-filter: blur(35px); border: 1px solid var(--border);
            border-radius: 25px; padding: 25px; display: none; z-index: 2000;
        }
        .contact-card.active { display: block; animation: slideInUp 0.3s ease; }

        .view {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: transparent; z-index: 1000; display: none;
            padding: 40px 20px; overflow-y: auto; backdrop-filter: blur(45px);
        }
        .view.active { display: block; animation: fadeUp 0.4s ease forwards; }

        .back { font-family: 'Space Mono'; font-size: 11px; font-weight: 900; color: var(--accent); cursor: pointer; margin-bottom: 30px; display: inline-block; text-transform: uppercase; }
        
        .guide-glass { background: var(--glass); border-radius: 25px; padding: 25px; border: 1px solid var(--border); margin-bottom: 20px; }
        .ins-list { list-style: none; margin-bottom: 20px; }
        .ins-list li { font-size: 12px; margin-bottom: 10px; display: flex; gap: 10px; line-height: 1.4; }
        .ins-list li span { color: var(--accent); font-weight: 900; font-family: 'Space Mono'; }

        .v-input { width: 100%; padding: 18px; background: rgba(0,0,0,0.05); border: 1px solid var(--border); border-radius: 20px; color: var(--text); font-family: 'Space Mono'; margin: 15px 0; outline: none; text-align: center; font-size: 14px; }

        .dl-btn { 
            width: 100%; padding: 16px; background: var(--accent); color: #fff; border: none;
            border-radius: 15px; font-weight: 900; margin-top: 10px; cursor: pointer; position: relative; overflow: hidden;
        }
        .dl-btn.loading::before { content: ""; position: absolute; left: -100%; top: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.2); animation: load 2.5s linear forwards; }
        @keyframes load { to { left: 0; } }

        .res-box { background: var(--text); color: var(--bg); padding: 15px; border-radius: 20px; margin-top: 15px; display: none; font-family: 'Space Mono'; font-size: 12px; text-align: center; }

        @keyframes fadeUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes slideInUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body data-theme="light" onclick="closeSupportExternally(event)">

<div class="container">
    <div class="top-nav">
        <h1>Nothing<br>Community</h1>
        <div class="theme-ico" onclick="toggleTheme()"><i class="fa-solid fa-moon" id="tBtn"></i></div>
    </div>

    <div class="bento">
        <div class="box full" onclick="openView('softView')">
            <i class="fa-solid fa-download"></i>
            <h2>Software & Updates</h2>
        </div>
        <div class="box" onclick="openView('wallView')">
            <i class="fa-solid fa-palette"></i>
            <h2>Wallpapers</h2>
        </div>
        <div class="box" onclick="openView('tipsView')">
            <i class="fa-solid fa-lightbulb"></i>
            <h2>Tips</h2>
        </div>
        <div class="box full" onclick="openView('verifyView')">
            <i class="fa-solid fa-shield-halved"></i>
            <h2>Verify Device</h2>
        </div>
    </div>
</div>

<div class="contact-trigger" onclick="toggleContact(event)"><i class="fa-solid fa-headset"></i></div>
<div class="contact-card" id="contactCard" onclick="event.stopPropagation()">
    <h4 style="font-size:12px; text-transform:uppercase; margin-bottom:10px; color:var(--accent);">Support Hub</h4>
    <div style="font-size:11px; opacity:0.8; font-family:'Space Mono';">
        <p>Email: support@nothing.tech</p>
    </div>
</div>

<div id="softView" class="view">
    <div class="container" style="padding:0">
        <span class="back" onclick="closeView('softView')">← SYSTEM HUB</span>
        <div class="guide-glass">
            <h3>Update Instructions</h3>
            <ul class="ins-list">
                <li><span>01.</span> Download & Install Beta Tool APK below.</li>
                <li><span>02.</span> Place firmware ZIP in root/ota folder.</li>
                <li><span>03.</span> Open Settings > System > Beta Hub.</li>
                <li><span>04.</span> Select ZIP and start flashing.</li>
            </ul>
            <button class="dl-btn" onclick="handleDownload(this, 'BETA TOOL APK', 'toolRes', 'https://example.com/tool.apk')"><span>DOWNLOAD BETA TOOL</span></button>
            <div id="toolRes" class="res-box"></div>
        </div>
        <div class="bento" id="phoneContainer" style="grid-template-columns: 1fr 1fr;"></div>
        <div id="logArea" style="background:var(--text); color:var(--bg); border-radius:25px; padding:25px; margin-top:20px; display:none;">
            <h3 id="selName"></h3>
            <p id="selLog" style="font-family:'Space Mono'; font-size:11px; opacity:0.6; margin:15px 0; white-space:pre-line;"></p>
            <button id="firmBtn" class="dl-btn" style="background:var(--bg); color:var(--text)" onclick="triggerFirmware()"><span>DOWNLOAD ZIP</span></button>
            <div id="firmRes" class="res-box" style="background:var(--bg); color:var(--text); border:1px solid var(--border);"></div>
        </div>
    </div>
</div>

<div id="wallView" class="view">
    <div class="container" style="padding:0">
        <span class="back" onclick="closeView('wallView')">← GALLERY</span>
        <div class="bento" id="wallGrid"></div>
    </div>
</div>

<div id="verifyView" class="view">
    <div class="container" style="padding:0">
        <span class="back" onclick="closeView('verifyView')">← AUTHENTICATION</span>
        <div class="guide-glass">
            <h3>Product Verification</h3>
            <input type="text" id="vID" class="v-input" placeholder="ENTER IMEI">
            <button class="dl-btn" onclick="checkAuth(this)"><span>ANALYZE DEVICE</span></button>
            <div id="vResult" class="res-box"></div>
        </div>
    </div>
</div>

<div id="tipsView" class="view"><div class="container" style="padding:0"><span class="back" onclick="closeView('tipsView')">← FEATURES</span><div class="box full"><h2>Tips</h2><p style="font-size:12px; opacity:0.6;">Music Viz: Sync lights with audio.</p></div></div></div>

<script>
    const phoneDB = {
        'Phone (1)': { log: '• NOS 2.5.5 Stable', url: 'https://phone1-link.zip' },
        'Phone (2)': { log: '• NOS 2.6.0 Beta', url: 'https://phone2-link.zip' },
        'Phone (2a)': { log: '• NOS 2.5.5.a', url: 'https://phone2a-link.zip' },
        'CMF Phone 1': { log: '• v1.0.5 Patch', url: 'https://cmf-link.zip' }
    };

    const wallDB = [
        { img: 'https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe', dl: 'https://wall-link-1.jpg' },
        { img: 'https://images.unsplash.com/photo-1634017839464-5c339ebe3cb4', dl: 'https://wall-link-2.jpg' }
    ];

    let currentSelectedPhone = "";

    function init() {
        document.getElementById('phoneContainer').innerHTML = Object.keys(phoneDB).map(p => `<div class="box" style="padding:20px; text-align:center; font-size:12px; font-weight:800;" onclick="showLog('${p}')">${p}</div>`).join('');
        
        document.getElementById('wallGrid').innerHTML = wallDB.map((w, i) => `
            <div class="box" style="padding:10px;">
                <img src="${w.img}" style="width:100%; border-radius:20px; aspect-ratio:9/16; object-fit:cover;">
                <button class="dl-btn" style="padding:10px; font-size:10px;" onclick="handleDownload(this, 'WALLPAPER', 'wallRes${i}', '${w.dl}')"><span>DOWNLOAD</span></button>
                <div id="wallRes${i}" class="res-box" style="padding:10px; font-size:9px;"></div>
            </div>
        `).join('');
    }

    // --- FIX: ACTUAL DOWNLOAD TRIGGER LOGIC ---
    function handleDownload(btn, type, resId, url) {
        const res = document.getElementById(resId);
        btn.classList.add('loading');
        btn.querySelector('span').innerText = "PREPARING...";
        
        setTimeout(() => {
            btn.classList.remove('loading');
            btn.querySelector('span').innerText = "DONE ✅";
            
            // Create hidden link to force download
            const link = document.createElement('a');
            link.href = url;
            link.download = ''; // Some browsers need this
            link.target = '_blank';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);

            if(res) {
                res.style.display = 'block';
                res.innerHTML = `<b style="color:#00ff00;">${type} SENT TO BROWSER</b>`;
            }
        }, 2000);
    }

    function triggerFirmware() {
        const btn = document.getElementById('firmBtn');
        handleDownload(btn, 'FIRMWARE', 'firmRes', phoneDB[currentSelectedPhone].url);
    }

    function showLog(name) {
        currentSelectedPhone = name;
        document.getElementById('logArea').style.display = 'block';
        document.getElementById('selName').innerText = name;
        document.getElementById('selLog').innerText = phoneDB[name].log;
        document.getElementById('firmRes').style.display = 'none';
        document.getElementById('firmBtn').querySelector('span').innerText = "DOWNLOAD ZIP";
        document.getElementById('logArea').scrollIntoView({ behavior: 'smooth' });
    }

    function toggleContact(e) { e.stopPropagation(); document.getElementById('contactCard').classList.toggle('active'); }
    function closeSupportExternally() { document.getElementById('contactCard').classList.remove('active'); }

    function isValidIMEI(n) {
        if (n.length !== 15 || isNaN(n)) return false;
        let sum = 0;
        for (let i = 0; i < 15; i++) {
            let d = parseInt(n[i]);
            if (i % 2 !== 0) { d *= 2; if (d > 9) d -= 9; }
            sum += d;
        }
        return sum % 10 === 0;
    }

    function checkAuth(btn) {
        const id = document.getElementById('vID').value.trim();
        const res = document.getElementById('vResult');
        btn.classList.add('loading');
        btn.querySelector('span').innerText = "ANALYZING...";
        setTimeout(() => {
            btn.classList.remove('loading');
            btn.querySelector('span').innerText = "ANALYZE DEVICE";
            res.style.display = 'block';
            res.innerHTML = isValidIMEI(id) ? `<b style="color:#00ff00;">VERIFIED ✅</b>` : `<b style="color:#ff2d2d;">FAILED ❌</b>`;
        }, 2000);
    }

    function openView(id) { document.getElementById(id).classList.add('active'); }
    function closeView(id) { document.getElementById(id).classList.remove('active'); }
    function toggleTheme() {
        const b = document.body;
        const isDark = b.getAttribute('data-theme') === 'dark';
        b.setAttribute('data-theme', isDark ? 'light' : 'dark');
        document.getElementById('tBtn').className = isDark ? 'fa-solid fa-moon' : 'fa-solid fa-sun';
    }
    window.onload = init;
</script>
</body>
</html>
