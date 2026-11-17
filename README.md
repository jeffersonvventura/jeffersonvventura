<div align="center">

<img src="assets/banner.svg" alt="Jefferson Ventura — Desenvolvedor Full Stack, IA & Automação, Análise de Dados e Perícia Digital" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jeffersonventura-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jeffersonventura)
[![GitHub](https://img.shields.io/badge/GitHub-jeffersonvventura-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jeffersonvventura)

</div>

## 👋 Sobre mim

Desenvolvo soluções completas que transformam processos complexos em ferramentas simples, rápidas e confiáveis. Meu trabalho combina **desenvolvimento de software**, **inteligência artificial**, **automação** e **perícia digital**, com foco em quem usa a ferramenta no dia a dia.

| | Área | O que faço |
|:-:|---|---|
| 🤖 | **Inteligência Artificial** | Agentes inteligentes e sistemas autônomos com validação humana |
| ⚙️ | **Automação** | Robôs, automação de navegador, integrações e RPA |
| 🔍 | **Perícia Digital** | Ferramentas de apoio à análise forense e à investigação de dados |
| 📊 | **Dados** | Análise, visualização, grafos de vínculos, linhas do tempo e mapas |
| 💻 | **Desenvolvimento** | Aplicativos desktop, sistemas web e APIs |

---

## 🧰 Ferramentas em destaque

Algumas das ferramentas que desenvolvi, prontas ou em desenvolvimento. Os nomes dos repositórios e a tecnologia de cada uma ficam de fora; o foco aqui é o que elas resolvem.

> [!NOTE]
> Todas as telas abaixo usam **dados fictícios**, criados só para estas capturas. Nenhuma informação real aparece nas imagens.

| Ferramenta | Em uma frase |
|---|---|
| [**ARGOS**](#argos) | Agentes de IA que apoiam a análise investigativa, com validação humana de cada achado |
| [**WRA — WhatsApp Records Analyzer**](#wra) | Extração e análise dos registros entregues pela plataforma WhatsApp Records |
| [**IPED Manager**](#iped-manager) | Fila de indexação de evidências digitais, com acompanhamento ao vivo |
| [**Step Navigator**](#step-navigator) | Navegador de automação: passos reproduzíveis, montados direto na página |
| [**Gerenciador de Processos**](#gerenciador-de-processos) | O que está rodando no Windows, quem iniciou e quanto consome |
| [**USB Identifier**](#usb-identifier) | Descobre a versão real de cada porta USB e o que está ligado nela |
| [**ScreenShare**](#screenshare) | Capturas de tela com editor embutido e envio direto ao Google Drive |
| [**ZoomScreen**](#zoomscreen) | Zoom, desenho, gravação e roteiros digitados para apresentações ao vivo |
| [**Copicola**](#copicola) | Histórico da área de transferência e expansão de texto em qualquer programa |

---

<a id="argos"></a>

### 🛰️ ARGOS

**Agente de Reconhecimento, Gestão e Organização de Sinais.** Uma estação de trabalho forense em que agentes de IA especializados consultam o acervo indexado no IPED, organizam os resultados e propõem achados. Cada achado é classificado como **fato, inferência ou hipótese**, aponta para a evidência de origem e só entra no relatório depois de **validado pelo analista**. A IA ajuda; quem decide é o analista.

- Grade de dados que continua fluida com 100 mil linhas, com filtros e inspetor de itens
- Grafo de vínculos, quadro de análise com sugestões dos agentes, linha do tempo e mapa
- Pedidos de aprovação em tempo real: nada é gravado sem a decisão do analista
- Relatório montado só com achados validados, com trilha de auditoria verificável

<p align="center"><img src="assets/screens/argos-vinculos.png" alt="ARGOS — grafo de vínculos" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<table>
  <tr>
    <td width="50%"><img src="assets/screens/argos-geo-timeline.png" alt="ARGOS — linha do tempo e mapa"/></td>
    <td width="50%"><img src="assets/screens/argos-dados.png" alt="ARGOS — grade de dados e console do agente"/></td>
  </tr>
  <tr>
    <td align="center"><sub>Linha do tempo e mapa</sub></td>
    <td align="center"><sub>Grade de dados e decisão do analista no console</sub></td>
  </tr>
</table>
</details>

---

<a id="wra"></a>

### 💬 WRA — WhatsApp Records Analyzer

Ferramenta de uso restrito para **extrair e analisar** os arquivos entregues pela plataforma WhatsApp Records (grupos, interceptação e registros). Reúne tudo de uma operação num só lugar e transforma milhares de registros em visões que respondem perguntas.

- Dashboard da operação: volume diário por conta, tipos de mensagem, dispositivos e principais interlocutores
- Mensagens, chamadas, contatos em comum, grupos e participantes
- Análise de IPs com geolocalização, análise de horários noturnos e linha do tempo
- Grafo de vínculos entre contas, grupos e IPs compartilhados, com caminho mais curto entre dois números
- Controle de acesso por perfil e trilha de auditoria

<p align="center"><img src="assets/screens/wra-dashboard.png" alt="WRA — dashboard da operação" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<p align="center"><img src="assets/screens/wra-grafo.png" alt="WRA — grafo de vínculos" width="100%"/></p>
<p align="center"><sub>Grafo de vínculos entre contas alvo, interlocutores, grupos e IPs</sub></p>
</details>

---

<a id="iped-manager"></a>

### 🗂️ IPED Manager

Gerenciador da **fila de indexação** do IPED (Indexador e Processador de Evidências Digitais). Organiza operações e coletas, monta os comandos a partir de modelos, executa a fila respeitando o paralelismo configurado e mostra a saída de cada processamento ao vivo.

- Dashboard com espaço em disco, indexações por status, volume e tempo processados
- Fila com reordenação por arrastar, atraso programado, cancelamento e reprocessamento
- Saída do terminal em tempo real e log completo de cada execução
- Destinos pós-processamento (copiar, mover ou manter) e notificações de status

<p align="center"><img src="assets/screens/iped-manager-dashboard.png" alt="IPED Manager — dashboard" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<table>
  <tr>
    <td width="50%"><img src="assets/screens/iped-manager-fila.png" alt="IPED Manager — fila de processamento"/></td>
    <td width="50%"><img src="assets/screens/iped-manager-output.png" alt="IPED Manager — saída ao vivo"/></td>
  </tr>
  <tr>
    <td align="center"><sub>Fila de processamento</sub></td>
    <td align="center"><sub>Saída do processamento ao vivo</sub></td>
  </tr>
</table>
</details>

---

<a id="step-navigator"></a>

### 🧭 Step Navigator

Navegador de automação para montar **passos reproduzíveis**: abrir páginas, escolher elementos direto na tela, preencher, extrair, decidir e repetir. As automações podem ser agendadas, acionadas por um bot do Telegram, conversar com endpoints e pedir ajuda a modelos de IA.

- Editor em lista ou em fluxo visual, com formulário de cada passo ao lado
- Variáveis, tabelas de dados, subautomações e desvios entre passos
- Agendamento, bot do Telegram, endpoints e IA cadastrados uma vez e reaproveitados
- Execução com o mínimo de rastros de automação e licença vinculada à máquina

<p align="center"><img src="assets/screens/step-navigator-fluxo.png" alt="Step Navigator — fluxo da automação" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<p align="center"><img src="assets/screens/step-navigator-passos.png" alt="Step Navigator — lista de passos" width="100%"/></p>
<p align="center"><sub>Lista de passos</sub></p>
</details>

---

<a id="gerenciador-de-processos"></a>

### 📈 Gerenciador de Processos

Monitor de processos para o Windows que vai além do Gerenciador de Tarefas: mostra **quando e por quem** cada processo foi iniciado, de onde ele veio (sistema, serviço, inicialização, tarefa agendada) e quanto de CPU, memória, GPU, disco e rede ele usa.

- Visão geral com CPU por núcleo, memória, GPU, discos e internet Wi‑Fi × cabo
- Árvore de processos e linhagem de quem iniciou cada um
- Tudo o que inicia com o Windows: registro, pastas, tarefas agendadas e serviços
- Verificação de executáveis no VirusTotal e bloqueio contra encerrar processos essenciais

<p align="center"><img src="assets/screens/process-manager-visao-geral.png" alt="Gerenciador de Processos — visão geral" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<table>
  <tr>
    <td width="50%"><img src="assets/screens/process-manager-processos.png" alt="Gerenciador de Processos — lista de processos"/></td>
    <td width="50%"><img src="assets/screens/process-manager-arvore.png" alt="Gerenciador de Processos — árvore de processos"/></td>
  </tr>
  <tr>
    <td align="center"><sub>Processos com origem da inicialização</sub></td>
    <td align="center"><sub>Árvore de processos</sub></td>
  </tr>
</table>
</details>

---

<a id="usb-identifier"></a>

### 🔌 USB Identifier

Ferramenta portátil que localiza as portas USB do computador, identifica a **versão real de cada uma** (de USB 2.0 a USB4) e mostra o que está ligado em tempo real. Avisa quando um dispositivo trabalha abaixo da capacidade por causa do cabo, do hub ou da porta.

- Painel com as portas agrupadas como estão no gabinete (traseiro, frontal…)
- Assistente que nomeia as portas uma a uma: é só plugar um dispositivo
- Topologia controladora → hubs → portas → dispositivos
- Histórico de conexões e relatórios para exportar, importar e comparar

<p align="center"><img src="assets/screens/usb-identifier-painel.png" alt="USB Identifier — painel de portas" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<p align="center"><img src="assets/screens/usb-identifier-topologia.png" alt="USB Identifier — topologia" width="100%"/></p>
<p align="center"><sub>Topologia: controladoras, hubs, portas e dispositivos</sub></p>
</details>

---

<a id="screenshare"></a>

### 📸 ScreenShare

Capturas de tela **portáteis** com editor embutido e envio direto ao Google Drive, sempre mantendo uma cópia local.

- Captura de região, janela, monitor atual ou todos os monitores, com lupa e medidas
- Setas, formas, textos, passos numerados, marca-texto, destaque e recorte
- Desfoque e pixelização para esconder dados sensíveis
- Reedição não destrutiva: o original e as anotações ficam guardados
- Envio ao Google Drive com escolha de pasta e link copiado automaticamente

<p align="center"><img src="assets/screens/screenshare-editor.png" alt="ScreenShare — editor de anotações" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<p align="center"><img src="assets/screens/screenshare-historico.png" alt="ScreenShare — histórico de capturas" width="100%"/></p>
<p align="center"><sub>Histórico de capturas com status do envio ao Drive</sub></p>
</details>

---

<a id="zoomscreen"></a>

### 🔎 ZoomScreen

Feita para **apresentações e demonstrações ao vivo**: amplia e desenha sobre a tela, grava, recorta com reconhecimento de texto e até digita trechos roteirizados como se fosse ao vivo.

- Zoom com a tela congelada e LiveZoom sobre a tela em movimento
- Desenho por cima de qualquer programa: caneta, linhas, setas, formas, texto e desfoque
- Recorte com OCR, gravação de tela e contagem regressiva para intervalos
- DemoType: roteiros de trechos digitados com um atalho, com pausas e teclas especiais

<p align="center"><img src="assets/screens/zoom-screen-desenho.png" alt="ZoomScreen — desenho sobre a tela" width="100%"/></p>

<details>
<summary><b>Mais telas</b></summary>
<br/>
<p align="center"><img src="assets/screens/zoom-screen-demotype.png" alt="ZoomScreen — DemoType" width="100%"/></p>
<p align="center"><sub>Roteiros do DemoType</sub></p>
</details>

---

<a id="copicola"></a>

### 📋 Copicola

Gerenciador do **histórico da área de transferência** com expansão de texto. Um único executável, sem instalação, que funciona 100% offline.

- Guarda textos, imagens e arquivos copiados, sem duplicatas, com busca instantânea
- Itens fixados no topo e colagem rápida pelo teclado
- Atalhos de texto que se expandem em qualquer programa (ex.: `;email`), com variáveis de data e hora
- Respeita conteúdos marcados como privados por gerenciadores de senha
- Estatísticas de uso e backup automático

<table>
  <tr>
    <td width="33%"><img src="assets/screens/copicola-historico.png" alt="Copicola — histórico"/></td>
    <td width="33%"><img src="assets/screens/copicola-atalhos.png" alt="Copicola — atalhos de texto"/></td>
    <td width="33%"><img src="assets/screens/copicola-estatisticas.png" alt="Copicola — estatísticas"/></td>
  </tr>
  <tr>
    <td align="center"><sub>Histórico</sub></td>
    <td align="center"><sub>Atalhos de texto</sub></td>
    <td align="center"><sub>Estatísticas</sub></td>
  </tr>
</table>

---

## 🛠️ Stack

<details>
<summary><b>Linguagens, frameworks e ferramentas com que trabalho</b></summary>
<br/>

**Linguagens**<br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" title="PHP" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="Kotlin" title="Kotlin" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="Dart" title="Dart" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash" title="Bash" width="40" height="40"/>

**IA e dados**<br/>
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" title="TensorFlow" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" title="PyTorch" width="40" height="40"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit-learn" title="scikit-learn" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV" title="OpenCV" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" title="pandas" width="40" height="40"/>
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" title="seaborn" width="40" height="40"/>

**Frontend e mobile**<br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" title="Bootstrap" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="Vue.js" title="Vue.js" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter" title="Flutter" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original.svg" alt="Android" title="Android" width="40" height="40"/>

**Backend**<br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="Express" title="Express" width="40" height="40"/>
<img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="Django" title="Django" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original.svg" alt="Laravel" title="Laravel" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original.svg" alt=".NET" title=".NET" width="40" height="40"/>

**Bancos de dados**<br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" width="40" height="40"/>
<img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="SQL Server" title="SQL Server" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" title="Redis" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="SQLite" title="SQLite" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-icon.svg" alt="Cassandra" title="Cassandra" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="MariaDB" title="MariaDB" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="Elasticsearch" title="Elasticsearch" width="40" height="40"/>

**DevOps e nuvem**<br/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" title="Git" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" title="AWS" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud" title="Google Cloud" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" title="Firebase" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="40" height="40"/>

**Automação e outras ferramentas**<br/>
<img src="https://www.vectorlogo.zone/logos/pptrdev/pptrdev-official.svg" alt="Puppeteer" title="Puppeteer" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" title="Postman" width="40" height="40"/>
<img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" title="Arduino" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-original.svg" alt="Photoshop" title="Photoshop" width="40" height="40"/>

</details>

---

## 📫 Vamos conversar?

<div align="center">

Projetos, colaborações ou consultorias: me chame no LinkedIn.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jeffersonventura)

<br/>

*"Transformando ideias em código, dados em insights e processos em automação."*

![Visualizações do perfil](https://komarev.com/ghpvc/?username=jeffersonvventura&color=blueviolet&style=flat-square)

</div>
