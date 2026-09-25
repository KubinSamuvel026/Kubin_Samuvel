<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Kubin Samuvel — Software Developer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,600;9..144,700&family=Space+Grotesk:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#f4f2ee;
    --bg-alt:#ebe7df;
    --ink:#1c1b19;
    --ink-soft:#59564f;
    --line:#d8d3c8;
    --accent:#2f5233;
    --accent-soft:#e4ecdf;
    --card:#ffffff;
    --mono: 'JetBrains Mono', monospace;
    --display: 'Fraunces', serif;
    --body: 'Space Grotesk', sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--bg);
    color:var(--ink);
    font-family:var(--body);
    line-height:1.5;
    overflow-x:hidden;
  }
  section{padding:120px 8vw; position:relative;}
  h1,h2,h3{font-family:var(--display); font-weight:600; letter-spacing:-0.01em;}
  a{color:inherit;}
  .eyebrow{font-family:var(--mono); font-size:13px; color:var(--accent); margin-bottom:14px; display:block;}
  .wrap{max-width:1080px; margin:0 auto;}

  /* ---- robot overlay ---- */
  #robot-stage{
    position:fixed;
    left:0; top:0;
    width:min(30vw, 340px);
    height:100vh;
    z-index:40;
    pointer-events:none;
  }
  #robot-canvas{width:100%; height:100%; pointer-events:auto; cursor:pointer;}
  #robot-hint{
    position:fixed;
    left:24px; bottom:28px;
    font-family:var(--mono); font-size:12px; color:var(--ink-soft);
    background:var(--card); border:1px solid var(--line); border-radius:20px;
    padding:8px 14px; z-index:41; transition:opacity .6s ease;
  }
  #robot-hint.hidden{opacity:0; pointer-events:none;}

  /* ---- hero ---- */
  #hero{
    min-height:100vh;
    display:flex; align-items:flex-end;
    padding-left:calc(30vw + 6vw);
    padding-bottom:100px;
    background:
      linear-gradient(180deg, rgba(244,242,238,0) 40%, var(--bg) 96%),
      url('assets/hero.jpg') center/cover no-repeat;
  }
  #hero .inner{max-width:640px;}
  #hero h1{font-size:clamp(40px,6vw,76px); line-height:1.02; color:#fdfcf9;}
  #hero p.role{
    font-family:var(--mono); font-size:15px; color:#e9e6de;
    margin-top:18px; letter-spacing:0.02em;
  }
  #hero .scroll-cue{
    position:absolute; bottom:36px; left:calc(30vw + 6vw);
    font-family:var(--mono); font-size:12px; color:var(--ink-soft);
  }

  /* ---- about ---- */
  #about{padding-left:calc(30vw + 8vw);}
  #about .grid{display:grid; grid-template-columns:1.1fr 0.9fr; gap:60px;}
  #about h2{font-size:clamp(28px,3vw,40px);}
  #about p{color:var(--ink-soft); font-size:17px; margin-top:20px; max-width:52ch;}
  .facts{display:flex; flex-direction:column; gap:0; border-top:1px solid var(--line);}
  .fact{display:flex; justify-content:space-between; padding:16px 0; border-bottom:1px solid var(--line); font-size:15px;}
  .fact span:first-child{color:var(--ink-soft); font-family:var(--mono); font-size:13px;}

  /* ---- desk showcase ---- */
  #showcase{background:var(--bg-alt); padding-left:calc(30vw + 8vw);}
  #showcase .head{max-width:640px; margin-bottom:40px;}
  #desk-frame{
    width:100%; height:520px; border-radius:6px; overflow:hidden;
    background:linear-gradient(160deg,#e8e4da,#d9d4c6);
    border:1px solid var(--line);
  }
  #desk-canvas{width:100%; height:100%;}
  #showcase .caption{font-family:var(--mono); font-size:12px; color:var(--ink-soft); margin-top:14px;}

  /* ---- github activity ---- */
  #activity{padding-left:calc(30vw + 8vw);}
  #activity .head{max-width:640px; margin-bottom:44px;}
  .stat-row{display:flex; flex-wrap:wrap; gap:24px;}
  .stat-row img{border-radius:6px; flex:1 1 320px; max-width:420px; border:1px solid var(--line);}
  .snake{margin-top:24px; border-radius:6px; overflow:hidden; border:1px solid var(--line);}
  .snake img{width:100%; display:block;}

  /* ---- projects ---- */
  #projects{background:var(--bg-alt); padding-left:calc(30vw + 8vw);}
  #projects .head{max-width:640px; margin-bottom:44px;}
  .proj-list{border-top:1px solid var(--line);}
  .proj{
    display:grid; grid-template-columns:60px 1fr auto; gap:24px; align-items:baseline;
    padding:28px 0; border-bottom:1px solid var(--line);
  }
  .proj .n{font-family:var(--mono); color:var(--accent); font-size:14px;}
  .proj h3{font-size:22px;}
  .proj p{color:var(--ink-soft); font-size:15px; margin-top:6px; max-width:56ch;}
  .proj .tags{font-family:var(--mono); font-size:12px; color:var(--ink-soft);}

  /* ---- contact ---- */
  #contact{padding-left:calc(30vw + 8vw); min-height:70vh; display:flex; align-items:center;}
  #contact h2{font-size:clamp(32px,5vw,58px); max-width:14ch;}
  #contact .links{display:flex; gap:28px; margin-top:36px; flex-wrap:wrap;}
  #contact .links a{
    font-family:var(--mono); font-size:14px; border-bottom:1px solid var(--ink);
    padding-bottom:3px;
  }
  footer{padding:28px 8vw; font-family:var(--mono); font-size:12px; color:var(--ink-soft); padding-left:calc(30vw + 8vw);}

  @media (max-width: 860px){
    #robot-stage{width:120px; height:120px; top:auto; bottom:100px;}
    #about, #showcase, #activity, #projects, #contact, footer{padding-left:8vw;}
    #hero{padding-left:8vw;}
    #hero .scroll-cue{left:8vw;}
    #about .grid{grid-template-columns:1fr;}
    .proj{grid-template-columns:32px 1fr; grid-template-areas:"n h" ". p" ". t";}
  }
</style>
</head>
<body>

<div id="robot-stage"><canvas id="robot-canvas"></canvas></div>
<div id="robot-hint">click the robot →</div>

<section id="hero">
  <div class="inner">
    <span class="eyebrow">score. user_inspiration = (done)</span>
    <h1>Kubin Samuvel</h1>
    <p class="role">Software Developer — building things with code, always learning.</p>
  </div>
  <div class="scroll-cue">scroll ↓</div>
</section>

<section id="about">
  <div class="grid">
    <div>
      <span class="eyebrow">about</span>
      <h2>Developer, problem solver.</h2>
      <p>I build software across the stack — from small tools that fix a real annoyance to full products that need someone to own the whole thing. I like the parts of the job that look like puzzles: an architecture that doesn't fit yet, a bug that hides, a UI that isn't quite right until it is.</p>
      <p>Currently sharpening skills in JavaScript, React, and Python, with a growing interest in bringing 3D and interactive work into everyday web projects.</p>
    </div>
    <div class="facts">
      <div class="fact"><span>based</span><span>—</span></div>
      <div class="fact"><span>stack</span><span>JS · React · Node · Python · Java</span></div>
      <div class="fact"><span>tools</span><span>Git · MySQL · Figma · VS Code</span></div>
      <div class="fact"><span>focus</span><span>full-stack & interactive web</span></div>
    </div>
  </div>
</section>

<section id="showcase">
  <div class="head">
    <span class="eyebrow">the setup</span>
    <h2>Where the work happens.</h2>
  </div>
  <div id="desk-frame"><canvas id="desk-canvas"></canvas></div>
  <p class="caption">drag to orbit · scroll to zoom</p>
</section>

<section id="activity">
  <div class="head">
    <span class="eyebrow">git activity</span>
    <h2>What I've been shipping.</h2>
  </div>
  <div class="stat-row">
    <img src="https://github-readme-stats.vercel.app/api?username=KubinSamuvel026&show_icons=true&theme=default&hide_border=true&bg_color=ffffff&title_color=2f5233&icon_color=59564f&text_color=1c1b19" alt="github stats" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KubinSamuvel026&layout=compact&theme=default&hide_border=true&bg_color=ffffff&title_color=2f5233&text_color=1c1b19" alt="top languages" />
  </div>
  <div class="snake">
    <img src="https://raw.githubusercontent.com/KubinSamuvel026/KubinSamuvel026/output/github-contribution-grid-snake-dark.svg" alt="contribution snake" />
  </div>
</section>

<section id="projects">
  <div class="head">
    <span class="eyebrow">selected work</span>
    <h2>Projects.</h2>
  </div>
  <div class="proj-list">
    <div class="proj">
      <span class="n">01</span>
      <div><h3>Project One</h3><p>A short description of what this project does and the problem it solves.</p></div>
      <span class="tags">React · Node</span>
    </div>
    <div class="proj">
      <span class="n">02</span>
      <div><h3>Project Two</h3><p>A short description of what this project does and the problem it solves.</p></div>
      <span class="tags">Python</span>
    </div>
    <div class="proj">
      <span class="n">03</span>
      <div><h3>Project Three</h3><p>A short description of what this project does and the problem it solves.</p></div>
      <span class="tags">Java · MySQL</span>
    </div>
  </div>
</section>

<section id="contact">
  <div>
    <span class="eyebrow">get in touch</span>
    <h2>Let's build something.</h2>
    <div class="links">
      <a href="mailto:you@example.com">email</a>
      <a href="https://github.com/KubinSamuvel026" target="_blank">github</a>
      <a href="#" target="_blank">linkedin</a>
    </div>
  </div>
</section>

<footer>© 2026 Kubin Samuvel — built with code, coffee, and a little three.js</footer>

<script src="https://unpkg.com/three@0.160.0/build/three.min.js"></script>
<script src="https://unpkg.com/three@0.160.0/examples/js/loaders/GLTFLoader.js"></script>
<script src="https://unpkg.com/three@0.160.0/examples/js/controls/OrbitControls.js"></script>
<script>
/* ---------------- ROBOT (fixed, click-to-follow) ---------------- */
(function(){
  const canvas = document.getElementById('robot-canvas');
  const stage = document.getElementById('robot-stage');
  const hint = document.getElementById('robot-hint');
  const renderer = new THREE.WebGLRenderer({canvas, alpha:true, antialias:true});
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(35, 1, 0.1, 100);
  camera.position.set(0, 1.2, 5);

  const hemi = new THREE.HemisphereLight(0xffffff, 0xcfc9b8, 1.1);
  scene.add(hemi);
  const dir = new THREE.DirectionalLight(0xffffff, 1.2);
  dir.position.set(3,5,4);
  scene.add(dir);

  let robot = null;
  let following = false;
  const target = new THREE.Vector2(0,0);
  const current = new THREE.Vector2(0,0);

  function resize(){
    const w = stage.clientWidth, h = stage.clientHeight;
    renderer.setSize(w, h, false);
    camera.aspect = w/h;
    camera.updateProjectionMatrix();
  }
  window.addEventListener('resize', resize);

  const loader = new THREE.GLTFLoader();
  loader.load('assets/robot.glb', (gltf)=>{
    robot = gltf.scene;
    const box = new THREE.Box3().setFromObject(robot);
    const size = box.getSize(new THREE.Vector3());
    const scale = 2.4 / Math.max(size.x,size.y,size.z);
    robot.scale.setScalar(scale);
    const center = box.getCenter(new THREE.Vector3()).multiplyScalar(scale);
    robot.position.sub(center);
    robot.position.y -= 0.2;
    scene.add(robot);
    resize();
  }, undefined, (err)=>console.warn('robot load error', err));

  canvas.addEventListener('click', ()=>{
    following = !following;
    hint.classList.toggle('hidden', following);
    hint.textContent = following ? 'click to release' : 'click the robot →';
  });

  window.addEventListener('mousemove', (e)=>{
    if(!following) return;
    target.x = (e.clientX / window.innerWidth) * 2 - 1;
    target.y = -(e.clientY / window.innerHeight) * 2 + 1;
  });

  let floatT = 0;
  function animate(){
    requestAnimationFrame(animate);
    floatT += 0.015;
    if(robot){
      current.x += (target.x - current.x) * 0.06;
      current.y += (target.y - current.y) * 0.06;
      if(following){
        robot.rotation.y = current.x * 0.9;
        robot.rotation.x = -current.y * 0.25;
        robot.position.x = current.x * 0.5;
      } else {
        robot.rotation.y = Math.sin(floatT*0.6) * 0.25;
        robot.position.x = 0;
      }
      robot.position.y = -0.2 + Math.sin(floatT) * 0.08;
    }
    renderer.render(scene, camera);
  }
  resize();
  animate();
})();

/* ---------------- DESK SHOWCASE (orbit) ---------------- */
(function(){
  const canvas = document.getElementById('desk-canvas');
  const frame = document.getElementById('desk-frame');
  const renderer = new THREE.WebGLRenderer({canvas, antialias:true, alpha:true});
  renderer.setClearColor(0x000000, 0);
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(40, 1, 0.1, 200);
  camera.position.set(3.5, 2.5, 5);

  const hemi = new THREE.HemisphereLight(0xffffff, 0xd9d4c6, 1.2);
  scene.add(hemi);
  const dir = new THREE.DirectionalLight(0xffffff, 1.1);
  dir.position.set(4,6,3);
  scene.add(dir);

  const controls = new THREE.OrbitControls(camera, renderer.domElement);
  controls.enableDamping = true;
  controls.dampingFactor = 0.08;
  controls.minDistance = 2;
  controls.maxDistance = 12;
  controls.target.set(0,0.5,0);

  function resize(){
    const w = frame.clientWidth, h = frame.clientHeight;
    renderer.setSize(w,h,false);
    camera.aspect = w/h;
    camera.updateProjectionMatrix();
  }
  window.addEventListener('resize', resize);

  const loader = new THREE.GLTFLoader();
  loader.load('assets/desk.glb', (gltf)=>{
    const model = gltf.scene;
    const box = new THREE.Box3().setFromObject(model);
    const size = box.getSize(new THREE.Vector3());
    const scale = 4 / Math.max(size.x,size.y,size.z);
    model.scale.setScalar(scale);
    const center = box.getCenter(new THREE.Vector3()).multiplyScalar(scale);
    model.position.sub(center);
    scene.add(model);
    resize();
  }, undefined, (err)=>console.warn('desk load error', err));

  function animate(){
    requestAnimationFrame(animate);
    controls.update();
    renderer.render(scene, camera);
  }
  resize();
  animate();
})();
</script>
</body>
</html>
