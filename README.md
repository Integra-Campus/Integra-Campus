# 🎓 Integra Campus

**SuperApp educacional para o uso consciente, seguro e pedagógico de smartphones na educação básica.**

Projeto desenvolvido pela equipe **Hack'n Roll** para o **HackaTudo 2026**.

---

## 📌 Sobre o projeto

O crescimento do uso de smartphones entre crianças e adolescentes trouxe desafios reais para a escola: distração, queda de desempenho, ansiedade e uso sem mediação. Ao mesmo tempo, a proibição total do celular também não resolve o problema sozinha.

O **Integra Campus** propõe um modelo de **regulação contextual**: em vez de proibir o celular, o app o transforma em ferramenta pedagógica quando autorizado pelo professor — e bloqueia distrações no momento certo.

A proposta é sustentada por uma revisão de **36 referências científicas (2012–2026)**, pela legislação brasileira (Lei nº 15.100/2025 e LGPD), por documentos da UNESCO e por uma entrevista de campo com um professor da rede pública paulista e do Centro Paula Souza.

### Os cinco eixos da solução

| Módulo | O que faz |
|---|---|
| 🛡️ **Modo Sala de Foco** | Bloqueia apps de distração durante atividades autorizadas pelo professor (whitelist/blacklist contextual) |
| 🏫 **Campus Virtual** | Biblioteca, cursos complementares, aulas síncronas, notas e presença |
| 👨‍👩‍👧 **Controle Parental e Educacional** | Painel transparente para os responsáveis, alertas inteligentes e campanha de conscientização |
| 🏆 **Gamificação e Banco de Horas** | XP, badges, missões e desafios para engajar o estudante |
| 🤖 **IA Educacional** | Perfil dinâmico do aluno, recomendações personalizadas e apoio ao professor (sem substituir o docente) |

---

## 🌐 Páginas do projeto

| Página | Descrição |
|---|---|
| [`index.html`](./index.html) | Página inicial do projeto — apresentação, solução e equipe |
| [`documentacao.html`](./documentacao.html) | Leitor estilizado do documento completo do projeto (HackaTudo) |
| [`simulacao.html`](./simulacao.html) | Simulação interativa em formato de dashboard (desktop), com os 4 perfis de acesso |
| [`simulacao_app.html`](./simulacao_app.html) | Protótipo interativo do **app mobile**, em mockup de celular |

## 📱 Protótipo do app mobile — `simulacao_app.html`

Simulação navegável do aplicativo em formato de celular, cobrindo os quatro perfis de acesso (**Aluno, Professor, Responsável e Escola**) e demonstrando na prática os conceitos centrais do projeto:

- **Modo Sala de Foco** — ativar o modo bloqueia, em tempo real, apps recreativos (Instagram, TikTok, WhatsApp, YouTube) e libera apenas apps pedagógicos (Google Classroom, Calculadora, Biblioteca). A tentativa de abrir um app bloqueado dispara um modal de bloqueio e um alerta automático para o professor.
- **Painel de alertas do professor** — feedback em tempo real sobre o uso dos apps na turma, sem precisar observar tela por tela.
- **Gamificação (Banco de Horas)** — concluir tarefas soma XP e gera notificações de conquista.
- **Alertas para os responsáveis** — o mesmo fluxo de alertas do professor é refletido, de forma transparente, no app dos pais.

Basta abrir o arquivo `simulacao_app.html` em um navegador — não há dependências externas além das fontes do Google Fonts.

---

## 🎨 Identidade visual

| Elemento | Valor |
|---|---|
| Fundo | `#F0F2F5` |
| Azul (Aluno/Professor) | `#B9D8F2` · `#8AB6E1` · `#6FA3D6` |
| Laranja (Responsável) | `#F5A623` |
| Roxo (Gamificação) | `#9013FE` |
| Verde (Sucesso/Liberado) | `#2F7D3A` |
| Vermelho (Alerta/Bloqueio) | `#D0021B` |
| Texto principal / secundário | `#23282E` · `#5B6470` |
| Tipografia | [Inter](https://fonts.google.com/specimen/Inter) |
| Estilo | Cantos arredondados, cards brancos com sombra suave, visual clean e moderno |

---

## 🗂️ Estrutura do repositório

```
.
├── index.html              # Página inicial
├── documentacao.html        # Documentação do projeto (leitor do PDF)
├── simulacao.html            # Simulação dashboard (desktop)
├── simulacao_app.html        # Protótipo do app mobile (mockup de celular)
├── styles.css                 # Estilos compartilhados do site
└── assets/
    ├── Integra_Campus.pdf     # Documento completo do projeto (HackaTudo)
    └── Referencias.zip        # Pacote com as referências científicas
```

---

## 🔬 Metodologia

Pesquisa aplicada, de abordagem qualitativa e quantitativa, combinando:

- Revisão bibliográfica (36 referências científicas, 2012–2026)
- Análise documental da legislação brasileira (Lei nº 15.100/2025 e LGPD)
- Entrevista semiestruturada com um professor com mais de 25 anos de experiência na rede pública de SP e no Centro Paula Souza (setembro de 2026)

O documento completo, com todas as seções e referências no padrão ABNT, está disponível em [`assets/Integra_Campus.pdf`](./assets/Integra_Campus.pdf).

---

## 🔒 Privacidade e LGPD

O Integra Campus foi desenhado desde a concepção em conformidade com a **Lei Geral de Proteção de Dados (Lei nº 13.709/2018)**:

- Coleta mínima de dados, com finalidade exclusivamente educacional
- Nenhum acesso a mensagens, fotos, conversas ou conteúdo de tela do estudante
- O professor recebe apenas alertas de comportamento digital — nunca visualiza a tela do aluno
- Transparência: o estudante sabe quais regras estão ativas a qualquer momento

---

## 👥 Equipe — Hack'n Roll

- Joaquim Pedro do Nascimento Moreira de Jesus
- Luiz Gabriel da Silva Cabrera
- Melissa Hollanda de Oliveira Alves
- Victória de Almeida Tambasco

Projeto desenvolvido para o **HackaTudo 2026** — Alfenas, 2026.

---

## 📄 Licença

Protótipo conceitual desenvolvido para fins de competição (HackaTudo). Consulte a equipe antes de reutilizar o conteúdo ou a identidade visual do projeto.
