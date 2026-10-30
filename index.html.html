<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<title>EcaHanie Arcade</title>
<style>
:root{--ink:#39463d;--sage:#91aa81;--pink:#e9a69d;--paper:#fffdfb;--line:#e8ece6;--soft:#f3f6f1;--avatar-color:#f7d8d3}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
body{margin:0;min-height:100dvh;display:grid;place-items:center;background:linear-gradient(135deg,#f9e5e4,#e0ebe3);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;color:var(--ink)}
button,input,select{font:inherit}button{border:0;cursor:pointer;touch-action:manipulation}
.app{width:min(100%,430px);height:min(900px,100dvh);background:var(--paper);display:flex;flex-direction:column;overflow:hidden;position:relative;box-shadow:0 15px 50px #64765b33}
@media(min-width:450px){.app{height:92dvh;border:6px solid var(--sage);border-radius:32px}}
body.dark-rest{background:#111720;color:#eef2ed}body.dark-rest .app{background:#202a34}
body.dark-rest header,body.dark-rest .stats,body.dark-rest .tray,body.dark-rest .topline{background:#303744;color:#f7f8f8}
header{padding:11px 13px;background:#f6dfe1;display:flex;align-items:center;justify-content:space-between;font-weight:800;border-bottom:1px solid var(--line);gap:5px}
.title{font-size:1rem}.pills{display:flex;gap:5px;align-items:center}.pill{background:white;border:1px solid #f1c8c4;border-radius:20px;padding:4px 7px;font-size:.76rem}
.screen{display:none;flex:1;min-height:0;flex-direction:column}.screen.active{display:flex}
.stats{padding:10px 14px;background:var(--soft);display:grid;gap:7px}.stat{display:grid;grid-template-columns:82px 1fr 30px;gap:8px;align-items:center;font-size:.79rem;font-weight:700}
.bar{height:10px;background:#e3e9e1;border-radius:9px;overflow:hidden}.fill{height:100%;width:100%;background:var(--sage);transition:width .25s}.fill.hungry{background:var(--pink)}
.pet-stage{flex:1;min-height:170px;display:grid;place-content:center;justify-items:center;gap:8px;background:radial-gradient(ellipse,#fff2ee 0,#fffdfb 65%)}
body.dark-rest .pet-stage{background:radial-gradient(ellipse,#293746 0,#202a34 65%)}
.bubble{background:white;border:2px solid #f2c9c4;border-radius:20px;padding:7px 12px;text-align:center;max-width:90%;font-size:.83rem}
body.dark-rest .bubble{background:#303744;border-color:#5c6874;color:white}
.avatar-wrap{width:138px;height:138px;border-radius:50%;background:var(--avatar-color);display:grid;place-items:center;position:relative;overflow:hidden;border:5px solid #ffffffaa;box-shadow:0 7px 22px #00000016}
.avatar-emoji{font-size:5.6rem;line-height:1}.avatar-photo{width:100%;height:100%;object-fit:cover;display:none}
.expression{position:absolute;right:1px;bottom:1px;border-radius:50%;width:38px;height:38px;display:grid;place-items:center;background:white;font-size:1.35rem;border:2px solid #fff}
.pet-name{font-weight:800}.mood-label{font-size:.78rem;color:#69746c;margin-top:-6px}
body.dark-rest .mood-label{color:#c9d2cc}
.tray{padding:10px;background:white;border-top:1px solid var(--line);display:grid;gap:8px}
.icon-row{display:flex;justify-content:space-around;gap:8px}.icon-btn{width:56px;height:48px;border-radius:15px;background:#edf2e9;font-size:1.5rem}.icon-btn.pink{background:#f8e2df}
.btn{background:var(--sage);color:white;padding:9px 11px;border-radius:12px;font-weight:750}.btn.pink{background:var(--pink);color:#513e3b}.btn.light{background:#edf2e9;color:var(--ink)}
.btn:active,.icon-btn:active{transform:scale(.97)}.row{display:flex;gap:8px}.row>*{flex:1}
.scroll{overflow:auto;padding:13px;flex:1}.card{background:white;border:1px solid var(--line);border-radius:15px;padding:11px;margin-bottom:9px;display:flex;align-items:center;justify-content:space-between;gap:8px}
.card h3{font-size:.94rem;margin:0 0 3px}.card p{font-size:.76rem;color:#69746c;margin:0}
.topline{padding:9px 12px;display:flex;align-items:center;justify-content:space-between;background:var(--soft);font-weight:750}
.game-area{flex:1;min-height:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;padding:10px}
#arcade .game-area{touch-action:none;user-select:none;-webkit-user-select:none;-webkit-touch-callout:none}
canvas{width:min(100%,360px);height:auto;max-height:52vh;background:linear-gradient(#253450,#35424a);border-radius:14px;box-shadow:0 5px 18px #0002;touch-action:none;user-select:none;-webkit-user-select:none;-webkit-touch-callout:none}
.controls{display:flex;gap:7px;width:min(100%,360px)}.controls button{flex:1;min-height:43px;user-select:none;-webkit-user-select:none;-webkit-touch-callout:none}
.note{font-size:.8rem;text-align:center;min-height:20px}.level-picker{display:flex;align-items:center;gap:8px;font-size:.86rem;font-weight:700}
.level-picker select{padding:7px 9px;border:1px solid #dce5d9;border-radius:9px;background:white;color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(5,46px);grid-template-rows:repeat(5,46px);gap:3px;padding:4px;background:var(--sage);border-radius:9px}
.cell{width:46px;height:46px;background:white;border:0;text-align:center;font-size:1.15rem;font-weight:750;color:var(--ink);border-radius:3px}
.cell.fixed{background:#edf0eb;color:#455248}.cell.selected{background:#ffedb7;outline:2px solid #e4aa32;outline-offset:-2px}.cell.error{background:#ffd4d0;color:#9c2922}
.numpad{display:grid;grid-template-columns:repeat(5,48px);gap:6px}
.small{font-size:.75rem;color:#68746b;text-align:center}
.settings-backdrop{position:absolute;inset:0;background:#17201dbb;display:none;align-items:flex-end;z-index:5}
.settings-backdrop.open{display:flex}.settings{width:100%;max-height:88%;overflow:auto;background:var(--paper);border-radius:22px 22px 0 0;padding:16px;color:var(--ink)}
.setting-row{padding:9px 0;border-bottom:1px solid var(--line);display:grid;gap:6px}.setting-row label{font-weight:700;font-size:.86rem}
.setting-row input[type=text]{padding:9px;border:1px solid var(--line);border-radius:9px}.setting-row input[type=range]{width:100%}
.setting-row input[type=color]{width:52px;height:36px;border:0;padding:0;background:transparent}
.toggle-line{display:flex;align-items:center;justify-content:space-between;gap:12px}
.selfie-intro{font-size:.82rem;color:#5d6960;margin:4px 0 6px;text-align:center}
.selfie-progress{font-weight:800;font-size:.85rem;text-align:center;margin:0 0 4px}
.selfie-status{font-size:.8rem;text-align:center;min-height:20px;color:#7a5a20;margin:4px 0}
.selfie-item{display:grid;grid-template-columns:56px 1fr auto;gap:10px;align-items:center;padding:9px 6px;border-bottom:1px solid var(--line)}
.selfie-item.next{background:#fff6e0;border-radius:12px}
.selfie-thumb{width:56px;height:56px;border-radius:50%;background:var(--avatar-color);display:grid;place-items:center;font-size:1.7rem;overflow:hidden;border:2px solid #fff;box-shadow:0 2px 8px #0001}
.selfie-thumb img{width:100%;height:100%;object-fit:cover}
.selfie-item b{display:block;font-size:.9rem}.selfie-item span{font-size:.75rem;color:#68746b}
.selfie-actions{display:flex;gap:5px}
</style>
</head>
<body>
<div class="app">
  <header>
    <span class="title">🌸 EcaHanie Arcade</span>
    <div class="pills">
      <span class="pill">🔥 <b id="streak">1</b>d</span>
      <span class="pill">🪙 <b id="coins">50</b></span>
      <button class="btn light" aria-label="Settings" onclick="openSettings()">⚙️</button>
    </div>
  </header>

  <section id="home" class="screen active">
    <div class="stats">
      <div class="stat"><span>🍎 Hunger</span><div class="bar"><div id="hungerFill" class="fill hungry"></div></div><span id="hungerNum"></span></div>
      <div class="stat"><span>🌿 Energy</span><div class="bar"><div id="energyFill" class="fill"></div></div><span id="energyNum"></span></div>
      <div class="stat"><span>🫧 Clean</span><div class="bar"><div id="cleanFill" class="fill"></div></div><span id="cleanNum"></span></div>
    </div>
    <div class="pet-stage">
      <div id="speech" class="bubble">Welcome! Take good care of me 💕</div>
      <div class="avatar-wrap">
        <span id="avatarEmoji" class="avatar-emoji">🐱</span>
        <img id="avatarPhoto" class="avatar-photo" alt="Your avatar">
        <span id="expression" class="expression">😸</span>
      </div>
      <b id="petName" class="pet-name">Hanie</b>
      <span id="moodLabel" class="mood-label">feeling happy</span>
    </div>
    <div class="tray">
      <div class="icon-row">
        <button class="icon-btn pink" aria-label="Feed" title="Feed" onclick="feed()">🍓</button>
        <button class="icon-btn" aria-label="Rest" title="Rest" onclick="rest()">💤</button>
        <button class="icon-btn" aria-label="Clean" title="Clean" onclick="cleanPet()">🫧</button>
        <button class="icon-btn" aria-label="Record voice" title="Record voice" onclick="recordVoice()">🎙️</button>
      </div>
      <div class="row">
        <button class="btn" onclick="show('hub')">🎮 Mini-Game Hub</button>
        <button class="btn light" onclick="openSelfies()">🤳 Emotion selfies</button>
      </div>
      <input id="selfieInput" type="file" accept="image/*" capture="user" hidden>
    </div>
  </section>

  <section id="hub" class="screen">
    <div class="topline"><span>🎮 Mini-Game Hub</span><button class="btn light" onclick="show('home')">Home 🏠</button></div>
    <div class="scroll">
      <div class="card"><div><h3>🧩 Sudoku 5×5</h3><p>Easy, Medium, or Hard · +20 coins</p></div><button class="btn" onclick="startSudoku()">Play</button></div>
      <div class="card"><div><h3>🍓 Fruit Catcher</h3><p>Endless · game over after 3 dropped fruit · +1 coin per fruit</p></div><button class="btn" onclick="startGame('catcher')">Play</button></div>
      <div class="card"><div><h3>☁️ Sky Soarer</h3><p>Endless · game over after 3 crashes · +2 coins per gap</p></div><button class="btn" onclick="startGame('flyer')">Play</button></div>
      <div class="card"><div><h3>🚀 Star Blaster</h3><p>Endless · game over after 3 meteors slip by · +1 coin per hit</p></div><button class="btn" onclick="startGame('shooter')">Play</button></div>
      <div class="card"><div><h3>🏆 Best scores</h3><p id="records"></p></div></div>
      <p class="small">Your pet gets tired and dirty after each game.</p>
    </div>
  </section>

  <section id="sudoku" class="screen">
    <div class="topline"><span>🧩 Sudoku 5×5</span><button class="btn light" onclick="show('hub')">Exit</button></div>
    <div class="game-area">
      <label class="level-picker">Difficulty:
        <select id="sudokuLevel" onchange="startSudoku()">
          <option value="easy">Easy</option><option value="medium">Medium</option><option value="hard">Hard</option>
        </select>
      </label>
      <div id="sudokuMsg" class="note">Fill each row and column with 1–5, without repeats.</div>
      <div id="sudokuGrid" class="grid" role="grid" aria-label="5 by 5 Sudoku board"></div>
      <div class="numpad" aria-label="Number pad">
        <button class="btn" onclick="putNumber(1)">1</button><button class="btn" onclick="putNumber(2)">2</button>
        <button class="btn" onclick="putNumber(3)">3</button><button class="btn" onclick="putNumber(4)">4</button>
        <button class="btn" onclick="putNumber(5)">5</button>
      </div>
      <div class="row" style="max-width:280px;width:100%">
        <button class="btn light" onclick="putNumber(0)">Erase</button>
        <button class="btn pink" onclick="checkSudoku()">Check ✨</button>
      </div>
      <div class="small">5×5 variant: each row and column must contain 1–5 once.</div>
    </div>
  </section>

  <section id="arcade" class="screen">
    <div class="topline"><span id="gameTitle">Arcade</span><button class="btn light" onclick="endGame()">Exit</button></div>
    <div class="game-area" id="gameArea">
      <canvas id="gameCanvas" width="360" height="400" aria-label="Game play area"></canvas>
      <div class="small" id="gameHint"></div>
      <div class="controls" id="gameControls"></div>
    </div>
  </section>

  <div id="selfieBackdrop" class="settings-backdrop" onclick="selfieBackdropClick(event)">
    <div class="settings">
      <div class="topline" style="padding:0 0 9px;background:transparent">
        <b>🤳 Emotion selfies</b><button class="btn light" onclick="closeSelfies()">Done ✓</button>
      </div>
      <p class="selfie-intro">Take a selfie for each feeling! Your pet will show the matching photo whenever it feels that way.</p>
      <p id="selfieProgress" class="selfie-progress">0 of 5 selfies taken</p>
      <div id="selfieStatus" class="selfie-status" aria-live="polite"></div>
      <div id="selfieList"></div>
      <p class="small" style="margin-top:10px">Photos are saved only on this device.</p>
    </div>
  </div>

  <div id="settingsBackdrop" class="settings-backdrop" onclick="backdropClick(event)">
    <div class="settings">
      <div class="topline" style="padding:0 0 9px;background:transparent">
        <b>⚙️ Settings</b><button class="btn light" onclick="closeSettings()">Close ✕</button>
      </div>
      <div class="setting-row">
        <label for="nameInput">Pet name</label>
        <div class="row"><input id="nameInput" type="text" maxlength="18"><button class="btn" onclick="saveName()">Save</button></div>
      </div>
      <div class="setting-row">
        <label for="avatarColor">Avatar background color</label>
        <input id="avatarColor" type="color" value="#f7d8d3" oninput="setAvatarColor(this.value)">
      </div>
      <div class="setting-row">
        <div class="toggle-line"><label for="highPitch">High-pitch voice playback</label><input id="highPitch" type="checkbox" checked></div>
        <span class="small">Your recording plays back after about 1.5 seconds.</span>
      </div>
      <div class="setting-row">
        <div class="toggle-line"><label for="musicToggle">Background music</label><input id="musicToggle" type="checkbox" checked onchange="toggleMusic(this.checked)"></div>
        <label for="musicVolume">Music volume</label><input id="musicVolume" type="range" min="0" max="100" value="20" oninput="setMusicVolume(this.value)">
      </div>
      <div class="setting-row">
        <div class="toggle-line"><label for="sfxToggle">Sound effects</label><input id="sfxToggle" type="checkbox" checked onchange="setSfx(this.checked)"></div>
        <label for="sfxVolume">Sound-effects volume</label><input id="sfxVolume" type="range" min="0" max="100" value="55" oninput="setSfxVolume(this.value)">
      </div>
      <div class="setting-row">
        <button class="btn" onclick="closeSettings();openSelfies()">🤳 Manage emotion selfies</button>
        <button class="btn light" onclick="removeAllSelfies()">Remove all selfies and use cat avatar</button>
        <span class="small">Selfies are saved on this device. Voice recordings stay in this page session.</span>
      </div>
    </div>
  </div>
</div>

<script>
const $=id=>document.getElementById(id);
const defaults={coins:50,hunger:100,energy:100,clean:100,streak:1,name:"Hanie",best:{catcher:0,flyer:0,shooter:0},lastTick:Date.now(),avatarColor:"#f7d8d3",musicOn:true,musicVolume:20,sfxOn:true,sfxVolume:55,selfiePromptSeen:false};
let data;
try{data={...defaults,...JSON.parse(localStorage.getItem("ecahanie_req2")||"{}")}}catch{data={...defaults}}
data.best={...defaults.best,...(data.best||{})};
let restTimer=null,game=null,rafId=0,lastFrame=0;
let sudokuBoard=[],sudokuPuzzle=[],sudokuFixed=[],selectedCell=-1,sudokuDone=false;
const sudokuErrors=new Set();
let dragPointerId=null;
let recorder=null,recordedChunks=[],voiceUrl=null,audioCtx=null,musicTimer=null,musicIndex=0;

/* ---------- Emotion selfies ---------- */
const EMOTIONS=[
  {key:"happy",label:"Happy",emoji:"😸",tip:"Give a big smile 😄"},
  {key:"sad",label:"Sad",emoji:"😿",tip:"Make a sad, pouty face 😢"},
  {key:"hungry",label:"Hungry",emoji:"🍓",tip:"Open wide like you want a snack 😋"},
  {key:"dirty",label:"Dirty",emoji:"🫧",tip:"Scrunch your nose — yuck! 🤢"},
  {key:"tired",label:"Tired",emoji:"😴",tip:"Yawn or close your eyes 🥱"}
];
const SELFIE_KEY="ecahanie_selfies";
let selfies={};
try{selfies=JSON.parse(localStorage.getItem(SELFIE_KEY)||"{}")||{}}catch{selfies={}}
let pendingEmotion=null,moodOverride=null,moodTimer=null;

function saveSelfies(){
  try{localStorage.setItem(SELFIE_KEY,JSON.stringify(selfies));return true}
  catch{$("selfieStatus").textContent="Storage is full — these selfies will only last for this session.";return false}
}
function currentMood(){
  if(moodOverride)return moodOverride;
  if(restTimer)return "tired";
  if(data.clean<25)return "dirty";
  if(data.hunger<25)return "hungry";
  if(data.energy<25)return "tired";
  if(data.hunger<50||data.energy<50||data.clean<50)return "sad";
  return "happy";
}
function flashMood(mood,ms=4000){
  moodOverride=mood;clearTimeout(moodTimer);
  moodTimer=setTimeout(()=>{moodOverride=null;renderAvatar()},ms);
  renderAvatar();
}
function renderAvatar(){
  const mood=currentMood(),em=EMOTIONS.find(x=>x.key===mood),src=selfies[mood],photo=$("avatarPhoto");
  if(src){
    if(photo.getAttribute("src")!==src)photo.src=src;
    photo.alt=`${data.name} feeling ${em.label.toLowerCase()}`;
    photo.style.display="block";$("avatarEmoji").style.display="none";
  }else{
    photo.removeAttribute("src");photo.style.display="none";$("avatarEmoji").style.display="block";
  }
  $("expression").textContent=restTimer?"😴":em.emoji;
  $("moodLabel").textContent=restTimer?"sleeping… 💤":`feeling ${em.label.toLowerCase()}`;
}
function renderSelfieList(){
  const list=$("selfieList");list.innerHTML="";
  const next=EMOTIONS.find(em=>!selfies[em.key]);
  for(const em of EMOTIONS){
    const has=!!selfies[em.key];
    const item=document.createElement("div");
    item.className="selfie-item"+(next&&next.key===em.key?" next":"");

    const thumb=document.createElement("div");thumb.className="selfie-thumb";
    if(has){const img=document.createElement("img");img.src=selfies[em.key];img.alt=`${em.label} selfie`;thumb.appendChild(img)}
    else thumb.textContent=em.emoji;

    const text=document.createElement("div");
    const title=document.createElement("b");title.textContent=`${em.emoji} ${em.label}`;
    const sub=document.createElement("span");sub.textContent=has?"✓ Saved":em.tip;
    text.append(title,sub);

    const actions=document.createElement("div");actions.className="selfie-actions";
    const take=document.createElement("button");take.type="button";take.className="btn";
    take.textContent=has?"Retake":"📸 Take";take.onclick=()=>takeSelfie(em.key);
    actions.appendChild(take);
    if(has){
      const del=document.createElement("button");del.type="button";del.className="btn light";
      del.textContent="✕";del.setAttribute("aria-label",`Remove ${em.label} selfie`);
      del.onclick=()=>{delete selfies[em.key];saveSelfies();renderSelfieList();renderAvatar()};
      actions.appendChild(del);
    }
    item.append(thumb,text,actions);list.appendChild(item);
  }
  const count=EMOTIONS.filter(em=>selfies[em.key]).length;
  $("selfieProgress").textContent=`${count} of 5 selfies taken`;
}
function openSelfies(){
  renderSelfieList();
  const next=EMOTIONS.find(em=>!selfies[em.key]);
  $("selfieStatus").textContent=next?`Start with ${next.label}: ${next.tip}`:"All 5 emotions are ready! Tap Retake to change one.";
  $("selfieBackdrop").classList.add("open");
}
function closeSelfies(){
  $("selfieBackdrop").classList.remove("open");
  if(!data.selfiePromptSeen){data.selfiePromptSeen=true;save()}
}
function selfieBackdropClick(e){if(e.target===$("selfieBackdrop"))closeSelfies()}
function takeSelfie(key){pendingEmotion=key;$("selfieInput").click()}
function removeAllSelfies(){
  if(!Object.keys(selfies).length)return;
  if(!confirm("Remove all emotion selfies?"))return;
  selfies={};saveSelfies();renderAvatar();renderSelfieList();
  say("Back to my cat look! 🐱");
}
function resizeImage(file,size=320){
  return new Promise((resolve,reject)=>{
    const img=new Image(),url=URL.createObjectURL(file);
    img.onload=()=>{
      const side=Math.min(img.width,img.height),cv=document.createElement("canvas");
      cv.width=cv.height=size;
      cv.getContext("2d").drawImage(img,(img.width-side)/2,(img.height-side)/2,side,side,0,0,size,size);
      URL.revokeObjectURL(url);resolve(cv.toDataURL("image/jpeg",.82));
    };
    img.onerror=()=>{URL.revokeObjectURL(url);reject()};
    img.src=url;
  });
}
$("selfieInput").addEventListener("change",async e=>{
  const file=e.target.files&&e.target.files[0];e.target.value="";
  const key=pendingEmotion;pendingEmotion=null;
  if(!file||!key)return;
  try{selfies[key]=await resizeImage(file)}
  catch{$("selfieStatus").textContent="Sorry, that photo couldn't be loaded. Please try again.";return}
  const stored=saveSelfies();
  renderSelfieList();renderAvatar();effect(700);
  if(stored){
    const next=EMOTIONS.find(em=>!selfies[em.key]);
    $("selfieStatus").textContent=next?`Saved! Next: ${next.label} — ${next.tip}`:"All 5 emotions are ready! 🎉";
  }
  say("Your new selfie is ready! 🤳");
});

/* ---------- Pet care ---------- */
function save(){try{localStorage.setItem("ecahanie_req2",JSON.stringify(data))}catch{}}
function show(id){document.querySelectorAll(".screen").forEach(s=>s.classList.remove("active"));$(id).classList.add("active");if(id==="hub")renderRecords()}
function say(text){$("speech").textContent=text}
function update(){
  $("coins").textContent=data.coins;$("streak").textContent=data.streak;$("petName").textContent=data.name;
  for(const key of ["hunger","energy","clean"]){$(key+"Fill").style.width=data[key]+"%";$(key+"Num").textContent=data[key]}
  document.documentElement.style.setProperty("--avatar-color",data.avatarColor);
  renderAvatar();save();
}
function tickStats(){
  const interval=180000,ticks=Math.floor((Date.now()-data.lastTick)/interval);if(ticks<1)return;
  for(const key of ["hunger","energy","clean"])data[key]=Math.max(0,data[key]-4*ticks);
  data.lastTick+=ticks*interval;update();
}
setInterval(tickStats,10000);
function feed(){if(data.coins<10){say("Not enough coins—play a mini-game to earn more!");flashMood("sad");return}data.coins-=10;data.hunger=Math.min(100,data.hunger+30);say("Yum! That was delicious 🍓");effect(620);update()}
function rest(){clearTimeout(restTimer);document.body.classList.add("dark-rest");data.energy=Math.min(100,data.energy+35);say(`${data.name} is sleeping... Zzz 🌙`);restTimer=setTimeout(()=>{restTimer=null;document.body.classList.remove("dark-rest");say("That was a good nap! 💕");update()},15000);update()}
function cleanPet(){data.clean=100;say("All clean and fresh! 🫧");effect(750);update()}
function setAvatarColor(color){data.avatarColor=color;update()}
function openSettings(){$("nameInput").value=data.name;$("avatarColor").value=data.avatarColor;$("musicToggle").checked=data.musicOn;$("musicVolume").value=data.musicVolume;$("sfxToggle").checked=data.sfxOn;$("sfxVolume").value=data.sfxVolume;$("settingsBackdrop").classList.add("open")}
function closeSettings(){$("settingsBackdrop").classList.remove("open")}
function backdropClick(e){if(e.target===$("settingsBackdrop"))closeSettings()}
function saveName(){const v=$("nameInput").value.trim();if(v){data.name=v.slice(0,18);say(`Hello, ${data.name}! 💕`);update()}}

/* ---------- Audio ---------- */
function getAudio(){if(!audioCtx)audioCtx=new(window.AudioContext||window.webkitAudioContext)();if(audioCtx.state==="suspended")audioCtx.resume();return audioCtx}
function effect(freq=600){if(!data.sfxOn||!Number(data.sfxVolume))return;try{const ac=getAudio(),o=ac.createOscillator(),g=ac.createGain(),end=ac.currentTime+.13;o.frequency.value=freq;o.type="sine";g.gain.setValueAtTime(Number(data.sfxVolume)/100*.12,ac.currentTime);g.gain.exponentialRampToValueAtTime(.001,end);o.connect(g);g.connect(ac.destination);o.start();o.stop(end)}catch{}}
function setMusicVolume(v){data.musicVolume=Number(v);save()}
function setSfxVolume(v){data.sfxVolume=Number(v);save()}
function setSfx(v){data.sfxOn=v;save()}
function toggleMusic(v){data.musicOn=v;save();if(v)startMusic();else stopMusic()}
function startMusic(){stopMusic();const notes=[392,494,587,494,440,523,659,523];musicTimer=setInterval(()=>{if(!data.musicOn||!Number(data.musicVolume))return;try{const ac=getAudio(),o=ac.createOscillator(),g=ac.createGain(),end=ac.currentTime+.22;o.frequency.value=notes[musicIndex++%notes.length];o.type="sine";g.gain.setValueAtTime(Number(data.musicVolume)/100*.035,ac.currentTime);g.gain.exponentialRampToValueAtTime(.001,end);o.connect(g);g.connect(ac.destination);o.start();o.stop(end)}catch{}},430)}
function stopMusic(){clearInterval(musicTimer)}startMusic();

async function recordVoice(){
  if(recorder&&recorder.state==="recording"){recorder.stop();say("Finishing your voice recording...");return}
  if(!navigator.mediaDevices?.getUserMedia||!window.MediaRecorder){alert("Voice recording is not supported in this browser.");return}
  try{
    const stream=await navigator.mediaDevices.getUserMedia({audio:true});recordedChunks=[];recorder=new MediaRecorder(stream);
    recorder.ondataavailable=e=>{if(e.data.size)recordedChunks.push(e.data)};
    recorder.onstop=()=>{stream.getTracks().forEach(t=>t.stop());if(voiceUrl)URL.revokeObjectURL(voiceUrl);voiceUrl=URL.createObjectURL(new Blob(recordedChunks,{type:recorder.mimeType||"audio/webm"}));setTimeout(()=>{const a=new Audio(voiceUrl);a.playbackRate=$("highPitch").checked?1.5:1;a.play().catch(()=>{})},1500);say("Voice recording ready 🎙️")};
    recorder.start();say("Recording… tap the microphone again to stop.");
  }catch{alert("Please allow microphone access to record your voice.")}
}

/* ---------- 5×5 Sudoku: each row and column must contain 1–5 once ---------- */
function shuffleSudoku(values){
  for(let i=values.length-1;i>0;i--){
    const j=Math.floor(Math.random()*(i+1));
    [values[i],values[j]]=[values[j],values[i]];
  }
  return values;
}
function startSudoku(){
  stopGameLoop();
  sudokuDone=false;
  selectedCell=-1;
  sudokuErrors.clear();

  const symbols=shuffleSudoku([1,2,3,4,5]);
  const shift=Math.floor(Math.random()*5);

  sudokuBoard=Array.from({length:5},(_,r)=>
    Array.from({length:5},(_,c)=>symbols[(r+c+shift)%5])
  );
  sudokuPuzzle=sudokuBoard.map(row=>row.slice());

  const clueCount={easy:17,medium:13,hard:10}[$("sudokuLevel").value]||17;
  const spots=shuffleSudoku(Array.from({length:25},(_,i)=>i));

  for(const index of spots.slice(0,25-clueCount)){
    sudokuPuzzle[Math.floor(index/5)][index%5]=0;
  }

  sudokuFixed=sudokuPuzzle.map(row=>row.map(value=>value!==0));
  $("sudokuMsg").textContent="Fill each row and column with 1–5, without repeats.";
  renderSudoku();
  show("sudoku");
}
function renderSudoku(){
  const grid=$("sudokuGrid");
  grid.innerHTML="";

  for(let r=0;r<5;r++){
    for(let c=0;c<5;c++){
      const index=r*5+c;
      const value=sudokuPuzzle[r][c];
      const cell=document.createElement("button");

      cell.type="button";
      cell.className="cell";
      if(sudokuFixed[r][c])cell.classList.add("fixed");
      if(selectedCell===index)cell.classList.add("selected");
      if(sudokuErrors.has(index))cell.classList.add("error");

      cell.textContent=value||"";
      cell.setAttribute("role","gridcell");
      cell.setAttribute("aria-label",`Row ${r+1}, column ${c+1}${value?", "+value:", empty"}`);

      cell.addEventListener("click",()=>{
        if(sudokuDone||sudokuFixed[r][c])return;
        selectedCell=index;
        renderSudoku();
      });

      grid.appendChild(cell);
    }
  }
}
function putNumber(number){
  if(sudokuDone)return;

  if(selectedCell<0){
    $("sudokuMsg").textContent="Tap an empty square first.";
    return;
  }

  const row=Math.floor(selectedCell/5);
  const col=selectedCell%5;
  if(sudokuFixed[row][col])return;

  sudokuPuzzle[row][col]=number;
  sudokuErrors.clear();
  $("sudokuMsg").textContent="";
  renderSudoku();
}
function checkSudoku(){
  if(sudokuDone)return;

  sudokuErrors.clear();
  let hasEmptyCells=false;

  for(let r=0;r<5;r++){
    for(let c=0;c<5;c++){
      if(sudokuPuzzle[r][c]===0)hasEmptyCells=true;
    }
  }

  // Find duplicate values in every row and column.
  for(let i=0;i<5;i++){
    for(let a=0;a<5;a++){
      const rowValue=sudokuPuzzle[i][a];
      const colValue=sudokuPuzzle[a][i];

      if(rowValue!==0){
        for(let b=a+1;b<5;b++){
          if(sudokuPuzzle[i][b]===rowValue){
            sudokuErrors.add(i*5+a);
            sudokuErrors.add(i*5+b);
          }
        }
      }

      if(colValue!==0){
        for(let b=a+1;b<5;b++){
          if(sudokuPuzzle[b][i]===colValue){
            sudokuErrors.add(a*5+i);
            sudokuErrors.add(b*5+i);
          }
        }
      }
    }
  }

  if(sudokuErrors.size>0){
    $("sudokuMsg").textContent="Some numbers repeat in a row or column. Try again.";
    effect(220);
    renderSudoku();
    return;
  }

  if(hasEmptyCells){
    $("sudokuMsg").textContent="No repeats so far—fill in every empty cell.";
    return;
  }

  sudokuDone=true;
  data.coins+=20;
  data.energy=Math.max(0,data.energy-5);
  data.clean=Math.max(0,data.clean-3);
  $("sudokuMsg").textContent="Solved! Great work — you earned 20 coins 🎉";
  effect(820);
  update();
  renderSudoku();
}

$("sudokuGrid").addEventListener("keydown",e=>{
  if(e.key>="1"&&e.key<="5"){
    putNumber(Number(e.key));
    e.preventDefault();
  }else if(e.key==="Backspace"||e.key==="Delete"){
    putNumber(0);
    e.preventDefault();
  }else if(["ArrowUp","ArrowDown","ArrowLeft","ArrowRight"].includes(e.key)){
    if(selectedCell<0)return;
    const delta={ArrowUp:-5,ArrowDown:5,ArrowLeft:-1,ArrowRight:1}[e.key];
    selectedCell=(selectedCell+delta+25)%25;
    renderSudoku();
    e.preventDefault();
  }
});

/* ---------- Arcade games (endless — game over after 3 misses) ---------- */
const canvas=$("gameCanvas"),ctx=canvas.getContext("2d"),W=canvas.width,H=canvas.height;
const MAX_MISSES=3;
const COIN_RATE={catcher:1,flyer:2,shooter:1};
const SCORE_LABEL={catcher:"Caught",flyer:"Gaps",shooter:"Hits"};
function stopGameLoop(){cancelAnimationFrame(rafId);rafId=0}
function renderRecords(){$("records").textContent=`Fruit: ${data.best.catcher} · Sky: ${data.best.flyer} · Blaster: ${data.best.shooter}`}
function startGame(type){
  stopGameLoop();
  dragPointerId=null;
  const titles={catcher:"🍓 Fruit Catcher",flyer:"☁️ Sky Soarer",shooter:"🚀 Star Blaster"};
  $("gameTitle").textContent=titles[type];
  $("gameControls").innerHTML="";
  game={type,over:false,rewarded:false,time:0,score:0,misses:0,invuln:0,flash:0,playerX:W/2,playerY:200,items:[],shots:[],keys:{},spawn:0};
  const hint={
    catcher:"Slide your finger to move the basket. Drop 3 fruit and it's game over!",
    flyer:"Tap or press Space to flap. 3 crashes and it's game over!",
    shooter:"Hold and slide to steer, tap anywhere to fire. Let 3 meteors pass and it's game over!"
  };
  $("gameHint").textContent=hint[type];
  if(type==="catcher"){
    game.playerY=H-38;game.spawn=35;
    makeHoldControl("◀","ArrowLeft");makeHoldControl("▶","ArrowRight");
  }else if(type==="flyer"){
    game.playerY=H/2;game.velocity=0;game.spawn=70;
    makeControl("FLAP 🪽",flap);
  }else{
    game.playerY=H-42;game.spawn=55;
    makeHoldControl("◀","ArrowLeft");makeControl("FIRE ✨",shoot);makeHoldControl("▶","ArrowRight");
  }
  show("arcade");lastFrame=performance.now();drawGame();rafId=requestAnimationFrame(loop);
}
function makeControl(text,fn){
  const b=document.createElement("button");b.className="btn";b.textContent=text;
  b.addEventListener("pointerdown",e=>{e.preventDefault();fn()});$("gameControls").appendChild(b);
}
function makeHoldControl(text,key){
  const b=document.createElement("button");b.className="btn";b.textContent=text;
  b.addEventListener("pointerdown",e=>{e.preventDefault();if(game&&!game.over)game.keys[key]=true});
  for(const type of ["pointerup","pointerleave","pointercancel"])b.addEventListener(type,()=>{if(game)game.keys[key]=false});
  b.addEventListener("contextmenu",e=>e.preventDefault());
  $("gameControls").appendChild(b);
}
function playerPad(){return game&&game.type==="catcher"?31:18}
function movePlayer(dx){if(!game||game.over)return;const pad=playerPad();game.playerX=Math.max(pad,Math.min(W-pad,game.playerX+dx))}
function movePlayerTo(x){if(!game||game.over)return;const pad=playerPad();game.playerX=Math.max(pad,Math.min(W-pad,x))}
function flap(){if(game&&game.type==="flyer"&&!game.over){game.velocity=-6.2;effect(520)}}
function shoot(){if(game&&game.type==="shooter"&&!game.over){game.shots.push({x:game.playerX,y:game.playerY-20});effect(720)}}
function canvasPoint(e){const r=canvas.getBoundingClientRect();return{x:(e.clientX-r.left)*W/r.width,y:(e.clientY-r.top)*H/r.height}}
function isDragGame(){return game&&!game.over&&(game.type==="catcher"||game.type==="shooter")}

/* Count a miss; the game ends on the 3rd one. */
function addMiss(){
  if(!game||game.over)return;
  game.misses++;game.flash=14;effect(200);
  if(game.misses>=MAX_MISSES)finishGame();
}

/* Press on the canvas: flap (Sky Soarer), or grab + steer (Catcher / Blaster). Blaster also fires on every tap. */
canvas.addEventListener("pointerdown",e=>{
  if(!game||game.over)return;
  e.preventDefault();
  if(game.type==="flyer"){flap();return}
  if(dragPointerId===null){
    dragPointerId=e.pointerId;
    try{canvas.setPointerCapture(e.pointerId)}catch{}
    movePlayerTo(canvasPoint(e).x);
  }
  if(game.type==="shooter")shoot();
});
canvas.addEventListener("pointermove",e=>{
  if(!isDragGame())return;
  const dragging=dragPointerId===e.pointerId;
  const mouseHover=e.pointerType==="mouse"&&dragPointerId===null;
  if(dragging||mouseHover){e.preventDefault();movePlayerTo(canvasPoint(e).x)}
});
function releaseDrag(e){
  if(dragPointerId!==e.pointerId)return;
  dragPointerId=null;
  try{canvas.releasePointerCapture(e.pointerId)}catch{}
}
for(const type of ["pointerup","pointercancel","lostpointercapture"])canvas.addEventListener(type,releaseDrag);
canvas.addEventListener("contextmenu",e=>e.preventDefault());

/* Star Blaster: tapping anywhere else on the game screen (not on a button) also fires. */
$("arcade").addEventListener("pointerdown",e=>{
  if(!game||game.over||game.type!=="shooter")return;
  if(e.target===canvas||e.target.closest("button"))return;
  e.preventDefault();
  shoot();
});
$("arcade").addEventListener("contextmenu",e=>{if(game)e.preventDefault()});

window.addEventListener("keydown",e=>{
  if(!game||game.over)return;
  if(["ArrowLeft","ArrowRight","ArrowUp","ArrowDown"," "].includes(e.key))e.preventDefault();
  if(e.repeat&&e.key===" ")return;
  game.keys[e.key]=true;
  if(game.type==="flyer"&&(e.key===" "||e.key==="ArrowUp"))flap();
  if(game.type==="shooter"&&e.key===" ")shoot();
});
window.addEventListener("keyup",e=>{if(game)game.keys[e.key]=false});
function loop(now){
  if(!game||game.over)return;
  const dt=Math.min(2,(now-lastFrame)/16.67);lastFrame=now;game.time+=dt;
  updateGame(dt);drawGame();if(game&&!game.over)rafId=requestAnimationFrame(loop);
}
function flyerCrash(){
  addMiss();
  if(!game||game.over)return;
  // Clear pipes near the cat and give a short safe period.
  game.items=game.items.filter(p=>p.x>150||p.x+48<20);
  game.playerY=H/2;game.velocity=-3;game.invuln=90;
}
function updateGame(dt){
  if(game.flash>0)game.flash-=dt;
  if(game.type==="catcher"){
    if(game.keys.ArrowLeft)movePlayer(-5*dt);if(game.keys.ArrowRight)movePlayer(5*dt);
    game.spawn-=dt;
    if(game.spawn<=0){
      const speedUp=Math.min(2.5,game.score*.06);
      game.items.push({x:18+Math.random()*(W-36),y:-20,vy:2.4+Math.random()*1.4+speedUp,emoji:["🍓","🍎","🍊"][Math.floor(Math.random()*3)]});
      game.spawn=Math.max(20,38-game.score*.5);
    }
    for(const f of game.items){
      f.y+=f.vy*dt;
      if(Math.abs(f.x-game.playerX)<28&&f.y>H-63&&f.y<H-17){f.caught=true;game.score++;effect(650)}
      else if(f.y>H+10){f.missed=true;addMiss();if(game.over)return}
    }
    game.items=game.items.filter(f=>!f.caught&&!f.missed);
  }else if(game.type==="flyer"){
    if(game.invuln>0)game.invuln-=dt;
    if(game.keys.ArrowUp)game.velocity=-6;
    game.velocity=Math.min(7,game.velocity+.24*dt);game.playerY+=game.velocity*dt;
    game.spawn-=dt;
    if(game.spawn<=0){
      const gap=Math.max(115,150-game.score*2);
      const gapY=90+Math.random()*220;
      game.items.push({x:W+30,gapY,gap,passed:false});game.spawn=92;
    }
    let hit=false;
    for(const p of game.items){
      p.x-=2.4*dt;
      if(!p.passed&&p.x<58){p.passed=true;game.score++;effect(650)}
      if(p.x<82&&p.x+48>34&&(game.playerY<p.gapY-p.gap/2||game.playerY>p.gapY+p.gap/2))hit=true;
    }
    game.items=game.items.filter(p=>p.x>-60);
    const outOfBounds=game.playerY<10||game.playerY>H-10;
    if(game.invuln>0){
      if(outOfBounds){game.playerY=Math.max(12,Math.min(H-12,game.playerY));game.velocity=0}
    }else if(hit||outOfBounds){
      flyerCrash();
    }
  }else{
    if(game.keys.ArrowLeft)movePlayer(-5*dt);if(game.keys.ArrowRight)movePlayer(5*dt);
    game.spawn-=dt;
    if(game.spawn<=0){
      const speedUp=Math.min(1.5,game.score*.04);
      game.items.push({x:22+Math.random()*(W-44),y:-24,vy:1.05+Math.random()*.6+speedUp,r:15+Math.random()*5,opacity:.94});
      game.spawn=Math.max(26,55-game.score*.8);
    }
    for(const m of game.items)m.y+=m.vy*dt;
    for(const s of game.shots)s.y-=7*dt;
    for(const s of game.shots)for(const m of game.items)if(!m.hit&&!s.hit&&Math.hypot(s.x-m.x,s.y-m.y)<m.r+5){m.hit=true;s.hit=true;game.score++;effect(850)}
    for(const m of game.items){
      if(!m.hit&&m.y>H+20){m.missed=true;addMiss();if(game.over)return}
    }
    game.shots=game.shots.filter(s=>!s.hit&&s.y>-10);
    game.items=game.items.filter(m=>!m.hit&&!m.missed);
  }
}
function drawGame(){
  if(!game)return;
  ctx.clearRect(0,0,W,H);
  ctx.fillStyle="#26364f";ctx.fillRect(0,0,W,H);
  for(let i=0;i<22;i++){ctx.fillStyle="#ffffff";ctx.globalAlpha=.18+(i%3)*.12;ctx.beginPath();ctx.arc((i*71+game.time*-.35)%W,(i*47)%H,1.5,0,Math.PI*2);ctx.fill()}
  ctx.globalAlpha=1;
  if(game.type==="catcher"){
    ctx.fillStyle="#8fb3a0";ctx.fillRect(0,H-12,W,12);
    ctx.fillStyle="#b56d45";ctx.fillRect(game.playerX-27,H-48,54,28);
    ctx.fillStyle="#e5ad70";ctx.fillRect(game.playerX-31,H-52,62,9);
    ctx.font="25px sans-serif";ctx.textAlign="center";
    for(const f of game.items){ctx.globalAlpha=.98;ctx.fillText(f.emoji,f.x,f.y)}ctx.globalAlpha=1;
  }else if(game.type==="flyer"){
    ctx.fillStyle="#b7d8b1";
    for(const p of game.items){ctx.fillRect(p.x,0,48,p.gapY-p.gap/2);ctx.fillRect(p.x,p.gapY+p.gap/2,48,H-(p.gapY+p.gap/2))}
    if(game.invuln>0&&Math.floor(game.time/6)%2)ctx.globalAlpha=.35;
    ctx.font="30px sans-serif";ctx.textAlign="center";ctx.fillText("🐱",58,game.playerY+10);
    ctx.globalAlpha=1;
  }else{
    if(dragPointerId!==null){
      ctx.fillStyle="#fff6a833";ctx.beginPath();ctx.arc(game.playerX,H-36,26,0,Math.PI*2);ctx.fill();
    }
    ctx.font="30px sans-serif";ctx.textAlign="center";ctx.fillText("🚀",game.playerX,H-26);
    for(const m of game.items){ctx.globalAlpha=m.opacity;ctx.font=`${m.r*2}px sans-serif`;ctx.fillText("☄️",m.x,m.y)}ctx.globalAlpha=1;
    ctx.fillStyle="#fff6a8";for(const s of game.shots){ctx.fillRect(s.x-2,s.y-8,4,13)}
  }
  if(game.flash>0){ctx.fillStyle="#ff5a5a";ctx.globalAlpha=Math.min(.3,game.flash/40);ctx.fillRect(0,0,W,H);ctx.globalAlpha=1}
  drawScore(`${SCORE_LABEL[game.type]}: ${game.score}`);
  drawLives();
}
function drawScore(text){ctx.fillStyle="#fff";ctx.font="bold 17px system-ui";ctx.textAlign="left";ctx.fillText(text,12,25)}
function drawLives(){
  const left=Math.max(0,MAX_MISSES-game.misses);
  ctx.font="16px sans-serif";ctx.textAlign="right";
  ctx.fillText("❤️".repeat(left)+"🖤".repeat(MAX_MISSES-left),W-10,25);
}
function finishGame(){
  if(!game||game.over)return;
  game.over=true;dragPointerId=null;stopGameLoop();game.flash=0;drawGame();
  const coins=game.score*COIN_RATE[game.type];
  const newBest=game.score>0&&game.score>(data.best[game.type]||0);
  ctx.fillStyle="#0009";ctx.fillRect(0,0,W,H);ctx.fillStyle="#fff";ctx.textAlign="center";
  ctx.font="bold 26px system-ui";ctx.fillText("Game over",W/2,H/2-40);
  ctx.font="bold 20px system-ui";ctx.fillText(`Score: ${game.score}`,W/2,H/2-6);
  ctx.font="17px system-ui";ctx.fillText(`+${coins} coins 🪙`,W/2,H/2+22);
  if(newBest){ctx.fillStyle="#ffe58a";ctx.fillText("🏆 New best score!",W/2,H/2+48);ctx.fillStyle="#fff"}
  ctx.font="15px system-ui";ctx.fillText("Tap Continue to collect",W/2,H/2+78);
  $("gameHint").textContent=newBest?"Amazing — a new record!":"Nice playing! Try to beat your best.";
  showGameContinue();
}
function showGameContinue(){
  $("gameControls").innerHTML="";const b=document.createElement("button");b.className="btn pink";b.textContent="Continue";
  b.onclick=()=>endGame();$("gameControls").appendChild(b);
}
/* Called by Continue and by Exit: collects coins earned so far, then returns to the hub. */
function endGame(){
  stopGameLoop();
  dragPointerId=null;
  if(game&&!game.rewarded){
    game.rewarded=true;
    const type=game.type,score=game.score;
    if(score>0){
      const coins=score*COIN_RATE[type];
      const newBest=score>(data.best[type]||0);
      data.coins+=coins;data.best[type]=Math.max(data.best[type]||0,score);
      data.energy=Math.max(0,data.energy-8);data.clean=Math.max(0,data.clean-5);
      if(newBest){say(`New best score: ${score}! +${coins} coins 🎉`);flashMood("happy",5000)}
      else say(`Good game! You earned ${coins} coins 🪙`);
      update();
    }else if(game.over){
      say("Aww, no points this time… let's try again! 😿");flashMood("sad",5000);
    }
  }
  game=null;show("hub");
}

update();
if(!data.selfiePromptSeen&&!Object.keys(selfies).length)setTimeout(openSelfies,600);
</script>
</body>
</html>
