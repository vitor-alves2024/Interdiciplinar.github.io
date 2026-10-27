<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#102b46">
  <meta name="description" content="Carteira Eleitoral Digital — um projeto interdisciplinar do IFPR para ajudar o eleitor a pesquisar, organizar e consultar informações públicas sobre candidaturas.">
  <title>Carteira Eleitoral Digital | Projeto Interdisciplinar IFPR</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <nav class="nav container" aria-label="Navegação principal">
      <a class="brand" href="#inicio" aria-label="Carteira Eleitoral Digital — início">
        <span class="brand-mark" aria-hidden="true"><svg viewBox="0 0 24 24"><path d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v15H6.5A2.5 2.5 0 0 1 4 15.5z"/><path d="M4 7h13M8 11h8M8 14h5"/></svg></span>
        <span>Carteira <b>Eleitoral Digital</b></span>
      </a>
      <button class="menu-toggle" aria-label="Abrir menu" aria-expanded="false"><span></span><span></span><span></span></button>
      <div class="nav-links">
        <a href="#projeto">O projeto</a>
        <a href="#funcionalidades">Funcionalidades</a>
        <a href="#metodologia">Metodologia</a>
        <a href="#etica">Neutralidade</a>
        <a class="nav-cta" href="#proximos-passos">Conheça as etapas <span>↗</span></a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero" id="inicio">
      <div class="hero-glow glow-one"></div><div class="hero-glow glow-two"></div>
      <div class="container hero-grid">
        <div class="hero-copy">
          <div class="eyebrow"><span class="eyebrow-dot"></span> PROJETO INTERDISCIPLINAR · IFPR</div>
          <h1>Seu voto começa com <span>informação.</span></h1>
          <p class="hero-lead">Uma forma mais prática de pesquisar, organizar e consultar informações públicas sobre candidaturas — com autonomia para decidir.</p>
          <div class="hero-actions">
            <a class="button button-light" href="#projeto">Explore o projeto <span>↓</span></a>
            <a class="text-link" href="#etica">Entenda nosso compromisso <span>↗</span></a>
          </div>
          <div class="hero-proof">
            <div class="proof-icon"><svg viewBox="0 0 24 24"><path d="M12 3 19 6v5c0 4.5-3 7.5-7 10-4-2.5-7-5.5-7-10V6z"/><path d="m9 12 2 2 4-4"/></svg></div>
            <div><strong>Informação pública. Escolha pessoal.</strong><small>Sem recomendar candidatos ou partidos.</small></div>
          </div>
        </div>
        <div class="hero-visual" aria-label="Ilustração de uma carteira eleitoral digital">
          <div class="orbit orbit-a"></div><div class="orbit orbit-b"></div>
          <div class="floating-tag tag-top"><span class="tag-icon green">✓</span><span><b>Fontes oficiais</b><small>Informação verificável</small></span></div>
          <div class="phone">
            <div class="phone-top"><span class="phone-time">9:41</span><span class="phone-status">● ▰</span></div>
            <div class="app-head"><div class="app-symbol"><svg viewBox="0 0 24 24"><path d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v15H6.5A2.5 2.5 0 0 1 4 15.5z"/><path d="M4 7h13M8 11h8M8 14h5"/></svg></div><div><b>Minha carteira</b><small>Organize suas escolhas</small></div><span class="app-menu">•••</span></div>
            <div class="app-greeting">Olá, eleitor(a) 👋<h3>Prepare-se com<br>antecedência.</h3></div>
            <div class="app-search"><span>⌕</span> Pesquisar candidaturas <span class="search-filter">☷</span></div>
            <div class="app-section-title">Sua organização <a href="#funcionalidades">Ver tudo ↗</a></div>
            <div class="app-item"><span class="app-item-icon blue"><svg viewBox="0 0 24 24"><circle cx="10.5" cy="8" r="3.5"/><path d="M4 20v-2a6.5 6.5 0 0 1 13 0v2M18 8h3m-1.5-1.5v3"/></svg></span><span><b>Candidaturas salvas</b><small>Suas pesquisas e referências</small></span><span class="item-arrow">›</span></div>
            <div class="app-item"><span class="app-item-icon yellow"><svg viewBox="0 0 24 24"><path d="M7 3h10v18l-5-3-5 3z"/><path d="m9 10 2 2 4-4"/></svg></span><span><b>Minhas anotações</b><small>Opiniões e observações pessoais</small></span><span class="item-arrow">›</span></div>
            <div class="app-item"><span class="app-item-icon purple"><svg viewBox="0 0 24 24"><rect x="4" y="4" width="16" height="16" rx="3"/><path d="m8 12 2.5 2.5L16 9"/></svg></span><span><b>Checklist eleitoral</b><small>Organize seus números</small></span><span class="item-arrow">›</span></div>
            <div class="app-foot"><span class="active">⌂<small>Início</small></span><span>⌕<small>Pesquisar</small></span><span>▤<small>Carteira</small></span><span>⚙<small>Ajustes</small></span></div>
          </div>
          <div class="floating-tag tag-bottom"><span class="tag-icon navy">↗</span><span><b>Você decide.</b><small>A ferramenta não indica voto.</small></span></div>
          <div class="visual-caption">CONCEITO VISUAL DO PROTÓTIPO</div>
        </div>
      </div>
      <div class="hero-bottom container"><span>TECNOLOGIA A SERVIÇO DA CIDADANIA</span><span class="hero-line"></span><span>01 / 06</span></div>
    </section>

   <section class="value-strip" aria-label="Princípios do projeto">
      <div class="container value-grid">
        <div class="value-item"><span class="value-icon">◎</span><div><b>Autonomia</b><small>Decisão do próprio eleitor</small></div></div>
        <div class="value-item"><span class="value-icon">⌘</span><div><b>Dados públicos</b><small>Fontes oficiais e verificáveis</small></div></div>
        <div class="value-item"><span class="value-icon">▤</span><div><b>Organização</b><small>Informações em um só lugar</small></div></div>
        <div class="value-item"><span class="value-icon">♻</span><div><b>Consciência ambiental</b><small>Alternativa ao papel pessoal</small></div></div>
      </div>
    </section>

   <section class="section section-white" id="projeto">
      <div class="container">
        <div class="section-heading">
          <div><span class="section-kicker">01 — O CONTEXTO</span><h2>Informação existe.<br><span>Organização faz diferença.</span></h2></div>
          <p>Pesquisar candidaturas pode envolver várias fontes, anotações dispersas e decisões deixadas para a última hora. O projeto investiga como uma ferramenta digital pode ajudar nesse processo.</p>
        </div>
        <div class="problem-grid">
          <article class="problem-card"><div class="card-number">01</div><div class="card-icon coral"><svg viewBox="0 0 24 24"><path d="M7 3h10v18l-5-3-5 3z"/><path d="M9 8h6M9 11h4"/></svg></div><h3>Anotações dispersas</h3><p>Papéis e santinhos impressos podem dificultar a consulta e a organização das informações.</p><span class="card-bottom">DESAFIO DE ORGANIZAÇÃO</span></article>
          <article class="problem-card"><div class="card-number">02</div><div class="card-icon blue"><svg viewBox="0 0 24 24"><circle cx="10.5" cy="10.5" r="6.5"/><path d="m16 16 4 4M8 10h5M8 13h3"/></svg></div><h3>Informações fragmentadas</h3><p>Dados sobre candidaturas ficam distribuídos em diferentes páginas e materiais.</p><span class="card-bottom">DESAFIO DE PESQUISA</span></article>
          <article class="problem-card"><div class="card-number">03</div><div class="card-icon yellow"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></svg></div><h3>Preparação tardia</h3><p>A escolha pode ser organizada com antecedência, em vez de depender da consulta de última hora.</p><span class="card-bottom">DESAFIO DE PLANEJAMENTO</span></article>
        </div>
        <div class="research-question"><span class="quote-mark">“</span><div><span class="section-kicker">PERGUNTA DE PESQUISA</span><h3>Uma ferramenta digital de organização eleitoral ajuda o eleitor a se preparar antecipadamente e reduz a dependência de materiais impressos?</h3></div><div class="question-badge"><span>?</span><small>Questão norteadora</small></div></div>
      </div>
    </section>
    <section class="section feature-section" id="funcionalidades">
      <div class="container feature-layout">
        <div class="feature-intro"><span class="section-kicker light-kicker">02 — A PROPOSTA</span><h2>Uma carteira.<br><span>Mais organização.</span></h2><p>O protótipo reúne recursos de apoio à pesquisa e à preparação eleitoral sem interferir na decisão individual.</p><a class="button button-outline" href="#metodologia">Como será desenvolvido <span>↗</span></a></div>
        <div class="feature-list">
          <article class="feature-row"><span class="feature-index">01</span><span class="feature-icon"><svg viewBox="0 0 24 24"><circle cx="10.5" cy="10.5" r="6.5"/><path d="m16 16 4 4M8 10h5"/></svg></span><div><h3>Busca de candidaturas</h3><p>Consulta de dados públicos e acesso a informações sobre candidaturas e propostas.</p></div><span class="feature-arrow">↗</span></article>
          <article class="feature-row"><span class="feature-index">02</span><span class="feature-icon"><svg viewBox="0 0 24 24"><path d="M5 4h14v16H5z"/><path d="M8 8h8M8 12h8M8 16h5"/></svg></span><div><h3>Anotações pessoais</h3><p>Espaço para registrar opiniões, dúvidas e observações de forma organizada.</p></div><span class="feature-arrow">↗</span></article>
          <article class="feature-row"><span class="feature-index">03</span><span class="feature-icon"><svg viewBox="0 0 24 24"><rect x="4" y="4" width="16" height="16" rx="3"/><path d="m8 12 2.5 2.5L16 9"/></svg></span><div><h3>Checklist de votação</h3><p>Uma “colinha eleitoral” organizada para consultar os números escolhidos pelo próprio eleitor.</p></div><span class="feature-arrow">↗</span></article>
          <article class="feature-row"><span class="feature-index">04</span><span class="feature-icon"><svg viewBox="0 0 24 24"><path d="M10 13a5 5 0 0 0 7.1 0l2-2a5 5 0 0 0-7.1-7.1l-1.1 1.1"/><path d="M14 11a5 5 0 0 0-7.1 0l-2 2A5 5 0 0 0 12 20l1.1-1.1"/></svg></span><div><h3>Links de fontes oficiais</h3><p>Atalhos para consultar as fontes públicas registradas, incluindo os dados do TSE.</p></div><span class="feature-arrow">↗</span></article>
        </div>
      </div>
    </section>

   <section class="section section-white" id="etica">
      <div class="container ethics-layout">
        <div><span class="section-kicker">03 — COMPROMISSO ÉTICO</span><h2>Tecnologia sem<br><span>escolher por você.</span></h2><p class="ethics-lead">A carteira é uma ferramenta de organização, não de recomendação política. O protagonismo permanece com o cidadão.</p><div class="source-note"><span class="source-seal"><svg viewBox="0 0 24 24"><path d="M12 3 19 6v5c0 4.5-3 7.5-7 10-4-2.5-7-5.5-7-10V6z"/><path d="m9 12 2 2 4-4"/></svg></span><div><b>Transparência nas fontes</b><p>O projeto prevê acesso a dados públicos oficiais, sem criar uma “verdade política” própria.</p><a href="https://dadosabertos.tse.jus.br/" target="_blank" rel="noopener noreferrer">Portal de Dados Abertos do TSE ↗</a></div></div></div>
        <div class="ethics-card">
          <div class="ethics-card-head"><span class="ethics-shield"><svg viewBox="0 0 24 24"><path d="M12 3 19 6v5c0 4.5-3 7.5-7 10-4-2.5-7-5.5-7-10V6z"/><path d="m9 12 2 2 4-4"/></svg></span><div><small>NOSSO PRINCÍPIO</small><h3>Neutralidade e autonomia</h3></div></div>
          <div class="ethics-item"><span class="cross">×</span><div><b>Não recomenda candidatos ou partidos</b><p>Não indica em quem votar.</p></div></div>
          <div class="ethics-item"><span class="cross">×</span><div><b>Não cria rankings ideológicos</b><p>Não atribui notas ou posições políticas.</p></div></div>
          <div class="ethics-item"><span class="check">✓</span><div><b>Organiza informações pessoais</b><p>O usuário registra suas próprias observações.</p></div></div>
          <div class="ethics-item"><span class="check">✓</span><div><b>Facilita o acesso a dados públicos</b><p>A decisão continua sendo individual.</p></div></div>
        </div>
      </div>
    </section>

   <section class="section methodology" id="metodologia">
      <div class="container">
        <div class="section-heading">
          <div><span class="section-kicker light-kicker">04 — MÉTODO CIENTÍFICO</span><h2>Da pergunta à <span>validação.</span></h2></div>
          <p>O desenvolvimento combina investigação, construção do protótipo e avaliação com usuários para entender a utilidade real da solução.</p>
        </div>
        <div class="timeline">
          <div class="timeline-item"><span class="timeline-dot">01</span><b>Pesquisa bibliográfica</b><small>Entender o contexto e reunir referências.</small></div>
          <div class="timeline-item"><span class="timeline-dot">02</span><b>Formulário de campo</b><small>Investigar hábitos e dificuldades dos eleitores.</small></div>
          <div class="timeline-item"><span class="timeline-dot">03</span><b>Análise estatística</b><small>Organizar e interpretar as respostas.</small></div>
          <div class="timeline-item"><span class="timeline-dot">04</span><b>Requisitos do app</b><small>Definir necessidades e funcionalidades.</small></div>
          <div class="timeline-item"><span class="timeline-dot">05</span><b>Protótipo funcional</b><small>Construir e preparar a solução para testes.</small></div>
          <div class="timeline-item"><span class="timeline-dot">06</span><b>Testes de usabilidade</b><small>Avaliar clareza, navegação e utilidade.</small></div>
          <div class="timeline-item"><span class="timeline-dot">07</span><b>Comparação de dados</b><small>Observar resultados e percepções dos usuários.</small></div>
          <div class="timeline-item"><span class="timeline-dot">08</span><b>Análise e conclusões</b><small>Registrar achados, limites e aprendizados.</small></div>
        </div>
      </div>
    </section>

   <section class="section section-white" id="avaliacao">
      <div class="container">
        <div class="section-heading compact-heading"><div><span class="section-kicker">05 — COMO AVALIAR</span><h2>O que queremos <span>descobrir.</span></h2></div><p>O sucesso será avaliado com dados e percepções dos participantes, sem presumir resultados antes da pesquisa.</p></div>
        <div class="metrics-grid">
          <div class="metric-card"><span class="metric-symbol">◷</span><h3>Tempo de busca</h3><p>Quanto tempo o usuário leva para localizar a informação desejada.</p></div>
          <div class="metric-card"><span class="metric-symbol">☷</span><h3>Facilidade de organização</h3><p>Se a estrutura ajuda a manter as informações selecionadas em ordem.</p></div>
          <div class="metric-card"><span class="metric-symbol">♡</span><h3>Satisfação do usuário</h3><p>Como os participantes avaliam conforto, clareza e usabilidade.</p></div>
          <div class="metric-card"><span class="metric-symbol">♻</span><h3>Substituição digital</h3><p>Intenção de substituir anotações físicas pela ferramenta.</p></div>
        </div>
        <div class="limitation-note"><span>i</span><p><b>Compromisso com o rigor:</b> os resultados dependerão da amostra pesquisada. O protótipo facilita o acesso a fontes, mas não realiza auditoria autônoma de todas as informações da internet nem permite concluir, sozinho, impactos ambientais em escala nacional.</p></div>
      </div>
    </section>

   <section class="section disciplines">
      <div class="container disciplines-layout">
        <div><span class="section-kicker light-kicker">06 — APRENDIZAGEM INTEGRADA</span><h2>Um projeto,<br><span>várias áreas.</span></h2><p>A proposta conecta tecnologia, investigação científica, comunicação e cidadania em uma experiência interdisciplinar.</p></div>
        <div class="discipline-grid">
          <div class="discipline"><span>⌘</span><b>Tecnologia e programação</b><small>Desenvolvimento do protótipo</small></div>
          <div class="discipline"><span>∑</span><b>Matemática e estatística</b><small>Tratamento de dados</small></div>
          <div class="discipline"><span>¶</span><b>Língua Portuguesa</b><small>Clareza e acessibilidade</small></div>
          <div class="discipline"><span>◉</span><b>Ciências humanas</b><small>Cidadania e processo eleitoral</small></div>
          <div class="discipline"><span>♻</span><b>Ciências ambientais</b><small>Impacto dos materiais impressos</small></div>
          <div class="discipline"><span>✳</span><b>Design e UX</b><small>Usabilidade centrada no usuário</small></div>
        </div>
      </div>
    </section>

   <section class="closing-cta" id="proximos-passos">
      <div class="container cta-inner"><div class="cta-orb">✓</div><span class="section-kicker">PRÓXIMAS ETAPAS</span><h2>Preparar-se para votar<br><span>também é exercer cidadania.</span></h2><p>Aplicar o formulário, analisar os dados, mapear requisitos, modelar as telas, desenvolver o MVP e testar com usuários.</p><a class="button button-light" href="https://dadosabertos.tse.jus.br/" target="_blank" rel="noopener noreferrer">Conheça os dados abertos do TSE <span>↗</span></a><small class="cta-note">Projeto acadêmico · IFPR · Carteira Eleitoral Digital</small></div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer-main"><a class="brand footer-brand" href="#inicio"><span class="brand-mark"><svg viewBox="0 0 24 24"><path d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v15H6.5A2.5 2.5 0 0 1 4 15.5z"/><path d="M4 7h13M8 11h8M8 14h5"/></svg></span><span>Carteira <b>Eleitoral Digital</b></span></a><p>Organização, informação e preparação consciente para o exercício do voto.</p><a href="#inicio" class="back-top">Voltar ao início ↑</a></div>
    <div class="container footer-bottom"><span>Projeto Interdisciplinar 1 · IFPR</span><span>Informação para decidir com autonomia.</span></div>
  </footer>
  <script src="script.js"></script>
</body>
</html>
