<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thovaguh</title>
<style>
  :root {
    --bg: #0b0220;
    --card: #140838;
    --line: #2f1a66;
    --cyan: #8be9fd;
    --pink: #ff79c6;
    --text: #d6c8ff;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: radial-gradient(circle at 20% 0%, #2a1458 0%, var(--bg) 60%);
    color: var(--text);
    font-family: 'Courier New', monospace;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    padding: 40px 16px;
  }
  .container { width: 100%; max-width: 860px; }
  .banner {
    width: 100%;
    display: block;
    border-radius: 14px;
    border: 1px solid var(--line);
    box-shadow: 0 0 40px rgba(255, 121, 198, 0.2);
  }
  h1 {
    text-align: center;
    margin: 32px 0 8px;
    font-size: 2.2rem;
    background: linear-gradient(90deg, var(--cyan), var(--pink));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    letter-spacing: 4px;
  }
  .quote { text-align: center; font-style: italic; color: var(--pink); margin-bottom: 20px; }
  .about { text-align: center; line-height: 1.8; margin-bottom: 32px; }
  pre {
    background: var(--card);
    border: 1px solid var(--line);
    border-radius: 12px;
    padding: 22px;
    font-size: 0.95rem;
    line-height: 1.6;
    overflow-x: auto;
    margin-bottom: 28px;
  }
  .k { color: var(--cyan); }
  .s { color: var(--pink); }
  .p { color: #f8f8f2; }
  .badges { display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; margin-bottom: 28px; }
  .badge {
    padding: 8px 16px;
    border: 1px solid var(--line);
    border-radius: 8px;
    background: var(--card);
    color: var(--cyan);
    font-size: 0.9rem;
    transition: transform 0.2s, box-shadow 0.2s, color 0.2s;
  }
  .badge:hover {
    transform: translateY(-3px);
    color: var(--pink);
    box-shadow: 0 0 16px rgba(255, 121, 198, 0.4);
  }
  .footer {
    background: var(--card);
    border-left: 3px solid var(--pink);
    border-radius: 8px;
    padding: 16px 20px;
    font-size: 0.9rem;
    overflow-x: auto;
  }
</style>
</head>
<body>
  <div class="container">
    <img class="banner" src="banner.svg" alt="banner thovaguh">

    <h1>THOVAGUH</h1>
    <p class="quote">código limpo não é escrito por acaso, é construído com intenção.</p>
    <p class="about">
      Estudante de Ciência da Computação na FEMA, em Assis - SP.<br>
      Estagiário no laboratório de informática, cuidando de hardware, software e suporte.<br>
      Curioso por cibersegurança, hardware e por construir coisas do zero.
    </p>

<pre><span class="p">{</span>
  <span class="k">"nome"</span>: <span class="s">"Thovaguh"</span>,
  <span class="k">"curso"</span>: <span class="s">"Ciência da Computação"</span>,
  <span class="k">"faculdade"</span>: <span class="s">"FEMA"</span>,
  <span class="k">"localizacao"</span>: <span class="s">"Assis, SP - Brasil"</span>,
  <span class="k">"stack"</span>: [<span class="s">"Python"</span>, <span class="s">"C#"</span>, <span class="s">"C++"</span>, <span class="s">"PHP"</span>, <span class="s">"JavaScript"</span>],
  <span class="k">"ferramentas"</span>: [<span class="s">"Visual Studio"</span>, <span class="s">"VS Code"</span>, <span class="s">"Git"</span>],
  <span class="k">"interesses"</span>: [<span class="s">"Cibersegurança"</span>, <span class="s">"Hardware"</span>, <span class="s">"OpenGL"</span>],
  <span class="k">"status"</span>: <span class="s">"sempre aprendendo"</span>
<span class="p">}</span></pre>

    <div class="badges">
      <span class="badge">Python</span>
      <span class="badge">C#</span>
      <span class="badge">C++</span>
      <span class="badge">PHP</span>
      <span class="badge">JavaScript</span>
      <span class="badge">Git</span>
    </div>

    <div class="footer">
      <span class="k">System.out.println</span>(<span class="s">"Código limpo não é escrito por acaso, é construído com intenção."</span>);
    </div>
  </div>
</body>
</html>
