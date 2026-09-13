# 📱 Integra Campus

**SuperApp educacional para o uso consciente, seguro e pedagógico de smartphones na educação básica.**

Projeto desenvolvido pela equipe **Hack'n Roll** para o **HackaTudo 2026**.

> Em vez de perguntar *"como proibir celulares?"*, o Integra Campus parte de uma pergunta diferente:
> **Como transformar o smartphone em um instrumento seguro, pedagógico e saudável para estudantes, professores e famílias?**

---

## 📖 Sobre o projeto

O crescimento do uso de smartphones entre crianças e adolescentes mudou profundamente o ambiente escolar, trazendo desafios de aprendizagem, atenção, saúde mental, convivência e segurança digital. O uso excessivo e sem mediação está associado à queda de desempenho, ansiedade, problemas de sono e cyberbullying — mas a proibição total e isolada também apresenta resultados limitados.

O **Integra Campus** propõe um modelo de **regulação contextual** em vez de proibição irrestrita, integrando cinco eixos principais em um único SuperApp:

| Módulo | Função |
|---|---|
| 🔒 **Modo Sala de Foco** | Whitelist/blacklist de aplicativos durante atividades autorizadas pelo professor |
| 🎓 **Campus Virtual** | Biblioteca digital, cursos complementares, aulas síncronas, notas e presença |
| 👨‍👩‍👧 **Controle Parental e Educacional** | Painel transparente, alertas inteligentes e campanha de conscientização para famílias |
| 🏆 **Gamificação e Banco de Horas** | XP, badges, missões e desafios para reforçar hábitos de estudo |
| 🤖 **IA Educacional** | Perfil dinâmico do estudante, recomendações personalizadas, correção inicial e relatórios automáticos para o professor |

A proposta se apoia em **36 referências científicas (2012–2026)**, legislação brasileira, documentos da UNESCO, notícias sobre regulação de plataformas digitais e uma **entrevista de campo** com um professor da rede pública paulista e do Centro Paula Souza, usada como validação qualitativa da solução.

---

## 🎯 Contexto e justificativa

Em janeiro de 2025, a **Lei nº 15.100/2025** passou a restringir o uso de celulares na educação básica durante todo o período escolar, com exceções pedagógicas — mas sem oferecer infraestrutura para viabilizar esse uso educativo. Existe uma lacuna entre a legislação (que restringe) e a infraestrutura tecnológica das escolas (que não oferece controle contextual).

O Integra Campus surge como resposta a essa lacuna, integrando gestão escolar, aprendizagem móvel, gamificação baseada em evidências, controle parental transparente, IA adaptativa, proteção da saúde mental e conformidade com a **LGPD** em uma única plataforma.

---

## 🏗️ Arquitetura da solução

O sistema foi concebido como uma plataforma multiplataforma (Android e iOS) com **quatro perfis de acesso**:

- **Aluno** — Campus Virtual, atividades, gamificação, cursos, biblioteca e bem-estar digital.
- **Professor** — Modo Sala de Foco, criação de atividades, alertas, relatórios e comunicação.
- **Responsável** — Acompanhamento escolar, notificações e mediação digital.
- **Gestão Escolar** — Configuração institucional, políticas de uso, analytics e integração com sistemas escolares.

O aplicativo possui **funcionamento parcial offline** (Modo Sala de Foco, blacklist local e gamificação funcionam sem internet), atendendo à realidade de escolas com conectividade limitada, e prevê integração com sistemas já existentes (Sala do Futuro, Google Classroom, Microsoft Teams Educação).

### Privacidade e LGPD

O tratamento de dados segue a **Lei Geral de Proteção de Dados (Lei nº 13.709/2018)**: coleta mínima, finalidade exclusivamente educacional, transparência e **nenhum acesso a mensagens, fotos ou conteúdo de tela do estudante**. O professor recebe apenas alertas de comportamento digital (ex.: tentativa de abrir app bloqueado), nunca o conteúdo da tela do aluno.

---

## 🔬 Metodologia

Pesquisa aplicada, de abordagem qualitativa e quantitativa, combinando:

- **Revisão bibliográfica** — 36 referências científicas (metanálises, revisões sistemáticas, estudos experimentais e pesquisas quantitativas/qualitativas).
- **Análise documental** — legislação brasileira (Lei nº 15.100/2025 e LGPD) e documentos da UNESCO.
- **Entrevista semiestruturada** — realizada em setembro de 2026 com um professor com mais de 25 anos de experiência na rede pública de São Paulo e no Centro Paula Souza.

Da entrevista emergiram cinco categorias incorporadas ao projeto: distração e perda de foco, o celular como ferramenta pedagógica, sobrecarga de trabalho docente, participação da família e a blacklist colaborativa.

---

## 🌐 Estrutura do site (GitHub Pages)

| Arquivo | Descrição |
|---|---|
| `index.html` | Página inicial do projeto — problema, solução, diferenciais, equipe e visão geral |
| `documentacao.html` | Leitor estilizado da documentação completa do projeto, com resumo de cada seção |
| `simulacao.html` | Simulação interativa do funcionamento do SuperApp |
| `simulacao_app.html` | Protótipo navegável do aplicativo |
| `styles.css` | Folha de estilos compartilhada entre as páginas |
| `assets/Integra_Campus.pdf` | Documento completo do projeto (Hackaton HackTudo) |
| `assets/Referencias.zip` | Pacote com os principais artigos científicos citados na revisão bibliográfica |

---

## 📊 Impactos esperados

Os impactos previstos foram organizados em quatro dimensões:

- **Aprendizagem** — maior concentração, redução de distrações e aprendizagem personalizada via IA.
- **Trabalho docente** — automação de relatórios e alertas, reduzindo a sobrecarga administrativa.
- **Participação das famílias** — painel transparente e campanha de conscientização digital.
- **Saúde mental e bem-estar digital** — limites saudáveis de uso, pausas inteligentes e rede de apoio.

---

## ⚠️ Limitações e trabalhos futuros

O projeto reconhece limitações importantes: validação qualitativa com apenas um especialista, ausência de piloto em ambiente escolar real e impactos ainda baseados em literatura e modelagem, não em dados longitudinais próprios.

Como trabalhos futuros, estão previstos: integração com wearables, IA generativa para tutoria personalizada, painéis para psicólogos escolares e expansão para redes públicas em escala nacional.

---

## 👥 Equipe — Hack'n Roll

- Joaquim Pedro do Nascimento Moreira de Jesus
- Luiz Gabriel da Silva Cabrera
- Melissa Hollanda de Oliveira Alves
- Victória de Almeida Tambasco

Alfenas — 2026

---

## 📚 Principais referências

- SUNDAY, ADESOPE & MAARHUIS (2021) — *The effects of smartphone addiction on learning: A meta-analysis*
- CAMPBELL et al. (2024) — *Evidence for and against banning mobile phones in schools: A scoping review*
- UNESCO — *Global Education Monitoring Report 2023*
- BRASIL — Lei nº 15.100/2025 e Lei nº 13.709/2018 (LGPD)

A lista completa com as 36 referências (ABNT NBR 6023:2018) está disponível no [PDF do projeto](assets/Integra_Campus.pdf).

---

## 📄 Licença

Protótipo conceitual desenvolvido para o HackaTudo 2026. Consulte a equipe Hack'n Roll para uso ou reprodução do conteúdo.

---

*Feito com dados científicos, entrevista de campo e muito café. ☕*
