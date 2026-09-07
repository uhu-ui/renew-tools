<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ReNew IT – Sichtprüfung: Sortieren</title>
<style>
:root{--blau:#075A7B;--gruen:#6B9F35;--rot:#C0392B}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
body{font-family:Arial,Helvetica,sans-serif;margin:0;background:#0b1d26;color:#e8eef1}
header{background:var(--blau);color:#fff;padding:10px 20px;display:flex;align-items:center;gap:16px}
.logo-kopf{height:40px;width:auto;flex:none}
header h1{margin:0;font-size:19px;flex:1}
main{max-width:1000px;margin:0 auto;padding:14px}
.wrap{background:#0e2530;border:1px solid #1d3947;border-radius:12px;padding:10px;box-shadow:0 10px 40px rgba(0,0,0,.45)}
canvas{display:block;width:100%;height:auto;border-radius:8px}
.bar{display:flex;gap:12px;align-items:stretch;flex-wrap:wrap;margin-top:12px}
button{font:inherit;border-radius:10px;cursor:pointer;border:1px solid #2c5568;background:#123240;color:#dfe9ee;padding:10px 16px}
button:disabled{opacity:.45;cursor:default}
.sort{flex:1;min-width:180px;font-size:19px;font-weight:bold;padding:16px;border-width:2px}
.sort.defekt{border-color:var(--rot);color:#ff9d92}
.sort.defekt:not(:disabled):hover{background:#3a1512}
.sort.ok{border-color:var(--gruen);color:#a5d97a}
.sort.ok:not(:disabled):hover{background:#1c2c10}
.stat{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
.s{background:#123240;border:1px solid #2c5568;border-radius:8px;padding:8px 14px;font-size:14px}
.s b{font-size:16px}
.s.rt b{color:#ff7a6e}.s.gr b{color:#7fd34e}
.s.right{margin-left:auto}
</style>
</head>
<body>
<header>
 <img class="logo-kopf" alt="ReNew IT GmbH" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIgogICAgIHdpZHRoPSIxNjAwIgogICAgIGhlaWdodD0iNjAwIgogICAgIHZpZXdCb3g9IjAgMCAxNjAwIDYwMCIKICAgICByb2xlPSJpbWciCiAgICAgYXJpYS1sYWJlbGxlZGJ5PSJ0aXRsZSBkZXNjIj4KICA8dGl0bGUgaWQ9InRpdGxlIj5SZU5ldyBJVCBHbWJIIExvZ288L3RpdGxlPgogIDxkZXNjIGlkPSJkZXNjIj5QZXRyb2xibGF1ZXMgdW5kIG1vb3NncsO8bmVzIExvZ28gbWl0IEtyZWlzbGF1ZnBmZWlsZW4sIExhcHRvcCB1bmQgTGVpdGVyYmFobmVuLjwvZGVzYz4KCiAgCgogIDwhLS0gS3JlaXNsYXVmc3ltYm9sIC0tPgogIDxwYXRoIGQ9Ik0xNDUgMjgwCiAgICAgICAgICAgQTE3OCAxNzggMCAwIDEgNDMwIDE2MiIKICAgICAgICBmaWxsPSJub25lIgogICAgICAgIHN0cm9rZT0iIzZiOWYzNSIKICAgICAgICBzdHJva2Utd2lkdGg9IjQyIgogICAgICAgIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgogIDxwYXRoIGQ9Ik00MTQgMTExIEw0OTMgMTg0IEwzOTEgMjA1IFoiIGZpbGw9IiM2YjlmMzUiLz4KCiAgPHBhdGggZD0iTTQ2NSAzMTkKICAgICAgICAgICBBMTc4IDE3OCAwIDAgMSAxODAgNDM4IgogICAgICAgIGZpbGw9Im5vbmUiCiAgICAgICAgc3Ryb2tlPSIjZmZmZmZmIgogICAgICAgIHN0cm9rZS13aWR0aD0iNDIiCiAgICAgICAgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIi8+CiAgPHBhdGggZD0iTTE5NyA0ODkgTDExOCA0MTYgTDIyMCAzOTUgWiIgZmlsbD0iI2ZmZmZmZiIvPgoKICA8IS0tIExhcHRvcCAtLT4KICA8cmVjdCB4PSIyMjAiIHk9IjIwNSIgd2lkdGg9IjIwNSIgaGVpZ2h0PSIxNDUiIHJ4PSIxMCIKICAgICAgICBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMjAiLz4KICA8cGF0aCBkPSJNMTk3IDM4MCBINDQ3IEw0NzkgNDE4IFE0ODQgNDI2IDQ3MiA0MjYgSDE3MyBRMTYxIDQyNiAxNjYgNDE4IFoiCiAgICAgICAgZmlsbD0iI2ZmZmZmZiIvPgogIDxwYXRoIGQ9Ik0yODYgNDA1IEgzNTQgTDM2NSA0MTkgSDI3NSBaIiBmaWxsPSJub25lIi8+CgogIDwhLS0gTGVpdGVyYmFobmVuIC0tPgogIDxwYXRoIGQ9Ik0zMTMgMjc5IEgzODYgTDQyNyAyMzYgSDQ5NSIKICAgICAgICBmaWxsPSJub25lIiBzdHJva2U9IiM2YjlmMzUiIHN0cm9rZS13aWR0aD0iMTMiCiAgICAgICAgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+CiAgPHBhdGggZD0iTTM1MCAzMTUgSDQyNiBMNDU5IDI4MSBINTQ4IgogICAgICAgIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzZiOWYzNSIgc3Ryb2tlLXdpZHRoPSIxMyIKICAgICAgICBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiLz4KICA8cGF0aCBkPSJNMzg5IDM1MCBINDU1IEw0ODUgMzI2IEg1MTEiCiAgICAgICAgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjNmI5ZjM1IiBzdHJva2Utd2lkdGg9IjEzIgogICAgICAgIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPgogIDxjaXJjbGUgY3g9IjUxMyIgY3k9IjIzNiIgcj0iMTUiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzZiOWYzNSIgc3Ryb2tlLXdpZHRoPSIxMSIvPgogIDxjaXJjbGUgY3g9IjU2NiIgY3k9IjI4MSIgcj0iMTUiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzZiOWYzNSIgc3Ryb2tlLXdpZHRoPSIxMSIvPgogIDxjaXJjbGUgY3g9IjUyOSIgY3k9IjMyNiIgcj0iMTUiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzZiOWYzNSIgc3Ryb2tlLXdpZHRoPSIxMSIvPgoKICA8IS0tIFdvcnRtYXJrZSAtLT4KICA8ZyBmb250LWZhbWlseT0iJ0RlamFWdSBTYW5zJywgQXJpYWwsIHNhbnMtc2VyaWYiIGZvbnQtd2VpZ2h0PSI3MDAiPgogICAgPHRleHQgeD0iNTg1IiB5PSIzNDUiIGZvbnQtc2l6ZT0iMTc4IiBmaWxsPSIjZmZmZmZmIj5SZTwvdGV4dD4KICAgIDx0ZXh0IHg9Ijc5NSIgeT0iMzQ1IiBmb250LXNpemU9IjE3OCIgZmlsbD0iIzZiOWYzNSI+TmV3PC90ZXh0PgogICAgPHRleHQgeD0iMTI2NSIgeT0iMzQ1IiBmb250LXNpemU9IjE3OCIgZmlsbD0iI2ZmZmZmZiI+SVQ8L3RleHQ+CiAgPC9nPgogIDx0ZXh0IHg9IjEyNjgiIHk9IjQzOCIKICAgICAgICBmb250LWZhbWlseT0iJ0RlamFWdSBTYW5zJywgQXJpYWwsIHNhbnMtc2VyaWYiCiAgICAgICAgZm9udC13ZWlnaHQ9IjQwMCIKICAgICAgICBmb250LXNpemU9IjgwIgogICAgICAgIGxldHRlci1zcGFjaW5nPSIyIgogICAgICAgIGZpbGw9IiNkOGUyZTgiPkdtYkg8L3RleHQ+Cjwvc3ZnPgo=">
 <h1>ReNew IT GmbH – Sichtprüfung: Sortieren</h1>
</header>
<main>
 <div class="wrap">
  <canvas id="c" width="1000" height="480"></canvas>
  <div class="bar">
   <button class="sort defekt" id="bDef" onclick="decide(true)">&#9888; BEFUND &rarr; Kiste links</button>
   <button class="sort ok" id="bOk" onclick="decide(false)">&#10003; KEIN BEFUND &rarr; Kiste rechts</button>
  </div>
  <div class="stat">
   <span class="s">Gerät <b id="nCur">1</b> / 40</span>
   <span class="s rt">Befund <b id="nDef">0</b></span>
   <span class="s gr">ohne Befund <b id="nOk">0</b></span>
   <span class="s right"><button onclick="restart()" style="padding:4px 12px">&#8635; Neue Palette (40 Geräte)</button></span>
  </div>
 </div>
</main>
<script>
"use strict";
var cv = document.getElementById("c"), ctx = cv.getContext("2d");
var W = 1000, H = 480;
var DPR = Math.min(window.devicePixelRatio || 1, 2);
cv.width = W * DPR; cv.height = H * DPR;
ctx.setTransform(DPR, 0, 0, DPR, 0, 0);

var CX = 500, CY = 300;               // Position des Prüfplatzes
var N = 40;
var COLS = [
 ["#9aa6ad","#77838a","#565f65"],
 ["#7a868e","#5c6870","#464f56"],
 ["#b0b9bd","#8d979c","#6e777c"],
 ["#6e7b85","#535e67","#414b53"]
];
var idx, nDef, nOk, dev, state, anim, done, pDef = 0.22;

function rnd(a, b){ return a + Math.random() * (b - a); }
function pick(a){ return a[Math.floor(Math.random() * a.length)]; }

function makeCrack(x0, y0, ang, len, seg){
 var pts = [[x0, y0]], a = ang;
 for (var i = 0; i < seg; i++){
  a += rnd(-0.5, 0.5);
  var l = len / seg * rnd(0.6, 1.4);
  x0 += Math.cos(a) * l; y0 += Math.sin(a) * l;
  pts.push([x0, y0]);
 }
 return pts;
}
function newDevice(){
 var defekt = Math.random() < pDef;
 var art = null;
 if (defekt){
  var rz = Math.random();
  art = rz < 0.30 ? "display" : rz < 0.55 ? "gehaeuse" : rz < 0.70 ? "taste" : rz < 0.82 ? "scharnier" : rz < 0.92 ? "delle" : "ecke";
 }
 var d = {
  col: pick(COLS),
  rot: rnd(-0.03, 0.03),
  scale: rnd(0.94, 1.05),
  serial: "RN-" + Math.floor(rnd(52000, 59999)),
  defekt: defekt, art: art,
  cracks: [], smudges: [], sticker: false,
  missingKeys: [], delle: null, ecke: null, scharnierDefekt: false
 };
 /* Risse erzeugen (in lokalen Bildschirm-/Basis-Koordinaten) */
 if (art === "display"){
  var edge = Math.floor(rnd(0, 4)), sx, sy, a0;
  if (edge === 0){ sx = rnd(-150, 150); sy = -108; a0 = rnd(0.9, 2.2); }
  else if (edge === 1){ sx = 158; sy = rnd(-100, -20); a0 = rnd(2.6, 3.6); }
  else if (edge === 2){ sx = -158; sy = rnd(-100, -20); a0 = rnd(-0.5, 0.5); }
  else { sx = rnd(-150, 150); sy = -16; a0 = rnd(-2.2, -0.9); }
  var haupt = makeCrack(sx, sy, a0, rnd(70, 190), 7);
  d.cracks.push({where:"screen", pts: haupt, w: rnd(1.1, 1.9)});
  var nb = Math.random() < 0.7 ? 1 + (Math.random() < 0.3 ? 1 : 0) : 0;
  for (var b = 0; b < nb; b++){
   var p = haupt[2 + Math.floor(rnd(0, haupt.length - 3))];
   d.cracks.push({where:"screen", pts: makeCrack(p[0], p[1], rnd(0, 6.28), rnd(25, 70), 4), w: rnd(0.7, 1.2)});
  }
 }
 if (art === "gehaeuse"){
  if (Math.random() < 0.5){ /* Riss in der Handballenauflage */
   d.cracks.push({where:"base", pts: makeCrack(rnd(-160, 60), rnd(28, 60), rnd(-0.4, 0.4), rnd(60, 130), 6), w: rnd(1.3, 2)});
  } else {                  /* Riss am Displayrahmen/Deckelrand */
   var oben = Math.random() < 0.5;
   d.cracks.push({where:"bezel", pts: makeCrack(rnd(-140, 140), oben ? -116 : -10, oben ? rnd(1.1, 2.0) : rnd(-2.0, -1.1), rnd(24, 46), 4), w: rnd(1.4, 2.1)});
  }
 }
 if (art === "taste"){
  var nk = 1 + (Math.random() < 0.35 ? 1 : 0);
  for (var mk = 0; mk < nk; mk++){
   d.missingKeys.push({ r: Math.floor(rnd(0, 3)), k: Math.floor(rnd(0, 14)) });
  }
 }
 if (art === "scharnier"){
  d.scharnierDefekt = true;
  d.cracks.push({where:"base", pts: makeCrack(rnd(-40, 40), 4, rnd(1.2, 1.9), rnd(18, 34), 3), w: rnd(1.0, 1.5)});
 }
 if (art === "delle"){
  var seite = Math.random() < 0.5 ? -1 : 1;
  d.delle = { x: seite * rnd(80, 185), y: rnd(30, 64), rx: rnd(16, 30), ry: rnd(9, 16), rot: rnd(-0.5, 0.5) };
 }
 if (art === "ecke"){
  d.ecke = { seite: Math.random() < 0.5 ? -1 : 1, gr: rnd(20, 34) };
 }
 /* Gebrauchsspuren (kein Befund!) */
 var ns = Math.floor(rnd(0, 3));
 for (var s = 0; s < ns; s++){
  d.smudges.push({x: rnd(-120, 120), y: rnd(-95, -25), rx: rnd(14, 34), ry: rnd(8, 18), a: rnd(0.025, 0.05), rot: rnd(0, 3)});
 }
 return d;
}

/* ---------- Zeichnen ---------- */
function bg(){
 var g = ctx.createLinearGradient(0, 0, 0, H);
 g.addColorStop(0, "#0c2836"); g.addColorStop(0.68, "#123a4b"); g.addColorStop(0.69, "#233238"); g.addColorStop(1, "#161f24");
 ctx.fillStyle = g; ctx.fillRect(0, 0, W, H);
 /* Prüftisch */
 var t = ctx.createLinearGradient(0, 330, 0, 470);
 t.addColorStop(0, "#37444c"); t.addColorStop(1, "#242e34");
 ctx.fillStyle = t;
 ctx.beginPath(); ctx.moveTo(120, 336); ctx.lineTo(880, 336); ctx.lineTo(940, 470); ctx.lineTo(60, 470); ctx.closePath(); ctx.fill();
 ctx.fillStyle = "rgba(255,255,255,0.05)"; ctx.fillRect(120, 336, 760, 4);
 /* Lupenleuchte */
 ctx.strokeStyle = "#3e4d56"; ctx.lineWidth = 9; ctx.lineCap = "round";
 ctx.beginPath(); ctx.moveTo(818, 336); ctx.lineTo(790, 210); ctx.lineTo(680, 130); ctx.stroke();
 ctx.fillStyle = "#4a5a64";
 ctx.beginPath(); ctx.ellipse(662, 122, 34, 16, -0.5, 0, 7); ctx.fill();
 ctx.fillStyle = "#e8f4fa";
 ctx.beginPath(); ctx.ellipse(660, 124, 24, 10, -0.5, 0, 7); ctx.fill();
 /* Lichtkegel */
 var lg = ctx.createRadialGradient(CX, CY - 40, 40, CX, CY - 40, 330);
 lg.addColorStop(0, "rgba(225,244,255,0.14)"); lg.addColorStop(1, "rgba(225,244,255,0)");
 ctx.fillStyle = lg;
 ctx.beginPath(); ctx.moveTo(636, 132); ctx.lineTo(CX - 290, 452); ctx.lineTo(CX + 290, 452); ctx.closePath(); ctx.fill();
 /* Kistenmarkierungen links/rechts */
 kiste(78, "#C0392B", "BEFUND", nDef);
 kiste(922, "#6B9F35", "KEIN BEFUND", nOk);
}
function kiste(x, col, label, n){
 ctx.save(); ctx.translate(x, 402);
 ctx.strokeStyle = col; ctx.lineWidth = 3;
 ctx.beginPath(); ctx.moveTo(-52, -34); ctx.lineTo(-52, 30); ctx.lineTo(52, 30); ctx.lineTo(52, -34); ctx.stroke();
 ctx.fillStyle = col.replace(")", ""); ctx.fillStyle = hexA(col, 0.12);
 ctx.fillRect(-50, -10, 100, 38);
 ctx.fillStyle = col; ctx.font = "bold 12px Arial"; ctx.textAlign = "center";
 ctx.fillText(label, 0, 48);
 ctx.fillStyle = "#dfe9ee"; ctx.font = "bold 17px Arial";
 ctx.fillText(n, 0, 14);
 ctx.restore();
}
function hexA(hex, a){
 var r = parseInt(hex.slice(1, 3), 16), g = parseInt(hex.slice(3, 5), 16), b = parseInt(hex.slice(5, 7), 16);
 return "rgba(" + r + "," + g + "," + b + "," + a + ")";
}
function drawDevice(d, x, y, s, rot, alpha){
 ctx.save();
 ctx.globalAlpha = alpha;
 ctx.translate(x, y); ctx.rotate(rot); ctx.scale(s, s);
 /* Schatten */
 ctx.fillStyle = "rgba(0,0,0,0.35)";
 ctx.beginPath(); ctx.ellipse(0, 80, 210, 22, 0, 0, 7); ctx.fill();
 /* Basis mit Tastatur (Trapez) */
 var c = d.col;
 var bg2 = ctx.createLinearGradient(0, 8, 0, 76);
 bg2.addColorStop(0, c[0]); bg2.addColorStop(1, c[2]);
 ctx.fillStyle = bg2;
 ctx.beginPath(); ctx.moveTo(-178, 2); ctx.lineTo(178, 2); ctx.lineTo(206, 74); ctx.lineTo(-206, 74); ctx.closePath(); ctx.fill();
 ctx.fillStyle = "rgba(255,255,255,0.10)"; ctx.fillRect(-178, 2, 356, 3);
 /* Tastenfeld */
 ctx.fillStyle = "rgba(0,0,0,0.28)";
 roundRect(-150, 14, 300, 30, 4); ctx.fill();
 for (var r = 0; r < 3; r++){
  for (var k = 0; k < 14; k++){
   var fehlt = false;
   for (var q = 0; q < d.missingKeys.length; q++){
    if (d.missingKeys[q].r === r && d.missingKeys[q].k === k){ fehlt = true; break; }
   }
   if (fehlt){
    ctx.fillStyle = "rgba(0,0,0,0.55)";
    ctx.fillRect(-146 + k * 21, 17 + r * 9, 17, 7);
    ctx.strokeStyle = "rgba(255,255,255,0.10)"; ctx.lineWidth = 0.8;
    ctx.strokeRect(-146 + k * 21 + 3, 17 + r * 9 + 2, 11, 3);
   } else {
    ctx.fillStyle = "rgba(255,255,255,0.10)";
    ctx.fillRect(-146 + k * 21, 17 + r * 9, 17, 7);
   }
  }
 }
 /* Touchpad */
 ctx.fillStyle = "rgba(0,0,0,0.18)";
 roundRect(-34, 50, 68, 18, 3); ctx.fill();
 /* Delle im Gehaeuse */
 if (d.delle){
  ctx.save(); ctx.translate(d.delle.x, d.delle.y); ctx.rotate(d.delle.rot);
  var dg = ctx.createRadialGradient(0, 0, 2, 0, 0, d.delle.rx);
  dg.addColorStop(0, "rgba(0,0,0,0.42)"); dg.addColorStop(0.75, "rgba(0,0,0,0.16)"); dg.addColorStop(1, "rgba(0,0,0,0)");
  ctx.fillStyle = dg;
  ctx.beginPath(); ctx.ellipse(0, 0, d.delle.rx, d.delle.ry, 0, 0, 7); ctx.fill();
  ctx.strokeStyle = "rgba(255,255,255,0.28)"; ctx.lineWidth = 1.1;
  ctx.beginPath(); ctx.ellipse(0, -1.5, d.delle.rx * 0.7, d.delle.ry * 0.55, 0, 3.4, 6.0); ctx.stroke();
  ctx.restore();
 }
 /* Abgebrochene Ecke */
 if (d.ecke){
  var ex = d.ecke.seite * 206, ey = 74, g2 = d.ecke.gr;
  ctx.fillStyle = "rgba(8,14,18,0.92)";
  ctx.beginPath();
  ctx.moveTo(ex, ey);
  ctx.lineTo(ex - d.ecke.seite * g2 * 1.5, ey);
  ctx.lineTo(ex - d.ecke.seite * g2 * 1.05, ey - g2 * 0.45);
  ctx.lineTo(ex - d.ecke.seite * g2 * 0.45, ey - g2 * 0.7);
  ctx.lineTo(ex, ey - g2 * 0.32);
  ctx.closePath(); ctx.fill();
  ctx.strokeStyle = "rgba(255,255,255,0.30)"; ctx.lineWidth = 1.2; ctx.lineJoin = "round";
  ctx.beginPath();
  ctx.moveTo(ex - d.ecke.seite * g2 * 1.5, ey);
  ctx.lineTo(ex - d.ecke.seite * g2 * 1.05, ey - g2 * 0.45);
  ctx.lineTo(ex - d.ecke.seite * g2 * 0.45, ey - g2 * 0.7);
  ctx.lineTo(ex, ey - g2 * 0.32);
  ctx.stroke();
 }
 /* Bildschirm: Rahmen */
 var lg = ctx.createLinearGradient(0, -120, 0, -8);
 lg.addColorStop(0, c[0]); lg.addColorStop(1, c[1]);
 ctx.fillStyle = lg;
 roundRect(-168, -122, 336, 118, 8); ctx.fill();
 /* Scharnier */
 if (d.scharnierDefekt){
  ctx.fillStyle = c[2]; ctx.fillRect(-60, -6, 44, 8);
  ctx.fillStyle = c[2]; ctx.fillRect(4, -6, 56, 8);
  ctx.fillStyle = "rgba(8,14,18,0.9)"; ctx.fillRect(-16, -7, 20, 10);
  ctx.save(); ctx.translate(-8, 6); ctx.rotate(0.35);
  ctx.fillStyle = c[2]; ctx.fillRect(-9, -3, 18, 6);
  ctx.restore();
  ctx.strokeStyle = "rgba(255,255,255,0.25)"; ctx.lineWidth = 1;
  ctx.strokeRect(-16, -7, 20, 10);
 } else {
  ctx.fillStyle = c[2]; ctx.fillRect(-60, -6, 120, 8);
 }
 /* Glas (Gerät ist AUS – dunkel spiegelnd) */
 var gl = ctx.createLinearGradient(-160, -114, 160, -12);
 gl.addColorStop(0, "#10181d"); gl.addColorStop(0.5, "#1a262d"); gl.addColorStop(1, "#0d1417");
 ctx.fillStyle = gl; ctx.fillRect(-158, -112, 316, 98);
 /* Spiegelung */
 ctx.save();
 ctx.beginPath(); ctx.rect(-158, -112, 316, 98); ctx.clip();
 ctx.fillStyle = "rgba(200,230,245,0.06)";
 ctx.beginPath(); ctx.moveTo(-158, -112); ctx.lineTo(-40, -112); ctx.lineTo(-130, -14); ctx.lineTo(-158, -14); ctx.closePath(); ctx.fill();
 ctx.fillStyle = "rgba(200,230,245,0.04)";
 ctx.beginPath(); ctx.moveTo(-10, -112); ctx.lineTo(30, -112); ctx.lineTo(-60, -14); ctx.lineTo(-100, -14); ctx.closePath(); ctx.fill();
 /* Gebrauchsspuren */
 d.smudges.forEach(function(sm){
  ctx.save(); ctx.translate(sm.x, sm.y); ctx.rotate(sm.rot);
  ctx.fillStyle = "rgba(210,225,235," + sm.a + ")";
  ctx.beginPath(); ctx.ellipse(0, 0, sm.rx, sm.ry, 0, 0, 7); ctx.fill();
  ctx.restore();
 });
 /* Display-Risse */
 d.cracks.forEach(function(cr){
  if (cr.where !== "screen") return;
  strokeCrack(cr.pts, cr.w, "rgba(235,245,250,0.85)", "rgba(150,180,195,0.35)");
 });
 ctx.restore();
 /* Rahmen-/Deckelrand-Risse */
 d.cracks.forEach(function(cr){
  if (cr.where !== "bezel") return;
  strokeCrack(cr.pts, cr.w, "rgba(25,32,36,0.95)", "rgba(255,255,255,0.18)");
 });
 /* Basis-Risse */
 d.cracks.forEach(function(cr){
  if (cr.where !== "base") return;
  strokeCrack(cr.pts, cr.w, "rgba(25,32,36,0.95)", "rgba(255,255,255,0.20)");
 });
 /* Inventaraufkleber */
 if (d.sticker){
  ctx.save(); ctx.translate(120, 56); ctx.rotate(0.06);
  ctx.fillStyle = "#e9e2c8"; ctx.fillRect(-26, -8, 52, 16);
  ctx.fillStyle = "#555"; ctx.font = "8px Arial"; ctx.textAlign = "center";
  ctx.fillText("INV 7-" + d.serial.slice(3), 0, 3);
  ctx.restore();
 }
 ctx.restore();
}
function strokeCrack(pts, w, col, glow){
 ctx.lineCap = "round"; ctx.lineJoin = "round";
 ctx.strokeStyle = glow; ctx.lineWidth = w + 2.4;
 pfad(pts); ctx.stroke();
 ctx.strokeStyle = col; ctx.lineWidth = w;
 pfad(pts); ctx.stroke();
}
function pfad(pts){
 ctx.beginPath(); ctx.moveTo(pts[0][0], pts[0][1]);
 for (var i = 1; i < pts.length; i++) ctx.lineTo(pts[i][0], pts[i][1]);
}
function roundRect(x, y, w, h, r){
 ctx.beginPath();
 ctx.moveTo(x + r, y);
 ctx.arcTo(x + w, y, x + w, y + h, r); ctx.arcTo(x + w, y + h, x, y + h, r);
 ctx.arcTo(x, y + h, x, y, r); ctx.arcTo(x, y, x + w, y, r);
 ctx.closePath();
}

/* ---------- Ablauf ---------- */
function draw(){
 bg();
 if (done){
  ctx.fillStyle = "rgba(10,25,33,0.88)"; ctx.fillRect(0, 0, W, H);
  ctx.fillStyle = "#dfe9ee"; ctx.font = "bold 30px Arial"; ctx.textAlign = "center";
  ctx.fillText("Palette fertig sortiert", CX, 200);
  ctx.font = "22px Arial";
  ctx.fillStyle = "#ff9d92"; ctx.fillText("Befund: " + nDef, CX - 130, 258);
  ctx.fillStyle = "#a5d97a"; ctx.fillText("ohne Befund: " + nOk, CX + 120, 258);
  ctx.fillStyle = "rgba(216,226,232,0.6)"; ctx.font = "16px Arial";
  ctx.fillText("Notiert eure Zahlen – dann „Neue Palette“.", CX, 306);
  return;
 }
 var x = CX, y = CY, s = dev.scale, rot = dev.rot, al = 1;
 if (state === "in"){
  var t = ease(anim);
  x = -260 + (CX + 260) * t; rot = dev.rot + (1 - t) * 0.12; s = dev.scale * (0.9 + 0.1 * t);
 } else if (state === "out"){
  var t2 = anim * anim;
  var ziel = dev.userSagtDefekt ? 78 : 922;
  x = CX + (ziel - CX) * t2;
  y = CY + (402 - CY) * t2 * t2 * 0.9;
  s = dev.scale * (1 - 0.72 * t2); rot = dev.rot + (dev.userSagtDefekt ? -1 : 1) * t2 * 0.5;
 }
 drawDevice(dev, x, y, s, rot, al);
 /* Seriennummer-Anhänger */
 if (state === "idle"){
  ctx.fillStyle = "rgba(14,37,48,0.9)"; roundRect(CX - 60, 400, 120, 30, 6); ctx.fill();
  ctx.strokeStyle = "#2c5568"; ctx.stroke();
  ctx.fillStyle = "#9fc3d2"; ctx.font = "bold 14px Arial"; ctx.textAlign = "center";
  ctx.fillText(dev.serial, CX, 420);
 }
}
function ease(t){ return 1 - Math.pow(1 - t, 3); }

var tPrev = 0;
function frame(now){
 if (!tPrev) tPrev = now;
 var dt = Math.min((now - tPrev) / 1000, 0.05);
 tPrev = now;
 if (state === "in"){
  anim += dt / 0.55;
  if (anim >= 1){ anim = 1; state = "idle"; knoepfe(true); }
 } else if (state === "out"){
  anim += dt / 0.42;
  if (anim >= 1){
   if (dev.userSagtDefekt) nDef++; else nOk++;
   idx++;
   if (idx >= N){ done = true; knoepfe(false); }
   else { dev = newDevice(); state = "in"; anim = 0; }
   stat();
  }
 }
 draw();
 requestAnimationFrame(frame);
}
function decide(defekt){
 if (state !== "idle" || done) return;
 dev.userSagtDefekt = defekt;
 state = "out"; anim = 0; knoepfe(false);
}
function knoepfe(an){
 document.getElementById("bDef").disabled = !an;
 document.getElementById("bOk").disabled = !an;
}
function stat(){
 document.getElementById("nCur").textContent = Math.min(idx + 1, N);
 document.getElementById("nDef").textContent = nDef;
 document.getElementById("nOk").textContent = nOk;
}
function restart(){
 pDef = 0.15 + Math.random() * 0.15;   /* jede Palette hat ihre eigene Quote (15 bis 30 %) */
 idx = 0; nDef = 0; nOk = 0; done = false;
 dev = newDevice(); state = "in"; anim = 0;
 knoepfe(false); stat();
}
document.addEventListener("keydown", function(e){
 if (e.key === "ArrowLeft") decide(true);
 if (e.key === "ArrowRight") decide(false);
});
restart();
requestAnimationFrame(frame);
</script>
</body>
</html>
