# 🌍 Carbono Quiz — Fases

## O que é

**Carbono Quiz — Fases** é um **jogo educativo interativo** voltado ao ensino e à aprendizagem sobre carbono, ciclo do carbono, gases de efeito estufa, processos ambientais e relações com o clima.

O jogo organiza o conteúdo em fases curtas, com perguntas de múltipla escolha, feedback explicativo, progressão e elementos de gamificação.

## 🎯 Objetivo educacional

O objetivo é ajudar o jogador a revisar, testar e ampliar conhecimentos sobre temas como:

- carbono e moléculas como CO₂ e CH₄;
- ciclo do carbono;
- fotossíntese, sumidouros e fluxos de carbono;
- combustíveis fósseis, queimadas e mudanças no uso da terra;
- gases de efeito estufa e clima;
- conceitos básicos de química do carbono;
- evidências e cenários relacionados ao IPCC.

O jogo também estimula a aprendizagem por tentativa, erro e feedback imediato.

## 🎮 Como funciona

O jogo atual possui **5 fases**, com **5 perguntas em cada fase**, totalizando **25 perguntas**.

### Mecânicas existentes

- **Perguntas de múltipla escolha:** cada questão apresenta quatro alternativas.
- **Embaralhamento:** a ordem das perguntas e das alternativas é embaralhada durante as partidas.
- **Progressão por fases:** o jogador começa na Fase 1 e desbloqueia as fases seguintes conforme avança.
- **Critério de aprovação:** é necessário obter **70% ou mais** na fase para avançar.
- **Tempo por fase:** os tempos do modo normal são de 90, 80, 70, 65 e 60 segundos, respectivamente.
- **3 vidas por fase:** cada resposta errada reduz uma vida. Ao perder todas as vidas, a fase é encerrada.
- **Pontuação:** o jogo calcula a porcentagem de acertos da fase e também o desempenho geral da rodada.
- **Feedback imediato:** após cada resposta, o jogador recebe indicação de acerto ou erro acompanhada de uma explicação.
- **Dicas:** existe um recurso de dicas rápidas com informações sobre carbono e clima.
- **Pular pergunta:** o jogador pode avançar sem responder, sem pontuar naquela questão.
- **Finalizar fase:** a fase também pode ser encerrada manualmente.
- **Moedas:** cada resposta correta rende moedas.
- **Modo Relâmpago:** reduz o tempo disponível da fase e dobra a quantidade de moedas recebidas por resposta correta.
- **Troféus:** há um troféu associado a cada uma das cinco fases.
- **Loja de badges:** moedas podem ser usadas para adquirir badges colecionáveis.
- **Ranking local:** o jogo registra os 10 melhores resultados no próprio navegador/aparelho.
- **Recordes e progresso local:** nome, fase desbloqueada, melhor resultado, moedas, troféus, badges, ranking e estado do modo Relâmpago são armazenados no navegador por meio de `localStorage`.
- **Feedback visual:** o jogo utiliza animações e confetes em alguns resultados positivos.

> O ranking e o progresso são **locais**. Atualmente não existe conta online, banco de dados remoto ou ranking compartilhado entre diferentes dispositivos.

## 👥 Público-alvo

O conteúdo e o formato são adequados para:

- estudantes;
- professores;
- atividades de Ciências, Biologia, Química, Geografia e áreas ambientais;
- ações de educação ambiental;
- atividades de revisão, introdução ou discussão sobre carbono e clima.

## 🔗 Como acessar

O jogo pode ser utilizado diretamente pelo navegador:

**https://ernandes-sobreira.github.io/carbon/**

Não é necessário instalar o jogo.

## 🏫 Como usar em sala de aula

Algumas formas simples de utilização:

**Individualmente:** cada estudante joga em seu próprio dispositivo e tenta avançar pelas cinco fases.

**Em pequenos grupos:** os estudantes discutem as alternativas antes de escolher uma resposta, justificando suas decisões.

**Projetado para a turma:** o professor pode abrir o jogo em um projetor, apresentar cada pergunta e pedir que a turma vote ou argumente antes de selecionar a resposta.

O feedback exibido após cada questão pode ser usado como ponto de partida para explicações, revisão de conceitos e discussão dos erros mais frequentes.

## 🛠️ Tecnologias utilizadas

O projeto é construído com tecnologias web simples, sem frameworks externos:

- **HTML5** — estrutura do jogo;
- **CSS3** — interface, responsividade e animações;
- **JavaScript puro (Vanilla JavaScript)** — lógica das perguntas, fases, pontuação, tempo, vidas, progressão, ranking e demais mecânicas;
- **Web Storage / localStorage** — armazenamento local do progresso e das configurações do jogador;
- **HTML5 Canvas** — efeito de confetes;
- **GitHub Pages** — publicação do jogo na web.

## 📁 Estrutura do repositório

Atualmente o repositório é simples e contém dois arquivos principais:

```text
carbon/
├── index.html
└── README.md
```

### `index.html`

Arquivo principal do projeto. Atualmente concentra:

- estrutura HTML;
- estilos CSS;
- perguntas e conteúdos do quiz;
- lógica JavaScript;
- fases e temporizadores;
- sistema de vidas e moedas;
- troféus e badges;
- loja;
- ranking local;
- armazenamento local do progresso;
- animações e interface do jogo.

### `README.md`

Documentação do projeto.

## 🚧 Status do projeto

**Funcional e em desenvolvimento.**

O jogo está publicado no GitHub Pages e suas principais mecânicas estão implementadas e utilizáveis. O projeto continua recebendo ajustes de interface e experiência de uso.

## 👤 Autoria

**Ernandes Sobreira**  
**Universidade do Estado de Mato Grosso — UNEMAT**

---

🌿 Projeto desenvolvido como recurso educativo para aproximar conceitos de carbono, ambiente e clima de uma experiência interativa de aprendizagem.
