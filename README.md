<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f4d3a,50:526747,100:869771&height=210&section=header&text=Rhayron%20Nogueira&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Engenheiro%20eletricista%20%C2%B7%20vis%C3%A3o%20computacional%20na%20ind%C3%BAstria%20%C2%B7%20ultrassom%20na%20GPU%20%C2%B7%20IA%20que%20faz%20companhia&descSize=17&descAlignY=57&animation=fadeIn" width="100%" alt="Rhayron Nogueira">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3200&pause=900&color=BCCF9D&center=true&vCenter=true&width=720&height=42&lines=Ol%C3%A1%2C+eu+sou+o+Rhayron+%F0%9F%91%8B;Ensino+c%C3%A2meras+a+enxergar+numa+linha+de+montagem;Reconstruo+imagens+de+ultrassom+na+GPU;Construo+a+Hina%2C+uma+companheira+de+desktop;Sempre+aprendendo+algo+novo">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3200&pause=900&color=526747&center=true&vCenter=true&width=720&height=42&lines=Ol%C3%A1%2C+eu+sou+o+Rhayron+%F0%9F%91%8B;Ensino+c%C3%A2meras+a+enxergar+numa+linha+de+montagem;Reconstruo+imagens+de+ultrassom+na+GPU;Construo+a+Hina%2C+uma+companheira+de+desktop;Sempre+aprendendo+algo+novo" alt="Olá, eu sou o Rhayron. Ensino câmeras a enxergar numa linha de montagem, reconstruo imagens de ultrassom na GPU e construo a Hina, uma companheira de desktop.">
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rhayron"><img src="https://img.shields.io/badge/LinkedIn-rhayron-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:rhayron.nogueira@gmail.com"><img src="https://img.shields.io/badge/E--mail-rhayron.nogueira%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://rhayron.github.io"><img src="https://img.shields.io/badge/Portf%C3%B3lio-rhayron.github.io-526747?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfólio"></a>
  <a href="https://github.com/Project-H-I-N-A"><img src="https://img.shields.io/badge/Project%20Hina-org-8f1f6e?style=for-the-badge&logo=github&logoColor=white" alt="Project Hina"></a>
  <img src="https://img.shields.io/badge/Curitiba-Brasil-2f6b3f?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Curitiba, Brasil">
</p>

## 👋 Sobre mim

<img align="right" width="250" src="assets/eletricaleng.png" alt="Ilustração de um engenheiro apontando para um transformador">

<ul>
  <li>🔭 <b>Hoje</b> sou analista de processos de manufatura na <b>Caterpillar Brasil</b>: visão computacional na linha de montagem, agentes LLM dentro das aplicações da fábrica e automação de bancadas e CLPs.</li>
  <li>🎓 <b>Mestrando</b> no CPGEI / UTFPR (conceito CAPES 6): modelo híbrido de deep learning com o método SEAM para imageamento ultrassônico de phased array. Engenheiro eletricista pela UTFPR, turma 2019 a 2023.</li>
  <li>🌙 <b>À noite</b> construo o <b>Project Hina</b>, uma companheira de desktop com voz, memória e humor, e o que mais aparecer no caderno.</li>
  <li>🌱 <b>Aprendendo agora</b>: Gaussian Splatting, Wear OS, Taichi Lang e modelos híbridos para ultrassom.</li>
  <li>💬 <b>Pergunte sobre</b>: YOLO em produção, RTSP e Modbus, TFM na GPU, Live2D, agentes com MCP.</li>
  <li>🗣️ <b>Idiomas</b>: português nativo · inglês avançado · francês A1.</li>
  <li>📫 <b>Contato</b>: <a href="mailto:rhayron.nogueira@gmail.com">rhayron.nogueira@gmail.com</a></li>
</ul>

<blockquote><em>“Gosto de conversar com as áreas, entender o processo real e construir a solução mais simples que resolve.”</em></blockquote>

<br clear="right">

## 🚀 Projetos em destaque

<table border="0" cellpadding="8">
  <tr>
    <td width="290" valign="top"><a href="https://github.com/Rhayron/acoustic_gpu"><img src="assets/projects/acoustic-gpu.jpg" width="270" alt="Reconstruções TFM lado a lado: referência de Bristol e acoustic_gpu"></a></td>
    <td valign="top">
      <b><a href="https://github.com/Rhayron/acoustic_gpu">acoustic_gpu</a></b> &nbsp;<sub>pesquisa · fev. 2026 · público</sub><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Taichi%20Lang-1b1b1b?style=flat-square" alt="Taichi"> <img src="https://img.shields.io/badge/GPU-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="GPU"> <img src="https://img.shields.io/badge/NDT%20%C2%B7%20TFM-526747?style=flat-square" alt="NDT TFM"><br>
      Reconstrução TFM de ultrassom em ensaio por imersão. Para cada imagem são mais de <b>16 milhões de trajetórias refratadas</b> (64 elementos × 512 × 512 pixels), cada uma um problema de minimização. O módulo move o cálculo para kernels Taichi na GPU, mantém uma referência na CPU para validar e cobre superfícies planas, inclinadas, tubulares e irregulares estimadas dos próprios ecos. Validado no dataset FMC de Bristol.
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://github.com/Rhayron/pose"><img src="assets/projects/pose.jpg" width="270" alt="Sonda de ultrassom com marcador ChArUco dentro do tanque, vista pela parede de vidro"></a></td>
    <td valign="top">
      <b><a href="https://github.com/Rhayron/pose">pose</a></b> &nbsp;<sub>pesquisa · jul. a out. 2026 · público</sub><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"> <img src="https://img.shields.io/badge/ChArUco-444?style=flat-square" alt="ChArUco"> <img src="https://img.shields.io/badge/Caliscope-444?style=flat-square" alt="Caliscope"><br>
      Onde está a sonda? Uma câmera 4K no tripé, fora do tanque, enxerga pela parede de vidro um marcador preso ao transdutor dentro da água e devolve a <b>pose 6DoF</b> da sonda. Com ela, cada quadro de ultrassom ganha um lugar no espaço, para registro 3D em inspeção subaquática. Calibração intrínseca do Caliscope, vídeo cru no disco e a matriz K viajando no JSON da sessão.
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://rhayron.github.io/#olho"><img src="assets/projects/errorproofing.jpg" width="270" alt="Interior de um contêiner com as caixas segmentadas pelo modelo"></a></td>
    <td valign="top">
      <b>ErrorProofing System</b> e <b>Container Occupancy</b> &nbsp;<sub>Caterpillar Brasil · 2023 em diante · privado</sub><br>
      <img src="https://img.shields.io/badge/YOLO%20v5%E2%80%93v11-111F68?style=flat-square&logo=ultralytics&logoColor=white" alt="YOLO"> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular"> <img src="https://img.shields.io/badge/RTSP-444?style=flat-square" alt="RTSP"> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure"><br>
      Inspeção visual da linha de montagem: lê os feeds RTSP das câmeras industriais, roda os modelos em microsserviços e devolve <b>pass/fail em tempo real</b> ao operador, cruzando com o torque das bancadas e os dados do MES em Oracle. Imagens de inferência no Azure Blob com rastreabilidade; Pytest e Coverage no Azure DevOps antes de cada versão ir para a linha. No Container Occupancy, uma webcam e um YOLOv10 de segmentação calculam o percentual de preenchimento do contêiner para a logística. Ao lado, um agente LLM com RAG responde dúvidas e executa tarefas dentro das aplicações da fábrica.
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://rhayron.github.io/#splat-project"><img src="assets/projects/splat.jpg" width="270" alt="Borboleta renderizada por Gaussian Splatting, cena pública de referência do Spark"></a></td>
    <td valign="top">
      <b>Splat SaaS</b> &nbsp;<sub>mai. 2026 · privado</sub><br>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Three.js-000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js"> <img src="https://img.shields.io/badge/pycolmap%20%C2%B7%20gsplat-444?style=flat-square" alt="pycolmap gsplat"> <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"><br>
      De muitas imagens, um espaço para explorar. O FFmpeg extrai os quadros, o SfM com pycolmap estima as câmeras, Splatfacto e gsplat ajustam gaussianas na GPU e o pipeline exporta PLY para um visualizador WebGL no navegador. Etapas acompanhadas por SSE, prévia durante o treino pelo viewer Viser, autenticação em cookie httpOnly e planos Free e Pro com Stripe. <sub>A imagem é a cena pública de referência do Spark, usada para explorar a técnica.</sub>
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://github.com/Rhayron/goals"><img src="assets/projects/coado.jpg" width="270" alt="Coado no navegador, no celular e no relógio"></a></td>
    <td valign="top">
      <b><a href="https://github.com/Rhayron/goals">Coado</a></b> &nbsp;<sub>out. 2026 · público</sub><br>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19"> <img src="https://img.shields.io/badge/Fastify%205-000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify"> <img src="https://img.shields.io/badge/Postgres%2017-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin"> <img src="https://img.shields.io/badge/Wear%20OS-4285F4?style=flat-square&logo=wearos&logoColor=white" alt="Wear OS"><br>
      Planner de estudos para concursos com tema de café e lofi: edital verticalizado, ciclo de estudos, pomodoro, revisões espaçadas em 1, 7, 30, 60 e 120 dias, estatísticas e simulados. O mesmo app roda no navegador, no Android (login nativo com Google e pomodoro em segundo plano) e no relógio Wear OS, onde o timer são carimbos de tempo e alarmes exatos. Login por authorization code com PKCE, isolamento por conta até nas chaves estrangeiras e sincronização em lote com retry.
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://github.com/Project-H-I-N-A/hina-releases"><img src="assets/projects/hina.jpg" width="270" alt="Dashboard da Hina com avatar, humor e capacidades"></a></td>
    <td valign="top">
      <b><a href="https://github.com/Project-H-I-N-A/hina-releases">Project Hina</a></b> &nbsp;<sub>jun. 2026 em diante · 929 commits · instaladores públicos</sub><br>
      <img src="https://img.shields.io/badge/Python%203.13-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Electron%2043-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron"> <img src="https://img.shields.io/badge/Live2D%20%C2%B7%20VRM-8f1f6e?style=flat-square" alt="Live2D VRM"> <img src="https://img.shields.io/badge/MCP-444?style=flat-square" alt="MCP"> <img src="https://img.shields.io/badge/SQLite%20%C2%B7%20sqlite--vec-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"><br>
      VTuber companion e desktop pet. Janela Electron com modo pet transparente e click-through; conversa, voz e memória num servidor Python local por FastAPI e WebSocket. Ela ouve pelo microfone, responde em áudio, olha para o ponteiro e acompanha o rosto pela câmera. Com o modo agente, executa ferramentas via MCP (busca, arquivos, shell, lembretes, Kanban com workers), perguntando antes de escrever ou executar. Por dentro: um <b>vetor de humor PAD que decai</b> à linha de base da persona, um <b>genoma de estilo</b> em dez dimensões com micro-mutações, e um <b>grafo de memória bi-temporal</b> em SQLite com busca vetorial, FTS5 e recall híbrido. A família: <b>HinaWatch</b> (o mesmo modelo Live2D na GPU do relógio, de 17,5 para 9,4 ms por quadro), <b>HinaMobile</b> (o celular acha o rosto e manda só a posição ao relógio) e <b>hina2d</b> (a identidade Live2D própria). <a href="https://hina-companion.rhayron.chatgpt.site">Site e documentação ↗</a>
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://adobe-pipeline.vercel.app"><img src="assets/projects/genstock.jpg" width="270" alt="Página inicial do GenStock Studio"></a></td>
    <td valign="top">
      <b><a href="https://adobe-pipeline.vercel.app">GenStock Studio</a></b> &nbsp;<sub>dez. 2025 a set. 2026 · 93 commits · no ar</sub><br>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind"> <img src="https://img.shields.io/badge/Gemini%20%C2%B7%20Imagen%20%C2%B7%20Veo-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"> <img src="https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"><br>
      Pipeline para produzir imagens de banco: coleta referências (Adobe Stock, Unsplash, Pixabay, Pexels), analisa cada uma com o Gemini e escreve prompts detalhados, gera novas imagens em paralelo com retry, remove duplicatas por hash perceptual, faz upscale, exporta o CSV de metadados no formato da Adobe e, se quiser, gera vídeo 4K com o Veo. A galeria atualiza por SSE enquanto o lote roda.
    </td>
  </tr>
  <tr>
    <td width="290" valign="top"><a href="https://rhayron.github.io/#arquivo"><img src="assets/projects/arquivo.jpg" width="270" alt="Montanha ao pôr do sol, a arte do dia do CaosDiffusion"></a></td>
    <td valign="top">
      <b>Arquivo</b> &nbsp;<sub>2021 a 2023</sub><br>
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"> <img src="https://img.shields.io/badge/C%20%C2%B7%20C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C e C++"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"><br>
      Onde tudo começou. <a href="https://github.com/Rhayron/CaosDiffusion">CaosDiffusion</a> sorteava um prompt, gerava uma arte por IA e postava no Twitter todo dia. Os cadernos de <a href="https://github.com/Rhayron/YOLOv3_detection_segmentation">detecção e segmentação com YOLOv3</a> explicam NMS, mAP e matriz de confusão, e antes deles veio um YOLOv3 construído do zero a partir do arquivo de configuração. No estágio na ART, firmware para computadores de bordo de locomotivas e automação de testes de hardware. Na UTFPR, análise automática de imagens termográficas de subestações para a Copel e o hardware de um veículo guiado automatizado.
    </td>
  </tr>
</table>

<details>
<summary><b>🧰 Também na bancada</b> · ferramentas menores que nasceram de necessidades concretas</summary>
<br>

<table>
  <tr><th align="left">quando</th><th align="left">o quê</th><th align="left"></th></tr>
  <tr><td nowrap valign="top"><sub>out. 2026</sub></td><td nowrap valign="top"><b>TaskbarSlim</b> · C++</td><td valign="top">Altura da barra de tarefas e um Explorer enxuto no Windows 11, como DLLs avulsas. No x64, a busca de offsets virou varredura de bytes.</td></tr>
  <tr><td nowrap valign="top"><sub>set. 2026</sub></td><td nowrap valign="top"><b>jev-decision</b> · Python</td><td valign="top">Camada de decisão para agentes de código, por hooks no Hermes Agent e no Claude Code: abre outra tarefa? o comando pode rodar? qual modelo basta?</td></tr>
  <tr><td nowrap valign="top"><sub>ago. 2026</sub></td><td nowrap valign="top"><b>vrchat</b> · Python</td><td valign="top">Gate de hardware e captura multirate de várias câmeras para full-body tracking, com Caliscope, SkellyCam, ONNX Runtime e PyTorch.</td></tr>
  <tr><td nowrap valign="top"><sub>jul. 2026</sub></td><td nowrap valign="top"><b><a href="https://github.com/Rhayron/applypilot">ApplyPilot</a></b> · Python</td><td valign="top">Agente que busca vagas, pontua o encaixe de 0 a 100, adapta o currículo e a carta sem inventar nada, renderiza PDF compatível com ATS e aplica sozinho via Playwright, ou manda pelo Telegram para revisão.</td></tr>
  <tr><td nowrap valign="top"><sub>jun. 2026</sub></td><td nowrap valign="top"><b>AetherChat</b> · Python, Android</td><td valign="top">Chat em grupo com vários modelos de IA na mesma conversa. Backend endurecido depois de uma auditoria adversarial: concorrência, BYOK, rate limit e teto de custo.</td></tr>
  <tr><td nowrap valign="top"><sub>jun. 2026</sub></td><td nowrap valign="top"><b>Hermes stack</b> · Docker, Shell</td><td valign="top">Gateway do Hermes Agent, MechaBrain e rclone numa VPS, com monitor de finanças e backup restaurável de tudo.</td></tr>
  <tr><td nowrap valign="top"><sub>2026</sub></td><td nowrap valign="top"><b>audio2text</b> · Python</td><td valign="top">Transcrição e resumo de reuniões gravadas.</td></tr>
  <tr><td nowrap valign="top"><sub>2024 a 2026</sub></td><td nowrap valign="top"><b>alexa-gemini</b> · Python</td><td valign="top">Skill da Alexa conversando com o Gemini.</td></tr>
</table>

</details>

## 🧭 Trajetória

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rhayron/Rhayron/main/assets/timeline-dark.svg">
  <img src="assets/timeline-light.svg" alt="Linha do tempo de 2021 a 2026: dos primeiros cadernos de YOLO e da termografia para a Copel, passando pelo firmware de locomotivas, a formatura na UTFPR e a Caterpillar, até acoustic_gpu, Coado e o Project Hina." width="100%">
</picture>

<p align="center"><sub>Cada ramo nasceu de um problema concreto: uma subestação que precisava ser vista por termografia, uma linha de montagem que precisava de um segundo par de olhos, uma peça que só podia ser vista por dentro com som.</sub></p>

## 🛠️ Stack

| | |
| --: | :-- |
| **Linguagens** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-444?style=flat-square) |
| **IA e visão** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO%20v3%E2%86%92v11-111F68?style=flat-square&logo=ultralytics&logoColor=white) ![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Taichi](https://img.shields.io/badge/Taichi%20Lang-1b1b1b?style=flat-square) ![Gaussian Splatting](https://img.shields.io/badge/Gaussian%20Splatting-444?style=flat-square) ![LLMs e agentes](https://img.shields.io/badge/LLMs%20%C2%B7%20agentes%20%C2%B7%20MCP%20%C2%B7%20RAG-444?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000?style=flat-square&logo=elevenlabs&logoColor=white) ![Live2D](https://img.shields.io/badge/Live2D%20%C2%B7%20VRM-8f1f6e?style=flat-square) |
| **Web e backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000?style=flat-square&logo=fastify&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000?style=flat-square&logo=threedotjs&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket%20%C2%B7%20SSE-444?style=flat-square) |
| **Mobile e desktop** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Wear OS](https://img.shields.io/badge/Wear%20OS-4285F4?style=flat-square&logo=wearos&logoColor=white) ![ML Kit](https://img.shields.io/badge/ML%20Kit-4285F4?style=flat-square&logo=google&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![OpenGL ES](https://img.shields.io/badge/OpenGL%20ES-5586A4?style=flat-square&logo=opengl&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |
| **Chão de fábrica** | ![RTSP](https://img.shields.io/badge/RTSP-444?style=flat-square) ![Modbus](https://img.shields.io/badge/Modbus%20TCP%2FIP-444?style=flat-square) ![CANopen](https://img.shields.io/badge/CANopen-444?style=flat-square) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) ![OPC-UA](https://img.shields.io/badge/OPC--UA-444?style=flat-square) ![CLP](https://img.shields.io/badge/CLP%20%C2%B7%20Ladder%20%C2%B7%20ST-444?style=flat-square) ![DeviceWise](https://img.shields.io/badge/DeviceWise-444?style=flat-square) ![Power BI](https://img.shields.io/badge/Power%20BI%20%C2%B7%20Power%20Platform-F2C811?style=flat-square&logoColor=black) |
| **Dados e infra** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite%20%C2%B7%20sqlite--vec%20%C2%B7%20FTS5-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![Azure](https://img.shields.io/badge/Azure%20%C2%B7%20Blob%20%C2%B7%20DevOps-0078D4?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git%20%C2%B7%20LFS-F05032?style=flat-square&logo=git&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest%20%C2%B7%20Coverage-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white) |

## 📊 GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Rhayron&show_icons=true&hide_rank=true&hide=stars&include_all_commits=true&locale=pt-br&hide_border=true&bg_color=00000000&title_color=bccf9d&icon_color=869771&text_color=9198a1&card_width=440">
    <img src="https://github-readme-stats.vercel.app/api?username=Rhayron&show_icons=true&hide_rank=true&hide=stars&include_all_commits=true&locale=pt-br&hide_border=true&bg_color=00000000&title_color=526747&icon_color=869771&text_color=57606a&card_width=440" alt="Estatísticas do GitHub" height="170">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Rhayron&layout=compact&langs_count=8&hide=jupyter%20notebook,html,css&locale=pt-br&hide_border=true&bg_color=00000000&title_color=bccf9d&text_color=9198a1&card_width=440">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rhayron&layout=compact&langs_count=8&hide=jupyter%20notebook,html,css&locale=pt-br&hide_border=true&bg_color=00000000&title_color=526747&text_color=57606a&card_width=440" alt="Linguagens mais usadas nos repositórios públicos" height="170">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Rhayron&locale=pt_BR&hide_border=true&background=00000000&ring=bccf9d&fire=dfb679&currStreakLabel=bccf9d&sideLabels=9198a1&dates=9198a1&currStreakNum=e6edf3&sideNums=e6edf3&stroke=3d444d">
    <img src="https://streak-stats.demolab.com?user=Rhayron&locale=pt_BR&hide_border=true&background=00000000&ring=526747&fire=dfb679&currStreakLabel=526747&sideLabels=57606a&dates=8b949e&currStreakNum=1f2328&sideNums=1f2328&stroke=d1d9e0" alt="Sequência de contribuições" height="170">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rhayron/Rhayron/output/github-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/Rhayron/Rhayron/output/github-snake.svg" alt="A cobra de contribuições" width="100%">
  </picture>
  <br><sub>Os cartões contam só o que é público. A maior parte do que está acima vive em repositórios privados ou na fábrica.</sub>
</p>

## 🤝 Vamos dar forma a uma ideia?

<p align="center">
  Pesquisa, visão computacional, IA aplicada ou um processo que precisa de um segundo par de olhos.<br>
  <a href="mailto:rhayron.nogueira@gmail.com"><b>rhayron.nogueira@gmail.com</b></a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/rhayron">linkedin.com/in/rhayron</a> &nbsp;·&nbsp; <a href="https://rhayron.github.io">rhayron.github.io</a> &nbsp;·&nbsp; <a href="https://github.com/Project-H-I-N-A">Project-H-I-N-A</a>
</p>

<details>
<summary><b>🇬🇧 In English, briefly</b></summary>
<br>

<p>Hi, I'm Rhayron, an electrical engineer from Curitiba, Brazil, building bridges between science, code and the real world.</p>
<ul>
  <li><b>By day</b>, at Caterpillar Brasil (since 2023): computer vision on the assembly line (RTSP cameras, YOLO models in microservices returning pass/fail to the operator), an LLM sidekick inside the factory web apps, industrial OCR, PLCs and benches over Modbus, CANopen and MQTT.</li>
  <li><b>At the university</b> (CPGEI / UTFPR, master's): ultrasound phased-array imaging. <a href="https://github.com/Rhayron/acoustic_gpu">acoustic_gpu</a> moves 16 million refracted time-of-flight paths per TFM image from the CPU to Taichi kernels on the GPU; <a href="https://github.com/Rhayron/pose">pose</a> tracks the probe's 6DoF pose through the tank wall with a ChArUco marker.</li>
  <li><b>At night</b>, <a href="https://github.com/Project-H-I-N-A/hina-releases">Project Hina</a>: a desktop companion with voice, a bi-temporal memory graph in SQLite, a decaying PAD mood vector and a drifting style genome. Plus a Wear OS watch face that renders the same Live2D model on the watch GPU.</li>
  <li><b>On the bench</b>: <a href="https://github.com/Rhayron/goals">Coado</a>, a study planner that runs in the browser, on Android and on the wrist; GenStock Studio, a pipeline from visual references to stock-ready images; <a href="https://github.com/Rhayron/applypilot">ApplyPilot</a>, an agent that finds jobs and applies on its own.</li>
</ul>
<p>The full portfolio lives at <a href="https://rhayron.github.io">rhayron.github.io</a>. Reach me at rhayron.nogueira@gmail.com or on <a href="https://www.linkedin.com/in/rhayron">LinkedIn</a>.</p>

</details>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:869771,50:526747,100:1f4d3a&height=110&section=footer" width="100%" alt="">
</p>
