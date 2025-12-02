# Diogo_Teixeira-
<h1 align="center">👋 Olá, eu sou o Diogo!</h1>

<p align="center">🚗 Motorista Particular | 💻 Técnico em Informática | 🛠️ Manutenção e Suporte</p>

---

## 🚀 Sobre mim

- Trabalho como **motorista particular** com foco em conforto e segurança  
- Atuo também com **manutenção de computadores, formatação e otimização de sistemas**  
- Estudante de **Análise e Desenvolvimento de Sistemas**  
- Apaixonado por tecnologia e aprendizado contínuo  

---

## 🛠️ Habilidades

### 🖥️ Tecnologia / Informática
- Manutenção de computadores  
- Limpeza e troca de peças  
- Formatação  
- Remoção de vírus  
- Upgrade de hardware  
- Instalação de programas  
- Redes e configuração  
- Suporte técnico  
- Desenvolvimento de sites e sistemas  

---

## 🌐 Conecte-se comigo:

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhyogoteixeira33@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diogo-teixeira-195211155/) 

---

## 🔧 Tecnologias que uso
<div>
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)

</div>


---

## 📊 Estatísticas do GitHub

<div align="center">
  
![Diogo GitHub Stats](https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&theme=dracula)
  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&theme=dracula)

</div>

---

## 🏁 Obrigado pela visita!




---

## 🌐 Conecte-se comigo:

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEUEMAILAQUI)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEULINKEDIN)

---

## 📊 Minhas Estatísticas:

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SEUUSUARIO&show_icons=true&theme=tokyonight&rank_icon=github)

![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SEUUSUARIO&layout=compact&theme=tokyonight)

</div>

---

## 🐍 Contribuições
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Jogo da Cobrinha — Diogo</title>
  <style>
    :root{
      --bg:#0f1724;
      --panel:#0b1220;
      --accent:#22c55e;
      --muted:#94a3b8;
      --danger:#ef4444;
      --glass: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    html,body{
      height:100%;
      margin:0;
      font-family:Inter,Segoe UI,Roboto,Arial, sans-serif;
      background:linear-gradient(180deg,#071021 0%, #0f1724 100%);
      color:#e6eef8;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .wrap{
      width:min(920px,96vw);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:12px;
      padding:20px;
      box-shadow: 0 8px 30px rgba(2,6,23,0.7);
      display:grid;
      grid-template-columns: 420px 1fr;
      gap:18px;
      align-items:start;
    }

    .card{
      background:var(--panel);
      border-radius:10px;
      padding:14px;
      border:1px solid rgba(255,255,255,0.03);
    }

    h1{margin:0 0 8px 0;font-size:18px}
    p.muted{color:var(--muted);margin:0 0 12px 0;font-size:13px}

    /* canvas area */
    .game-area{
      display:flex;
      flex-direction:column;
      align-items:center;
      gap:12px;
    }

    canvas{
      background:linear-gradient(180deg,#071025,#081227);
      border-radius:8px;
      width:100%;
      max-width:400px;
      height:auto;
      box-shadow: inset 0 2px 8px rgba(0,0,0,0.6), 0 6px 18px rgba(2,6,23,0.6);
    }

    .info{
      display:flex;
      gap:10px;
      width:100%;
      justify-content:space-between;
      align-items:center;
    }

    .score{
      display:flex;
      gap:8px;
      align-items:center;
    }
    .score .pill{
      background:var(--glass);
      padding:6px 10px;
      border-radius:999px;
      font-weight:600;
      color:var(--accent);
    }

    .controls{
      display:flex;
      gap:8px;
    }
    button.btn{
      background:transparent;
      color:var(--muted);
      border:1px solid rgba(255,255,255,0.03);
      padding:8px 10px;
      border-radius:8px;
      cursor:pointer;
      font-weight:600;
    }
    button.btn.primary{
      background:var(--accent);
      color:#04201a;
      border:none;
    }

    /* right column - instructions & highscore */
    .right{
      display:flex;
      flex-direction:column;
      gap:12px;
    }
    .kbd{
      display:inline-block;
      padding:6px 8px;
      border-radius:6px;
      background:rgba(255,255,255,0.03);
      border:1px solid rgba(255,255,255,0.02);
      color:var(--muted);
      font-size:13px;
      font-weight:600;
    }

    .mobile-controls{
      display:none;
      gap:8px;
      justify-content:center;
      margin-top:6px;
    }
    .mobile-controls button{
      width:56px;height:56px;border-radius:10px;border:none;background:rgba(255,255,255,0.03);
      color:var(--muted);font-weight:700;font-size:18px;box-shadow: 0 6px 16px rgba(0,0,0,0.4);
    }

    .overlay{
      position:fixed;
      left:0;right:0;top:0;bottom:0;
      display:flex;
      align-items:center;
      justify-content:center;
      z-index:40;
      pointer-events:none;
    }
    .overlay .panel{
      pointer-events:auto;
      background:linear-gradient(180deg, rgba(0,0,0,0.6), rgba(0,0,0,0.5));
      padding:22px;
      border-radius:12px;
      text-align:center;
      border:1px solid rgba(255,255,255,0.04);
      min-width:260px;
    }
    .overlay h2{margin:0 0 8px 0}
    .small{font-size:13px;color:var(--muted)}

    footer.small{font-size:12px;color:var(--muted);margin-top:8px;text-align:center}

    @media (max-width:880px){
      .wrap{grid-template-columns: 1fr; padding:12px}
      .right{order:2}
      .game-area{order:1}
      .mobile-controls{display:flex}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card game-area">
      <h1>🐍 Jogo da Cobrinha</h1>
      <p class="muted">Use as setas / WASD. Para celular, use os botões. Cole no GitHub e publique com Pages.</p>

      <canvas id="board" width="420" height="420"></canvas>

      <div class="info" style="width:100%">
        <div class="score">
          <div class="pill" id="score">Score: 0</div>
          <div class="pill" id="level">Velocidade: 6</div>
        </div>
        <div class="controls">
          <button class="btn" id="pauseBtn">Pausar</button>
          <button class="btn primary" id="restartBtn">Reiniciar</button>
        </div>
      </div>

      <div class="mobile-controls" id="mobileControls">
        <div style="display:flex;flex-direction:column;gap:8px">
          <button id="upBtn">↑</button>
          <div style="display:flex;gap:8px;justify-content:center">
            <button id="leftBtn">←</button>
            <button id="downBtn">↓</button>
            <button id="rightBtn">→</button>
          </div>
        </div>
      </div>

      <footer class="small">Autor: Diogo — Código aberto • Salve seu progresso no LocalStorage</footer>
    </div>

    <div class="right">
      <div class="card">
        <h1>Como Jogar</h1>
        <p class="muted">Movimente a cobrinha para comer a comida (círculo). A cada comida seu tamanho aumenta. Evite bater nas paredes ou na própria cobrinha.</p>

        <p><span class="kbd">↑ ↓ ← →</span> ou <span class="kbd">W A S D</span></p>
        <p class="small">Pausar: botão <strong>Pausar</strong>. Reiniciar: <strong>Reiniciar</strong>.</p>
      </div>

      <div class="card">
        <h1>Recorde</h1>
        <p class="muted">Recorde salvo localmente (no seu navegador).</p>
        <div style="display:flex;gap:10px;align-items:center">
          <div class="kbd" id="best">Melhor: 0</div>
          <button class="btn" id="clearBtn">Limpar recorde</button>
        </div>
      </div>

      <div class="card">
        <h1>Publicar no GitHub</h1>
        <p class="muted" style="margin-bottom:8px">Para publicar: crie um repositório no GitHub, envie este arquivo `index.html` e habilite <strong>GitHub Pages</strong> na branch <code>main</code>.</p>
        <ol class="small" style="margin-left:14px">
          <li>Crie repositório (ex: <code>snake-game</code>).</li>
          <li>Adicione `index.html` e faça commit/push.</li>
          <li>Vá em Settings → Pages → escolha branch <code>main</code> e root → Save.</li>
          <li>Após alguns segundos seu jogo estará em: <code>https://SEUUSUARIO.github.io/snake-game/</code></li>
        </ol>
      </div>
    </div>
  </div>

  <div class="overlay" id="overlay" style="display:none">
    <div class="panel">
      <h2 id="ovTitle">Game Over</h2>
      <p id="ovMsg" class="small">Score final: 0</p>
      <div style="margin-top:12px;display:flex;gap:8px;justify-content:center">
        <button class="btn" id="ovClose">Fechar</button>
        <button class="btn primary" id="ovRestart">Jogar novamente</button>
      </div>
    </div>
  </div>

  <script>
    // --- Configurações ---
    const canvas = document.getElementById('board');
    const ctx = canvas.getContext('2d');
    const CELL_COUNT = 21; // grade 21x21
    const CELL_SIZE = canvas.width / CELL_COUNT; // 420 / 21 = 20
    const initialSpeed = 6; // updates por segundo

    // elementos UI
    const scoreEl = document.getElementById('score');
    const levelEl = document.getElementById('level');
    const pauseBtn = document.getElementById('pauseBtn');
    const restartBtn = document.getElementById('restartBtn');
    const overlay = document.getElementById('overlay');
    const ovTitle = document.getElementById('ovTitle');
    const ovMsg = document.getElementById('ovMsg');
    const ovClose = document.getElementById('ovClose');
    const ovRestart = document.getElementById('ovRestart');
    const bestEl = document.getElementById('best');
    const clearBtn = document.getElementById('clearBtn');

    // mobile
    document.getElementById('upBtn').addEventListener('click', ()=>setDirection(0,-1));
    document.getElementById('downBtn').addEventListener('click', ()=>setDirection(0,1));
    document.getElementById('leftBtn').addEventListener('click', ()=>setDirection(-1,0));
    document.getElementById('rightBtn').addEventListener('click', ()=>setDirection(1,0));

    // estado do jogo
    let snake = [];
    let dir = {x:1,y:0}; // direção atual
    let nextDir = {x:1,y:0}; // buffer para evitar virar 180°
    let food = null;
    let score = 0;
    let speed = initialSpeed;
    let running = true;
    let gameInterval = null;
    let best = parseInt(localStorage.getItem('snake_best') || '0', 10);

    bestEl.textContent = 'Melhor: ' + best;

    // inicializa
    function resetGame(){
      snake = [
        {x:10, y:10},
        {x:9, y:10},
        {x:8, y:10}
      ];
      dir = {x:1,y:0};
      nextDir = {x:1,y:0};
      placeFood();
      score = 0;
      speed = initialSpeed;
      running = true;
      updateUI();
      hideOverlay();
      startLoop();
    }

    function placeFood(){
      while(true){
        const fx = Math.floor(Math.random()*CELL_COUNT);
        const fy = Math.floor(Math.random()*CELL_COUNT);
        if(!snake.some(s=>s.x===fx && s.y===fy)){
          food = {x:fx,y:fy};
          break;
        }
      }
    }

    function updateUI(){
      scoreEl.textContent = 'Score: ' + score;
      levelEl.textContent = 'Velocidade: ' + speed;
    }

    // lógica do passo do jogo
    function step(){
      // aplicar direção pendente (evita 180 graus)
      if((nextDir.x !== -dir.x || nextDir.y !== -dir.y)){
        dir = {...nextDir};
      }

      const head = {x: snake[0].x + dir.x, y: snake[0].y + dir.y};

      // colisão com paredes --> game over
      if(head.x < 0 || head.x >= CELL_COUNT || head.y < 0 || head.y >= CELL_COUNT){
        return gameOver();
      }

      // colisão com o próprio corpo?
      if(snake.some(s => s.x === head.x && s.y === head.y)){
        return gameOver();
      }

      snake.unshift(head);

      // comer a comida?
      if(head.x === food.x && head.y === food.y){
        score += 1;
        // aumenta velocidade gradualmente (a cada 5 pontos)
        if(score % 5 === 0){
          speed = Math.min(18, speed + 1);
          restartLoop();
        }
        placeFood();
      } else {
        snake.pop();
      }

      draw();
      updateUI();
    }

    // desenho
    function draw(){
      // fundo
      ctx.clearRect(0,0,canvas.width,canvas.height);

      // grid sutil
      ctx.fillStyle = '#071224';
      ctx.fillRect(0,0,canvas.width,canvas.height);

      // comida
      drawCell(food.x, food.y, '#ffb86b', true, 0.5);

      // cobrinha
      for(let i=0;i<snake.length;i++){
        const s = snake[i];
        if(i===0) drawCell(s.x, s.y, '#22c55e', true); // cabeça
        else drawCell(s.x, s.y, '#16a34a', false);
      }
    }

    function drawCell(cx, cy, color, circular=false, alpha=1){
      const x = cx * CELL_SIZE;
      const y = cy * CELL_SIZE;
      ctx.globalAlpha = alpha;
      // forma com cantos arredondados
      if(circular){
        ctx.beginPath();
        const cxpx = x + CELL_SIZE/2;
        const cypx = y + CELL_SIZE/2;
        ctx.fillStyle = color;
        ctx.arc(cxpx, cypx, CELL_SIZE*0.38, 0, Math.PI*2);
        ctx.fill();
      } else {
        const r = CELL_SIZE*0.18;
        roundRect(ctx, x+1, y+1, CELL_SIZE-2, CELL_SIZE-2, r);
        ctx.fillStyle = color;
        ctx.fill();
      }
      ctx.globalAlpha = 1;
    }

    function roundRect(ctx, x, y, w, h, r){
      ctx.beginPath();
      ctx.moveTo(x+r, y);
      ctx.arcTo(x+w, y, x+w, y+h, r);
      ctx.arcTo(x+w, y+h, x, y+h, r);
      ctx.arcTo(x, y+h, x, y, r);
      ctx.arcTo(x, y, x+w, y, r);
      ctx.closePath();
    }

    // game loop intervalo controlado por speed (updates por segundo)
    function startLoop(){
      if(gameInterval) clearInterval(gameInterval);
      const ms = 1000 / speed;
      gameInterval = setInterval(step, ms);
    }
    function restartLoop(){
      startLoop();
    }
    function stopLoop(){ if(gameInterval) clearInterval(gameInterval); gameInterval = null; }

    // game over
    function gameOver(){
      running = false;
      stopLoop();
      ovTitle.textContent = 'Game Over';
      ovMsg.textContent = 'Score final: ' + score;
      overlay.style.display = 'flex';
      // salvar recorde
      if(score > best){
        best = score;
        localStorage.setItem('snake_best', String(best));
        bestEl.textContent = 'Melhor: ' + best;
      }
    }
    function hideOverlay(){ overlay.style.display = 'none' }

    // entradas teclado
    window.addEventListener('keydown', (e)=>{
      if(['ArrowUp','ArrowDown','ArrowLeft','ArrowRight','w','a','s','d','W','A','S','D'].includes(e.key)){
        e.preventDefault();
      }
      switch(e.key){
        case 'ArrowUp': case 'w': case 'W': setDirection(0,-1); break;
        case 'ArrowDown': case 's': case 'S': setDirection(0,1); break;
        case 'ArrowLeft': case 'a': case 'A': setDirection(-1,0); break;
        case 'ArrowRight': case 'd': case 'D': setDirection(1,0); break;
        case ' ': togglePause(); break;
        case 'r': resetGame(); break;
      }
    });

    function setDirection(x,y){
      // previne 180 graus: só aceita se não for exatamente inverso
      if(x === -dir.x && y === -dir.y) return;
      nextDir = {x,y};
    }

    // botões UI
    pauseBtn.addEventListener('click', togglePause);
    restartBtn.addEventListener('click', resetGame);
    ovClose.addEventListener('click', ()=>{ overlay.style.display='none'; });
    ovRestart.addEventListener('click', ()=>{ overlay.style.display='none'; resetGame(); });
    clearBtn.addEventListener('click', ()=>{
      localStorage.removeItem('snake_best');
      best = 0;
      bestEl.textContent = 'Melhor: 0';
    });

    function togglePause(){
      if(running){
        running = false;
        stopLoop();
        pauseBtn.textContent = 'Retomar';
      } else {
        running = true;
        startLoop();
        pauseBtn.textContent = 'Pausar';
      }
    }

    // iniciar
    resetGame();

    // responsividade visual (redesenha em resize)
    window.addEventListener('resize', draw);
  </script>
</body>
</html>


---

## 📌 Pinned (Projetos Destaque)

<a href="https://github.com/SEUUSUARIO/projeto1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SEUUSUARIO&repo=projeto1&theme=tokyonight" />
</a>

<a href="https://github.com/SEUUSUARIO/projeto2">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SEUUSUARIO&repo=projeto2&theme=tokyonight" />
</a>

<a href="https://github.com/SEUUSUARIO/projeto3">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SEUUSUARIO&repo=projeto3&theme=tokyonight" />
</a>

<a href="https://github.com/SEUUSUARIO/projeto4">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SEUUSUARIO&repo=projeto4&theme=tokyonight" />
</a>

---

## 🟩 Contribuições no último ano

(Esse gráfico aparece automaticamente no seu perfil do GitHub.)

---
