<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil GitHub</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .wave {
            font-size: 1.5em;
            animation: wave 2s infinite;
        }
        
        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(20deg); }
            75% { transform: rotate(-20deg); }
        }
        
        .tech-section {
            margin: 25px 0;
        }
        
        .tech-section h3 {
            color: #2d3748;
            margin-bottom: 15px;
            font-size: 1.3em;
            border-left: 4px solid #667eea;
            padding-left: 10px;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 20px;
        }
        
        .badge {
            transition: transform 0.2s ease;
        }
        
        .badge:hover {
            transform: translateY(-2px);
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .stat-card {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        
        .about {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .contact {
            text-align: center;
            margin-top: 30px;
        }
        
        .contact a {
            color: #667eea;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }
        
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Olá! Bem-vindo ao meu GitHub <span class="wave">🖐️</span></h1>
            <p>Desenvolvedor Full Stack apaixonado por tecnologia e inovação</p>
        </div>

        <div class="about">
            <h3>💫 Sobre mim</h3>
            <p>Sou um desenvolvedor em constante evolução, sempre buscando aprender novas tecnologias e criar soluções inovadoras. Tenho experiência em desenvolvimento web moderno e trabalho com diversas tecnologias do ecossistema JavaScript.</p>
        </div>

        <div class="tech-section">
            <h3>🚀 Linguagens & Tecnologias Frontend</h3>
            <div class="badges">
                <img class="badge" alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
                <img class="badge" alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
                <img class="badge" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
                <img class="badge" alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
                <img class="badge" alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
                <img class="badge" alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
            </div>
        </div>

        <div class="tech-section">
            <h3>🗄️ Banco de Dados</h3>
            <div class="badges">
                <img class="badge" alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
                <img class="badge" alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
                <img class="badge" alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
            </div>
        </div>

        <div class="tech-section">
            <h3>🛠️ Ferramentas & Plataformas</h3>
            <div class="badges">
                <img class="badge" alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
                <img class="badge" alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
                <img class="badge" alt="VS Code" src="https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
                <img class="badge" alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
            </div>
        </div>

        <div class="stats">
            <div class="stat-card">
                <h4>📊 Nível de Experiência</h4>
                <p><strong>TypeScript:</strong> Intermediário</p>
                <p><strong>Next.js:</strong> Intermediário</p>
                <p><strong>JavaScript:</strong> Avançado</p>
            </div>
            <div class="stat-card">
                <h4>🎯 Foco Atual</h4>
                <p>Desenvolvimento Full Stack</p>
                <p>Arquitetura de Software</p>
                <p>Performance Web</p>
            </div>
        </div>

        <div class="tech-section">
            <h3>📈 Estatísticas GitHub</h3>
            <div style="text-align: center;">
                <img src="https://github-readme-stats.vercel.app/api?username=SEU_USERNAME&show_icons=true&theme=radical" alt="GitHub Stats" style="margin: 10px;" />
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USERNAME&layout=compact&theme=radical" alt="Top Languages" style="margin: 10px;" />
            </div>
        </div>

        <div class="about">
            <h3>🌟 Projetos em Destaque</h3>
            <ul>
                <li><strong>Sistema de E-commerce:</strong> Aplicação completa com Next.js, TypeScript e MongoDB</li>
                <li><strong>Dashboard Analytics:</strong> Interface moderna com React e integração MySQL</li>
                <li><strong>API RESTful:</strong> Backend robusto com Node.js e autenticação JWT</li>
            </ul>
        </div>

        <div class="contact">
            <h3>📫 Vamos nos conectar!</h3>
            <p>
                <a href="mailto:seu.email@exemplo.com">📧 Email</a>
                <a href="https://linkedin.com/in/seu-perfil">💼 LinkedIn</a>
                <a href="https://twitter.com/seu-usuario">🐦 Twitter</a>
            </p>
        </div>

        <div style="text-align: center; margin-top: 30px; padding-top: 20px; border-top: 1px solid #e1e4e8;">
            <p><em>"Código limpo não é escrito seguindo um conjunto de regras. Você não se torna um artesão de software aprendendo uma lista do que fazer e não fazer. Profissionalismo e artesanato vêm de valores que dirigem disciplinas."</em></p>
            <p><strong>- Robert C. Martin</strong></p>
        </div>
    </div>
</body>
</html>
\`\`\`

Criei um perfil de GitHub moderno e profissional que inclui:

## ✨ **Características principais:**

- **Design responsivo** com gradientes modernos
- **Animação na saudação** com emoji que balança
- **Badges organizados por categoria:**
  - Frontend: HTML5, CSS3, JavaScript, TypeScript, Next.js, React
  - Banco de Dados: MongoDB, MySQL, PostgreSQL
  - Ferramentas: Node.js, Git, VS Code, Vercel

## 🎯 **Seções incluídas:**

1. **Header atrativo** com saudação personalizada
2. **Sobre mim** - descrição profissional
3. **Tecnologias organizadas** por categoria
4. **Níveis de experiência** destacando TypeScript e Next.js como intermediário
5. **Estatísticas do GitHub** (você precisa substituir "SEU_USERNAME")
6. **Projetos em destaque** com exemplos
7. **Informações de contato**
8. **Citação inspiradora** sobre programação

## 🔧 **Para personalizar:**

- Substitua "SEU_USERNAME" pelas suas estatísticas reais do GitHub
- Atualize os links de contato com suas informações
- Modifique os projetos em destaque com seus próprios projetos
- Ajuste os níveis de experiência conforme sua evolução

