[proxima-interview-guide (3).html](https://github.com/user-attachments/files/26860720/proxima-interview-guide.3.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Proxima — Interview Process</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{--bg:#07090f;--card:#0f1420;--blue:#4db8ff;--blue2:#7dd3fc;--cyan:#22d3ee;--text:#e2e8f0;--muted:#7a8699;--bdr:rgba(77,184,255,0.12);--bdr2:rgba(77,184,255,0.06);}
html{scroll-behavior:smooth;}
body{background:var(--bg);color:var(--text);font-family:'Jost',sans-serif;font-weight:300;line-height:1.8;overflow-x:hidden;}
#pcv{position:fixed;inset:0;z-index:0;pointer-events:none;opacity:0.35;}
nav{position:fixed;top:0;left:0;right:0;z-index:200;display:flex;align-items:center;justify-content:space-between;padding:1.2rem 3rem;background:rgba(7,9,15,0.9);backdrop-filter:blur(24px);border-bottom:1px solid var(--bdr2);}
.nl{font-family:'Jost',sans-serif;font-weight:200;font-size:1.35rem;letter-spacing:0.35em;color:#fff;text-transform:uppercase;}
.nm{display:flex;gap:2rem;}
.nm a{font-size:0.72rem;letter-spacing:0.15em;text-transform:uppercase;color:var(--muted);text-decoration:none;transition:color 0.3s;}
.nm a:hover{color:var(--blue2);}
.hero{position:relative;min-height:100vh;display:flex;flex-direction:column;justify-content:flex-end;padding:0 3rem 6rem;overflow:hidden;z-index:1;}
.hbg{position:absolute;inset:0;z-index:0;background:radial-gradient(ellipse 80% 60% at 70% 20%,rgba(14,60,120,0.5),transparent 65%),radial-gradient(ellipse 60% 50% at 20% 80%,rgba(5,30,70,0.3),transparent 60%),var(--bg);}
.hm{position:absolute;top:-5%;right:-6%;width:58%;z-index:1;pointer-events:none;}
.hm2{position:absolute;bottom:-8%;right:8%;width:28%;z-index:1;pointer-events:none;opacity:0.75;}
.hc{position:relative;z-index:2;max-width:640px;}
.ey{font-size:0.72rem;letter-spacing:0.25em;text-transform:uppercase;color:var(--blue);margin-bottom:1.5rem;opacity:0;animation:fu 0.8s ease 0.3s forwards;}
.hw{font-family:'Jost',sans-serif;font-weight:200;font-size:clamp(3rem,8vw,6rem);letter-spacing:0.3em;text-transform:uppercase;color:#fff;line-height:1;margin-bottom:1rem;opacity:0;animation:fu 0.8s ease 0.5s forwards;}
.hs{font-family:'Cormorant Garamond',serif;font-size:clamp(1.5rem,4vw,2.5rem);font-weight:300;color:rgba(255,255,255,0.5);letter-spacing:0.08em;margin-bottom:2.5rem;opacity:0;animation:fu 0.8s ease 0.7s forwards;}
.hl{width:60px;height:1px;background:linear-gradient(90deg,var(--blue),transparent);margin-bottom:2rem;opacity:0;animation:fu 0.8s ease 0.9s forwards;}
.hi{max-width:520px;font-size:0.92rem;color:rgba(226,232,240,0.6);line-height:1.9;opacity:0;animation:fu 0.8s ease 1.1s forwards;}
.hi strong{color:rgba(226,232,240,0.95);font-weight:400;}
.hi a{color:var(--blue2);text-decoration:none;border-bottom:1px solid rgba(125,211,252,0.3);}
.gl{margin-top:2rem;font-family:'Cormorant Garamond',serif;font-size:1.8rem;font-weight:300;color:var(--blue2);letter-spacing:0.05em;opacity:0;animation:fu 0.8s ease 1.3s forwards;}
.si{position:absolute;bottom:2.5rem;right:3rem;z-index:2;display:flex;flex-direction:column;align-items:center;gap:0.5rem;}
.si span{font-size:0.65rem;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted);writing-mode:vertical-lr;}
.sd{width:1px;height:50px;background:var(--bdr);position:relative;overflow:hidden;}
.sd::after{content:'';position:absolute;top:-100%;left:0;width:100%;height:100%;background:var(--blue);animation:sdwn 2s ease-in-out infinite;}
@keyframes sdwn{0%{top:-100%;}100%{top:200%;}}
.dvd{width:100%;height:1px;background:linear-gradient(90deg,transparent,var(--blue) 30%,var(--cyan) 70%,transparent);opacity:0.2;}
.ch{position:relative;min-height:55vh;display:flex;align-items:center;overflow:hidden;background:var(--bg);}
.cml{position:absolute;left:-4%;top:50%;transform:translateY(-50%);width:50%;z-index:1;pointer-events:none;}
.cmr{position:absolute;right:-4%;top:50%;transform:translateY(-50%);width:46%;z-index:1;pointer-events:none;}
.ct{position:relative;z-index:2;padding:5rem 3rem;}
.ctr{margin-left:auto;text-align:right;}
.ctit{font-family:'Cormorant Garamond',serif;font-size:clamp(2.5rem,6vw,5rem);font-weight:300;color:#fff;letter-spacing:0.05em;line-height:1.1;}
.cnum{position:absolute;bottom:2rem;font-size:0.65rem;letter-spacing:0.3em;text-transform:uppercase;color:var(--blue);opacity:0.7;}
.cnl{left:3rem;}.cnr{right:3rem;}
.cs{position:relative;z-index:1;max-width:900px;margin:0 auto;padding:5rem 3rem;}
.csw{max-width:1100px;}
.sl{font-size:0.68rem;letter-spacing:0.25em;text-transform:uppercase;color:var(--blue);margin-bottom:1.5rem;display:block;}
.ic{background:rgba(13,16,24,0.85);border:1px solid var(--bdr);border-radius:4px;padding:3.5rem;position:relative;overflow:hidden;}
.ic::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--blue),var(--cyan));}
.ic p{font-size:1rem;color:rgba(226,232,240,0.72);line-height:1.95;margin-bottom:1.2rem;}
.ic p:last-child{margin-bottom:0;}
.ic strong{color:var(--text);font-weight:400;}
.ic a{color:var(--blue2);text-decoration:none;border-bottom:1px solid rgba(125,211,252,0.3);}
.sg{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:3rem;}
.sc{background:var(--card);border:1px solid var(--bdr2);border-radius:4px;padding:2rem;position:relative;transition:border-color 0.3s,transform 0.3s;}
.sc:hover{border-color:rgba(77,184,255,0.25);transform:translateY(-2px);}
.sc::after{content:'';position:absolute;top:0;left:0;width:3px;height:100%;background:linear-gradient(180deg,var(--blue),var(--cyan));border-radius:4px 0 0 4px;}
.st{font-weight:400;font-size:0.9rem;color:var(--blue2);letter-spacing:0.05em;margin-bottom:0.75rem;}
.sb{font-size:0.85rem;color:var(--muted);line-height:1.85;}
.cn{margin-top:3rem;padding:2rem 2.5rem;border:1px solid var(--bdr2);border-radius:4px;background:rgba(13,16,24,0.5);font-size:0.9rem;color:rgba(226,232,240,0.65);line-height:1.9;}
.pb{font-size:1rem;color:rgba(226,232,240,0.7);line-height:1.95;}
.pb strong{color:var(--text);font-weight:400;}
.pb p{margin-bottom:1.5rem;}
.pb p:last-child{margin-bottom:0;}
.pl{display:inline-block;font-size:0.82rem;font-weight:400;letter-spacing:0.08em;color:var(--blue2);text-decoration:none;border:1px solid rgba(125,211,252,0.25);padding:0.6rem 1.25rem;border-radius:2px;transition:background 0.3s,border-color 0.3s;margin-top:2rem;}
.pl:hover{background:rgba(77,184,255,0.08);border-color:rgba(125,211,252,0.5);}
.ec{background:var(--card);border:1px solid var(--bdr);border-radius:4px;padding:3rem;margin-bottom:2rem;position:relative;overflow:hidden;}
.ec::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--blue),transparent);}
.ec h3{font-weight:400;font-size:1rem;color:var(--text);letter-spacing:0.03em;margin-bottom:1.5rem;}
.el{list-style:none;display:flex;flex-direction:column;gap:1rem;}
.el li{display:flex;align-items:flex-start;gap:1rem;font-size:0.88rem;color:rgba(226,232,240,0.65);line-height:1.8;}
.el li::before{content:'';flex-shrink:0;width:5px;height:5px;border-radius:50%;background:var(--blue);margin-top:0.6rem;}
.ab{background:rgba(7,9,15,0.6);border:1px solid var(--bdr2);border-radius:4px;padding:3rem;}
.ab p{font-size:0.95rem;color:rgba(226,232,240,0.68);line-height:1.95;margin-bottom:1.2rem;}
.ab p:last-child{margin-bottom:0;}
.ab strong{color:var(--text);font-weight:400;}
.qg{margin-bottom:3rem;}
.qtit{font-weight:400;font-size:0.85rem;letter-spacing:0.08em;color:var(--blue2);text-transform:uppercase;margin-bottom:1.5rem;}
.ql{list-style:none;display:flex;flex-direction:column;}
.ql li{display:flex;align-items:flex-start;gap:1.25rem;font-size:0.88rem;color:rgba(226,232,240,0.65);line-height:1.85;padding:1rem 0;border-bottom:1px solid var(--bdr2);}
.ql li:last-child{border-bottom:none;}
.qn{flex-shrink:0;font-size:0.65rem;letter-spacing:0.1em;color:var(--blue);margin-top:0.2rem;font-weight:400;min-width:24px;}
.rg{display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:3rem;}
.rlc{display:block;background:var(--card);border:1px solid var(--bdr2);border-radius:4px;padding:1.25rem 1.5rem;text-decoration:none;transition:border-color 0.3s,background 0.3s;}
.rlc:hover{border-color:rgba(77,184,255,0.3);background:rgba(13,16,24,0.95);}
.rlc span{font-size:0.85rem;color:var(--blue2);display:block;margin-bottom:0.25rem;}
.rlc small{font-size:0.75rem;color:var(--muted);}
.pubs{list-style:none;display:flex;flex-direction:column;gap:1rem;}
.pubs li{padding:1.25rem 1.5rem;background:var(--card);border:1px solid var(--bdr2);border-radius:4px;font-size:0.82rem;line-height:1.75;transition:border-color 0.3s;}
.pubs li:hover{border-color:rgba(77,184,255,0.25);}
.pubs a{color:var(--blue2);text-decoration:none;}
.pn{display:block;color:var(--muted);margin-top:0.35rem;font-size:0.78rem;}
.toc{background:var(--card);border:1px solid var(--bdr);border-radius:4px;overflow:hidden;margin-bottom:5rem;}
.ti{display:flex;align-items:center;justify-content:space-between;padding:1.25rem 2rem;border-bottom:1px solid var(--bdr2);text-decoration:none;transition:background 0.2s;}
.ti:last-child{border-bottom:none;}
.ti:hover{background:rgba(77,184,255,0.04);}
.ti span{font-size:0.88rem;color:var(--blue2);letter-spacing:0.03em;}
.ti em{font-size:0.72rem;color:var(--muted);font-style:normal;letter-spacing:0.1em;}
footer{position:relative;z-index:1;border-top:1px solid var(--bdr2);padding:5rem 3rem;text-align:center;overflow:hidden;}
.fm{position:absolute;top:-10%;left:50%;transform:translateX(-50%);width:75%;opacity:0.1;pointer-events:none;}
.fw{font-family:'Jost',sans-serif;font-weight:200;font-size:2rem;letter-spacing:0.4em;text-transform:uppercase;color:#fff;margin-bottom:1rem;position:relative;}
.fa{font-size:0.78rem;color:var(--muted);letter-spacing:0.08em;line-height:2;position:relative;}
.fa a{color:var(--blue2);text-decoration:none;}
@keyframes fu{from{opacity:0;transform:translateY(22px);}to{opacity:1;transform:translateY(0);}}
@keyframes fA{0%,100%{transform:translateY(0) rotate(0deg);}50%{transform:translateY(-16px) rotate(1.5deg);}}
@keyframes fB{0%,100%{transform:translateY(0) rotate(0deg);}50%{transform:translateY(-12px) rotate(-1.2deg);}}
@keyframes fC{0%,100%{transform:translateY(0) rotate(0deg);}50%{transform:translateY(-20px) rotate(1deg);}}
.fa1{animation:fA 9s ease-in-out infinite;}
.fa2{animation:fB 11s ease-in-out infinite 1s;}
.fa3{animation:fC 13s ease-in-out infinite 2s;}
.rev{opacity:0;transform:translateY(24px);transition:opacity 0.7s ease,transform 0.7s ease;}
.rev.vis{opacity:1;transform:translateY(0);}
@media(max-width:768px){nav{padding:1rem 1.5rem;}.nm{display:none;}.hero,.cs{padding-left:1.5rem;padding-right:1.5rem;}.ct{padding:3rem 1.5rem;}.sg,.rg{grid-template-columns:1fr;}}
</style>
</head>
<body>
<canvas id="pcv"></canvas>
<svg width="0" height="0" style="position:absolute">
  <defs>
    <radialGradient id="g1" cx="38%" cy="32%" r="65%"><stop offset="0%" stop-color="#b8ecff"/><stop offset="30%" stop-color="#4db8ff"/><stop offset="65%" stop-color="#0e5fa0"/><stop offset="100%" stop-color="#041830" stop-opacity="0.2"/></radialGradient>
    <radialGradient id="g2" cx="45%" cy="38%" r="60%"><stop offset="0%" stop-color="#d4f4ff"/><stop offset="35%" stop-color="#7dd3fc"/><stop offset="70%" stop-color="#1a6aaa"/><stop offset="100%" stop-color="#031020" stop-opacity="0.2"/></radialGradient>
    <radialGradient id="g3" cx="42%" cy="36%" r="58%"><stop offset="0%" stop-color="#eafaff"/><stop offset="28%" stop-color="#bae6fd"/><stop offset="62%" stop-color="#38aee0"/><stop offset="100%" stop-color="#021530" stop-opacity="0.25"/></radialGradient>
    <radialGradient id="g4" cx="40%" cy="34%" r="62%"><stop offset="0%" stop-color="#f5fdff"/><stop offset="22%" stop-color="#e0f6ff"/><stop offset="52%" stop-color="#90cff0"/><stop offset="85%" stop-color="#2270aa"/><stop offset="100%" stop-color="#021228" stop-opacity="0.3"/></radialGradient>
    <radialGradient id="gw" cx="50%" cy="50%" r="50%"><stop offset="0%" stop-color="#0c3d78" stop-opacity="0.55"/><stop offset="100%" stop-color="#020c1a" stop-opacity="0"/></radialGradient>
  </defs>
</svg>
<nav>
  <a href="#" style="display:flex;align-items:center;text-decoration:none;"><img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:28px;width:auto;filter:brightness(0) invert(1);"/></a>
  <div class="nm">
    <a href="#intro-call">Intro Call</a>
    <a href="#panel">Panel Interviews</a>
    <a href="#exercise">Technical Exercise</a>
    <a href="#questions">Questions</a>
    <a href="#science">Science</a>
  </div>
</nav>

<section class="hero">
  <div class="hbg"></div>
  <div class="hm fa1">
    <svg viewBox="0 0 680 600" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="400" cy="230" rx="265" ry="235" fill="url(#gw)" opacity="0.75"/>
      <path d="M260,75 C305,32 388,22 445,55 C502,88 538,152 535,215 C532,278 492,332 432,358 C372,384 298,372 252,332 C206,292 195,228 208,172 C220,120 225,108 260,75Z" fill="url(#g1)" opacity="0.9"/>
      <path d="M400,48 C438,12 498,20 515,62 C532,104 506,148 468,156 C430,164 395,132 392,96 C390,65 388,72 400,48Z" fill="url(#g2)" opacity="0.86"/>
      <path d="M510,145 C545,112 592,132 604,174 C616,216 588,258 552,262 C516,266 488,234 495,198 C501,168 496,165 510,145Z" fill="url(#g3)" opacity="0.8"/>
      <path d="M215,305 C185,275 182,238 206,215 C230,192 268,200 285,226 C302,252 292,295 266,310 C242,323 232,320 215,305Z" fill="url(#g2)" opacity="0.76"/>
      <circle cx="478" cy="72" r="24" fill="url(#g3)" opacity="0.84"/><circle cx="512" cy="50" r="17" fill="url(#g2)" opacity="0.78"/>
      <circle cx="540" cy="76" r="13" fill="url(#g4)" opacity="0.72"/><circle cx="498" cy="32" r="11" fill="url(#g3)" opacity="0.68"/>
      <circle cx="558" cy="56" r="9" fill="url(#g2)" opacity="0.64"/><circle cx="548" cy="96" r="8" fill="url(#g3)" opacity="0.68"/>
      <circle cx="572" cy="78" r="6" fill="url(#g4)" opacity="0.56"/><circle cx="520" cy="24" r="8" fill="url(#g2)" opacity="0.62"/>
      <circle cx="592" cy="122" r="16" fill="url(#g2)" opacity="0.66"/><circle cx="616" cy="100" r="11" fill="url(#g3)" opacity="0.6"/>
      <circle cx="626" cy="144" r="8" fill="url(#g2)" opacity="0.56"/><circle cx="642" cy="124" r="6" fill="url(#g4)" opacity="0.48"/>
      <circle cx="418" cy="28" r="14" fill="url(#g4)" opacity="0.7"/><circle cx="444" cy="10" r="9" fill="url(#g3)" opacity="0.64"/>
      <circle cx="560" cy="195" r="19" fill="url(#g2)" opacity="0.68"/><circle cx="585" cy="172" r="13" fill="url(#g3)" opacity="0.62"/>
      <circle cx="305" cy="128" r="4.5" fill="#e8f8ff" opacity="0.92"/><circle cx="425" cy="74" r="3.5" fill="#f5fdff" opacity="0.94"/>
      <path d="M175,398 C148,372 145,338 168,316 C191,294 228,302 244,326 C260,350 250,386 228,400 C208,412 196,414 175,398Z" fill="url(#g2)" opacity="0.72"/>
      <circle cx="155" cy="405" r="18" fill="url(#g3)" opacity="0.67"/><circle cx="134" cy="424" r="13" fill="url(#g2)" opacity="0.6"/>
      <g opacity="0.38">
        <circle cx="50" cy="520" r="2.5" fill="#4db8ff"/><circle cx="114" cy="524" r="2.5" fill="#7dd3fc"/>
        <circle cx="178" cy="527" r="2" fill="#4db8ff"/><circle cx="242" cy="529" r="2" fill="#7dd3fc"/>
        <circle cx="306" cy="531" r="2.5" fill="#4db8ff"/><circle cx="370" cy="533" r="2" fill="#4db8ff"/>
        <circle cx="434" cy="535" r="2" fill="#7dd3fc"/><circle cx="498" cy="537" r="2.5" fill="#4db8ff"/>
        <circle cx="562" cy="539" r="2" fill="#4db8ff"/><circle cx="626" cy="541" r="2" fill="#7dd3fc"/>
        <circle cx="82" cy="544" r="1.5" fill="#38bdf8"/><circle cx="162" cy="551" r="1.5" fill="#38bdf8"/>
        <circle cx="258" cy="547" r="1.5" fill="#38bdf8"/><circle cx="354" cy="558" r="1.5" fill="#38bdf8"/>
        <circle cx="450" cy="554" r="1.5" fill="#38bdf8"/><circle cx="546" cy="564" r="1.5" fill="#38bdf8"/>
      </g>
    </svg>
  </div>
  <div class="hm2 fa2">
    <svg viewBox="0 0 300 265" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="150" cy="132" rx="132" ry="115" fill="url(#gw)" opacity="0.55"/>
      <path d="M72,55 C104,24 158,18 192,46 C226,74 238,122 224,160 C210,198 168,220 128,218 C88,216 58,188 48,155 C38,122 48,80 72,55Z" fill="url(#g1)" opacity="0.86"/>
      <path d="M145,35 C172,10 210,20 220,56 C230,92 206,128 178,132 C150,136 124,110 124,80 C124,54 126,52 145,35Z" fill="url(#g4)" opacity="0.8"/>
      <circle cx="205" cy="48" r="19" fill="url(#g3)" opacity="0.79"/><circle cx="228" cy="30" r="14" fill="url(#g2)" opacity="0.73"/>
      <circle cx="248" cy="54" r="10" fill="url(#g4)" opacity="0.67"/><circle cx="234" cy="14" r="9" fill="url(#g3)" opacity="0.64"/>
      <circle cx="92" cy="200" r="18" fill="url(#g2)" opacity="0.72"/><circle cx="70" cy="218" r="13" fill="url(#g3)" opacity="0.65"/>
      <circle cx="138" cy="106" r="4" fill="#e8f8ff" opacity="0.9"/>
    </svg>
  </div>
  <div class="hc">
    <p class="ey">Candidate Guide</p>
    <div class="hw" style="margin-bottom:1.5rem;opacity:0;animation:fu 0.8s ease 0.5s forwards;"><img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:clamp(48px,8vw,90px);width:auto;filter:brightness(0) invert(1);display:block;"/></div>
    <div class="hs">Interview Process</div>
    <div class="hl"></div>
    <p class="hi"><strong>This is your prep guide for your interviews with Proxima.</strong> Our department leaders and recruiters put together this guide so you know what to expect and how to prepare. This document covers all of the steps in the typical interview process however your particular interview process may be altered and customized depending on your particular areas of expertise, the role you're interviewing for and the business needs. In summary, this guide is designed to answer most of the questions you may have about the interview process, and how to set yourself up for success by preparing. <strong>If you have further questions be sure to reach out to <a href="mailto:recruiting@proximabio.com">recruiting</a> and they'd be happy to answer them for you.</strong></p>
    <div class="gl">Good Luck!</div>
  </div>
  <div class="si"><div class="sd"></div><span>Scroll</span></div>
</section>
<div class="dvd"></div>

<div class="cs" style="padding-top:5rem;padding-bottom:2rem;">
  <span class="sl rev">Table of Contents</span>
  <div class="toc rev">
    <a href="#intro-call" class="ti"><span>Intro Call</span><em>01</em></a>
    <a href="#panel" class="ti"><span>Panel Interviews</span><em>02</em></a>
    <a href="#exercise" class="ti"><span>Technical / Thought Exercise &amp; Presentation</span><em>03</em></a>
    <a href="#questions" class="ti"><span>Additional Resources</span><em>04</em></a>
    <a href="#role-agnostic" class="ti" style="padding-left:3.5rem;"><span style="color:var(--muted);font-size:0.82rem;">Role agnostic, generalized questions</span><em>14</em></a>
    <a href="#role-specific" class="ti" style="padding-left:3.5rem;"><span style="color:var(--muted);font-size:0.82rem;">Role &amp; Team specific questions</span><em>15</em></a>
    <a href="#soft-skills" class="ti" style="padding-left:3.5rem;"><span style="color:var(--muted);font-size:0.82rem;">Soft Skills Questions</span><em>16</em></a>
    <a href="#science" class="ti"><span>Proxima Science</span><em>17</em></a>
  </div>
</div>

<div id="intro-call"></div>
<section class="ch">
  <div class="cml fa1">
    <svg viewBox="0 0 480 460" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="240" cy="230" rx="220" ry="200" fill="url(#gw)" opacity="0.5"/>
      <path d="M95,110 C136,62 218,48 278,78 C338,108 368,174 360,234 C352,294 308,338 248,356 C188,374 122,352 88,308 C54,264 58,196 75,150 C88,115 68,140 95,110Z" fill="url(#g1)" opacity="0.88"/>
      <path d="M248,55 C284,20 342,30 356,72 C370,114 344,158 306,164 C268,170 232,140 230,104 C228,72 228,78 248,55Z" fill="url(#g2)" opacity="0.84"/>
      <circle cx="328" cy="66" r="23" fill="url(#g3)" opacity="0.81"/><circle cx="358" cy="44" r="16" fill="url(#g2)" opacity="0.75"/>
      <circle cx="380" cy="70" r="12" fill="url(#g4)" opacity="0.69"/><circle cx="400" cy="52" r="9" fill="url(#g2)" opacity="0.62"/>
      <circle cx="432" cy="142" r="18" fill="url(#g2)" opacity="0.68"/><circle cx="455" cy="120" r="13" fill="url(#g3)" opacity="0.62"/>
      <path d="M62,295 C36,268 34,230 58,210 C82,190 118,202 134,228 C150,254 138,290 116,302 C96,314 78,308 62,295Z" fill="url(#g2)" opacity="0.7"/>
      <circle cx="42" cy="302" r="15" fill="url(#g3)" opacity="0.64"/>
      <circle cx="178" cy="125" r="4" fill="#e8f8ff" opacity="0.9"/>
      <g opacity="0.33"><circle cx="60" cy="430" r="2" fill="#4db8ff"/><circle cx="124" cy="434" r="2.5" fill="#4db8ff"/><circle cx="188" cy="437" r="2" fill="#7dd3fc"/><circle cx="252" cy="440" r="2.5" fill="#4db8ff"/><circle cx="316" cy="442" r="2" fill="#4db8ff"/><circle cx="380" cy="444" r="2.5" fill="#7dd3fc"/><circle cx="444" cy="446" r="2" fill="#4db8ff"/></g>
    </svg>
  </div>
  <div class="ct ctr" style="margin-left:auto;max-width:52%;"><div class="ctit rev">Intro Call</div></div>
  <span class="cnum cnr">01</span>
<div style="position:absolute;bottom:1.5rem;right:2rem;z-index:10;">
  <img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:22px;width:auto;filter:brightness(0) invert(1);opacity:0.7;"/>
</div>
</section>

<div class="cs">
  <div class="ic rev">
    <p><strong>Despite the name, the Intro Call is a formal interview.</strong> The interviewer will ask you to speak about your academic and industry experience as well as ask questions to assess your hard skill sets, both generally and as they relate to the specific role and team that you're interviewing for. Be sure to read and understand the job description carefully.</p>
    <p>The Intro Call will also assess soft skill sets and personality traits that we look for here at Proxima. They will want to understand your underlying motivations, ie why are you interested in working here at Proxima.</p>
    <p><strong>We operate in a flat, fast paced, highly unstructured environment so the interviewer will be looking for the following signals that correlate to success in this type of setting:</strong></p>
  </div>
  <div class="sg">
    <div class="sc rev"><div class="st">Ambiguity, Adaptability &amp; Self-Sufficiency</div><div class="sb">How do you operate in an ambiguous and quickly changing environment? Can you make independent decisions and sustain productivity when missing information? How did you react when you had to pivot away from a project due to a shift in priority?</div></div>
    <div class="sc rev"><div class="st">Problem Solving</div><div class="sb">We're evaluating how you comprehend and explain complex ideas and think creatively when solving problems. Are you providing the reasoning behind a particular solution? Developing and comparing multiple solutions? Speaking about space and time complexity? Optimizing your solution? Be prepared to talk walk through complex problem you faced and solved.</div></div>
    <div class="sc rev"><div class="st">Collaboration &amp; Communication</div><div class="sb">How well do you communicate with your teammates, managers, cross functional partners and clients? How do you partner with people and work cross functionally? What are some successful collaborations you've had?</div></div>
    <div class="sc rev"><div class="st">Growth, Challenges, Conflict</div><div class="sb">Discuss a challenging project that you led that succeeded or that failed. Why did it succeed/fail and what did you learn? Do you take constructive criticism as an opportunity to improve? Examples of how you're growing as a professional.</div></div>
  </div>
  <div class="cn rev">At the end of the interview the candidate will have some time to ask questions about Proxima, the role and what it's like to work here. Be prepared to answer the question of why you're interested in Proxima and how you see yourself contributing here.</div>
</div>
<div class="dvd"></div>

<div id="panel"></div>
<section class="ch">
  <div class="cmr fa2">
    <svg viewBox="0 0 460 500" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="230" cy="248" rx="205" ry="225" fill="url(#gw)" opacity="0.48"/>
      <path d="M112,76 C152,32 234,24 290,56 C346,88 375,155 366,216 C357,277 314,322 254,340 C194,358 128,336 96,294 C64,252 68,184 86,138 C100,104 82,108 112,76Z" fill="url(#g1)" opacity="0.88"/>
      <path d="M268,40 C306,6 362,18 376,62 C390,106 362,150 324,156 C286,162 250,130 250,94 C250,62 252,64 268,40Z" fill="url(#g2)" opacity="0.83"/>
      <circle cx="348" cy="44" r="22" fill="url(#g3)" opacity="0.81"/><circle cx="376" cy="24" r="16" fill="url(#g2)" opacity="0.75"/>
      <circle cx="398" cy="48" r="12" fill="url(#g4)" opacity="0.69"/><circle cx="385" cy="150" r="18" fill="url(#g2)" opacity="0.68"/>
      <path d="M78,295 C50,266 48,228 72,207 C96,186 134,198 150,226 C166,254 154,292 130,306 C108,318 92,312 78,295Z" fill="url(#g2)" opacity="0.72"/>
      <circle cx="58" cy="304" r="16" fill="url(#g3)" opacity="0.65"/>
      <path d="M175,396 C148,370 145,334 168,312 C191,290 228,298 244,324 C260,350 248,388 224,402 C202,414 192,416 175,396Z" fill="url(#g1)" opacity="0.78"/>
      <circle cx="153" cy="406" r="17" fill="url(#g3)" opacity="0.7"/>
      <circle cx="190" cy="116" r="4" fill="#e8f8ff" opacity="0.9"/>
      <g opacity="0.3"><circle cx="50" cy="468" r="2" fill="#4db8ff"/><circle cx="114" cy="472" r="2.5" fill="#4db8ff"/><circle cx="178" cy="475" r="2" fill="#7dd3fc"/><circle cx="242" cy="478" r="2.5" fill="#4db8ff"/><circle cx="306" cy="480" r="2" fill="#4db8ff"/><circle cx="370" cy="482" r="2.5" fill="#7dd3fc"/><circle cx="434" cy="484" r="2" fill="#4db8ff"/></g>
    </svg>
  </div>
  <div class="ct" style="max-width:50%;"><div class="ctit rev">Panel<br/>Interviews</div></div>
  <span class="cnum cnl">02</span>
<div style="position:absolute;bottom:1.5rem;right:2rem;z-index:10;">
  <img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:22px;width:auto;filter:brightness(0) invert(1);opacity:0.7;"/>
</div>
</section>

<div class="cs">
  <div class="ic rev">
    <div class="pb">
      <p><strong>The Panel Interviews are a continuation of the assessment that we begin in the Intro Call.</strong> Typically we conduct 2-4 Panel Interviews, each with a separate individual from the business group that you are being considered for, as well as individuals from cross functional partner teams.</p>
      <p>The assessment process will be similar to that of the Intro Call with the expectation that we will dive much deeper into your domain expertise. The Panel Interview will be further customized to your professional and academic background as well as your target role and department, ie Strategy &amp; Ops, Computational Chemistry, Computational Biology, AI Science, Software Engineering etc. You will not be asked to conduct any coding, whiteboarding or provide any visauals during these interviews however if this is a preference of yours when answering more technical questions then you are free to introduce a whiteboard or other form of visual.</p>
      <p>Regardless of what team and role you're interviewing for, keep in mind we'll be assessing how you'd fit into our ecosystem as a whole. Many of our scientists contribute to our code base and AI/ML models, and many of our AI Scientists and Software Engineers contribute to our biological and chemistry insights and pipelines. To call us a collaborative work environment is an understatement.</p>
    </div>
    <a href="#questions" class="pl">See Additional Resources section for sample Intro Call &amp; Panel Interview Questions &#8594;</a>
  </div>
</div>
<div class="dvd"></div>

<div id="exercise"></div>
<section class="ch">
  <div class="cml fa3" style="width:48%;">
    <svg viewBox="0 0 440 490" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="220" cy="240" rx="195" ry="215" fill="url(#gw)" opacity="0.44"/>
      <path d="M88,88 C128,42 210,35 265,65 C320,95 348,160 340,220 C332,280 290,324 230,340 C170,356 106,334 74,290 C42,246 46,178 65,132 C80,98 62,122 88,88Z" fill="url(#g1)" opacity="0.87"/>
      <path d="M228,48 C262,14 318,24 330,66 C342,108 316,150 280,155 C244,160 210,130 210,96 C210,66 212,68 228,48Z" fill="url(#g4)" opacity="0.81"/>
      <circle cx="305" cy="50" r="22" fill="url(#g3)" opacity="0.8"/><circle cx="333" cy="28" r="15" fill="url(#g2)" opacity="0.74"/>
      <circle cx="355" cy="54" r="11" fill="url(#g4)" opacity="0.68"/>
      <circle cx="350" cy="158" r="17" fill="url(#g2)" opacity="0.64"/>
      <path d="M56,285 C30,258 28,220 52,200 C76,180 112,192 128,218 C144,244 132,282 110,294 C90,306 72,300 56,285Z" fill="url(#g2)" opacity="0.7"/>
      <circle cx="36" cy="293" r="15" fill="url(#g3)" opacity="0.63"/>
      <circle cx="168" cy="110" r="4" fill="#e8f8ff" opacity="0.9"/>
    </svg>
  </div>
  <div class="ct ctr" style="margin-left:auto;max-width:54%;"><div class="ctit rev">Technical / Thought<br/>Exercise &amp;<br/>Presentation</div></div>
  <span class="cnum cnr">03</span>
<div style="position:absolute;bottom:1.5rem;right:2rem;z-index:10;">
  <img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:22px;width:auto;filter:brightness(0) invert(1);opacity:0.7;"/>
</div>
</section>

<div class="cs">
  <div class="ic rev" style="margin-bottom:2rem;">
    <div class="pb"><p><strong>If the Intro Call &amp; Panel Interviews go well, you will progress to our final round.</strong> Depending on the role this will either be a Technical or Thought Exercise along with a Presentation. We will send you an exercise that you will have 5-7 days to complete - duration is exercise dependent- and deliver your results. After delivery we will schedule a 1 hr Presentation, 30 minutes to present your work, 30 minutes for a Q&amp;A with the interview panel. See below for some insight on what the exercise is designed to evaluate.</p></div>
  </div>
  <div class="ec rev">
    <h3>The Proxima technical exercise is designed to evaluate your ability to:</h3>
    <ul class="el">
      <li><span>Leverage your scientific and project management skills</span></li>
      <li><span>Interpret an ambiguous multi-step scientific problem, break it down into its core modules</span></li>
      <li><span>Create a reproducible project &#8220;plan of attack&#8221;</span></li>
      <li><span>Identify pros/cons with your approach and plan &#8220;next-steps&#8221; to address them</span></li>
      <li><span>Decide where to innovate and where to leverage the existing solutions</span></li>
      <li><span>Communicate your work both to team members and clients</span></li>
    </ul>
  </div>
  <div class="ab rev">
    <p><strong>Keep in mind that this exercise is intentionally ambiguous &#8212; part of what we are evaluating is your ability to achieve a reasonable &#8220;week 1,&#8221; answer given incomplete information and insufficient time.</strong></p>
    <p>We recognize that these exercises can seem like a heavy lift and at times- depending on the specific problem, your work schedule etc- not possible to do properly in the time we have allotted you, which is by design. It's not about the hours you spend, it's about convincing us that you can thrive here and will make the team better. <strong>Every person at Proxima has gone through an exercise exactly like this and been voted to receive an offer from the Proxima team. This process is why, in our view, we have one of the top tech-bio teams in the world.</strong> The exercise is a platform for you to show us you belong here, how you do that is up to you &#8211; again there is no length or hours threshold.</p>
  </div>
</div>
<div class="dvd"></div>

<div id="questions"></div>
<section class="ch">
  <div class="cmr fa1" style="width:46%;">
    <svg viewBox="0 0 420 450" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="210" cy="220" rx="188" ry="202" fill="url(#gw)" opacity="0.42"/>
      <path d="M72,90 C110,46 192,38 246,68 C300,98 326,162 318,220 C310,278 270,320 212,336 C154,352 92,328 62,286 C32,244 38,176 56,132 C70,100 48,122 72,90Z" fill="url(#g1)" opacity="0.86"/>
      <path d="M215,55 C248,22 298,32 310,72 C322,112 296,152 262,157 C228,162 196,132 196,98 C196,68 198,72 215,55Z" fill="url(#g2)" opacity="0.82"/>
      <circle cx="285" cy="52" r="20" fill="url(#g3)" opacity="0.79"/><circle cx="312" cy="30" r="14" fill="url(#g2)" opacity="0.73"/>
      <circle cx="332" cy="56" r="10" fill="url(#g4)" opacity="0.67"/>
      <circle cx="332" cy="155" r="17" fill="url(#g2)" opacity="0.64"/>
      <path d="M54,276 C28,250 26,214 50,194 C74,174 110,186 126,212 C142,238 130,274 108,286 C88,298 70,292 54,276Z" fill="url(#g2)" opacity="0.7"/>
      <circle cx="34" cy="284" r="14" fill="url(#g3)" opacity="0.63"/>
      <circle cx="156" cy="108" r="4" fill="#e8f8ff" opacity="0.9"/>
    </svg>
  </div>
  <div class="ct" style="max-width:52%;"><div class="ctit rev">Additional<br/>Resources</div></div>
  <span class="cnum cnl">04</span>
<div style="position:absolute;bottom:1.5rem;right:2rem;z-index:10;">
  <img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:22px;width:auto;filter:brightness(0) invert(1);opacity:0.7;"/>
</div>
</section>

<div class="cs csw">
  <span class="sl rev">Intro Call &amp; Panel Interview: Questions we may ask</span>
  <div id="role-agnostic" class="qg rev">
    <div class="qtit">Role agnostic, generalized questions:</div>
    <ul class="ql">
      <li><span class="qn">01</span><span>Can you identify personal experiences or skills that you believe would uniquely contribute to novel areas like targeted protein degradation?</span></li>
      <li><span class="qn">02</span><span>Do you have any small-molecule project experience?</span></li>
      <li><span class="qn">03</span><span>What's your contribution in developing tools that were used in your projects?</span></li>
      <li><span class="qn">04</span><span>Have you worked on open source projects, either your own or within the community, as an external contributor or a core developer?</span></li>
      <li><span class="qn">05</span><span>Have you done any method development work or do you primarily leverage existing solutions?</span></li>
      <li><span class="qn">06</span><span>What do you prefer working on? Would you be more interested in client-facing projects or internal R&amp;D?</span></li>
      <li><span class="qn">07</span><span>Tell me about your journey from XYZ into computational biology or chemistry/software/machine learning?</span></li>
      <li><span class="qn">08</span><span>What do you like about your current job? What do you dislike?</span></li>
      <li><span class="qn">09</span><span>Why are you looking for a new job and what are you looking for in a new job?</span></li>
      <li><span class="qn">10</span><span>If you had all the resources in the world, what would you work on?</span></li>
      <li><span class="qn">11</span><span>In your opinion, what are the most exciting AI technologies in our problem space?</span></li>
      <li><span class="qn">12</span><span>What aspect of innovative drug discovery approaches, like induced proximity, do you find most intriguing or promising?</span></li>
      <li><span class="qn">13</span><span>What do you think will be the next major innovation within the induced proximity space?</span></li>
    </ul>
  </div>
  <div id="role-specific" class="qg rev">
    <div class="qtit">Role &amp; Team specific questions:</div>
    <ul class="ql">
      <li><span class="qn">01</span><span>What experience do you have collaborating with a big pharma partner?</span></li>
      <li><span class="qn">02</span><span>How did you solve outliners in your QSAR model?</span></li>
      <li><span class="qn">03</span><span>How do you measure the uncertainty of your ML models?</span></li>
      <li><span class="qn">04</span><span>What were some of the most difficult problems you faced when deciding how to design the initial XYZ architecture / concepts?</span></li>
      <li><span class="qn">05</span><span>What's your familiarity with: distributed computing/GKE, deployment stacks, CI/CD, workflow automation, Scientific Computing, data and compute infra?</span></li>
      <li><span class="qn">06</span><span>How about cheminformatics, do you have experience with rdkit?</span></li>
      <li><span class="qn">07</span><span>What experience in bioinformatics do you have, any experience working with structural data?</span></li>
      <li><span class="qn">08</span><span>What areas of molecular modeling and scientific computing would you say you're a domain expert in?</span></li>
      <li><span class="qn">09</span><span>Can you tell me about how you would approach visualizing chemical similarity for 1B molecules?</span></li>
      <li><span class="qn">10</span><span>Sometimes projects don't go according to the research plan in the contract. The partner wants to gain more confidence and do more work than we anticipated. But it would end up affecting the timeline and budget. What would you do as a Project Lead in this situation?</span></li>
    </ul>
  </div>
  <div id="soft-skills" class="qg rev">
    <div class="qtit">Soft Skills Questions:</div>
    <ul class="ql">
      <li><span class="qn">01</span><span>Can you share an example of a complex problem you faced in your previous role and how you went about solving it?</span></li>
      <li><span class="qn">02</span><span>Describe a situation where you had to make a decision under time constraints. How did you approach it, and what was the outcome?</span></li>
      <li><span class="qn">03</span><span>What do you do when projects fall behind schedule? Do you have an escalation framework?</span></li>
      <li><span class="qn">04</span><span>Tell us about a time when you had to quickly learn a new skill or adapt to a new work environment. What was your approach, and what did you learn from the experience?</span></li>
      <li><span class="qn">05</span><span>How do you stay updated on industry trends and incorporate new knowledge into your work?</span></li>
      <li><span class="qn">06</span><span>Provide an example of a successful collaboration experience. What role did you play, and how did it contribute to the team's success?</span></li>
      <li><span class="qn">07</span><span>Describe a situation where you had a disagreement with a team member. How did you handle it, and what was the resolution?</span></li>
      <li><span class="qn">08</span><span>Share an experience where you took the initiative to lead a project or drive a significant change. What were the challenges, and how did you overcome them?</span></li>
      <li><span class="qn">09</span><span>How do you motivate and inspire your team to achieve common goals?</span></li>
    </ul>
  </div>
</div>
<div class="dvd"></div>

<div id="science"></div>
<section class="ch">
  <div class="cml fa2" style="width:46%;">
    <svg viewBox="0 0 360 560" xmlns="http://www.w3.org/2000/svg" style="width:100%;overflow:visible">
      <ellipse cx="180" cy="280" rx="160" ry="250" fill="url(#gw)" opacity="0.4"/>
      <path d="M95,55 C130,18 200,14 238,48 C276,82 280,145 262,198 C244,251 196,272 166,308 C136,344 140,392 158,432 C176,472 198,492 182,520 C166,548 126,554 100,530 C74,506 70,462 78,415 C86,368 108,335 100,285 C92,235 58,200 62,152 C66,105 70,82 95,55Z" fill="url(#g1)" opacity="0.87"/>
      <path d="M182,25 C216,-8 260,4 270,42 C280,80 254,118 220,122 C186,126 156,98 158,66 C160,38 162,48 182,25Z" fill="url(#g2)" opacity="0.82"/>
      <path d="M246,215 C276,188 314,208 320,248 C326,288 298,322 264,324 C230,326 206,298 216,264 C223,240 228,232 246,215Z" fill="url(#g3)" opacity="0.74"/>
      <circle cx="248" cy="36" r="20" fill="url(#g3)" opacity="0.79"/><circle cx="272" cy="14" r="14" fill="url(#g2)" opacity="0.73"/>
      <circle cx="292" cy="40" r="10" fill="url(#g4)" opacity="0.67"/>
      <circle cx="315" cy="182" r="16" fill="url(#g2)" opacity="0.63"/>
      <path d="M138,518 C110,494 106,458 130,438 C154,418 188,430 200,456 C212,482 198,516 175,527 C155,537 152,534 138,518Z" fill="url(#g2)" opacity="0.66"/>
      <circle cx="116" cy="526" r="14" fill="url(#g3)" opacity="0.6"/>
      <circle cx="150" cy="105" r="4" fill="#e8f8ff" opacity="0.9"/>
    </svg>
  </div>
  <div class="ct ctr" style="margin-left:auto;max-width:52%;"><div class="ctit rev">Proxima<br/>Science</div></div>
  <span class="cnum cnr">05</span>
<div style="position:absolute;bottom:1.5rem;right:2rem;z-index:10;">
  <img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:22px;width:auto;filter:brightness(0) invert(1);opacity:0.7;"/>
</div>
</section>

<div class="cs">
  <span class="sl rev">Explore Further</span>
  <!-- VERIFIED LINKS — checked live April 2026 -->
  <div class="rg rev">
    <a href="https://proximabio.com/news" target="_blank" class="rlc">
      <span>News &amp; Events</span>
      <small>proximabio.com/news</small>
    </a>
    <a href="https://proximabio.com/team" target="_blank" class="rlc">
      <span>Our Team</span>
      <small>proximabio.com/team</small>
    </a>
    <a href="https://www.genaiindrugdiscovery.com/" target="_blank" class="rlc">
      <span>GenAI in Drug Discovery Tech Talk Series</span>
      <small>genaiindrugdiscovery.com</small>
    </a>
    <a href="https://proximabio.com/team" target="_blank" class="rlc">
      <span>Michael Bronstein &#8212; Chief Scientist in Residence</span>
      <small>proximabio.com/team</small>
    </a>
  </div>

  <span class="sl rev" style="margin-top:0.5rem;">Recommended Publications to read:</span>
  <!-- All publication URLs verified against PDF source -->
  <ul class="pubs rev">
    <li>
      <a href="https://www.mlsb.io/papers_2023/LatentDock_Protein-Protein_Docking_with_Latent_Diffusion.pdf" target="_blank">LatentDock: Protein-Protein Docking with Latent Diffusion</a>
      <span class="pn">www.mlsb.io/papers_2023/LatentDock_Protein-Protein_Docking_with_Latent_Diffusion.pdf</span>
    </li>
    <li>
      <a href="https://openreview.net/forum?id=S4zpk61r6G" target="_blank">openreview.net/forum?id=S4zpk61r6G</a>
    </li>
    <li>
      <a href="https://openreview.net/pdf?id=PQa3giMLZp" target="_blank">openreview.net/pdf?id=PQa3giMLZp</a>
    </li>
    <li>
      <a href="https://arxiv.org/abs/2306.08166" target="_blank">arxiv.org/abs/2306.08166</a>
    </li>
    <li>
      <a href="https://www.nature.com/articles/s41573-024-01128-9" target="_blank">King, Meyers &amp; Nomura (2025) &#8220;Induced proximity-based therapeutic modalities&#8221; Nat Rev Drug Discov</a>
      <span class="pn">Comprehensive review of induced proximity as a therapeutic modality</span>
    </li>
    <li>
      <a href="https://www.cell.com/cell/fulltext/S0092-8674(21)00030-X" target="_blank">Schreiber (2021) &#8220;The Rise of Molecular Glues&#8221; Cell</a>
      <span class="pn">Old, but foundational broad perspective on induced proximity as a modality</span>
    </li>
    <li>
      <a href="https://www.nature.com/articles/s41594-018-0064-8" target="_blank">O'Reilly &amp; Rappsilber (2018) &#8220;Cross-linking mass spectrometry: methods and applications&#8221; Nat Struct Mol Biol</a>
      <span class="pn">The experimental technique behind NeoLink &#8211; imagine this plus $100M in optimization and scaling&#8230;mixed with frontier ML</span>
    </li>
    <li>
      <a href="https://www.nature.com/articles/s41586-024-07487-w" target="_blank">Abramson et al. (2024) &#8220;Accurate structure prediction of biomolecular interactions with AlphaFold 3&#8221; Nature</a>
      <span class="pn">What public AI structural models can and can't do</span>
    </li>
  </ul>
</div>

<footer>
  <div class="fm">
    <svg viewBox="0 0 800 280" xmlns="http://www.w3.org/2000/svg" style="width:100%">
      <ellipse cx="400" cy="140" rx="370" ry="130" fill="url(#gw)" opacity="0.6"/>
      <path d="M145,55 C196,18 296,12 354,46 C412,80 430,148 406,202 C382,256 302,275 234,260 C166,245 112,192 108,138 C104,88 106,82 145,55Z" fill="url(#g1)" opacity="0.28"/>
      <circle cx="365" cy="40" r="26" fill="url(#g3)" opacity="0.26"/><circle cx="396" cy="16" r="18" fill="url(#g2)" opacity="0.2"/>
      <circle cx="535" cy="64" r="20" fill="url(#g2)" opacity="0.22"/>
    </svg>
  </div>
  <div class="fw" style="margin-bottom:1.5rem;"><img src="https://proximabio.com/icons/proxima_logo.svg" alt="Proxima" style="height:48px;width:auto;filter:brightness(0) invert(1);"/></div>
  <div class="fa">
    116 East 16th Street, 12th Floor<br/>New York, NY 10003<br/>
    <a href="https://proximabio.com" target="_blank">proximabio.com</a>
  </div>
</footer>

<script>
const canvas=document.getElementById('pcv'),ctx=canvas.getContext('2d');
let W,H,P=[];
function resize(){W=canvas.width=window.innerWidth;H=canvas.height=window.innerHeight;}
resize();window.addEventListener('resize',resize);
function Pt(){this.x=Math.random()*W;this.y=Math.random()*H;this.r=Math.random()*1.2+0.3;this.dx=(Math.random()-0.5)*0.18;this.dy=(Math.random()-0.5)*0.12;this.a=Math.random()*0.4+0.08;}
for(let i=0;i<75;i++)P.push(new Pt());
function draw(){
  ctx.clearRect(0,0,W,H);
  P.forEach(p=>{ctx.beginPath();ctx.arc(p.x,p.y,p.r,0,Math.PI*2);ctx.fillStyle=`rgba(77,184,255,${p.a})`;ctx.fill();p.x+=p.dx;p.y+=p.dy;if(p.x<0||p.x>W)p.dx*=-1;if(p.y<0||p.y>H)p.dy*=-1;});
  for(let i=0;i<P.length;i++)for(let j=i+1;j<P.length;j++){const dx=P[i].x-P[j].x,dy=P[i].y-P[j].y,d=Math.sqrt(dx*dx+dy*dy);if(d<110){ctx.beginPath();ctx.moveTo(P[i].x,P[i].y);ctx.lineTo(P[j].x,P[j].y);ctx.strokeStyle=`rgba(77,184,255,${0.05*(1-d/110)})`;ctx.lineWidth=0.5;ctx.stroke();}}
  requestAnimationFrame(draw);
}
draw();
const els=document.querySelectorAll('.rev');
const ob=new IntersectionObserver(entries=>{entries.forEach((e,i)=>{if(e.isIntersecting){setTimeout(()=>e.target.classList.add('vis'),i*55);ob.unobserve(e.target);}});},{threshold:0.08});
els.forEach(el=>ob.observe(el));
</script>
</body>
</html>
