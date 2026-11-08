<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Luiz Gabriel – Segurança da Informação</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=DM+Sans:wght@400;500;700&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div id="bar"></div>
<div class="wrap">
<header class="top">
<b>Luiz Gabriel</b>
<nav aria-label="Principal"><a href="#sobre">Sobre</a><a href="#competencias">Competências</a><a href="#projetos">Projetos</a><a href="#terminal">Terminal</a><a href="#contato">Contato</a><button id="theme" type="button" aria-label="Alternar tema">Tema</button></nav>
</header>
</div>

<main>
<div class="hero">
<canvas id="net" aria-hidden="true"></canvas>
<div class="wrap">
<span class="status"><i></i>Disponível para novos projetos</span>
<h1 id="name" aria-label="Luiz Gabriel">Luiz Gabriel</h1>
<div class="role" id="role" aria-live="off"></div>
<p class="lead">Profissional de segurança da informação. Eu ataco sistemas para encontrar falhas, depois ajudo times a corrigi-las antes que alguém mal-intencionado chegue lá.</p>
<div class="cta"><a class="btn main" href="#projetos">Ver projetos</a><a class="btn" href="#terminal">Abrir terminal</a></div>
<p class="tip">Mova o mouse (ou toque) sobre o fundo e clique para criar novos nós na rede.</p>
</div>
</div>

<section id="sobre"><div class="wrap">
<h2>Sobre mim</h2>
<div class="about">
<div>
<p>Comecei em segurança por curiosidade: queria entender como os sistemas quebram. Hoje transformo essa curiosidade em relatórios claros que times de tecnologia conseguem corrigir.</p>
<p>Gosto de trabalhar perto de desenvolvedores e do negócio, explicando o risco em linguagem simples e priorizando o que realmente importa. Fora do trabalho, disputo CTFs e escrevo sobre o que aprendo.</p>
</div>
<div class="facts">
<div><strong data-n="4">0</strong><span>anos de experiência (exemplo)</span></div>
<div><strong data-n="32">0</strong><span>vulnerabilidades reportadas (exemplo)</span></div>
<div><strong data-n="12">0</strong><span>CTFs disputados (exemplo)</span></div>
</div>
</div>
</div></section>

<section id="competencias"><div class="wrap">
<h2>Competências</h2>
<div class="tabs" role="tablist" aria-label="Filtrar competências">
<button class="tab" role="tab" aria-selected="true" data-f="all">Todas</button>
<button class="tab" role="tab" aria-selected="false" data-f="off">Ofensiva</button>
<button class="tab" role="tab" aria-selected="false" data-f="def">Defensiva</button>
<button class="tab" role="tab" aria-selected="false" data-f="tool">Ferramentas</button>
</div>
<div class="skills" id="skills"></div>
</div></section>

<section id="projetos"><div class="wrap">
<h2>Projetos</h2>
<article class="proj"><button type="button" aria-expanded="false"><h3>Pentest em e-commerce</h3><span class="sev s-c">CVSS 9.1 · Crítico</span><span class="sum">Falha de controle de acesso expunha dados de clientes.</span></button>
<div class="more"><div><div class="in"><div><h4>Desafio</h4><p>Aplicação com milhões de acessos mensais e várias integrações com terceiros.</p></div><div><h4>O que fiz</h4><p>Mapeei a superfície de ataque, explorei uma falha de IDOR na API de pedidos e documentei a prova de conceito.</p></div><div><h4>Resultado</h4><p>Correção em 48 horas e plano de remediação priorizado para o time.</p></div></div><div class="chips"><span>Burp Suite</span><span>OWASP</span><span>Relatório executivo</span></div></div></div></article>
<article class="proj"><button type="button" aria-expanded="false"><h3>Laboratório de detecção</h3><span class="sev s-h">CVSS 7.4 · Alto</span><span class="sum">SIEM com regras que simulam ataques comuns.</span></button>
<div class="more"><div><div class="in"><div><h4>Desafio</h4><p>Medir quanto tempo um time leva para perceber um ataque real.</p></div><div><h4>O que fiz</h4><p>Montei um ambiente com Splunk, criei regras mapeadas no MITRE ATT&amp;CK e automatizei simulações em Python.</p></div><div><h4>Resultado</h4><p>Tempo médio de detecção caiu de 40 para 9 minutos nos testes.</p></div></div><div class="chips"><span>Splunk</span><span>MITRE ATT&amp;CK</span><span>Python</span></div></div></div></article>
<article class="proj"><button type="button" aria-expanded="false"><h3>Phishing simulado</h3><span class="sev s-m">CVSS 5.3 · Médio</span><span class="sum">Campanha com 300 colaboradores e treinamento guiado.</span></button>
<div class="more"><div><div class="in"><div><h4>Desafio</h4><p>Reduzir o risco humano sem punir ninguém.</p></div><div><h4>O que fiz</h4><p>Criei três e-mails de teste, medi cliques e desenhei um treinamento baseado nos erros mais comuns.</p></div><div><h4>Resultado</h4><p>A taxa de cliques caiu 62% na segunda rodada.</p></div></div><div class="chips"><span>Engenharia social</span><span>Treinamento</span><span>LGPD</span></div></div></div></article>
</div></section>

<section id="terminal"><div class="wrap">
<h2>Converse com meu terminal</h2>
<div class="term">
<div class="tbar"><i></i><i></i><i></i></div>
<div id="out" role="log" aria-live="polite"></div>
<div class="prompt"><label for="cmd">luiz@portfolio:~$</label><input id="cmd" autocomplete="off" autocapitalize="off" spellcheck="false" aria-label="Digite um comando"></div>
</div>
<div class="quick" id="quick"></div>
</div></section>

<section id="contato"><div class="wrap contact">
<h2>Tem um sistema para proteger?</h2>
<a class="mail" id="mail" href="mailto:luizgabriellrb@gmail.com">luizgabriellrb@gmail.com</a>
<div class="links"><button class="btn main" id="copy" type="button">Copiar e-mail</button><a class="btn" href="#">LinkedIn</a><a class="btn" href="#">GitHub</a><a class="btn" href="#">Hack The Box</a></div>
</div></section>
</main>
<div class="wrap"><footer>© 2026 Luiz Gabriel. Todos os direitos reservados.</footer></div>
<div id="toast" role="status"></div>

<script src="script.js"></script>
</body>
</html>
