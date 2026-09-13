<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Integra Campus | SuperApp Educacional</title>
    <style>
        :root {
            --primary: #2ea44f;
            --primary-dark: #22863a;
            --secondary: #0366d6;
            --accent: #6f42c1;
            --warning: #e36209;
            --bg: #f6f8fa;
            --text: #24292e;
            --text-light: #586069;
            --border: #e1e4e8;
            --code-bg: #f6f8fa;
            --card-bg: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 40px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        /* Cabeçalho */
        header {
            text-align: center;
            border-bottom: 2px solid var(--border);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 2.5em;
            color: var(--primary-dark);
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
            color: var(--text-light);
            font-style: italic;
        }

        .badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 8px;
            margin-top: 15px;
        }

        .badge {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 600;
            color: #fff;
        }

        .badge-green { background-color: var(--primary); }
        .badge-blue { background-color: var(--secondary); }
        .badge-orange { background-color: var(--warning); }
        .badge-purple { background-color: var(--accent); }

        /* Seções */
        h2 {
            font-size: 1.8em;
            color: var(--text);
            margin-top: 35px;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 1px solid var(--border);
        }

        h3 {
            font-size: 1.3em;
            margin-top: 25px;
            margin-bottom: 10px;
            color: var(--text);
        }

        p {
            margin-bottom: 15px;
            color: var(--text-light);
        }

        ul, ol {
            margin-bottom: 15px;
            padding-left: 25px;
            color: var(--text-light);
        }

        li {
            margin-bottom: 6px;
        }

        /* Tabelas */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-size: 0.95em;
        }

        th, td {
            border: 1px solid var(--border);
            padding: 10px 14px;
            text-align: left;
        }

        th {
            background-color: var(--bg);
            font-weight: 600;
            color: var(--text);
        }

        tr:nth-child(even) {
            background-color: #fafbfc;
        }

        /* Blocos de código */
        pre {
            background-color: var(--code-bg);
            border: 1px solid var(--border);
            border-radius: 6px;
            padding: 16px;
            overflow-x: auto;
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
            font-size: 0.9em;
            line-height: 1.5;
            margin: 20px 0;
            color: var(--text);
        }

        code {
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
            background-color: rgba(27,31,35,0.05);
            padding: 2px 6px;
            border-radius: 4px;
            font-size: 0.9em;
        }

        pre code {
            background: none;
            padding: 0;
        }

        /* Destaques */
        .highlight-box {
            background-color: #f0fff4;
            border-left: 4px solid var(--primary);
            padding: 15px 20px;
            border-radius: 0 6px 6px 0;
            margin: 20px 0;
        }

        .highlight-box p {
            margin-bottom: 0;
            color: var(--text);
        }

        .warning-box {
            background-color: #fff5f5;
            border-left: 4px solid #d73a49;
            padding: 15px 20px;
            border-radius: 0 6px 6px 0;
            margin: 20px 0;
        }

        .warning-box p {
            margin-bottom: 0;
            color: var(--text);
        }

        /* Rodapé */
        footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 2px solid var(--border);
            text-align: center;
            color: var(--text-light);
            font-size: 0.9em;
        }

        footer strong {
            color: var(--primary-dark);
        }

        /* Responsividade */
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
            header h1 {
                font-size: 1.8em;
            }
            h2 {
                font-size: 1.4em;
            }
            table {
                font-size: 0.85em;
            }
            th, td {
                padding: 8px;
            }
        }
    </style>
</head>
<body>

<div class="container">

    <!-- CABEÇALHO -->
    <header>
        <h1>🎓 Integra Campus</h1>
        <p>Transformando o smartphone de distração em ferramenta de aprendizagem.</p>
        <div class="badges">
            <span class="badge badge-green">Hackathon HackaTudo</span>
            <span class="badge badge-blue">Equipe Hack'n Roll</span>
            <span class="badge badge-orange">Projeto Conceitual</span>
            <span class="badge badge-purple">Conformidade LGPD</span>
        </div>
    </header>

    <!-- SOBRE -->
    <section>
        <h2>📖 Sobre o Projeto</h2>
        <p>
            O <strong>Integra Campus</strong> é um <strong>SuperApp educacional</strong> desenvolvido para promover o uso consciente, seguro e pedagógico de smartphones na educação básica. Diferentemente de aplicativos que apenas monitoram tempo de tela ou restringem acesso a conteúdos, a proposta integra <strong>aprendizagem, gestão escolar, participação da família, inteligência artificial e bem-estar digital</strong> em uma única plataforma.
        </p>
        <p>A solução foi construída a partir de três princípios fundamentais:</p>
        <ul>
            <li>📱 O smartphone deve ser <strong>regulado, não eliminado</strong>, quando houver finalidade pedagógica.</li>
            <li>🤖 A tecnologia precisa <strong>reduzir a carga de trabalho docente</strong>, e não aumentá-la.</li>
            <li>👨‍👩‍👧 Família, escola e estudante precisam <strong>compartilhar responsabilidades</strong> sobre o uso digital.</li>
        </ul>
        <div class="highlight-box">
            <p><strong>Pergunta central:</strong> <em>Como transformar o smartphone em um instrumento seguro, pedagógico e saudável para estudantes, professores e famílias?</em></p>
        </div>
    </section>

    <!-- PROBLEMA -->
    <section>
        <h2>🎯 O Problema</h2>
        <p>
            O crescimento do uso de smartphones entre crianças e adolescentes transformou profundamente o ambiente escolar. Pesquisas recentes demonstram que o uso excessivo e desregulado está associado a:
        </p>
        <ul>
            <li>📉 Redução do desempenho acadêmico</li>
            <li>😰 Aumento da ansiedade e problemas de sono</li>
            <li>🚫 Cyberbullying e dependência digital</li>
            <li>🧠 Prejuízos à atenção, memória de trabalho e autorregulação</li>
        </ul>
        <p>
            No Brasil, a <strong>Lei nº 15.100/2025</strong> restringe o uso de celulares nas escolas, mas não oferece infraestrutura tecnológica capaz de transformar o dispositivo em ferramenta pedagógica quando autorizado pelo professor.
        </p>
    </section>

    <!-- MÓDULOS -->
    <section>
        <h2>🧩 Módulos da Solução</h2>
        <p>O Integra Campus é composto por <strong>5 eixos principais</strong> + módulos complementares:</p>
        <table>
            <thead>
                <tr>
                    <th>Módulo</th>
                    <th>Descrição</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>🎯 <strong>Modo Sala de Foco</strong></td>
                    <td>Bloqueia aplicativos recreativos durante atividades pedagógicas, liberando apenas uma <em>whitelist</em> autorizada pelo professor.</td>
                </tr>
                <tr>
                    <td>🏫 <strong>Campus Virtual</strong></td>
                    <td>Biblioteca digital, cursos complementares, aulas síncronas, chat educacional e gerenciamento acadêmico.</td>
                </tr>
                <tr>
                    <td>👨‍👩‍👧 <strong>Controle Parental e Educacional</strong></td>
                    <td>Painel dos responsáveis com acompanhamento transparente, alertas inteligentes e programa de conscientização familiar.</td>
                </tr>
                <tr>
                    <td>🎮 <strong>Gamificação e Banco de Horas</strong></td>
                    <td>Sistema de XP, níveis, badges e missões para incentivar hábitos de estudo saudáveis.</td>
                </tr>
                <tr>
                    <td>🤖 <strong>IA Educacional</strong></td>
                    <td>Perfil dinâmico do estudante, recomendações personalizadas, correção automática e analytics para professores.</td>
                </tr>
                <tr>
                    <td>💚 <strong>Bem-estar Digital</strong></td>
                    <td>Painel de tempo de tela, pausas inteligentes, alertas educativos e rede de apoio.</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- ARQUITETURA -->
    <section>
        <h2>🏗️ Arquitetura</h2>
        <p>O sistema é concebido como uma plataforma <strong>multiplataforma</strong> (Android/iOS) com quatro perfis de acesso:</p>
        <pre><code>┌─────────────────────────────────────────────┐
│           SERVIDOR SEGURO (API)             │
│   Criptografia • Autenticação • Logs        │
└──────────────┬──────────────────────────────┘
               │
     ┌─────────┼─────────┬─────────────┐
     ▼         ▼         ▼             ▼
┌─────────┐ ┌─────────┐ ┌──────────┐ ┌──────────┐
│ Aluno   │ │Professor│ │Responsável│ │  Escola  │
└─────────┘ └─────────┘ └──────────┘ └──────────┘</code></pre>

        <h3>Stack tecnológica prevista</h3>
        <table>
            <thead>
                <tr>
                    <th>Camada</th>
                    <th>Tecnologia</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>App Móvel</td><td>Flutter ou React Native</td></tr>
                <tr><td>Backend</td><td>API REST segura</td></tr>
                <tr><td>Banco de Dados</td><td>Criptografado</td></tr>
                <tr><td>IA</td><td>Modelos preditivos educacionais</td></tr>
                <tr><td>Integrações</td><td>Google Classroom, Sala do Futuro, Teams</td></tr>
            </tbody>
        </table>
    </section>

    <!-- FUNDAMENTAÇÃO -->
    <section>
        <h2>🔬 Fundamentação Científica</h2>
        <p>O projeto foi fundamentado em <strong>36 referências científicas nacionais e internacionais (2012–2026)</strong>, incluindo:</p>
        <ul>
            <li><strong>Metanálises</strong> — Sunday, Adesope &amp; Maarhuis (2021): 44 estudos, ~147.943 estudantes</li>
            <li><strong>Estudos experimentais</strong> — Beland &amp; Murphy (2016): 91 escolas inglesas</li>
            <li><strong>Revisões sistemáticas</strong> — Campbell et al. (2024); Gath et al. (2024)</li>
            <li><strong>Documentos UNESCO</strong> — Relatório Global de Monitoramento da Educação</li>
            <li><strong>Legislação brasileira</strong> — Lei nº 15.100/2025 e LGPD (Lei nº 13.709/2018)</li>
            <li><strong>Pesquisa de campo</strong> — Entrevista semiestruturada com professor da rede pública paulista e Centro Paula Souza (25+ anos de experiência)</li>
        </ul>
        <div class="highlight-box">
            <p><strong>Conclusão central da literatura:</strong> Regulação contextual produz melhores resultados do que extremos entre proibição absoluta e uso irrestrito.</p>
        </div>
    </section>

    <!-- LGPD -->
    <section>
        <h2>🔐 Privacidade e LGPD</h2>
        <p>O Integra Campus foi estruturado conforme os princípios da <strong>Lei Geral de Proteção de Dados</strong>:</p>
        <ul>
            <li>✅ <strong>Minimização</strong> — coleta apenas de dados indispensáveis</li>
            <li>✅ <strong>Transparência</strong> — estudante visualiza regras ativas</li>
            <li>✅ <strong>Segurança</strong> — criptografia ponta a ponta e autenticação multifator</li>
            <li>✅ <strong>Melhor interesse</strong> — proteção específica para crianças e adolescentes (Art. 14)</li>
        </ul>
        <div class="warning-box">
            <p><strong>Dados NÃO coletados:</strong> mensagens pessoais, fotos privadas, conteúdo de WhatsApp, localização contínua, gravações de tela, histórico completo de navegação.</p>
        </div>
    </section>

    <!-- IMPACTOS -->
    <section>
        <h2>📊 Impactos Esperados</h2>
        <table>
            <thead>
                <tr>
                    <th>Dimensão</th>
                    <th>Impacto</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>🎓 <strong>Aprendizagem</strong></td><td>Maior concentração, redução de distrações, engajamento acadêmico</td></tr>
                <tr><td>👩‍🏫 <strong>Professores</strong></td><td>Redução da sobrecarga, alertas automáticos, relatórios gerados por IA</td></tr>
                <tr><td>👨‍👩‍👧 <strong>Famílias</strong></td><td>Maior participação, comunicação escola-família, educação digital</td></tr>
                <tr><td>💚 <strong>Bem-estar</strong></td><td>Limites saudáveis de uso, prevenção, rede de apoio</td></tr>
            </tbody>
        </table>
    </section>

    <!-- ROADMAP -->
    <section>
        <h2>🚀 Roadmap</h2>
        <table>
            <thead>
                <tr>
                    <th>Fase</th>
                    <th>Objetivo</th>
                    <th>Prazo</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1️⃣ Pesquisa e Design</td><td>Levantamento bibliográfico, entrevistas, prototipação</td><td>2 meses</td></tr>
                <tr><td>2️⃣ MVP</td><td>Autenticação, Campus Virtual, Modo Sala de Foco, painéis</td><td>3 meses</td></tr>
                <tr><td>3️⃣ Piloto</td><td>Aplicação em escola participante</td><td>2 meses</td></tr>
                <tr><td>4️⃣ IA e Analytics</td><td>Recomendações, perfil adaptativo, relatórios automáticos</td><td>2 meses</td></tr>
                <tr><td>5️⃣ Escala Institucional</td><td>Integração com plataformas educacionais</td><td>3 meses</td></tr>
            </tbody>
        </table>
    </section>

    <!-- EQUIPE -->
    <section>
        <h2>👥 Equipe Hack'n Roll</h2>
        <table>
            <thead>
                <tr>
                    <th>Nome</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>Joaquim Pedro do Nascimento Moreira de Jesus</td></tr>
                <tr><td>Luiz Gabriel da Silva Cabrera</td></tr>
                <tr><td>Melissa Hollanda de Oliveira Alves</td></tr>
                <tr><td>Victória de Almeida Tambasco</td></tr>
            </tbody>
        </table>
        <p><strong>Instituição:</strong> Alfenas — 2026<br>
        <strong>Evento:</strong> Hackathon HackaTudo</p>
    </section>

    <!-- REFERÊNCIAS -->
    <section>
        <h2>📚 Referências Principais</h2>
        <ul>
            <li>SUNDAY, O. J.; ADESOPE, O. O.; MAARHUIS, P. L. <em>The effects of smartphone addiction on learning: A meta-analysis.</em> Computers in Human Behavior Reports, 2021.</li>
            <li>BELAND, L-P.; MURPHY, R. <em>Ill Communication: Technology, distraction and student performance.</em> Labour Economics, 2016.</li>
            <li>CAMPBELL, M. et al. <em>Evidence for and against banning mobile phones in schools: A scoping review.</em> 2024.</li>
            <li>GATH, M. E. et al. <em>Smartphones at School: A Mixed-Methods Analysis.</em> Education Sciences, 2024.</li>
            <li>UNESCO. <em>Global Education Monitoring Report 2023: Technology in Education.</em></li>
            <li>BRASIL. <em>Lei nº 15.100/2025</em> — Restrições ao uso de aparelhos eletrônicos na educação básica.</li>
            <li>BRASIL. <em>Lei nº 13.709/2018</em> — Lei Geral de Proteção de Dados Pessoais.</li>
        </ul>
    </section>

    <!-- LIMITAÇÕES -->
    <section>
        <h2>⚠️ Limitações e Trabalhos Futuros</h2>
        <p><strong>Limitações atuais:</strong></p>
        <ul>
            <li>Validação qualitativa com apenas um professor especialista</li>
            <li>Ausência de aplicação piloto em ambiente escolar real</li>
            <li>Ausência de dados longitudinais</li>
        </ul>
        <p><strong>Evoluções previstas:</strong></p>
        <ul>
            <li>Integração com wearables para bem-estar físico</li>
            <li>IA generativa para tutoria personalizada</li>
            <li>Expansão para redes municipais e estaduais</li>
        </ul>
    </section>

    <!-- RODAPÉ -->
    <footer>
        <p><strong>Licença:</strong> Projeto conceitual desenvolvido para o Hackathon HackaTudo 2026. Todos os direitos reservados à equipe Hack'n Roll.</p>
        <br>
        <p><em>"O problema não é o celular, mas seu uso sem mediação."</em></p>
        <br>
        <p>⭐ Se este projeto te inspirou, deixe uma estrela no repositório!</p>
    </footer>

</div>

</body>
</html>
