<!--
=============================================================
WORLD CUP ORACLE '26 — VISION DOCUMENT v2
=============================================================
-->

<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="mobile-web-app-capable" content="yes">
<title>World Cup Oracle '26</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Russo+One&family=Rajdhani:wght@400;500&display=swap');
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html,body{overflow:hidden;position:fixed;top:0;left:0;width:100%;height:100%;background:#000;font-family:Arial,sans-serif;touch-action:none;user-select:none;-webkit-user-select:none;}
#c,#sc-canvas{position:absolute;top:0;left:0;display:block;}
.screen{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:10;background:#0a1520;overflow-y:auto;}
.screen.off{display:none;}
.menu-box{display:flex;flex-direction:column;align-items:center;gap:10px;width:90%;max-width:420px;padding:20px 0;}
.title{font-size:26px;font-weight:bold;color:#fff;letter-spacing:3px;text-align:center;}
.subtitle{font-size:11px;color:rgba(255,204,0,0.7);letter-spacing:4px;text-transform:uppercase;}
.prow{display:flex;gap:12px;width:100%;flex-wrap:wrap;justify-content:center;}
.pbox{display:flex;flex-direction:column;gap:6px;align-items:center;flex:1;min-width:160px;}
.plabel{font-size:10px;letter-spacing:2px;color:rgba(255,255,255,0.5);text-transform:uppercase;}
input.nick{width:100%;background:rgba(255,255,255,0.07);border:1px solid rgba(255,255,255,0.2);border-radius:6px;padding:10px 12px;color:#fff;font-size:13px;text-align:center;outline:none;letter-spacing:2px;}
.csel{position:relative;width:100%;}
.csbtn{width:100%;background:rgba(255,255,255,0.06);border:1px solid rgba(255,255,255,0.15);border-radius:6px;padding:9px 12px;color:#fff;font-size:12px;display:flex;align-items:center;gap:8px;cursor:pointer;}
.csflag{font-size:18px;}.csname{flex:1;text-align:left;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;}
.csarrow{font-size:9px;color:rgba(255,255,255,0.4);transition:transform .2s;}
.csbtn.open .csarrow{transform:rotate(180deg);}
.csdd{position:absolute;top:calc(100% + 3px);left:0;right:0;background:#0d1c2e;border:1px solid rgba(255,255,255,0.15);border-radius:6px;max-height:200px;overflow-y:auto;z-index:100;box-shadow:0 8px 24px rgba(0,0,0,0.7);}
.csdd::-webkit-scrollbar{width:4px;}.csdd::-webkit-scrollbar-thumb{background:rgba(255,255,255,0.2);border-radius:2px;}
.csearch{padding:7px 10px;position:sticky;top:0;background:#0d1c2e;border-bottom:1px solid rgba(255,255,255,0.08);}
.csearch input{width:100%;background:rgba(255,255,255,0.07);border:none;border-radius:4px;padding:5px 9px;color:#fff;font-size:11px;outline:none;}
.csitem{display:flex;align-items:center;gap:8px;padding:8px 12px;cursor:pointer;font-size:12px;}
.csitem:hover,.csitem.active{background:rgba(79,195,247,0.12);}
.hidden{display:none;}
.drow{display:flex;gap:8px;flex-wrap:wrap;justify-content:center;}
.dbtn{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.15);border-radius:6px;padding:7px 14px;color:rgba(255,255,255,0.45);font-size:10px;letter-spacing:1px;text-transform:uppercase;cursor:pointer;}
.dbtn.sel{background:rgba(255,204,0,0.15);border-color:rgba(255,204,0,0.5);color:#ffd700;}
.abtn{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.15);border-radius:6px;padding:7px 14px;color:rgba(255,255,255,0.45);font-size:10px;letter-spacing:1px;cursor:pointer;display:flex;align-items:center;gap:5px;}
.abtn.sel{background:rgba(255,204,0,0.12);border-color:rgba(255,204,0,0.45);color:#ffd700;}
.btn-main{background:linear-gradient(135deg,#b8860b,#ffd700);border:none;border-radius:8px;padding:14px 44px;color:#000;font-size:15px;font-weight:bold;letter-spacing:3px;text-transform:uppercase;cursor:pointer;}
.btn-sec{background:transparent;border:1px solid rgba(255,255,255,0.2);border-radius:6px;padding:9px 24px;color:rgba(255,255,255,0.4);font-size:10px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;}
.ai-note{font-size:10px;color:rgba(255,160,0,0.7);letter-spacing:1px;}
#hud{position:absolute;top:6px;left:50%;transform:translateX(-50%);z-index:15;pointer-events:none;display:flex;align-items:center;gap:6px;}
#hud-bg{display:none;}
#hudtimer-wrap{background:rgba(0,0,0,0.82);border:1px solid rgba(255,255,255,0.25);border-radius:10px;padding:4px 16px;backdrop-filter:blur(6px);}
#hudtimer{font-size:22px;font-weight:900;color:#fff;letter-spacing:3px;line-height:1.2;text-align:center;}
#hudlbl{font-size:7px;letter-spacing:2px;color:rgba(255,204,0,0.75);text-align:center;display:block;}
.hteam,.hcard,.hflag,.hscore,.hname,.hrating,#hud-center{display:none!important;}
.hs1{color:#5bc8ff;}.hs2{color:#ff6b6b;}
#joyzone{position:absolute;z-index:5;}
#joybase{position:absolute;inset:0;border-radius:50%;border:2px solid rgba(255,255,255,0.18);background:rgba(255,255,255,0.04);pointer-events:none;}
#joystick{width:36px;height:36px;border-radius:50%;background:radial-gradient(circle at 35% 35%,rgba(255,255,255,0.5),rgba(255,255,255,0.12));border:2px solid rgba(255,255,255,0.4);position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);pointer-events:none;}
.joy-label{position:absolute;bottom:-16px;left:50%;transform:translateX(-50%);font-size:8px;letter-spacing:2px;color:rgba(255,255,255,0.25);text-transform:uppercase;white-space:nowrap;pointer-events:none;}
#shootbtn{position:absolute;border-radius:50%;border:2px solid rgba(91,200,255,0.45);background:radial-gradient(circle at 40% 35%,rgba(91,200,255,0.2),rgba(91,200,255,0.06));display:flex;align-items:center;justify-content:center;flex-direction:column;gap:2px;z-index:5;cursor:pointer;}
#shootbtn.firing{background:radial-gradient(circle at 40% 35%,rgba(91,200,255,0.45),rgba(91,200,255,0.18));border-color:rgba(91,200,255,0.9);transform:scale(0.91);}
.shoot-icon{font-size:22px;line-height:1;}.shoot-label{font-size:7px;letter-spacing:2px;color:rgba(91,200,255,0.65);text-transform:uppercase;}
#s-cd{background:rgba(0,0,0,0.92);}
#cdnum{font-size:140px;font-weight:bold;color:#fff;text-shadow:0 0 50px rgba(255,204,0,0.7);animation:cdp .85s ease-out;}
@keyframes cdp{0%{transform:scale(1.6);opacity:0;}50%{opacity:1;transform:scale(1);}100%{transform:scale(0.88);opacity:0.8;}}
#cdsub{font-size:12px;letter-spacing:5px;color:rgba(255,255,255,0.35);text-transform:uppercase;margin-bottom:16px;}
#gflash{position:absolute;inset:0;z-index:8;pointer-events:none;opacity:0;transition:opacity .1s;}
#gtxt{position:absolute;top:48%;left:50%;transform:translate(-50%,-50%);font-size:56px;font-weight:bold;letter-spacing:6px;z-index:9;pointer-events:none;opacity:0;text-transform:uppercase;text-shadow:3px 3px 0 rgba(0,0,0,0.5);transition:opacity .2s,transform .2s;}
#set-overlay{position:absolute;inset:0;z-index:20;display:flex;flex-direction:column;align-items:center;justify-content:center;background:rgba(0,0,0,0.88);opacity:0;pointer-events:none;transition:opacity .35s;}
#set-overlay.show{opacity:1;pointer-events:all;}
#set-msg{font-size:24px;font-weight:bold;letter-spacing:3px;text-align:center;text-transform:uppercase;text-shadow:0 0 30px currentColor;padding:0 20px;line-height:1.4;}
#set-cd{font-size:90px;font-weight:bold;color:#fff;margin-top:14px;}
#set-sub{font-size:10px;letter-spacing:4px;color:rgba(255,255,255,0.3);margin-top:8px;text-transform:uppercase;}
#s-end{background:rgba(5,10,20,0.97);}
#endflags{font-size:48px;margin-bottom:4px;}
#endscore{font-size:80px;font-weight:bold;color:#fff;letter-spacing:10px;margin:6px 0;}
#endlbl{font-size:13px;letter-spacing:4px;text-transform:uppercase;margin-bottom:24px;}
.el-win{color:#ffd700;text-shadow:0 0 20px rgba(255,215,0,0.5);}.el-draw{color:#90ee90;}
#sc-canvas{z-index:25;pointer-events:none;}
</style>
</head>
<body>
<canvas id="c"></canvas>
<canvas id="sc-canvas" class="off"></canvas>
<div class="screen" id="s-menu">
<div class="menu-box">
  <div class="title">WORLD CUP ORACLE</div>
  <div class="subtitle">⚽ World Cup Oracle '26</div>
  <div class="prow">
    <div class="pbox">
      <div class="plabel" style="color:#5bc8ff;">▶ You</div>
      <input class="nick" id="n1" type="text" maxlength="12" placeholder="YOUR NAME" autocomplete="off">
      <div class="csel" id="cw1">
        <button class="csbtn" id="cb1" onclick="toggleDD(1)"><span class="csflag" id="cf1">🌍</span><span class="csname" id="cn1">Select Country</span><span class="csarrow">▼</span></button>
        <div class="csdd hidden" id="cd1"><div class="csearch"><input type="text" placeholder="Search..." id="cs1" oninput="filterDD(1,this.value)"></div><div id="cl1"></div></div>
      </div>
    </div>
    <div class="pbox">
      <div class="plabel" style="color:#ff6b6b;">◀ AI Opponent</div>
      <input class="nick" id="n2" type="text" maxlength="12" placeholder="CPU NAME" autocomplete="off">
      <div class="ai-note">🤖 CPU Controlled</div>
      <div class="csel" id="cw2">
        <button class="csbtn" id="cb2" onclick="toggleDD(2)"><span class="csflag" id="cf2">🌍</span><span class="csname" id="cn2">Select Country</span><span class="csarrow">▼</span></button>
        <div class="csdd hidden" id="cd2"><div class="csearch"><input type="text" placeholder="Search..." id="cs2" oninput="filterDD(2,this.value)"></div><div id="cl2"></div></div>
      </div>
    </div>
  </div>
  <div style="font-size:9px;letter-spacing:2px;color:rgba(255,255,255,0.3);text-transform:uppercase;">🏟️ Arena</div>
  <div class="drow" id="arena-btns">
    <button class="abtn sel" id="ar0" onclick="setArena(0)">🇺🇸 USA</button>
    <button class="abtn" id="ar1" onclick="setArena(1)">🇨🇦 Canada</button>
    <button class="abtn" id="ar2" onclick="setArena(2)">🇲🇽 Mexico</button>
  </div>
  <div style="font-size:9px;letter-spacing:2px;color:rgba(255,255,255,0.3);text-transform:uppercase;">AI Difficulty</div>
  <div class="drow">
    <button class="dbtn" id="d0" onclick="setDiff(0)">Amateur</button>
    <button class="dbtn sel" id="d1" onclick="setDiff(1)">Semi-Pro</button>
    <button class="dbtn" id="d2" onclick="setDiff(2)">World Class</button>
  </div>
  <button class="btn-main" id="btn-play">⚽ KICK OFF</button>
</div>
</div>
<div class="screen off" id="s-cd"><div id="cdsub">Kick Off</div><div id="cdnum">3</div></div>
<div id="set-overlay"><div id="set-msg"></div><div id="set-cd">3</div><div id="set-sub"></div></div>
<div id="hud-bg"></div>
<div id="hud">
  <div class="hteam"><span class="hflag" id="hf1">🌍</span><div class="hcard"><div class="hscore hs1" id="hs1">0</div><div class="hname" id="hn1">YOU</div><div class="hrating" id="hr1" style="color:#90ee90;"></div></div></div>
  <div id="hud-center"><div id="hudtimer-wrap"><div id="hudtimer">1'</div></div><div id="hudlbl">WORLD CUP ORACLE</div></div>
  <div class="hteam hteam-right"><span class="hflag" id="hf2">🌍</span><div class="hcard hcard-right"><div class="hscore hs2" id="hs2">0</div><div class="hname" id="hn2">CPU</div><div class="hrating" id="hr2" style="color:#ff8888;"></div></div></div>
</div>
<div id="joyzone"><div id="joybase"><div id="joystick"></div></div><div class="joy-label">AIM</div></div>
<div id="shootbtn"><div class="shoot-icon">💧</div><div class="shoot-label">SHOOT</div></div>
<div id="gflash"></div><div id="gtxt">GOAL!</div>
<div class="screen off" id="s-end">
  <div id="endflags"></div>
  <div style="font-size:10px;letter-spacing:3px;color:rgba(255,255,255,0.3);text-transform:uppercase;">FULL TIME</div>
  <div id="endscore">0 – 0</div><div id="endlbl" class="el-draw">DRAW</div>
  <div id="humillacion-mundial" style="display:none;font-size:22px;font-weight:900;letter-spacing:4px;text-transform:uppercase;color:#ffd700;text-shadow:0 0 24px rgba(255,215,0,0.7);margin-bottom:8px;text-align:center;">HUMILLACIÓN MUNDIAL</div>
  <button class="btn-main" id="btn-share-result" style="background:linear-gradient(135deg,#1565c0,#1e88e5);margin-bottom:6px;">📤 SHARE RESULT</button>
  <button class="btn-main" id="btn-rm">↺ REMATCH</button>
  <button class="btn-sec" id="btn-menu" style="margin-top:8px;">MAIN MENU</button>
</div>

<div id="share-overlay" style="display:none;position:fixed;inset:0;z-index:50;background:rgba(0,0,0,0.93);flex-direction:column;align-items:center;justify-content:flex-start;gap:12px;padding:12px 12px 24px;overflow-y:auto;">
  <div id="share-card" style="width:100%;max-width:680px;background:#080d18;border-radius:18px;overflow:hidden;position:relative;box-shadow:0 20px 80px rgba(0,0,0,.9);border:1px solid rgba(255,255,255,.06);flex-shrink:0;">
    <div style="position:absolute;inset:0;z-index:0;background-image:repeating-linear-gradient(90deg,transparent,transparent 48px,rgba(255,255,255,.018) 48px,rgba(255,255,255,.018) 49px);"></div>
    <div id="sc-glow" style="position:absolute;inset:0;z-index:0;"></div>
    <div id="sc-strip" style="position:relative;z-index:2;height:4px;"></div>
    <div style="position:relative;z-index:2;display:flex;align-items:center;justify-content:center;gap:8px;padding:12px 24px 0;">
      <div style="width:3px;height:3px;border-radius:50%;background:rgba(255,255,255,.18);flex-shrink:0;"></div>
      <div id="sc-oracle-title" style="font-family:Arial,sans-serif;font-size:11px;letter-spacing:3px;color:rgba(255,255,255,.38);text-transform:uppercase;"></div>
      <div style="width:3px;height:3px;border-radius:50%;background:rgba(255,255,255,.18);flex-shrink:0;"></div>
    </div>
    <div style="position:relative;z-index:2;display:flex;align-items:center;padding:16px 24px 12px;gap:16px;">
      <div style="display:flex;flex-direction:column;align-items:center;gap:6px;width:110px;flex-shrink:0;">
        <div id="sc-p1-flag" style="font-size:52px;line-height:1;filter:drop-shadow(0 4px 16px rgba(0,0,0,.6));"></div>
        <div id="sc-p1-name" style="font-size:11px;letter-spacing:2px;color:rgba(255,255,255,.6);text-transform:uppercase;text-align:center;font-family:Arial,sans-serif;"></div>
        <div id="sc-p1-rating" style="font-size:10px;letter-spacing:1px;padding:3px 10px;border-radius:20px;font-weight:700;text-align:center;font-family:Arial,sans-serif;"></div>
      </div>
      <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:8px;">
        <div style="display:flex;align-items:center;gap:12px;">
          <div id="sc-score-p1" style="font-size:96px;line-height:1;letter-spacing:-2px;color:#5bc8ff;text-shadow:0 0 30px rgba(91,200,255,.5);font-family:Arial Black,Arial,sans-serif;font-weight:900;"></div>
          <div style="font-size:64px;line-height:1;color:rgba(255,255,255,.2);font-family:Arial Black,Arial,sans-serif;font-weight:900;">–</div>
          <div id="sc-score-p2" style="font-size:96px;line-height:1;letter-spacing:-2px;color:#ff6b6b;text-shadow:0 0 30px rgba(255,107,107,.5);font-family:Arial Black,Arial,sans-serif;font-weight:900;"></div>
        </div>
        <div id="sc-banner" style="width:100%;border-radius:10px;padding:10px 16px;text-align:center;">
          <div id="sc-banner-main" style="font-size:26px;letter-spacing:5px;line-height:1;font-family:Arial Black,Arial,sans-serif;font-weight:900;"></div>
          <div id="sc-banner-sub" style="font-size:9px;letter-spacing:3px;margin-top:3px;text-transform:uppercase;font-family:Arial,sans-serif;"></div>
        </div>
        <div style="display:flex;align-items:center;gap:28px;">
          <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
            <div style="font-family:'Russo One',sans-serif;font-size:10px;letter-spacing:1.5px;color:rgba(255,255,255,.82);text-transform:uppercase;">Ended In</div>
            <div id="sc-rounds" style="font-family:'Rajdhani',sans-serif;font-size:12px;font-weight:400;color:#5bc8ff;"></div>
          </div>
          <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
            <div id="sc-phase-lbl" style="font-family:'Russo One',sans-serif;font-size:10px;letter-spacing:1.5px;color:rgba(255,255,255,.82);text-transform:uppercase;"></div>
            <div id="sc-phase" style="font-family:'Rajdhani',sans-serif;font-size:12px;font-weight:400;color:#5bc8ff;"></div>
          </div>
          <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
            <div style="font-family:'Russo One',sans-serif;font-size:10px;letter-spacing:1.5px;color:rgba(255,255,255,.82);text-transform:uppercase;">Duration</div>
            <div id="sc-balls" style="font-family:'Rajdhani',sans-serif;font-size:12px;font-weight:400;color:#5bc8ff;"></div>
          </div>
        </div>
      </div>
      <div style="display:flex;flex-direction:column;align-items:center;gap:6px;width:110px;flex-shrink:0;">
        <div id="sc-p2-flag" style="font-size:52px;line-height:1;filter:drop-shadow(0 4px 16px rgba(0,0,0,.6));"></div>
        <div id="sc-p2-name" style="font-size:11px;letter-spacing:2px;color:rgba(255,255,255,.6);text-transform:uppercase;text-align:center;font-family:Arial,sans-serif;"></div>
        <div id="sc-p2-rating" style="font-size:10px;letter-spacing:1px;padding:3px 10px;border-radius:20px;font-weight:700;text-align:center;font-family:Arial,sans-serif;"></div>
      </div>
    </div>
    <div style="position:relative;z-index:2;display:flex;align-items:center;justify-content:space-between;padding:8px 24px 16px;gap:10px;">
      <div id="sc-arena-info" style="font-size:9px;letter-spacing:2px;color:rgba(255,255,255,.22);text-transform:uppercase;font-family:Arial,sans-serif;"></div>
      <div style="display:flex;gap:8px;">
        <button id="btn-do-share" style="background:linear-gradient(135deg,#1565c0,#1e88e5);border:none;border-radius:8px;padding:10px 20px;color:#fff;font-family:Arial,sans-serif;font-size:11px;letter-spacing:2px;font-weight:700;cursor:pointer;text-transform:uppercase;">SHARE</button>
        <button id="btn-rm-share" style="background:linear-gradient(135deg,#b8860b,#ffd700);border:none;border-radius:8px;padding:10px 20px;color:#000;font-family:Arial,sans-serif;font-size:11px;letter-spacing:2px;font-weight:700;cursor:pointer;text-transform:uppercase;">↺ REMATCH</button>
        <button id="btn-close-share" style="background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.12);border-radius:8px;padding:10px 20px;color:rgba(255,255,255,.4);font-family:Arial,sans-serif;font-size:11px;letter-spacing:2px;cursor:pointer;text-transform:uppercase;">MENU</button>
      </div>
    </div>
  </div>
</div>

<script>
var canvas=document.getElementById('c'),ctx=canvas.getContext('2d');
var scCanvas=document.getElementById('sc-canvas'),sctx=scCanvas.getContext('2d');
function W(){return canvas.width;}
function H(){return canvas.height;}
function CTRL_W(){return Math.max(72,Math.min(W()*0.22,110));}
function PITCH_L(){return CTRL_W();}
function PITCH_R(){return W()-CTRL_W();}
function PITCH_W(){return PITCH_R()-PITCH_L();}
function PITCH_T(){return Math.round(H()*0.17);}
function PITCH_B(){return H();}
function PITCH_H(){return PITCH_B()-PITCH_T();}
function PITCH_CX(){return Math.round(W()/2);}
function PITCH_CY(){return Math.round((PITCH_T()+PITCH_B())/2);}
function GH(){return PITCH_H()*0.55;}
function GT(){return PITCH_CY()-GH()/2;}
function GB(){return PITCH_CY()+GH()/2;}
function GD(){return PITCH_W()*0.04;}
function RR(){return Math.min(PITCH_W(),PITCH_H())*0.028;}
function LS(){return Math.min(PITCH_W(),PITCH_H())*0.066;}
function playerY(ay){var s=LS(),fo=s*1.05;return(PITCH_T()-fo)+ay*((PITCH_B()-fo)-(PITCH_T()-fo));}
function resize(){
var w=window.innerWidth||document.documentElement.clientWidth;
var h=window.innerHeight||document.documentElement.clientHeight;
canvas.width=w;canvas.height=h;canvas.style.width=w+'px';canvas.style.height=h+'px';
scCanvas.width=w;scCanvas.height=h;scCanvas.style.width=w+'px';scCanvas.style.height=h+'px';
seatCache={};positionControls();
}
function positionControls(){
var cw=CTRL_W(),bs=Math.min(cw*0.78,80);
var jz=document.getElementById('joyzone');
jz.style.cssText='width:'+bs+'px;height:'+bs+'px;left:'+(cw/2-bs/2)+'px;top:'+(H()/2-bs/2)+'px;position:absolute;z-index:5;';
var sb=document.getElementById('shootbtn');
sb.style.cssText='width:'+bs+'px;height:'+bs+'px;left:'+(W()-cw/2-bs/2)+'px;top:'+(H()/2-bs/2)+'px;position:absolute;z-index:5;';
}
window.addEventListener('resize',function(){resize();});
window.addEventListener('orientationchange',function(){setTimeout(resize,400);});

var selectedArena=0,activeArena=0;
function setArena(a){selectedArena=a;document.querySelectorAll('.abtn').forEach(function(b,i){b.classList.toggle('sel',i===a);});}

var ARENA_CFG=[
{name:'USA',flag:'🇺🇸',stadiumName:'SOFI STADIUM',seats:['#1a4a8a','#c8232c','#f0f0f0','#0d2a5c'],tribGrad:['#1a1f2e','#1e2640'],sideStripe:['#1a3d1a','#173517'],accentLine:'#3d5afe',pitchStripe:['#1a3d1a','#173517'],drawFlag:function(cx,cy,fw,fh){var sh=fh/13;for(var s=0;s<13;s++){ctx.fillStyle=s%2===0?'#c62828':'#f5f5f5';ctx.fillRect(cx-fw/2,cy-fh/2+s*sh,fw,sh);}var cw2=fw*.4,ch=sh*7;ctx.fillStyle='#1a3a7a';ctx.fillRect(cx-fw/2,cy-fh/2,cw2,ch);ctx.fillStyle='#fff';var sC=6,sR=5,spX=cw2/(sC+.5),spY=ch/(sR+.5);for(var r=0;r<sR;r++)for(var c=0;c<sC;c++){ctx.beginPath();ctx.arc(cx-fw/2+spX*(c+.75),cy-fh/2+spY*(r+.6),Math.max(1,fw*.018),0,Math.PI*2);ctx.fill();}}},
{name:'Canada',flag:'🇨🇦',stadiumName:'BC PLACE',seats:['#c8232c','#fff','#a00000','#cc0000'],tribGrad:['#1a0808','#2a0a0a'],sideStripe:['#5a0a0a','#3a0606'],accentLine:'#cc0000',pitchStripe:['#1a3d1a','#0d2a0d'],drawFlag:function(cx,cy,fw,fh){ctx.fillStyle='#d52b1e';ctx.fillRect(cx-fw/2,cy-fh/2,fw*.25,fh);ctx.fillStyle='#fff';ctx.fillRect(cx-fw*.25,cy-fh/2,fw*.5,fh);ctx.fillStyle='#d52b1e';ctx.fillRect(cx+fw*.25,cy-fh/2,fw*.25,fh);ctx.fillStyle='#d52b1e';ctx.font='bold '+Math.round(fh*.7)+'px serif';ctx.textAlign='center';ctx.fillText('🍁',cx,cy+fh*.25);}},
{name:'Mexico',flag:'🇲🇽',stadiumName:'ESTADIO AZTECA',seats:['#006847','#ce1126','#fff','#004d33'],tribGrad:['#051a0a','#0a2010'],sideStripe:['#063d12','#042d0c'],accentLine:'#ce1126',pitchStripe:['#1a3d1a','#0a2a0a'],drawFlag:function(cx,cy,fw,fh){ctx.fillStyle='#006847';ctx.fillRect(cx-fw/2,cy-fh/2,fw/3,fh);ctx.fillStyle='#fff';ctx.fillRect(cx-fw/6,cy-fh/2,fw/3,fh);ctx.fillStyle='#ce1126';ctx.fillRect(cx+fw/6,cy-fh/2,fw/3,fh);ctx.fillStyle='#8b6914';ctx.font=Math.round(fh*.55)+'px serif';ctx.textAlign='center';ctx.fillText('🦅',cx,cy+fh*.2);}}
];

var SPONSORS_BY_ARENA=[
{top:[{text:'MAXPAY',bg:'#1565c0',fg:'#fff'},{text:'SOLAR COLA',bg:'#c62828',fg:'#fff'},{text:'STRIKER',bg:'#1b5e20',fg:'#fff'},{text:'FASTGOAL',bg:'#e65100',fg:'#fff'}],left:[{text:'REDZONE',bg:'#b71c1c',fg:'#ffeb3b'},{text:'GOALPASS',bg:'#1a237e',fg:'#fff'},{text:'NEXTEL',bg:'#4a148c',fg:'#ffeb3b'}],right:[{text:'TITANBANK',bg:'#004d40',fg:'#fff'},{text:'SOLAR COLA',bg:'#c62828',fg:'#fff'},{text:'AEROFLY',bg:'#37474f',fg:'#fff'}]},
{top:[{text:'BOREALIS',bg:'#7b0000',fg:'#fff'},{text:'MAPLE BET',bg:'#cc0000',fg:'#fff'},{text:'NORTHPAY',bg:'#1a3a6a',fg:'#fff'},{text:'ICEGOAL',bg:'#003366',fg:'#ffcc00'}],left:[{text:'REDLEAF',bg:'#990000',fg:'#fff'},{text:'FROSTBANK',bg:'#003377',fg:'#fff'},{text:'YUKON',bg:'#cc3300',fg:'#ffeb3b'}],right:[{text:'CANSTRIKE',bg:'#002255',fg:'#fff'},{text:'POLAR FC',bg:'#880000',fg:'#fff'},{text:'CARIBOU',bg:'#443300',fg:'#ffcc00'}]},
{top:[{text:'AZTECA',bg:'#8b1a1a',fg:'#ffcc00'},{text:'TEQUILA FC',bg:'#9b1b1b',fg:'#fff'},{text:'MARIACHI',bg:'#cc6600',fg:'#fff'},{text:'SOLPAY',bg:'#7a1010',fg:'#ffdd00'}],left:[{text:'CHILI BET',bg:'#8b0000',fg:'#ffeb3b'},{text:'GUADALUPE',bg:'#5a3000',fg:'#ffcc00'},{text:'AGAVE',bg:'#664400',fg:'#ffcc00'}],right:[{text:'TENOCHTITLAN',bg:'#3d1a00',fg:'#ffdd00'},{text:'JALISCO',bg:'#cc0000',fg:'#fff'},{text:'OAXACA',bg:'#553300',fg:'#ffdd00'}]}
];
var SPONSORS=SPONSORS_BY_ARENA[0];
var adSO=0,adSliding=false,adLI=0,adRI=0,AD_SPD=0.012,AD_PAUSE=180,adPT=AD_PAUSE;
function updateAdSlide(){if(adSliding){adSO+=AD_SPD;if(adSO>=1){adSO=0;adSliding=false;adPT=AD_PAUSE;adLI=(adLI+1)%SPONSORS.left.length;adRI=(adRI+1)%SPONSORS.right.length;}}else{adPT--;if(adPT<=0)adSliding=true;}}
function drawAdH(x,y,w,h,sp){ctx.fillStyle=sp.bg;ctx.fillRect(x,y,w,h);var g=ctx.createLinearGradient(x,y,x,y+h);g.addColorStop(0,'rgba(255,255,255,.18)');g.addColorStop(1,'rgba(0,0,0,.1)');ctx.fillStyle=g;ctx.fillRect(x,y,w,h);ctx.fillStyle=sp.fg;ctx.font='bold '+Math.round(h*.54)+'px Arial';ctx.textAlign='center';ctx.fillText(sp.text,x+w/2,y+h*.73);}
function drawAdBoards(){
var pL=PITCH_L(),pR=PITCH_R(),pT=PITCH_T();
var adH=Math.max(10,Math.min((pT-2)*.5,20));
var pw=pR-pL,hw=pw/2,n=SPONSORS.top.length;
var i0=adLI%n,i1=(adLI+1)%n,i2=(adLI+2)%n,i3=(adLI+3)%n;
ctx.save();ctx.beginPath();ctx.rect(pL,pT-adH,hw,adH);ctx.clip();drawAdH(pL-adSO*hw,pT-adH,hw-1,adH,SPONSORS.top[i0]);drawAdH(pL+(1-adSO)*hw,pT-adH,hw-1,adH,SPONSORS.top[i1]);ctx.restore();
ctx.save();ctx.beginPath();ctx.rect(pL+hw,pT-adH,hw,adH);ctx.clip();drawAdH(pL+hw-adSO*hw,pT-adH,hw-1,adH,SPONSORS.top[i2]);drawAdH(pL+hw+(1-adSO)*hw,pT-adH,hw-1,adH,SPONSORS.top[i3]);ctx.restore();
}

var seatCache={};
function buildSeats(key,rows,cols,colors){if(seatCache[key])return seatCache[key];var a=[];for(var r=0;r<rows;r++){a[r]=[];for(var c=0;c<cols;c++)a[r][c]={color:colors[Math.floor(Math.random()*colors.length)],alpha:.45+Math.random()*.4};}return seatCache[key]=a;}
function drawTribunes(){
var arena=ARENA_CFG[activeArena];
var pT=PITCH_T(),tH=pT,tW=W(),cols=Math.floor(tW/7),rows=Math.max(3,Math.floor(tH/8));
var g=ctx.createLinearGradient(0,0,0,tH);g.addColorStop(0,arena.tribGrad[0]);g.addColorStop(1,arena.tribGrad[1]);
ctx.fillStyle=g;ctx.fillRect(0,0,tW,tH);
var cache=buildSeats('top_'+activeArena,rows,cols,arena.seats);
for(var r=0;r<rows;r++)for(var c=0;c<cols&&c<cache[r].length;c++){ctx.fillStyle=cache[r][c].color;ctx.globalAlpha=cache[r][c].alpha;ctx.fillRect(c*7+.5,r*(tH/rows)+1,6,Math.max(3,(tH/rows)*.65));}
ctx.globalAlpha=1;
ctx.globalAlpha=.78;arena.drawFlag(W()/2,tH/2,W()*.3,tH*.72);ctx.globalAlpha=1;
ctx.fillStyle=arena.accentLine;ctx.globalAlpha=.5;ctx.fillRect(0,tH-2,tW,2);ctx.globalAlpha=1;
}

var TEAMS=[
{n:"Austria",f:"🇦🇹",r:72},{n:"Belgium",f:"🇧🇪",r:82},{n:"Bosnia & Herz.",f:"🇧🇦",r:60},
{n:"Croatia",f:"🇭🇷",r:80},{n:"Czechia",f:"🇨🇿",r:65},{n:"England",f:"🏴󠁧󠁢󠁥󠁮󠁧󠁿",r:88},
{n:"France",f:"🇫🇷",r:96},{n:"Germany",f:"🇩🇪",r:87},{n:"Netherlands",f:"🇳🇱",r:86},
{n:"Norway",f:"🇳🇴",r:74},{n:"Portugal",f:"🇵🇹",r:91},{n:"Scotland",f:"🏴󠁧󠁢󠁳󠁣󠁴󠁿",r:65},
{n:"Spain",f:"🇪🇸",r:97},{n:"Sweden",f:"🇸🇪",r:69},{n:"Switzerland",f:"🇨🇭",r:78},{n:"Turkey",f:"🇹🇷",r:66},
{n:"Canada",f:"🇨🇦",r:70},{n:"Mexico",f:"🇲🇽",r:71},{n:"USA",f:"🇺🇸",r:72},
{n:"Curaçao",f:"🇨🇼",r:40},{n:"Haiti",f:"🇭🇹",r:42},{n:"Panama",f:"🇵🇦",r:53},
{n:"Argentina",f:"🇦🇷",r:98},{n:"Bolivia",f:"🇧🇴",r:38},{n:"Brazil",f:"🇧🇷",r:93},
{n:"Chile",f:"🇨🇱",r:55},{n:"Colombia",f:"🇨🇴",r:76},{n:"Ecuador",f:"🇪🇨",r:64},
{n:"Paraguay",f:"🇵🇾",r:58},{n:"Uruguay",f:"🇺🇾",r:77},{n:"Venezuela",f:"🇻🇪",r:52},
{n:"Australia",f:"🇦🇺",r:63},{n:"Bahrain",f:"🇧🇭",r:44},{n:"China",f:"🇨🇳",r:50},
{n:"Indonesia",f:"🇮🇩",r:45},{n:"Iran",f:"🇮🇷",r:65},{n:"Iraq",f:"🇮🇶",r:55},
{n:"Japan",f:"🇯🇵",r:83},{n:"Jordan",f:"🇯🇴",r:48},{n:"Kuwait",f:"🇰🇼",r:42},
{n:"Oman",f:"🇴🇲",r:43},{n:"Qatar",f:"🇶🇦",r:43},{n:"Saudi Arabia",f:"🇸🇦",r:59},
{n:"South Korea",f:"🇰🇷",r:75},{n:"Uzbekistan",f:"🇺🇿",r:52},
{n:"Algeria",f:"🇩🇿",r:62},{n:"Cape Verde",f:"🇨🇻",r:55},{n:"DR Congo",f:"🇨🇩",r:54},
{n:"Egypt",f:"🇪🇬",r:60},{n:"Morocco",f:"🇲🇦",r:79},{n:"Nigeria",f:"🇳🇬",r:61},
{n:"Senegal",f:"🇸🇳",r:73},{n:"South Africa",f:"🇿🇦",r:57},{n:"Tunisia",f:"🇹🇳",r:58},
{n:"New Caledonia",f:"🇳🇨",r:30},
];
var KITS={"Austria":['#ed2939','#fff','#fff','#ed2939'],"Belgium":['#ed2939','#000','#000','#ed2939'],"Bosnia & Herz.":['#003087','#ffcc00','#fff','#003087'],"Croatia":['#f00','#fff','#003087','#003087'],"Czechia":['#d7141a','#fff','#fff','#d7141a'],"England":['#fff','#c00','#c00','#fff'],"France":['#003087','#fff','#003087','#003087'],"Germany":['#fff','#000','#000','#000'],"Netherlands":['#f60','#fff','#fff','#f60'],"Norway":['#ef2b2d','#003087','#003087','#ef2b2d'],"Portugal":['#d4213d','#006600','#d4213d','#d4213d'],"Scotland":['#003087','#fff','#fff','#003087'],"Spain":['#aa151b','#f1bf00','#003087','#aa151b'],"Sweden":['#006aa7','#fecc02','#006aa7','#006aa7'],"Switzerland":['#d4213d','#fff','#d4213d','#d4213d'],"Turkey":['#e30a17','#fff','#e30a17','#e30a17'],"Canada":['#d80621','#fff','#d80621','#d80621'],"Mexico":['#006847','#fff','#d91023','#006847'],"USA":['#003087','#fff','#d4213d','#003087'],"Curaçao":['#003087','#ffcc00','#fff','#003087'],"Haiti":['#003087','#d4213d','#fff','#003087'],"Panama":['#d4213d','#003087','#003087','#d4213d'],"Argentina":['#75aadb','#fff','#000060','#000060'],"Bolivia":['#d52b1e','#007a3d','#007a3d','#d52b1e'],"Brazil":['#f9dd16','#009c3b','#003087','#f9dd16'],"Chile":['#d52b1e','#fff','#003082','#003082'],"Colombia":['#fcd116','#003087','#003087','#fcd116'],"Ecuador":['#ffdd00','#003087','#003087','#ffdd00'],"Paraguay":['#d4213d','#fff','#003087','#d4213d'],"Uruguay":['#5cb8e4','#fff','#000','#5cb8e4'],"Venezuela":['#cf142b','#003087','#003087','#cf142b'],"Australia":['#ffcd00','#00843d','#00843d','#00843d'],"Bahrain":['#ce1126','#fff','#fff','#ce1126'],"China":['#de2910','#ffde00','#fff','#de2910'],"Indonesia":['#ce1126','#fff','#fff','#ce1126'],"Iran":['#239f40','#fff','#fff','#239f40'],"Iraq":['#000','#ce1126','#fff','#000'],"Japan":['#003087','#fff','#003087','#003087'],"Jordan":['#007a3d','#fff','#ce1126','#007a3d'],"Kuwait":['#007a3d','#fff','#ce1126','#007a3d'],"Oman":['#db161b','#fff','#fff','#db161b'],"Qatar":['#8d1b3d','#fff','#8d1b3d','#8d1b3d'],"Saudi Arabia":['#006c35','#fff','#fff','#006c35'],"South Korea":['#fff','#cd2e3a','#003087','#cd2e3a'],"Uzbekistan":['#1eb53a','#fff','#003087','#1eb53a'],"Algeria":['#fff','#006233','#fff','#006233'],"Cape Verde":['#003087','#cf2027','#fff','#003087'],"DR Congo":['#007fff','#f7d618','#ce1126','#007fff'],"Egypt":['#d4213d','#fff','#fff','#d4213d'],"Morocco":['#c1272d','#006233','#006233','#c1272d'],"Nigeria":['#008751','#fff','#fff','#008751'],"Senegal":['#fff','#00853f','#00853f','#fff'],"South Africa":['#007a4d','#ffb612','#de3831','#007a4d'],"Tunisia":['#e70013','#fff','#fff','#e70013'],"New Caledonia":['#003087','#fff','#ce1126','#003087']};
var PALS=[['#cc2233','#fff','#3344aa'],['#006633','#fff','#cc1122'],['#1144aa','#44aaff','#ddeeff'],['#880044','#ff66aa','#ffddee'],['#115522','#55cc66','#eeffee'],['#cc3300','#ff8855','#fff5f0'],['#550088','#aa44cc','#f5eeff'],['#006655','#22ccdd','#e0ffff'],['#cc7700','#ffcc22','#fffff0'],['#334455','#88aacc','#eef2f5']];
function getKit(i){return i===null?['#44ccff','#1188cc','#003087','#44ccff']:KITS[TEAMS[i].n]||['#44ccff','#1188cc','#003087','#44ccff'];}
function hexRgb(h){return{r:parseInt(h.slice(1,3),16),g:parseInt(h.slice(3,5),16),b:parseInt(h.slice(5,7),16)};}
function tMult(i){if(i===null)return{power:1,cone:1,label:'',color:'#fff',rating:50};var r=TEAMS[i].r,n=(r-50)/50;return{power:1+n*.35,cone:1+n*.2,label:r>=85?'⭐⭐⭐':r>=70?'⭐⭐':r>=55?'⭐':'○',color:r>=85?'#ffd700':r>=70?'#90ee90':r>=55?'#87ceeb':'#ff8888',rating:r};}
var sel=[null,null],tm=[{power:1,cone:1},{power:1,cone:1}];
function buildDD(p){var list=document.getElementById('cl'+p);list.innerHTML='';TEAMS.forEach(function(t,i){var m=tMult(i),d=document.createElement('div');d.className='csitem'+(sel[p-1]===i?' active':'');d.innerHTML='<span style="font-size:16px">'+t.f+'</span><span style="flex:1;color:#ccc">'+t.n+'</span><span style="font-size:10px;color:'+m.color+'">'+m.label+' '+t.r+'</span>';d.onclick=function(){selectTeam(p,i);};list.appendChild(d);});}
function filterDD(p,q){document.querySelectorAll('#cl'+p+' .csitem').forEach(function(el,i){el.style.display=TEAMS[i].n.toLowerCase().indexOf(q.toLowerCase())>=0?'':'none';});}
function toggleDD(p){var dd=document.getElementById('cd'+p),btn=document.getElementById('cb'+p),o=p===1?2:1;document.getElementById('cd'+o).classList.add('hidden');document.getElementById('cb'+o).classList.remove('open');dd.classList.toggle('hidden');btn.classList.toggle('open');if(!dd.classList.contains('hidden')){buildDD(p);document.getElementById('cs'+p).value='';filterDD(p,'');}}
function selectTeam(p,i){sel[p-1]=i;document.getElementById('cf'+p).textContent=TEAMS[i].f;document.getElementById('cn'+p).textContent=TEAMS[i].n;document.getElementById('cd'+p).classList.add('hidden');document.getElementById('cb'+p).classList.remove('open');}
document.addEventListener('click',function(e){[1,2].forEach(function(p){if(!document.getElementById('cw'+p).contains(e.target)){document.getElementById('cd'+p).classList.add('hidden');document.getElementById('cb'+p).classList.remove('open');}});});
var aiDiff=1;
function setDiff(d){aiDiff=d;document.querySelectorAll('.dbtn').forEach(function(b,i){b.classList.toggle('sel',i===d);});}

var SKIN_TONES=['#f5c87a','#d4956a','#b5703a','#7a3d1a','#e8b87a'];
var CL={"Austria":{s:0,h:'#6b3a1f',t:'short'},"Belgium":{s:0,h:'#4a2c0a',t:'short'},"Bosnia & Herz.":{s:0,h:'#3b1f0a',t:'short'},"Croatia":{s:0,h:'#4a2c0a',t:'short'},"Czechia":{s:0,h:'#8b6914',t:'short'},"England":{s:0,h:'#c8a040',t:'short'},"France":{s:1,h:'#2a1500',t:'short'},"Germany":{s:0,h:'#d4a830',t:'short'},"Netherlands":{s:0,h:'#d4a830',t:'short'},"Norway":{s:0,h:'#e8d080',t:'short'},"Portugal":{s:1,h:'#2a1500',t:'short'},"Scotland":{s:0,h:'#c03000',t:'short'},"Spain":{s:1,h:'#2a1500',t:'short'},"Sweden":{s:0,h:'#e8d080',t:'short'},"Switzerland":{s:0,h:'#6b3a1f',t:'short'},"Turkey":{s:1,h:'#1a0a00',t:'short'},"Canada":{s:0,h:'#8b4513',t:'short'},"Mexico":{s:2,h:'#0a0600',t:'straight'},"USA":{s:0,h:'#8b4513',t:'short'},"Curaçao":{s:3,h:'#080400',t:'curly'},"Haiti":{s:3,h:'#080400',t:'curly'},"Panama":{s:2,h:'#0a0600',t:'straight'},"Argentina":{s:1,h:'#3b1f0a',t:'short'},"Bolivia":{s:2,h:'#0a0600',t:'straight'},"Brazil":{s:2,h:'#1a0a00',t:'short'},"Chile":{s:2,h:'#0a0600',t:'straight'},"Colombia":{s:2,h:'#1a0a00',t:'short'},"Ecuador":{s:2,h:'#0a0600',t:'straight'},"Paraguay":{s:2,h:'#0a0600',t:'straight'},"Uruguay":{s:1,h:'#3b1f0a',t:'short'},"Venezuela":{s:2,h:'#1a0a00',t:'short'},"Australia":{s:0,h:'#c8a040',t:'short'},"Bahrain":{s:2,h:'#0a0600',t:'short'},"China":{s:4,h:'#050300',t:'straight'},"Indonesia":{s:4,h:'#050300',t:'straight'},"Iran":{s:2,h:'#0a0600',t:'short'},"Iraq":{s:2,h:'#0a0600',t:'short'},"Japan":{s:4,h:'#050300',t:'straight'},"Jordan":{s:2,h:'#0a0600',t:'short'},"Kuwait":{s:2,h:'#0a0600',t:'short'},"Oman":{s:2,h:'#0a0600',t:'short'},"Qatar":{s:2,h:'#0a0600',t:'short'},"Saudi Arabia":{s:2,h:'#0a0600',t:'short'},"South Korea":{s:4,h:'#050300',t:'straight'},"Uzbekistan":{s:4,h:'#050300',t:'straight'},"Algeria":{s:2,h:'#1a0a00',t:'short'},"Cape Verde":{s:3,h:'#080400',t:'curly'},"DR Congo":{s:3,h:'#080400',t:'curly'},"Egypt":{s:2,h:'#0a0600',t:'short'},"Morocco":{s:2,h:'#0a0600',t:'short'},"Nigeria":{s:3,h:'#080400',t:'curly'},"Senegal":{s:3,h:'#080400',t:'curly'},"South Africa":{s:3,h:'#080400',t:'curly'},"Tunisia":{s:2,h:'#1a0a00',t:'short'},"New Caledonia":{s:3,h:'#080400',t:'curly'}};
function getApp(i){if(i===null)return{skin:'#f5c87a',hair:'#4a2c0a',htype:'short'};var l=CL[TEAMS[i].n]||{s:0,h:'#4a2c0a',t:'short'};return{skin:SKIN_TONES[l.s],hair:l.h,htype:l.t};}

var scAnim=0,scVisible=false,scTO=null,scSide=0,scFrame=0,scFTO=null,scType=0;
function showSC(side,type){
scSide=side;scType=type!==undefined?type:0;scVisible=true;scAnim=0;scFrame=0;
scCanvas.classList.remove('off');clearTimeout(scTO);clearTimeout(scFTO);
function lC(){scFrame=(scFrame+1)%2;drawSC();scFTO=setTimeout(lC,380);}lC();
var t0=null;
function up(ts){if(!t0)t0=ts;scAnim=Math.min((ts-t0)/520,1);drawSC();if(scAnim<1)requestAnimationFrame(up);else scTO=setTimeout(function(){clearTimeout(scFTO);var t1=null;function dn(ts2){if(!t1)t1=ts2;scAnim=1-Math.min((ts2-t1)/420,1);drawSC();if(scAnim>0)requestAnimationFrame(dn);else{scVisible=false;scCanvas.classList.add('off');}}requestAnimationFrame(dn);},5000);}
requestAnimationFrame(up);
}
function drawSC(){if(!scVisible)return;sctx.clearRect(0,0,W(),H());var s=Math.min(CTRL_W()*.9,H()*.5);var inset=s*0.55;var cx=scSide===0?Math.max(inset,CTRL_W()*.5):Math.min(W()-inset,W()-CTRL_W()*.5);var cy=H()*.62+(1-scAnim)*H()*.5;sctx.save();sctx.translate(cx,cy);if(scSide!==0)sctx.scale(-1,1);if(scType===1)drawSCCanadian(sctx,s,scFrame);else if(scType===2)drawSCMexican(sctx,s,scFrame);else drawSCB(sctx,s,scFrame);sctx.restore();}
function hideSC(){clearTimeout(scTO);clearTimeout(scFTO);scVisible=false;scCanvas.classList.add('off');sctx.clearRect(0,0,W(),H());}

function drawPointingArm(c,s,skinCol,sleeveCol,fr){
c.save();c.translate(s*.28,s*.1);
c.fillStyle=sleeveCol;c.beginPath();c.roundRect(0,-s*.08,s*.3,s*.16,s*.06);c.fill();
c.fillStyle=skinCol;c.beginPath();c.arc(s*.36,0,s*.11,0,Math.PI*2);c.fill();
c.strokeStyle='rgba(0,0,0,.1)';c.lineWidth=s*.01;c.beginPath();c.arc(s*.36,0,s*.07,Math.PI*1.1,Math.PI*1.9);c.stroke();
c.fillStyle=skinCol;c.save();c.translate(s*.36,-s*.09);c.rotate(-Math.PI/2+0.25);
c.beginPath();c.roundRect(-s*.03,0,s*.06,s*.2,s*.03);c.fill();
c.beginPath();c.arc(0,s*.2,s*.03,0,Math.PI*2);c.fill();
c.fillStyle='rgba(160,110,70,.5)';c.beginPath();c.roundRect(-s*.025,0,s*.05,s*.055,s*.015);c.fill();
c.restore();c.restore();
}
function drawBellyArm(c,s,skinCol,sleeveCol,fr){
c.save();var bounce=fr===0?0.1:-0.1;
c.save();c.translate(-s*.38,s*.1+bounce*s*.05);c.rotate(0.6+bounce);
c.fillStyle=sleeveCol;c.fillRect(-s*.09,0,s*.18,s*.26);
c.fillStyle=skinCol;c.beginPath();c.arc(0,s*.28,s*.1,0,Math.PI*2);c.fill();
for(var fj=-1;fj<=1;fj++){c.save();c.translate(fj*s*.06,s*.3);c.rotate(fj*0.2);c.fillStyle=skinCol;c.beginPath();c.roundRect(-s*.025,-s*.07,s*.05,s*.09,s*.02);c.fill();c.restore();}
c.restore();c.restore();
}

function drawSCB(c,s,fr){
var lw=fr===0;
c.fillStyle='rgba(0,0,0,.3)';c.beginPath();c.ellipse(0,s*1.1,s*.55,s*.1,0,0,Math.PI*2);c.fill();
c.fillStyle='#1c2951';c.beginPath();c.roundRect(-s*.3,s*.52,s*.24,s*.58,s*.05);c.fill();c.beginPath();c.roundRect(s*.06,s*.52,s*.24,s*.58,s*.05);c.fill();
c.fillStyle='#111';c.beginPath();c.ellipse(-s*.2,s*1.12,s*.24,s*.09,-.1,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.2,s*1.12,s*.24,s*.09,.1,0,Math.PI*2);c.fill();
c.fillStyle='#14142a';c.beginPath();c.roundRect(-s*.42,-s*.1,s*.84,s*.65,s*.08);c.fill();
c.fillStyle='#1e1e3e';c.beginPath();c.moveTo(-s*.42,-s*.1);c.lineTo(-s*.1,s*.28);c.lineTo(-s*.1,-s*.1);c.closePath();c.fill();
c.beginPath();c.moveTo(s*.42,-s*.1);c.lineTo(s*.1,s*.28);c.lineTo(s*.1,-s*.1);c.closePath();c.fill();
c.fillStyle='#f8f8f8';c.beginPath();c.moveTo(-s*.1,-s*.1);c.lineTo(s*.1,-s*.1);c.lineTo(s*.13,s*.3);c.lineTo(-s*.13,s*.3);c.closePath();c.fill();
for(var bi=0;bi<3;bi++){c.fillStyle='#ddd';c.beginPath();c.arc(0,s*(-.02+bi*.1),s*.022,0,Math.PI*2);c.fill();}
c.fillStyle='#cc1111';c.beginPath();c.moveTo(-s*.07,-s*.08);c.lineTo(s*.07,-s*.08);c.lineTo(s*.1,s*.28);c.lineTo(s*.05,s*.85);c.lineTo(0,s*.95);c.lineTo(-s*.05,s*.85);c.lineTo(-s*.1,s*.28);c.closePath();c.fill();
drawPointingArm(c,s,'#f0b86a','#14142a',fr);
drawBellyArm(c,s,'#f0b86a','#14142a',fr);
c.fillStyle='#f0b86a';c.beginPath();c.roundRect(-s*.11,-s*.28,s*.22,s*.2,s*.04);c.fill();
c.fillStyle='#f0b86a';c.beginPath();c.moveTo(0,-s*.98);c.bezierCurveTo(s*.42,-s*.98,s*.46,-s*.7,s*.44,-s*.5);c.bezierCurveTo(s*.42,-s*.22,s*.36,-s*.1,s*.24,-s*.06);c.lineTo(-s*.24,-s*.06);c.bezierCurveTo(-s*.36,-s*.1,-s*.42,-s*.22,-s*.44,-s*.5);c.bezierCurveTo(-s*.46,-s*.7,-s*.42,-s*.98,0,-s*.98);c.fill();
c.fillStyle='#e07818';c.beginPath();c.ellipse(0,-s*.88,s*.44,s*.22,0,Math.PI,0);c.fill();
var pg=c.createLinearGradient(-s*.3,-s*1.1,s*.3,-s*.7);pg.addColorStop(0,'#ffb030');pg.addColorStop(.4,'#ff9500');pg.addColorStop(1,'#e07010');c.fillStyle=pg;
c.beginPath();c.moveTo(-s*.44,-s*.62);c.bezierCurveTo(-s*.4,-s*1.05,s*.5,-s*1.12,s*.42,-s*.62);c.bezierCurveTo(s*.38,-s*.72,-s*.38,-s*.72,-s*.44,-s*.62);c.fill();
c.fillStyle='#ffaa28';for(var wi=-2;wi<=2;wi++){c.beginPath();c.arc(wi*s*.12,-s*.88,s*.12,Math.PI,0);c.fill();}
c.fillStyle='#d06810';c.beginPath();c.moveTo(-s*.44,-s*.62);c.quadraticCurveTo(0,-s*.78,s*.44,-s*.62);c.quadraticCurveTo(s*.2,-s*.56,-s*.2,-s*.56);c.closePath();c.fill();
c.fillStyle='#e07818';c.beginPath();c.ellipse(-s*.44,-s*.48,s*.07,s*.22,-.15,0,Math.PI*2);c.fill();
[[-s*.15,-s*.6],[s*.15,-s*.6]].forEach(function(p){c.fillStyle='#fff';c.beginPath();c.ellipse(p[0],p[1],s*.12,s*.09,0,0,Math.PI*2);c.fill();var ig=c.createRadialGradient(p[0]-s*.02,p[1]-s*.02,0,p[0],p[1],s*.07);ig.addColorStop(0,'#88ccee');ig.addColorStop(.5,'#4488cc');ig.addColorStop(1,'#224488');c.fillStyle=ig;c.beginPath();c.arc(p[0],p[1],s*.07,0,Math.PI*2);c.fill();c.fillStyle='#111';c.beginPath();c.arc(p[0],p[1],s*.035,0,Math.PI*2);c.fill();c.fillStyle='rgba(255,255,255,.8)';c.beginPath();c.arc(p[0]-s*.028,p[1]-s*.028,s*.016,0,Math.PI*2);c.fill();});
c.fillStyle='rgba(255,100,80,.22)';c.beginPath();c.ellipse(-s*.33,-s*.42,s*.14,s*.1,0,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.33,-s*.42,s*.14,s*.1,0,0,Math.PI*2);c.fill();
var _bw=s*1.5,_bh=s*.5,_bx=s*.1,_by=-s*1.12-_bh-s*.1;
c.fillStyle='rgba(0,0,0,.2)';c.beginPath();c.roundRect(_bx+3,_by+3,_bw,_bh,s*.08);c.fill();
c.fillStyle='#fff';c.beginPath();c.roundRect(_bx,_by,_bw,_bh,s*.08);c.fill();
c.strokeStyle='#ddd';c.lineWidth=s*.02;c.stroke();
c.fillStyle='#fff';c.beginPath();c.moveTo(_bx+s*.2,_by+_bh);c.lineTo(_bx+s*.05,_by+_bh+s*.2);c.lineTo(_bx+s*.45,_by+_bh);c.closePath();c.fill();
c.save();c.setTransform(1,0,0,1,0,0);
var _aX=scSide===0?CTRL_W()*.5:W()-CTRL_W()*.5,_aY=H()*.62+(1-scAnim)*H()*.5;
var _tX=scSide===0?_aX+_bx+_bw/2:_aX-(_bx+_bw/2),_tY=_aY+_by;
c.fillStyle='#cc0000';c.font='bold '+Math.round(s*.17)+'px Arial';c.textAlign='center';
c.fillText('WORLD',_tX,_tY+_bh*.44);c.font='bold '+Math.round(s*.14)+'px Arial';
c.fillText('HUMILIATION!',_tX,_tY+_bh*.84);c.restore();
if(lw){
c.fillStyle='#881010';c.beginPath();c.arc(0,-s*.22,s*.22,.08,Math.PI-.08);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.22,s*.18,.1,Math.PI-.1);c.fill();
c.strokeStyle='#ccc';c.lineWidth=s*.012;
for(var d=-2;d<=2;d++){c.beginPath();c.moveTo(d*s*.04,-s*.22);c.lineTo(d*s*.038,-s*.13);c.stroke();}
c.fillStyle='#e84040';c.beginPath();c.ellipse(0,-s*.14,s*.1,s*.05,0,0,Math.PI*2);c.fill();
}else{
c.fillStyle='#881010';c.beginPath();c.arc(0,-s*.22,s*.24,.06,Math.PI-.06);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.22,s*.2,.08,Math.PI-.08);c.fill();
c.strokeStyle='#ccc';c.lineWidth=s*.012;
for(var d3=-2;d3<=2;d3++){c.beginPath();c.moveTo(d3*s*.04,-s*.22);c.lineTo(d3*s*.038,-s*.12);c.stroke();}
c.fillStyle='#e84040';c.beginPath();c.ellipse(s*.01,-s*.13,s*.12,s*.055,0,0,Math.PI*2);c.fill();
}
}

function drawSCCanadian(c,s,fr){
var lw=fr===0;
c.fillStyle='rgba(0,0,0,.3)';c.beginPath();c.ellipse(0,s*1.48,s*.55,s*.1,0,0,Math.PI*2);c.fill();
c.fillStyle='#0d1a30';c.beginPath();c.roundRect(-s*.3,s*.52,s*.24,s*.78,s*.05);c.fill();c.beginPath();c.roundRect(s*.06,s*.52,s*.24,s*.78,s*.05);c.fill();
c.strokeStyle='#162040';c.lineWidth=s*.012;c.beginPath();c.moveTo(-s*.18,s*.54);c.lineTo(-s*.18,s*1.12);c.stroke();c.beginPath();c.moveTo(s*.18,s*.54);c.lineTo(s*.18,s*1.12);c.stroke();
c.fillStyle='#111';c.beginPath();c.ellipse(-s*.18,s*1.32,s*.28,s*.1,-.06,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.22,s*1.32,s*.28,s*.1,.06,0,Math.PI*2);c.fill();
c.fillStyle='#333';c.beginPath();c.ellipse(-s*.18,s*1.28,s*.22,s*.06,-.06,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.22,s*1.28,s*.22,s*.06,.06,0,Math.PI*2);c.fill();
c.fillStyle='#1a1a1a';c.beginPath();c.ellipse(-s*.32,s*1.3,s*.1,s*.07,-.1,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.34,s*1.3,s*.1,s*.07,.1,0,Math.PI*2);c.fill();
c.fillStyle='#112244';c.beginPath();c.roundRect(-s*.42,-s*.1,s*.84,s*.65,s*.06);c.fill();
c.fillStyle='#0a1830';c.beginPath();c.moveTo(-s*.42,-s*.1);c.lineTo(-s*.1,s*.28);c.lineTo(-s*.1,-s*.1);c.closePath();c.fill();c.beginPath();c.moveTo(s*.42,-s*.1);c.lineTo(s*.1,s*.28);c.lineTo(s*.1,-s*.1);c.closePath();c.fill();
c.fillStyle='#f2f2f2';c.beginPath();c.moveTo(-s*.1,-s*.1);c.lineTo(s*.1,-s*.1);c.lineTo(s*.12,s*.3);c.lineTo(-s*.12,s*.3);c.closePath();c.fill();
c.strokeStyle='rgba(255,255,255,.06)';c.lineWidth=s*.012;
for(var pi=-3;pi<=3;pi++){c.beginPath();c.moveTo(pi*s*.12,-s*.1);c.lineTo(pi*s*.12,s*.55);c.stroke();}
c.fillStyle='#6b0f1a';c.beginPath();c.moveTo(-s*.042,-s*.08);c.lineTo(s*.042,-s*.08);c.lineTo(s*.055,s*.28);c.lineTo(s*.032,s*.70);c.lineTo(0,s*.80);c.lineTo(-s*.032,s*.70);c.lineTo(-s*.055,s*.28);c.closePath();c.fill();
c.fillStyle='#4a0a12';c.beginPath();c.moveTo(-s*.03,-s*.1);c.lineTo(s*.03,-s*.1);c.lineTo(s*.04,-s*.04);c.lineTo(0,-s*.01);c.lineTo(-s*.04,-s*.04);c.closePath();c.fill();
c.fillStyle='#cc0000';c.font=Math.round(s*.1)+'px serif';c.textAlign='center';c.fillText('🍁',s*.28,s*.06);
c.fillStyle='#eee';c.beginPath();c.moveTo(-s*.38,-s*.02);c.lineTo(-s*.28,-s*.02);c.lineTo(-s*.28,s*.06);c.lineTo(-s*.38,s*.04);c.closePath();c.fill();
drawPointingArm(c,s,'#f0d0a0','#112244',fr);
drawBellyArm(c,s,'#f0d0a0','#112244',fr);
c.fillStyle='#f0d0a0';c.fillRect(-s*.1,-s*.18,s*.2,s*.14);
c.fillStyle='#f0d0a0';c.beginPath();c.moveTo(-s*.24,-s*.56);c.bezierCurveTo(-s*.33,-s*.55,-s*.34,-s*.36,-s*.31,-s*.2);c.bezierCurveTo(-s*.29,-s*.07,-s*.22,-s*.13,-s*.1,-s*.15);c.lineTo(0,-s*.14);c.lineTo(s*.1,-s*.15);c.bezierCurveTo(s*.22,-s*.13,s*.29,-s*.07,s*.31,-s*.2);c.bezierCurveTo(s*.34,-s*.36,s*.33,-s*.55,s*.24,-s*.56);c.closePath();c.fill();
c.strokeStyle='#888';c.lineWidth=s*.026;c.lineCap='round';c.beginPath();c.moveTo(-s*.22,-s*.44);c.lineTo(-s*.04,-s*.44);c.stroke();c.beginPath();c.moveTo(s*.04,-s*.44);c.lineTo(s*.22,-s*.44);c.stroke();
c.fillStyle='#fff';c.beginPath();c.ellipse(-s*.13,-s*.38,s*.088,s*.062,0,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.13,-s*.38,s*.088,s*.062,0,0,Math.PI*2);c.fill();
var ig1=c.createRadialGradient(-s*.13,-s*.39,0,-s*.13,-s*.38,s*.054);ig1.addColorStop(0,'#7ac4f0');ig1.addColorStop(.5,'#2e7ec4');ig1.addColorStop(1,'#1a5a9a');c.fillStyle=ig1;c.beginPath();c.arc(-s*.13,-s*.38,s*.05,0,Math.PI*2);c.fill();
var ig2=c.createRadialGradient(s*.13,-s*.39,0,s*.13,-s*.38,s*.054);ig2.addColorStop(0,'#7ac4f0');ig2.addColorStop(.5,'#2e7ec4');ig2.addColorStop(1,'#1a5a9a');c.fillStyle=ig2;c.beginPath();c.arc(s*.13,-s*.38,s*.05,0,Math.PI*2);c.fill();
c.fillStyle='#0a1a2a';c.beginPath();c.arc(-s*.13,-s*.38,s*.026,0,Math.PI*2);c.fill();c.beginPath();c.arc(s*.13,-s*.38,s*.026,0,Math.PI*2);c.fill();
c.fillStyle='rgba(255,255,255,.8)';c.beginPath();c.arc(-s*.12,-s*.4,s*.012,0,Math.PI*2);c.fill();c.beginPath();c.arc(s*.14,-s*.4,s*.012,0,Math.PI*2);c.fill();
c.fillStyle='#c8c8c8';c.beginPath();c.roundRect(-s*.28,-s*.62,s*.56,s*.2,s*.09);c.fill();c.beginPath();c.roundRect(-s*.3,-s*.56,s*.065,s*.14,s*.02);c.fill();c.beginPath();c.roundRect(s*.235,-s*.56,s*.065,s*.14,s*.02);c.fill();
if(lw){
c.fillStyle='#7a1010';c.beginPath();c.arc(0,-s*.18,s*.18,.05,Math.PI-.05);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.18,s*.155,.08,Math.PI-.08);c.fill();
c.strokeStyle='#ccc';c.lineWidth=s*.012;
for(var ti=-2;ti<=2;ti++){c.beginPath();c.moveTo(ti*s*.045,-s*.18);c.lineTo(ti*s*.042,-s*.1);c.stroke();}
c.fillStyle='#e05060';c.beginPath();c.ellipse(0,-s*.12,s*.1,s*.06,0,0,Math.PI*2);c.fill();
}else{
c.fillStyle='#6a0808';c.beginPath();c.arc(0,-s*.16,s*.2,.03,Math.PI-.03);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.16,s*.17,.06,Math.PI-.06);c.fill();
c.fillStyle='#e05060';c.beginPath();c.ellipse(s*.02,-s*.09,s*.11,s*.065,0,0,Math.PI*2);c.fill();
}
_drawBubble(c,s,'HUMILIATION','MONDIALE!','#0d1a30',-s*.62);
}

function drawSCMexican(c,s,fr){
var lw=fr===0;
c.fillStyle='rgba(0,0,0,.3)';c.beginPath();c.ellipse(0,s*1.1,s*.55,s*.1,0,0,Math.PI*2);c.fill();
c.fillStyle='#f0f0f0';c.beginPath();c.roundRect(-s*.3,s*.52,s*.24,s*.58,s*.05);c.fill();c.beginPath();c.roundRect(s*.06,s*.52,s*.24,s*.58,s*.05);c.fill();
c.fillStyle='#d4aa00';c.fillRect(-s*.19,s*.52,s*.04,s*.58);c.fillRect(s*.15,s*.52,s*.04,s*.58);
c.fillStyle='#111';c.beginPath();c.ellipse(-s*.2,s*1.12,s*.24,s*.09,-.1,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.2,s*1.12,s*.24,s*.09,.1,0,Math.PI*2);c.fill();
c.fillStyle='#0a3a0a';c.beginPath();c.roundRect(-s*.42,-s*.1,s*.84,s*.65,s*.08);c.fill();
c.strokeStyle='#d4aa00';c.lineWidth=s*.04;c.beginPath();c.moveTo(-s*.42,-s*.1);c.lineTo(-s*.42,s*.55);c.stroke();c.beginPath();c.moveTo(s*.42,-s*.1);c.lineTo(s*.42,s*.55);c.stroke();
c.fillStyle='#062a06';c.beginPath();c.moveTo(-s*.42,-s*.1);c.lineTo(-s*.1,s*.28);c.lineTo(-s*.1,-s*.1);c.closePath();c.fill();c.beginPath();c.moveTo(s*.42,-s*.1);c.lineTo(s*.1,s*.28);c.lineTo(s*.1,-s*.1);c.closePath();c.fill();
c.fillStyle='#f8f8f8';c.beginPath();c.moveTo(-s*.1,-s*.1);c.lineTo(s*.1,-s*.1);c.lineTo(s*.12,s*.3);c.lineTo(-s*.12,s*.3);c.closePath();c.fill();
c.fillStyle='#006847';c.beginPath();c.moveTo(-s*.05,-s*.08);c.lineTo(0,-s*.08);c.lineTo(0,s*.75);c.lineTo(-s*.04,s*.65);c.closePath();c.fill();
c.fillStyle='#fff';c.beginPath();c.moveTo(0,-s*.08);c.lineTo(s*.025,-s*.08);c.lineTo(s*.025,s*.75);c.lineTo(0,s*.75);c.closePath();c.fill();
c.fillStyle='#ce1126';c.beginPath();c.moveTo(s*.025,-s*.08);c.lineTo(s*.05,-s*.08);c.lineTo(s*.06,s*.65);c.lineTo(s*.025,s*.75);c.closePath();c.fill();
drawPointingArm(c,s,'#c8956a','#0a3a0a',fr);
drawBellyArm(c,s,'#c8956a','#0a3a0a',fr);
c.fillStyle='#c8956a';c.fillRect(-s*.1,-s*.18,s*.2,s*.14);
c.fillStyle='#c8956a';c.beginPath();c.roundRect(-s*.28,-s*.58,s*.56,s*.42,s*.07);c.fill();
c.fillStyle='#fff';c.beginPath();c.ellipse(-s*.1,-s*.42,s*.055,s*.06,0,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.1,-s*.42,s*.055,s*.06,0,0,Math.PI*2);c.fill();
c.fillStyle='#1a0800';c.beginPath();c.arc(-s*.07,-s*.42,s*.035,0,Math.PI*2);c.fill();c.beginPath();c.arc(s*.13,-s*.42,s*.035,0,Math.PI*2);c.fill();
c.fillStyle='#000';c.beginPath();c.arc(-s*.07,-s*.42,s*.018,0,Math.PI*2);c.fill();c.beginPath();c.arc(s*.13,-s*.42,s*.018,0,Math.PI*2);c.fill();
c.fillStyle='#1a0800';c.beginPath();c.ellipse(-s*.1,-s*.3,s*.12,s*.05,-.2,0,Math.PI*2);c.fill();c.beginPath();c.ellipse(s*.1,-s*.3,s*.12,s*.05,.2,0,Math.PI*2);c.fill();
if(lw){
c.fillStyle='#6b1010';c.beginPath();c.arc(0,-s*.2,s*.14,.1,Math.PI-.1);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.2,s*.11,.12,Math.PI-.12);c.fill();
c.fillStyle='#e05050';c.beginPath();c.ellipse(0,-s*.13,s*.07,s*.04,0,0,Math.PI*2);c.fill();
}else{
c.fillStyle='#6b1010';c.beginPath();c.arc(0,-s*.19,s*.16,.08,Math.PI-.08);c.closePath();c.fill();
c.fillStyle='#fffff0';c.beginPath();c.arc(0,-s*.19,s*.13,.1,Math.PI-.1);c.fill();
c.fillStyle='#e05050';c.beginPath();c.ellipse(s*.01,-s*.12,s*.08,s*.045,0,0,Math.PI*2);c.fill();
}
c.fillStyle='#8b6914';c.beginPath();c.ellipse(0,-s*.64,s*.7,s*.14,0,0,Math.PI*2);c.fill();
c.fillStyle='#d4aa00';c.lineWidth=s*.025;c.beginPath();c.ellipse(0,-s*.64,s*.7,s*.14,0,0,Math.PI*2);c.stroke();
var sg=c.createLinearGradient(0,-s*1.2,0,-s*.6);sg.addColorStop(0,'#a07820');sg.addColorStop(1,'#6b5010');c.fillStyle=sg;
c.beginPath();c.ellipse(0,-s*.64,s*.3,s*.08,0,0,Math.PI*2);c.fill();
c.beginPath();c.moveTo(-s*.3,-s*.64);c.bezierCurveTo(-s*.28,-s*1.15,s*.28,-s*1.15,s*.3,-s*.64);c.closePath();c.fill();
c.fillStyle='#d4aa00';
for(var wi2=-2;wi2<=2;wi2++){c.beginPath();c.arc(wi2*s*.22,-s*.66,s*.025,0,Math.PI*2);c.fill();}
_drawBubble(c,s,'VERGÜENZA','MUNDIAL!','#006847',-s*1.2);
}

function _drawBubble(c,s,line1,line2,col,headTop){
var ht=headTop!==undefined?headTop:-s*.62;
var bw=s*1.5,bh=s*.5,bx=s*.1,by=ht-bh-s*.1;
c.fillStyle='rgba(0,0,0,.2)';c.beginPath();c.roundRect(bx+3,by+3,bw,bh,s*.08);c.fill();
c.fillStyle='#fff';c.beginPath();c.roundRect(bx,by,bw,bh,s*.08);c.fill();
c.strokeStyle='#ddd';c.lineWidth=s*.02;c.stroke();
c.fillStyle='#fff';c.beginPath();c.moveTo(bx+s*.2,by+bh);c.lineTo(bx+s*.05,by+bh+s*.2);c.lineTo(bx+s*.45,by+bh);c.closePath();c.fill();
c.save();c.setTransform(1,0,0,1,0,0);
var aX=scSide===0?CTRL_W()*.5:W()-CTRL_W()*.5;
var aY=H()*.62+(1-scAnim)*H()*.5;
var tX=scSide===0?aX+bx+bw/2:aX-(bx+bw/2);
var tY=aY+by;
c.fillStyle=col;c.font='bold '+Math.round(s*.17)+'px Arial';c.textAlign='center';
c.fillText(line1,tX,tY+bh*.44);c.font='bold '+Math.round(s*.14)+'px Arial';
c.fillText(line2,tX,tY+bh*.84);c.restore();
}

function mkRot(rx,ry,rz){var cx=Math.cos(rx),sx=Math.sin(rx),cy=Math.cos(ry),sy=Math.sin(ry),cz=Math.cos(rz),sz=Math.sin(rz);return[[cy*cz,cz*sx*sy-cx*sz,cx*cz*sy+sx*sz],[cy*sz,cx*cz+sx*sy*sz,cx*sy*sz-cz*sx],[-sy,cy*sx,cx*cy]];}
function applyRot(m,v){return[m[0][0]*v[0]+m[0][1]*v[1]+m[0][2]*v[2],m[1][0]*v[0]+m[1][1]*v[1]+m[1][2]*v[2],m[2][0]*v[0]+m[2][1]*v[1]+m[2][2]*v[2]];}
function Ball(x,y,idx){this.x=x;this.y=y;this.vx=0;this.vy=0;this.r=RR();this.scored=false;this.rx=Math.random()*Math.PI*2;this.ry=Math.random()*Math.PI*2;this.rz=Math.random()*Math.PI*2;this.pal=PALS[idx%PALS.length];this.trail=[];this.powerHit=0;this.powerTrail=[];this.meteor=0;}
Ball.prototype.update=function(dt){
if(this.scored)return;
if(!ringsActive){this.rz+=.013;this.rx+=.008;return;}
var spd=Math.hypot(this.vx,this.vy);
if(spd>.05){this.rx+=-this.vy/this.r*.5;this.ry+=this.vx/this.r*.5;}
this.rz+=.008;
if(this.powerHit>0)this.powerHit-=dt;
if(this.meteor>0)this.meteor-=dt;else{this.vx*=.985;this.vy*=.985;}
this.vx+=(Math.random()-.5)*.004;this.vy+=(Math.random()-.5)*.004;
var mS=this.powerHit>0?22:9;spd=Math.hypot(this.vx,this.vy);if(spd>mS){this.vx=this.vx/spd*mS;this.vy=this.vy/spd*mS;}
this.trail.push({x:this.x,y:this.y});if(this.trail.length>6)this.trail.shift();
if(this.powerHit>0){this.powerTrail.push({x:this.x,y:this.y});if(this.powerTrail.length>18)this.powerTrail.shift();}else this.powerTrail=[];
this.x+=this.vx*dt*60;this.y+=this.vy*dt*60;
var pT=PITCH_T(),pB=PITCH_B(),pL=PITCH_L(),pR=PITCH_R(),gT=GT(),gB=GB(),gd=GD();
/* ── yellow balls: bounce off all walls, never score ── */
var isYellow=(this.pal===PALS[0]); /* PALS[0] is the yellow palette */
if(this.y-this.r<pT){this.y=pT+this.r;this.vy=Math.abs(this.vy)*.82;}
if(this.y+this.r>pB){this.y=pB-this.r;this.vy=-Math.abs(this.vy)*.82;}
if(!this.scored){
if(isYellow){
/* bounce off goal lines and side walls regardless of gT/gB */
if(this.x-this.r<pL){this.x=pL+this.r;this.vx=Math.abs(this.vx)*.82;}
if(this.x+this.r>pR){this.x=pR-this.r;this.vx=-Math.abs(this.vx)*.82;}
}else{
if(this.y>gT&&this.y<gB){if(this.x-this.r<pL-gd){this.scored=true;triggerGoal(1);return;}else if(this.x-this.r<pL){}}else if(this.x-this.r<pL){this.x=pL+this.r;this.vx=Math.abs(this.vx)*.82;}
if(this.y>gT&&this.y<gB){if(this.x+this.r>pR+gd){this.scored=true;triggerGoal(0);return;}else if(this.x+this.r>pR){}}else if(this.x+this.r>pR){this.x=pR-this.r;this.vx=-Math.abs(this.vx)*.82;}
}
}
if(!this.scored){var sp2=Math.hypot(this.vx,this.vy),nT=this.y-this.r<pT+2,nB=this.y+this.r>pB-2;if(sp2<.4&&(nT||nB)){if(nT||nB){this.vx+=(Math.random()-.5)*2.5;this.vy+=nT?1.2:-1.2;}}}
};
Ball.prototype.draw=function(){
if(this.scored)return;
var r=this.r,cx=this.x,cy=this.y,i;
if(this.powerHit>0&&this.powerTrail.length>1){for(i=0;i<this.powerTrail.length-1;i++){var t=i/this.powerTrail.length,al=t*this.powerHit*.8;ctx.beginPath();ctx.moveTo(this.powerTrail[i].x,this.powerTrail[i].y);ctx.lineTo(this.powerTrail[i+1].x,this.powerTrail[i+1].y);ctx.strokeStyle='rgba(255,'+(180+Math.round(t*75))+','+(50+Math.round(t*50))+','+al+')';ctx.lineWidth=r*(.7-t*.4);ctx.lineCap='round';ctx.stroke();}}
if(this.meteor>0&&this.powerTrail.length>1){for(i=0;i<this.powerTrail.length-1;i++){var m2=i/this.powerTrail.length,am=m2*this.meteor*1.2;ctx.beginPath();ctx.moveTo(this.powerTrail[i].x,this.powerTrail[i].y);ctx.lineTo(this.powerTrail[i+1].x,this.powerTrail[i+1].y);ctx.strokeStyle='rgba(255,'+(80+Math.round(m2*60))+',0,'+Math.min(am,1)+')';ctx.lineWidth=r*(1.2-m2*.7);ctx.lineCap='round';ctx.stroke();}}
for(i=0;i<this.trail.length;i++){ctx.beginPath();ctx.arc(this.trail[i].x,this.trail[i].y,r*(.15+i/this.trail.length*.45),0,Math.PI*2);ctx.fillStyle='rgba(180,220,255,'+(i/this.trail.length*.07)+')';ctx.fill();}
var sg=ctx.createRadialGradient(cx+r*.22,cy+r*.22,0,cx+r*.22,cy+r*.22,r*1.05);sg.addColorStop(0,'rgba(0,0,0,.28)');sg.addColorStop(1,'rgba(0,0,0,0)');ctx.beginPath();ctx.arc(cx+r*.22,cy+r*.22,r*1.05,0,Math.PI*2);ctx.fillStyle=sg;ctx.fill();
ctx.save();ctx.beginPath();ctx.arc(cx,cy,r,0,Math.PI*2);ctx.clip();
var bg=ctx.createRadialGradient(cx-r*.28,cy-r*.32,r*.04,cx,cy,r);bg.addColorStop(0,'#f8f8f8');bg.addColorStop(.55,'#d5d5d5');bg.addColorStop(1,'#888');
ctx.beginPath();ctx.arc(cx,cy,r,0,Math.PI*2);ctx.fillStyle=bg;ctx.fill();
var rot=mkRot(this.rx,this.ry,this.rz),axes=[[0,-1,0],[.866,.5,0],[-.866,.5,0]];
for(i=0;i<3;i++){var rp=applyRot(rot,axes[i]),z=rp[2],bpx=cx+rp[0]*r*.48,bpy=cy+rp[1]*r*.48,ps=r*(.42+z*.1),light=(z+1)*.5;var col=hexRgb(this.pal[i]);var lr=Math.round(col.r*(.45+light*.6)),lg=Math.round(col.g*(.45+light*.6)),lb=Math.round(col.b*(.45+light*.6));ctx.save();ctx.translate(bpx,bpy);ctx.rotate(Math.atan2(rp[1],rp[0])+Math.PI/2);ctx.beginPath();ctx.moveTo(0,0);ctx.bezierCurveTo(ps*.42,-ps*.13,ps*.78,ps*.09,ps*.82,ps*.43);ctx.bezierCurveTo(ps*.82,ps*.68,ps*.52,ps*.70,ps*.28,ps*.52);ctx.bezierCurveTo(ps*.09,ps*.38,ps*.04,ps*.14,0,0);ctx.fillStyle='rgb('+lr+','+lg+','+lb+')';ctx.globalAlpha=.93;ctx.fill();ctx.strokeStyle='rgba(255,255,255,'+(.12+light*.18)+')';ctx.lineWidth=.8;ctx.stroke();ctx.restore();}
ctx.beginPath();ctx.arc(cx,cy,r*.12,0,Math.PI*2);ctx.fillStyle='rgba(255,255,255,.8)';ctx.globalAlpha=1;ctx.fill();ctx.restore();
var spec=ctx.createRadialGradient(cx-r*.35,cy-r*.4,0,cx-r*.18,cy-r*.18,r*.6);spec.addColorStop(0,'rgba(255,255,255,.7)');spec.addColorStop(.4,'rgba(255,255,255,.1)');spec.addColorStop(1,'rgba(255,255,255,0)');ctx.beginPath();ctx.arc(cx,cy,r,0,Math.PI*2);ctx.fillStyle=spec;ctx.fill();
var ed=ctx.createRadialGradient(cx,cy,r*.65,cx,cy,r);ed.addColorStop(0,'rgba(0,0,0,0)');ed.addColorStop(1,'rgba(0,0,0,.35)');ctx.beginPath();ctx.arc(cx,cy,r,0,Math.PI*2);ctx.fillStyle=ed;ctx.fill();
};

var kickAnim=0,aiKickAnim=0;
function drawLego(x,y,kick,isAI){
var s=LS(),kit=getKit(isAI?sel[1]:sel[0]);var sh=kit[0],sh2=kit[1],pt=kit[2];
var app=getApp(isAI?sel[1]:sel[0]);var skin=app.skin,hc=app.hair,ht=app.htype;
var sb=s,sc=s;
ctx.save();ctx.translate(x,y);if(isAI)ctx.scale(-1,1);
ctx.beginPath();ctx.ellipse(0,sb*1.05,sb*.45,sb*.1,0,0,Math.PI*2);ctx.fillStyle='rgba(0,0,0,.25)';ctx.fill();
ctx.save();ctx.translate(-sb*.18,sb*.45);ctx.fillStyle=pt;ctx.fillRect(-sb*.12,0,sb*.24,sb*.28);ctx.fillStyle=skin;ctx.fillRect(-sb*.12,sb*.28,sb*.24,sb*.14);ctx.fillStyle='#111';ctx.beginPath();ctx.ellipse(-sb*.04,sb*.44,sb*.18,sb*.09,0,0,Math.PI*2);ctx.fill();ctx.restore();
ctx.save();ctx.translate(sb*.18,sb*.42);if(kick){var kf=kickAnim/6;ctx.rotate(-kf*1.1);ctx.fillStyle=pt;ctx.fillRect(-sb*.12,0,sb*.24,sb*.22);ctx.save();ctx.translate(0,sb*.22);ctx.rotate(kf*.9);ctx.fillStyle=skin;ctx.fillRect(-sb*.11,0,sb*.22,sb*.12);ctx.fillStyle='#ffcc00';ctx.beginPath();ctx.ellipse(sb*.08,sb*.23,sb*.18,sb*.09,-.3,0,Math.PI*2);ctx.fill();ctx.restore();}else{ctx.fillStyle=pt;ctx.fillRect(-sb*.12,0,sb*.24,sb*.28);ctx.fillStyle=skin;ctx.fillRect(-sb*.12,sb*.28,sb*.24,sb*.14);ctx.fillStyle='#111';ctx.beginPath();ctx.ellipse(sb*.04,sb*.44,sb*.18,sb*.09,0,0,Math.PI*2);ctx.fill();}ctx.restore();
ctx.fillStyle=sh;ctx.beginPath();ctx.roundRect(-sb*.3,-sb*.05,sb*.6,sb*.52,sb*.06);ctx.fill();ctx.strokeStyle=sh2;ctx.lineWidth=sb*.04;ctx.beginPath();ctx.moveTo(-sb*.3,sb*.18);ctx.lineTo(sb*.3,sb*.18);ctx.stroke();ctx.fillStyle=sh2;ctx.font='bold '+Math.round(sb*.18)+'px Arial';ctx.textAlign='center';ctx.fillText('10',0,sb*.13);
ctx.save();ctx.translate(-sb*.3,sb*.02);ctx.rotate(kick?-.5:.2);ctx.fillStyle=sh;ctx.fillRect(-sb*.1,0,sb*.2,sb*.32);ctx.fillStyle=skin;ctx.beginPath();ctx.arc(0,sb*.34,sb*.1,0,Math.PI*2);ctx.fill();ctx.restore();
ctx.save();ctx.translate(sb*.3,sb*.02);ctx.rotate(kick?.7:-.2);ctx.fillStyle=sh;ctx.fillRect(-sb*.1,0,sb*.2,sb*.32);ctx.fillStyle=skin;ctx.beginPath();ctx.arc(0,sb*.34,sb*.1,0,Math.PI*2);ctx.fill();ctx.restore();
ctx.fillStyle=skin;ctx.fillRect(-sc*.1,-sc*.18,sc*.2,sc*.14);
ctx.fillStyle=skin;ctx.beginPath();ctx.roundRect(-sc*.28,-sc*.58,sc*.56,sc*.42,sc*.07);ctx.fill();ctx.strokeStyle='rgba(0,0,0,.1)';ctx.lineWidth=sc*.02;ctx.stroke();
ctx.fillStyle='#222';ctx.beginPath();ctx.ellipse(-sc*.1,-sc*.42,sc*.06,sc*.06,0,0,Math.PI*2);ctx.fill();ctx.beginPath();ctx.ellipse(sc*.1,-sc*.42,sc*.06,sc*.06,0,0,Math.PI*2);ctx.fill();
ctx.fillStyle='#fff';ctx.beginPath();ctx.arc(-sc*.08,-sc*.44,sc*.022,0,Math.PI*2);ctx.fill();ctx.beginPath();ctx.arc(sc*.12,-sc*.44,sc*.022,0,Math.PI*2);ctx.fill();
ctx.strokeStyle='rgba(0,0,0,.3)';ctx.lineWidth=sc*.03;ctx.lineCap='round';ctx.beginPath();ctx.arc(0,-sc*.32,sc*.1,.2,Math.PI-.2);ctx.stroke();
ctx.fillStyle=hc;
if(ht==='straight'){ctx.beginPath();ctx.roundRect(-sc*.28,-sc*.62,sc*.56,sc*.22,sc*.07);ctx.fill();ctx.beginPath();ctx.roundRect(-sc*.3,-sc*.58,sc*.08,sc*.18,sc*.03);ctx.fill();ctx.beginPath();ctx.roundRect(sc*.22,-sc*.58,sc*.08,sc*.18,sc*.03);ctx.fill();}
else if(ht==='curly'){ctx.beginPath();ctx.arc(0,-sc*.52,sc*.3,Math.PI,0);ctx.fill();ctx.beginPath();ctx.arc(-sc*.22,-sc*.44,sc*.12,0,Math.PI*2);ctx.fill();ctx.beginPath();ctx.arc(sc*.22,-sc*.44,sc*.12,0,Math.PI*2);ctx.fill();}
else{ctx.beginPath();ctx.roundRect(-sc*.28,-sc*.62,sc*.56,sc*.18,sc*.07);ctx.fill();ctx.beginPath();ctx.roundRect(-sc*.3,-sc*.56,sc*.06,sc*.12,sc*.02);ctx.fill();ctx.beginPath();ctx.roundRect(sc*.24,-sc*.56,sc*.06,sc*.12,sc*.02);ctx.fill();}
ctx.restore();
}

function pOrigin(pl,ay){var s=LS(),cx=pl===0?PITCH_L():PITCH_R(),cy=playerY(ay);return{x:pl===0?cx+s*.26:cx-s*.26,y:cy+s*1.05};}
function Pulse(pl,ay,str){this.p=pl;this.str=str;this.age=0;this.life=.4;var o=pOrigin(pl,ay);this.ox=o.x;this.oy=o.y;}
Pulse.prototype.update=function(dt){this.age+=dt;return this.age<this.life;};
Pulse.prototype.apply=function(ball){
if(ball.scored)return;var dx=ball.x-this.ox,dy=ball.y-this.oy,dist=Math.hypot(dx,dy);if(dist<1)return;
var dir=this.p===0?0:Math.PI,ad=Math.abs(Math.atan2(dy,dx)-dir);if(ad>Math.PI)ad=Math.PI*2-ad;
var cone=(this.p===0?tm[0].cone:tm[1].cone)*(ball.vx*(this.p===0?-1:1)>0?.52:.26);
var maxD=PITCH_W()*.72;
var oZ=PITCH_W()*.28,inOZ=this.p===1?ball.x<PITCH_L()+oZ:ball.x>PITCH_R()-oZ;
if(inOZ){var tBDY=ball.y-this.oy,aDY=(this.p===1?aiAimY:aimY)*PITCH_H()+PITCH_T()-this.oy;if((aDY*tBDY>=0)&&(Math.abs(tBDY)<PITCH_H()*.25)){var nudge=.02*(this.p===1?tm[1].power:tm[0].power);ball.vx+=(this.p===1?-nudge:nudge);var spd=Math.hypot(ball.vx,ball.vy);if(spd>.01)ball.vy+=(ball.vy/spd)*nudge*.5;}}
if(ad>cone)return;if(dist>maxD)return;
var f=Math.exp(-2.5*(ad/cone)*(ad/cone))*Math.pow(1-dist/maxD,1.4)*(1-this.age/this.life)*this.str*1.05*(this.p===0?tm[0].power:tm[1].power);
ball.vx+=dx/dist*f;ball.vy+=dy/dist*f;
if(f>1.8){ball.powerHit=Math.min(f*.4,2.2);ball.powerTrail=[];}
var sp=Math.hypot(ball.vx,ball.vy),mS=ball.powerHit>0?22:9;if(sp>mS){ball.vx=ball.vx/sp*mS;ball.vy=ball.vy/sp*mS;}
};
Pulse.prototype.draw=function(){var t=1-this.age/this.life,r=PITCH_W()*.52*(this.age/this.life),cone=.26,dir=this.p===0?0:Math.PI;var col=this.p===0?'91,200,255':'255,107,107';ctx.save();ctx.translate(this.ox,this.oy);ctx.rotate(dir);var g=ctx.createRadialGradient(0,0,0,0,0,r);g.addColorStop(0,'rgba('+col+','+(.32*t)+')');g.addColorStop(.3,'rgba('+col+','+(.18*t)+')');g.addColorStop(1,'rgba('+col+',0)');ctx.beginPath();ctx.moveTo(0,0);ctx.arc(0,0,r,-cone,cone);ctx.closePath();ctx.fillStyle=g;ctx.fill();ctx.beginPath();ctx.moveTo(0,0);ctx.lineTo(r*.9,0);ctx.strokeStyle=this.str>2.5?'rgba(255,220,0,'+(.9*t)+')':'rgba('+col+','+(.55*t)+')';ctx.lineWidth=this.str>2.5?3:2;ctx.stroke();ctx.restore();};

function collide(){for(var p=0;p<3;p++)for(var i=0;i<balls.length;i++)for(var j=i+1;j<balls.length;j++){var a=balls[i],b=balls[j];if(a.scored||b.scored)continue;var dx=b.x-a.x,dy=b.y-a.y,dist=Math.hypot(dx,dy),minD=a.r+b.r+.5;if(dist>=minD||dist<.001)continue;var nx=dx/dist,ny=dy/dist,push=(minD-dist)*.55;a.x-=nx*push;a.y-=ny*push;b.x+=nx*push;b.y+=ny*push;var dvn=(b.vx-a.vx)*nx+(b.vy-a.vy)*ny;if(dvn>=0)continue;var imp=(1+.65)*dvn*.5;a.vx+=imp*nx;a.vy+=imp*ny;b.vx-=imp*nx;b.vy-=imp*ny;[a,b].forEach(function(rr){var sp=Math.hypot(rr.vx,rr.vy);if(sp>7){rr.vx=rr.vx/sp*7;rr.vy=rr.vy/sp*7;}});}}

var aiTimer=0,aiShootT=0,aiAimY=.5,aiAimTarget=.5;
var AI_CFG=[{accuracy:.55,rate:.9},{accuracy:.72,rate:1.4},{accuracy:.88,rate:2.0}];
function updateAI(dt){var cfg=AI_CFG[aiDiff];aiShootT+=dt;var alive=balls.filter(function(b){return !b.scored;});if(!alive.length)return;var target=alive.reduce(function(a,b){return(PITCH_R()-a.x)<(PITCH_R()-b.x)?a:b;});aiTimer+=dt;if(aiTimer>.18+(1-cfg.accuracy)*.35+Math.random()*.12){aiTimer=0;aiAimTarget=Math.max(.06,Math.min(.94,(target.y+(1-cfg.accuracy)*(Math.random()-.5)*H()*.35)/H()));}var diff=aiAimTarget-aiAimY;aiAimY+=Math.sign(diff)*Math.min(Math.abs(diff),(.55+aiDiff*.15)*dt);var urgency=1+(1-(PITCH_R()-target.x)/PITCH_R())*.8;if(aiShootT>(1/cfg.rate)*(.6+Math.random()*.8)/urgency){aiShootT=0;aiKickAnim=6;pulses.push(new Pulse(1,aiAimY,.8+Math.random()*1.2));}}

function drawArena(){
var pL=PITCH_L(),pR=PITCH_R(),pT=PITCH_T(),pB=PITCH_B();
var fw=PITCH_W(),fh=PITCH_H(),cx=PITCH_CX(),cy=PITCH_CY();
var gT=GT(),gB=GB(),gd=GD();
ctx.fillStyle='#040810';ctx.fillRect(0,0,W(),H());
drawTribunes();drawAdBoards();
var arena=ARENA_CFG[activeArena];
var sw=fw/12;for(var i=0;i<12;i++){ctx.fillStyle=i%2===0?arena.pitchStripe[0]:arena.pitchStripe[1];ctx.fillRect(pL+i*sw,pT,sw,fh);}
var lc='rgba(255,255,255,.55)';ctx.strokeStyle=lc;ctx.lineWidth=1.8;
ctx.strokeRect(pL,pT,fw,fh);
ctx.beginPath();ctx.moveTo(cx,pT);ctx.lineTo(cx,pB);ctx.stroke();
var cr=Math.min(fw,fh)*.1;ctx.beginPath();ctx.arc(cx,cy,cr,0,Math.PI*2);ctx.stroke();
ctx.fillStyle=lc;ctx.globalAlpha=.7;ctx.beginPath();ctx.arc(cx,cy,3,0,Math.PI*2);ctx.fill();ctx.globalAlpha=1;
var paW=fw*.157,paH=fh*.593;ctx.strokeRect(pL,cy-paH/2,paW,paH);ctx.strokeRect(pR-paW,cy-paH/2,paW,paH);
var gaW=fw*.052,gaH=fh*.269;ctx.strokeRect(pL,cy-gaH/2,gaW,gaH);ctx.strokeRect(pR-gaW,cy-gaH/2,gaW,gaH);
var penX=fw*.11;ctx.fillStyle=lc;ctx.globalAlpha=.7;ctx.beginPath();ctx.arc(pL+penX,cy,3,0,Math.PI*2);ctx.fill();ctx.beginPath();ctx.arc(pR-penX,cy,3,0,Math.PI*2);ctx.fill();ctx.globalAlpha=1;
var penR=fw*.097,paDist=paW-penX,arcA=Math.acos(Math.min(1,paDist/penR));
ctx.strokeStyle=lc;ctx.lineWidth=1.8;ctx.beginPath();ctx.arc(pL+penX,cy,penR,-arcA,arcA);ctx.stroke();ctx.beginPath();ctx.arc(pR-penX,cy,penR,Math.PI-arcA,Math.PI+arcA);ctx.stroke();
var cR=fw*.022;[[pL,pT],[pR,pT],[pL,pB],[pR,pB]].forEach(function(p,idx){var sA=[0,Math.PI/2,-Math.PI/2,Math.PI][idx];ctx.beginPath();ctx.arc(p[0],p[1],cR,sA,sA+Math.PI/2);ctx.stroke();});
[true,false].forEach(function(left){var col=left?'91,200,255':'255,107,107',gx=left?pL-gd:pR;ctx.globalAlpha=.18;ctx.strokeStyle='rgb('+col+')';ctx.lineWidth=.8;for(var gy=gT;gy<gB;gy+=10){ctx.beginPath();ctx.moveTo(gx,gy);ctx.lineTo(gx+gd,gy);ctx.stroke();}for(var gx2=0;gx2<=gd;gx2+=10){ctx.beginPath();ctx.moveTo(gx+gx2,gT);ctx.lineTo(gx+gx2,gB);ctx.stroke();}ctx.globalAlpha=1;ctx.strokeStyle='rgba('+col+',.85)';ctx.lineWidth=2.5;ctx.beginPath();if(left){ctx.moveTo(pL,gT);ctx.lineTo(pL-gd,gT);ctx.lineTo(pL-gd,gB);ctx.lineTo(pL,gB);}else{ctx.moveTo(pR,gT);ctx.lineTo(pR+gd,gT);ctx.lineTo(pR+gd,gB);ctx.lineTo(pR,gB);}ctx.stroke();[[left?pL:pR,gT],[left?pL:pR,gB]].forEach(function(p){ctx.beginPath();ctx.arc(p[0],p[1],5,0,Math.PI*2);ctx.fillStyle='rgba('+col+',.9)';ctx.fill();});var ti=left?sel[0]:sel[1];if(ti!==null){ctx.font=gd*1.2+'px serif';ctx.textAlign='center';ctx.globalAlpha=.15;ctx.fillText(TEAMS[ti].f,left?pL-gd/2:pR+gd/2,cy+gd*.4);ctx.globalAlpha=1;}});
if(gState==='playing'||gState==='countdown'||gState==='paused'){drawLego(pL,playerY(aimY),kickAnim>0,false);drawLego(pR,playerY(aiAimY),aiKickAnim>0,true);}
if(gState==='playing'||gState==='countdown'||gState==='paused'||gState==='end'){drawCanvasScore();}
}

var hudScoreData=[{score:0,name:'YOU',flag:'🌍',color:'#5bc8ff'},{score:0,name:'CPU',flag:'🌍',color:'#ff6b6b'}];
function drawCanvasScore(){
var pL=PITCH_L(),pR=PITCH_R(),pT=PITCH_T(),pB=PITCH_B();
var zoneW=CTRL_W();
var gap=5;
var cardW=Math.min(zoneW*0.88,90);
var fullH=pB-pT-gap*2;

/* ── single tall card per side spanning full pitch height ── */
[0,1].forEach(function(p){
var cx=p===0?zoneW/2:pR+zoneW/2;
var col=hudScoreData[p].color;
var t=pT+gap, cH=fullH;
var tIdx=p===0?sel[0]:sel[1];

/* card background */
ctx.save();ctx.shadowColor=col;ctx.shadowBlur=14;
ctx.fillStyle='rgba(0,0,0,0.72)';ctx.beginPath();ctx.roundRect(cx-cardW/2,t,cardW,cH,9);ctx.fill();ctx.restore();
ctx.strokeStyle=col;ctx.lineWidth=1;ctx.globalAlpha=0.28;ctx.beginPath();ctx.roundRect(cx-cardW/2,t,cardW,cH,9);ctx.stroke();ctx.globalAlpha=1;
/* top accent */
ctx.fillStyle=col;ctx.globalAlpha=0.85;ctx.beginPath();ctx.roundRect(cx-cardW/2,t,cardW,4,9);ctx.fill();ctx.globalAlpha=1;

/* ── section heights ── */
var secName=cH*0.13;   /* name row */
var secTimer=cH*0.12;  /* timer row */
var secScore=cH*0.25;  /* score number */
var secFlag=cH*0.32;   /* flag */
var secInfo=cH-secName-secTimer-secScore-secFlag; /* country+rating */

var y=t+4; /* start just after accent bar */

/* NAME */
ctx.textAlign='center';
var nameSz=Math.max(7,Math.round(secName*0.58));
ctx.font='bold '+nameSz+'px Arial';ctx.fillStyle='rgba(255,255,255,0.75)';
var nm=hudScoreData[p].name;if(nm.length>8)nm=nm.slice(0,8);
ctx.fillText(nm.toUpperCase(),cx,y+secName*0.78);
y+=secName;

/* TIMER (only player 0 shows clock; player 1 shows mirror label) */
var timerSz=Math.max(6,Math.round(secTimer*0.55));
if(p===0){
ctx.font='900 '+Math.round(secTimer*0.72)+'px Arial';
ctx.fillStyle='rgba(255,255,255,0.92)';ctx.shadowColor='rgba(255,255,255,0.3)';ctx.shadowBlur=6;
ctx.fillText(document.getElementById('hudtimer').textContent,cx,y+secTimer*0.78);ctx.shadowBlur=0;
ctx.font=Math.round(timerSz*0.75)+'px Arial';ctx.fillStyle='rgba(255,204,0,0.6)';
ctx.fillText('TIME',cx,y+secTimer*0.94);
}else{
ctx.font='bold '+timerSz+'px Arial';ctx.fillStyle='rgba(255,255,255,0.25)';
ctx.fillText('CPU',cx,y+secTimer*0.72);
}
y+=secTimer;

/* SCORE */
var scoreSz=Math.round(secScore*0.72);
ctx.font='900 '+scoreSz+'px Arial';ctx.fillStyle=col;ctx.shadowColor=col;ctx.shadowBlur=12;
ctx.fillText(hudScoreData[p].score,cx,y+secScore*0.82);ctx.shadowBlur=0;
y+=secScore;

/* FLAG */
var flagSz=Math.round(secFlag*0.88);
ctx.font=flagSz+'px serif';ctx.globalAlpha=0.85;
ctx.fillText(hudScoreData[p].flag,cx,y+secFlag*0.76);ctx.globalAlpha=1;
y+=secFlag;

/* gradient fade over flag→info boundary */
var grd=ctx.createLinearGradient(0,y-secFlag*0.4,0,y+secInfo*0.2);
grd.addColorStop(0,'rgba(0,0,0,0)');grd.addColorStop(1,'rgba(0,0,0,0.9)');
ctx.fillStyle=grd;ctx.beginPath();ctx.roundRect(cx-cardW/2,y-secFlag*0.4,cardW,secFlag*0.4+secInfo*0.2,4);ctx.fill();

/* COUNTRY NAME */
var countrySz=Math.max(8,Math.round(secInfo*0.34));
ctx.font='bold '+countrySz+'px Arial';ctx.fillStyle='rgba(255,255,255,0.9)';
var cname=tIdx!==null?TEAMS[tIdx].n:'—';if(cname.length>10)cname=cname.slice(0,10);
ctx.fillText(cname.toUpperCase(),cx,y+secInfo*0.42);

/* RATING */
if(tIdx!==null){
var rat=tMult(tIdx);
var ratSz=Math.max(7,Math.round(secInfo*0.28));
ctx.font='bold '+ratSz+'px Arial';ctx.fillStyle=rat.color;
ctx.fillText(rat.label+' '+rat.rating,cx,y+secInfo*0.74);
}

/* bottom accent */
ctx.fillStyle=col;ctx.globalAlpha=0.85;ctx.beginPath();ctx.roundRect(cx-cardW/2,t+cH-4,cardW,4,9);ctx.fill();ctx.globalAlpha=1;
});
}

var roundsPlayed=0;
var gState='menu',score=[0,0],timeLeft=60,timeFrozen=false,lastTs=0;
var balls=[],pulses=[],ringsActive=false,aimY=.5,goalTO=null;
var pNames=['YOU','CPU'],setSize=2,isHolding=false,holdStartTime=0,overlayTO=null;
var phase='main',phasebusy=false;

function resetPhase(){phase='main';phasebusy=false;timeFrozen=false;}
function onSetDone(){
if(phasebusy)return;phasebusy=true;
var eq=score[0]===score[1],col=score[0]>score[1]?'#5bc8ff':'#ff6b6b';
var sweep=(score[0]===0||score[1]===0)&&!eq;
if(phase==='sudden'){endGame();return;}
if(phase==='tiebreaker'){if(eq)doSudden();else endGame();return;}
if(phase==='extra2'){if(eq)doSudden();else endGame();return;}
if(phase==='extra1'){
if(eq)doTieBreaker();
else if(sweep){phase='extra2';timeLeft=60;doOverlay('CONSOLATION GOAL OR WORLD HUMILIATION',col,'final set — '+setSize+' balls',setSize);}
else endGame();return;
}
if(eq)doTieBreaker();
else if(sweep){phase='extra1';timeLeft=60;doOverlay('REMONTADA OR HUMILIATION',col,'extra set — '+setSize+' balls',setSize);}
else endGame();
}
function doTieBreaker(){phase='tiebreaker';timeFrozen=false;timeLeft=60;doOverlay('TIE BREAKER','#ff9500','60s · draw → sudden death',setSize);}
function doSudden(){phase='sudden';timeFrozen=true;doOverlay('⚡ SUDDEN DEATH','#ffd700','first goal wins',1);}
function doOverlay(msg,col,sub,n){
gState='paused';
var ov=document.getElementById('set-overlay'),cdEl=document.getElementById('set-cd');
document.getElementById('set-msg').textContent=msg;document.getElementById('set-msg').style.color=col;
document.getElementById('set-sub').textContent=sub;cdEl.textContent='3';ov.classList.add('show');
var c=3;function tick(){c--;if(c>0){cdEl.textContent=c;overlayTO=setTimeout(tick,1000);}else{ov.classList.remove('show');spawnBalls(n);ringsActive=true;phasebusy=false;gState='playing';}}
overlayTO=setTimeout(tick,1000);
}
function onTimeUp(){if(score[0]===score[1]){if(phase==='main'||phase==='extra1')doTieBreaker();else if(phase==='extra2')doSudden();}else endGame();}
function spawnBalls(n){balls=[];var cx=PITCH_CX(),cy=PITCH_CY(),sp=RR()*2.2;for(var i=0;i<n;i++){var a=n>1?(i/n)*Math.PI*2:0;balls.push(new Ball(cx+Math.cos(a)*sp*(n>1?1:0),cy+Math.sin(a)*sp*(n>1?1:0),i));}}
function calcSetSize(){var r1=sel[0]!==null?TEAMS[sel[0]].r:70,r2=sel[1]!==null?TEAMS[sel[1]].r:70,d=Math.abs(r1-r2);return d>40?4:d>20?3:2;}

function loop(ts){
requestAnimationFrame(loop);var dt=Math.min((ts-lastTs)/1000,.05);lastTs=ts;
ctx.clearRect(0,0,W(),H());drawArena();
if(gState==='countdown'||gState==='paused'){balls.forEach(function(b){b.update(0);b.draw();});}
if(gState==='playing'){
if((phase==='main'||phase==='extra1'||phase==='extra2'||phase==='tiebreaker')&&!timeFrozen){timeLeft-=dt;if(timeLeft<=0){timeLeft=0;onTimeUp();}updateTimer();}
if(phase==='sudden'&&timeFrozen){timeLeft-=dt;if(timeLeft<=0){timeLeft=0;endGame();}updateTimer();}
if(kickAnim>0)kickAnim=Math.max(0,kickAnim-dt*18);
if(aiKickAnim>0)aiKickAnim=Math.max(0,aiKickAnim-dt*18);
updateAdSlide();updateAI(dt);
pulses=pulses.filter(function(p){return p.update(dt);});
pulses.forEach(function(p){balls.forEach(function(b){p.apply(b);});p.draw();});
balls.forEach(function(b){b.update(dt);});collide();
balls.forEach(function(b){b.draw();});
var alive=balls.filter(function(b){return !b.scored;}).length;
/* game title below centre circle, clear of the flag */
var ccY=PITCH_CY()+Math.min(PITCH_W(),PITCH_H())*0.1+Math.min(PITCH_W(),PITCH_H())*0.115;
ctx.fillStyle='rgba(255,204,0,0.28)';ctx.font='bold '+Math.round(Math.min(W(),H())*0.018)+'px Arial';ctx.textAlign='center';
ctx.fillText('WORLD CUP ORACLE \'26',W()/2,ccY);
ctx.fillStyle='rgba(255,255,255,.10)';ctx.font=Math.min(W(),H())*.011+'px Arial';
ctx.fillText(alive+' ball'+(alive!==1?'s':'')+' · '+phase,W()/2,ccY+Math.min(W(),H())*0.022);
if(alive===0)onSetDone();
}
}

var joyActive=false,joyTouchId=null,joyBaseY=0,joyMouseActive=false;
var joyZone=document.getElementById('joyzone'),joystick=document.getElementById('joystick');
function getJoyBaseY(){var r=document.getElementById('joybase').getBoundingClientRect();return r.top+r.height/2;}
function setJoyKnob(off){var c=Math.max(-32,Math.min(32,off));joystick.style.transform='translate(-50%,calc(-50% + '+c+'px))';aimY=Math.max(0,Math.min(1,(c/32+.5)));}
joyZone.addEventListener('touchstart',function(e){e.preventDefault();if(gState!=='playing')return;var t=e.changedTouches[0];joyActive=true;joyTouchId=t.identifier;joyBaseY=getJoyBaseY();setJoyKnob(t.clientY-joyBaseY);},{passive:false});
joyZone.addEventListener('touchmove',function(e){e.preventDefault();if(!joyActive)return;for(var i=0;i<e.changedTouches.length;i++){if(e.changedTouches[i].identifier===joyTouchId){setJoyKnob(e.changedTouches[i].clientY-joyBaseY);break;}}},{passive:false});
joyZone.addEventListener('touchend',function(e){e.preventDefault();joyActive=false;joyTouchId=null;joystick.style.transform='translate(-50%,-50%)';},{passive:false});
joyZone.addEventListener('mousedown',function(e){if(gState!=='playing')return;joyMouseActive=true;joyBaseY=getJoyBaseY();setJoyKnob(e.clientY-joyBaseY);});
document.addEventListener('mousemove',function(e){if(joyMouseActive)setJoyKnob(e.clientY-joyBaseY);});
document.addEventListener('mouseup',function(){joyMouseActive=false;joystick.style.transform='translate(-50%,-50%)';});

var shootBtn=document.getElementById('shootbtn');
function fireShotPress(){if(gState!=='playing')return;isHolding=true;holdStartTime=Date.now();kickAnim=6;shootBtn.classList.add('firing');pulses.push(new Pulse(0,aimY,1.0));}
function fireShotRelease(){
if(!isHolding||gState!=='playing'){isHolding=false;return;}
var held=(Date.now()-holdStartTime)/1000;
isHolding=false;shootBtn.classList.remove('firing');if(held<.1)return;
kickAnim=6;var po=pOrigin(0,aimY);
if(held>=3){
var alive=balls.filter(function(b){return !b.scored;}),bonus=alive.length<=1?2.6:1,str=10*tm[0].power*bonus;
var inC=[];balls.forEach(function(b){if(b.scored)return;var dx=b.x-po.x,dy=b.y-po.y,d=Math.hypot(dx,dy);if(d<1)return;var ad=Math.abs(Math.atan2(dy,dx));if(ad>Math.PI)ad=Math.PI*2-ad;if(ad<=.14)inC.push({b:b,dist:d});});
inC.sort(function(a,b){return a.dist-b.dist;});
inC.slice(0,2).forEach(function(t){var dx=t.b.x-po.x,dy=t.b.y-po.y,d=t.dist,nx=dx/d,ny=dy/d,dot=nx;t.b.vx+=(dot*str)+((nx-dot)*str*.65);t.b.vy+=(ny*str*.65);t.b.powerHit=2.5;t.b.powerTrail=[];t.b.meteor=2.5;var sp=Math.hypot(t.b.vx,t.b.vy);if(sp>28){t.b.vx=t.b.vx/sp*28;t.b.vy=t.b.vy/sp*28;}});
pulses.push(new Pulse(0,aimY,str));
}else if(held>=2){
var ps=2.0*tm[0].power,inP=[];balls.forEach(function(b){if(b.scored)return;var dx=b.x-po.x,dy=b.y-po.y,d=Math.hypot(dx,dy);if(d<1)return;var ad=Math.abs(Math.atan2(dy,dx));if(ad>Math.PI)ad=Math.PI*2-ad;if(ad<=.52)inP.push({b:b,dist:d});});
inP.sort(function(a,b){return a.dist-b.dist;});
if(inP.length>0){var pr=inP[0],dx2=pr.b.x-po.x,dy2=pr.b.y-po.y,d2=pr.dist;pr.b.vx+=dx2/d2*ps;pr.b.vy+=dy2/d2*ps;pr.b.powerHit=1.2;pr.b.powerTrail=[];var sp2=Math.hypot(pr.b.vx,pr.b.vy);if(sp2>16){pr.b.vx=pr.b.vx/sp2*16;pr.b.vy=pr.b.vy/sp2*16;}}
inP.slice(1).forEach(function(t){var a2=Math.random()*Math.PI*2,w=ps*.1;t.b.vx+=Math.cos(a2)*w;t.b.vy+=Math.sin(a2)*w;var sp3=Math.hypot(t.b.vx,t.b.vy);if(sp3>4){t.b.vx=t.b.vx/sp3*4;t.b.vy=t.b.vy/sp3*4;}});
pulses.push(new Pulse(0,aimY,ps));
}else{pulses.push(new Pulse(0,aimY,1.0));}
}
shootBtn.addEventListener('touchstart',function(e){e.preventDefault();e.stopPropagation();fireShotPress();},{passive:false});
shootBtn.addEventListener('touchend',function(e){e.preventDefault();e.stopPropagation();fireShotRelease();},{passive:false});
shootBtn.addEventListener('mousedown',function(e){e.preventDefault();fireShotPress();});
shootBtn.addEventListener('mouseup',function(e){e.preventDefault();fireShotRelease();});

function triggerGoal(p){score[p]++;hudScoreData[p].score=score[p];document.getElementById('hs1').textContent=score[0];document.getElementById('hs2').textContent=score[1];var fl=document.getElementById('gflash'),tx=document.getElementById('gtxt');var col=p===0?'#5bc8ff':'#ff6b6b',ti=sel[p]!==null?TEAMS[sel[p]]:null;fl.style.background='radial-gradient(ellipse,'+col+'22,transparent 65%)';fl.style.opacity='1';tx.style.color=col;tx.style.opacity='1';tx.style.transform='translate(-50%,-50%) scale(1.1)';tx.textContent=ti?ti.f+' GOAL!':'GOAL!';clearTimeout(goalTO);goalTO=setTimeout(function(){fl.style.opacity='0';tx.style.opacity='0';tx.style.transform='translate(-50%,-50%) scale(1)';},1100);}
function updateTimer(){var el=document.getElementById('hudtimer'),elapsed=60-timeLeft;el.textContent=Math.min(90,Math.floor(1+(elapsed/60)*89))+"'";el.style.color=timeLeft<=10?'#ff6b6b':'#fff';}
function showScreen(id){document.getElementById(id).classList.remove('off');}
function hideScreen(id){document.getElementById(id).classList.add('off');}

document.getElementById('btn-play').addEventListener('click',function(){
var n1=document.getElementById('n1').value.trim()||'PLAYER',n2=document.getElementById('n2').value.trim()||'CPU';
pNames=[n1.toUpperCase(),n2.toUpperCase()];
var f1=sel[0]!==null?TEAMS[sel[0]].f:'🌍';
var f2=sel[1]!==null?TEAMS[sel[1]].f:'🌍';
document.getElementById('hf1').textContent=f1;document.getElementById('hf2').textContent=f2;
var m0=tMult(sel[0]),m1=tMult(sel[1]);
document.getElementById('hn1').textContent=pNames[0];document.getElementById('hn2').textContent=pNames[1];
document.getElementById('hr1').textContent=m0.label+' '+m0.rating;document.getElementById('hr1').style.color=m0.color;
document.getElementById('hr2').textContent=m1.label+' '+m1.rating;document.getElementById('hr2').style.color=m1.color;
hudScoreData[0]={score:0,name:pNames[0],flag:f1,color:'#5bc8ff'};
hudScoreData[1]={score:0,name:pNames[1],flag:f2,color:'#ff6b6b'};
hideScreen('s-menu');startCD();
});
document.getElementById('btn-rm').addEventListener('click',function(){hideScreen('s-end');startCD();});
document.getElementById('btn-menu').addEventListener('click',function(){hideScreen('s-end');showScreen('s-menu');gState='menu';});

function startCD(){
tm[0]=tMult(sel[0]);tm[1]=tMult(sel[1]);
if(sel[1]!==null){var r=TEAMS[sel[1]].r;aiDiff=r>=85?2:r>=65?1:0;document.querySelectorAll('.dbtn').forEach(function(b,i){b.classList.toggle('sel',i===aiDiff);});}
var aiArena=Math.floor(Math.random()*3);
activeArena=selectedArena===aiArena?selectedArena:Math.random()<.5?selectedArena:aiArena;
SPONSORS=SPONSORS_BY_ARENA[activeArena];
hideSC();seatCache={};matchStartTime=null;matchDuration=0;
setSize=calcSetSize();score=[0,0];timeLeft=60;timeFrozen=false;resetPhase();
hudScoreData[0].score=0;hudScoreData[1].score=0;
var hm=document.getElementById('humillacion-mundial');if(hm)hm.style.display='none';
document.getElementById('hs1').textContent='0';document.getElementById('hs2').textContent='0';
document.getElementById('hudtimer').textContent="1'";document.getElementById('hudtimer').style.color='#fff';
spawnBalls(setSize);pulses=[];aimY=.5;ringsActive=false;kickAnim=0;aiKickAnim=0;
isHolding=false;holdStartTime=0;aiTimer=0;aiShootT=0;aiAimY=.5;aiAimTarget=.5;
adSO=0;adSliding=false;adLI=0;adRI=0;adPT=AD_PAUSE;
clearTimeout(overlayTO);document.getElementById('set-overlay').classList.remove('show');
gState='countdown';showScreen('s-cd');
var el=document.getElementById('cdnum'),c=3;
function anim(){el.style.animation='none';void el.offsetWidth;el.style.animation='cdp .85s ease-out';}
el.textContent=c;anim();
var iv=setInterval(function(){c--;if(c>0){el.textContent=c;anim();}else{clearInterval(iv);el.textContent='GO!';anim();setTimeout(function(){hideScreen('s-cd');gState='playing';ringsActive=true;if(!matchStartTime)matchStartTime=Date.now();},800);}},1000);
}

var matchStartTime=null,matchDuration=0;
function endGame(){
gState='end';matchDuration=matchStartTime?Math.round((Date.now()-matchStartTime)/1000):0;matchStartTime=null;var s0=score[0],s1=score[1];
roundsPlayed++;
document.getElementById('endscore').textContent=s0+' – '+s1;
var lbl=document.getElementById('endlbl');
document.getElementById('endflags').textContent=(sel[0]!==null?TEAMS[sel[0]].f:'⚽')+'  '+(sel[1]!==null?TEAMS[sel[1]].f:'🤖');
if(s0===s1){lbl.textContent='DRAW';lbl.className='el-draw';}
else if(s0>s1){lbl.textContent=pNames[0]+' WINS! 🏆';lbl.className='el-win';}
else{lbl.textContent=pNames[1]+' WINS!';lbl.className='el-win';}
if(roundsPlayed>=3){var hm=document.getElementById('humillacion-mundial');if(hm)hm.style.display='block';}
showScreen('s-end');
if((s0===0||s1===0)&&phase==='extra2'){var losingSide=s0>s1?0:1;var charType=selectedArena;showSC(losingSide,charType);}
}

var HUMIL_TEXT={0:'WORLD HUMILIATION',1:'HUMILIATION MONDIALE',2:'VERGÜENZA MUNDIAL'};
function generateShareCard(){
var s0=score[0],s1=score[1];
var isHumil=(s0===0||s1===0)&&phase==='extra2';
var p1Name=sel[0]!==null?TEAMS[sel[0]].n:'Team 1';
var p2Name=sel[1]!==null?TEAMS[sel[1]].n:'Team 2';
var p1Flag=sel[0]!==null?TEAMS[sel[0]].f:'🌍';
var p2Flag=sel[1]!==null?TEAMS[sel[1]].f:'🌍';
var m0=tMult(sel[0]),m1=tMult(sel[1]);
var arena=ARENA_CFG[activeArena];
var roundLabel=phase==='main'?'1st Round':phase==='extra1'?'2nd Round':phase==='extra2'?'3rd Round':phase==='sudden'?'Sudden Death':'Tiebreaker';
var arenaSub=(arena.stadiumName||arena.name+' Stadium')+' · '+roundLabel;
var stripCol,glowCol,bannerBg,bannerBorder,bannerShadow,resultText,resultCol,resultSubCol;
if(isHumil){stripCol='linear-gradient(90deg,#5bc8ff,#cc0000,#cc0000)';glowCol='radial-gradient(ellipse at 30% 50%,rgba(91,200,255,.08),transparent 55%),radial-gradient(ellipse at 70% 50%,rgba(206,17,38,.1),transparent 55%)';bannerBg='linear-gradient(135deg,rgba(180,0,20,.8),rgba(100,0,10,.8))';bannerBorder='1px solid rgba(255,50,50,.25)';bannerShadow='0 0 20px rgba(180,0,20,.3)';resultText=HUMIL_TEXT[activeArena]||'WORLD HUMILIATION';resultCol='#fff';resultSubCol='rgba(255,180,180,.6)';}
else if(s0>s1){stripCol='linear-gradient(90deg,#b8860b,#ffd700,#b8860b)';glowCol='radial-gradient(ellipse at 50% 40%,rgba(180,134,11,.1),transparent 60%)';bannerBg='linear-gradient(135deg,rgba(140,100,5,.8),rgba(80,60,0,.8))';bannerBorder='1px solid rgba(255,215,0,.3)';bannerShadow='0 0 20px rgba(180,134,11,.25)';resultText=p1Name.toUpperCase()+' WINS';resultCol='#ffd700';resultSubCol='rgba(255,215,0,.5)';}
else if(s1>s0){stripCol='linear-gradient(90deg,#b8860b,#ffd700,#b8860b)';glowCol='radial-gradient(ellipse at 50% 40%,rgba(180,134,11,.1),transparent 60%)';bannerBg='linear-gradient(135deg,rgba(140,100,5,.8),rgba(80,60,0,.8))';bannerBorder='1px solid rgba(255,215,0,.3)';bannerShadow='0 0 20px rgba(180,134,11,.25)';resultText=p2Name.toUpperCase()+' WINS';resultCol='#ffd700';resultSubCol='rgba(255,215,0,.5)';}
else{stripCol='linear-gradient(90deg,#5bc8ff,#90ee90,#ff6b6b)';glowCol='radial-gradient(ellipse at 50% 40%,rgba(144,238,144,.07),transparent 60%)';bannerBg='rgba(144,238,144,.08)';bannerBorder='1px solid rgba(144,238,144,.2)';bannerShadow='0 0 20px rgba(144,238,144,.1)';resultText='LEGENDARY DRAW';resultCol='#90ee90';resultSubCol='rgba(144,238,144,.5)';}
var endedIn;
if(phase==='main'){endedIn='1ST ROUND';}else if(phase==='extra1'){endedIn='2ND ROUND';}else if(phase==='extra2'&&!(s0===0||s1===0)){endedIn='3RD ROUND';}else if((s0===0||s1===0)&&phase==='extra2'){endedIn='CLEAN SWEEP';}else if(phase==='sudden'){endedIn='SUDDEN DEATH';}else if(phase==='tiebreaker'){endedIn='TIEBREAKER';}else{endedIn='FINAL';}
var dur=matchDuration>0?matchDuration:0;var durMin=Math.floor(dur/60);var durSec=dur%60;var durStr=durMin>0?(durMin+'m '+(durSec<10?'0':'')+durSec+'s'):(durSec+'s');
document.getElementById('sc-oracle-title').innerHTML='Oracle result for <span style="color:rgba(255,204,0,.75);letter-spacing:2px;">'+p1Name+'</span> vs <span style="color:rgba(255,204,0,.75);letter-spacing:2px;">'+p2Name+'</span> match:';
document.getElementById('sc-strip').style.background=stripCol;document.getElementById('sc-glow').style.background=glowCol;
document.getElementById('sc-p1-flag').textContent=p1Flag;document.getElementById('sc-p1-name').textContent=pNames[0].slice(0,8);document.getElementById('sc-p1-rating').textContent=m0.label+' '+m0.rating;document.getElementById('sc-p1-rating').style.cssText+='background:rgba(255,215,0,.12);color:'+m0.color+';border:1px solid rgba(255,215,0,.25);';
document.getElementById('sc-p2-flag').textContent=p2Flag;document.getElementById('sc-p2-name').textContent=pNames[1].slice(0,8);document.getElementById('sc-p2-rating').textContent=m1.label+' '+m1.rating;document.getElementById('sc-p2-rating').style.cssText+='background:rgba(255,215,0,.12);color:'+m1.color+';border:1px solid rgba(255,215,0,.25);';
var p1ScoreCol,p2ScoreCol,p1Shadow,p2Shadow;
if(s0===s1){p1ScoreCol='#90ee90';p1Shadow='rgba(144,238,144,.5)';p2ScoreCol='#90ee90';p2Shadow='rgba(144,238,144,.5)';}
else if(s0>s1){p1ScoreCol='#5bc8ff';p1Shadow='rgba(91,200,255,.5)';p2ScoreCol='rgba(255,107,107,.35)';p2Shadow='transparent';}
else{p1ScoreCol='rgba(91,200,255,.35)';p1Shadow='transparent';p2ScoreCol='#ff6b6b';p2Shadow='rgba(255,107,107,.5)';}
var p1ScoreEl=document.getElementById('sc-score-p1');p1ScoreEl.textContent=s0;p1ScoreEl.style.color=p1ScoreCol;p1ScoreEl.style.textShadow='0 0 30px '+p1Shadow;
var p2ScoreEl=document.getElementById('sc-score-p2');p2ScoreEl.textContent=s1;p2ScoreEl.style.color=p2ScoreCol;p2ScoreEl.style.textShadow='0 0 30px '+p2Shadow;
var banner=document.getElementById('sc-banner');banner.style.background=bannerBg;banner.style.border=bannerBorder;banner.style.boxShadow=bannerShadow;
document.getElementById('sc-banner-main').textContent=resultText;document.getElementById('sc-banner-main').style.color=resultCol;document.getElementById('sc-banner-main').style.textShadow='0 0 20px '+resultCol;
document.getElementById('sc-banner-sub').textContent=arenaSub.toUpperCase();document.getElementById('sc-banner-sub').style.color=resultSubCol;
var metaCol=s0===s1?'#90ee90':s0>s1?'#5bc8ff':'#ff6b6b';
document.getElementById('sc-rounds').style.color=metaCol;document.getElementById('sc-phase').style.color=metaCol;document.getElementById('sc-balls').style.color=metaCol;
document.getElementById('sc-rounds').textContent=endedIn;document.getElementById('sc-phase').textContent=setSize;document.getElementById('sc-phase-lbl').textContent='BALLS / ROUND';document.getElementById('sc-balls').textContent=durStr;
document.getElementById('sc-arena-info').textContent='🏟 '+(arena.stadiumName||arena.name)+' · '+arena.name+' Arena';
}
document.getElementById('btn-share-result').addEventListener('click',function(){generateShareCard();document.getElementById('share-overlay').style.display='flex';});
document.getElementById('btn-close-share').addEventListener('click',function(){document.getElementById('share-overlay').style.display='none';hideScreen('s-end');showScreen('s-menu');gState='menu';});
document.getElementById('btn-rm-share').addEventListener('click',function(){document.getElementById('share-overlay').style.display='none';hideScreen('s-end');startCD();});
document.getElementById('btn-do-share').addEventListener('click',function(){var s0=score[0],s1=score[1];var p1=sel[0]!==null?TEAMS[sel[0]].n:'P1';var p2=sel[1]!==null?TEAMS[sel[1]].n:'P2';var txt=p1+' '+s0+' – '+s1+' '+p2+' · World Cup Oracle';if(navigator.share){try{navigator.share({title:'World Cup Oracle',text:txt});}catch(e){}}});

resize();
requestAnimationFrame(function(ts){lastTs=ts;requestAnimationFrame(loop);});
</script>

</body>
</html>
