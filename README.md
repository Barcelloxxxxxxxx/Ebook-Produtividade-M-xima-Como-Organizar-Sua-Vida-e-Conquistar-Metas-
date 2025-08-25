<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produtividade Máxima: Como Organizar Sua Vida e Conquistar Metas</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --success: #27ae60;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: #333;
            line-height: 1.6;
            background-color: #f9f9f9;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .hero {
            padding: 60px 0;
            text-align: center;
            background-color: white;
        }
        
        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
            color: #555;
        }
        
        .cta-button {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 15px 40px;
            font-size: 1.2rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        
        .cta-button:hover {
            background-color: #c0392b;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.15);
        }
        
        section {
            padding: 60px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: var(--primary);
        }
        
        .benefits {
            background-color: var(--light);
        }
        
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .benefit-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            text-align: center;
        }
        
        .benefit-icon {
            font-size: 2.5rem;
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        .methodology {
            background-color: white;
        }
        
        .method-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .method-card {
            background: var(--light);
            padding: 25px;
            border-radius: 10px;
            text-align: center;
        }
        
        .method-letter {
            font-size: 2rem;
            font-weight: bold;
            color: var(--secondary);
            margin-bottom: 15px;
        }
        
        .pricing {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            text-align: center;
        }
        
        .price-box {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 10px;
            max-width: 600px;
            margin: 0 auto;
            backdrop-filter: blur(10px);
        }
        
        .price {
            font-size: 3rem;
            font-weight: bold;
            margin: 20px 0;
        }
        
        .guarantee {
            margin: 20px 0;
            font-style: italic;
        }
        
        .faq-item {
            margin-bottom: 20px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.05);
        }
        
        .faq-question {
            font-weight: bold;
            margin-bottom: 10px;
            color: var(--primary);
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            
            .cta-button {
                padding: 12px 30px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Produtividade Máxima</div>
            <div class="tagline">Organize sua vida e conquiste suas metas</div>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <h1>Domine Seu Tempo e Alcance Suas Metas: O Guia Definitivo de Produtividade</h1>
            <p>Descubra estratégias comprovadas, exercícios práticos e ferramentas essenciais para organizar sua vida, eliminar a procrastinação e conquistar resultados extraordinários — mesmo com uma rotina agitada.</p>
            <a href="#pricing" class="cta-button">Quero Garantir Meu Acesso Imediato!</a>
        </div>
    </section>
    
    <section class="benefits">
        <div class="container">
            <h2 class="section-title">O que você vai encontrar neste ebook</h2>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <div class="benefit-icon">📋</div>
                    <h3>Questionários de Autoavaliação</h3>
                    <p>Identifique seus pontos de melhoria e acompanhe seu progresso.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🛠️</div>
                    <h3>Exercícios Práticos</h3>
                    <p>Aplicação imediata dos conceitos com atividades ao final de cada capítulo.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">📊</div>
                    <h3>Casos Reais</h3>
                    <p>Exemplos reais que ilustram a transformação possível com as metodologias.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">⚙️</div>
                    <h3>Ferramentas Recomendadas</h3>
                    <p>Trello, Notion, Pomodoro e outros recursos para potencializar sua produtividade.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🌅</div>
                    <h3>Rotinas Matinais e Noturnas</h3>
                    <p>Roteiros para consolidar hábitos produtivos no seu dia a dia.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">💪</div>
                    <h3>Técnicas de Motivação</h3>
                    <p>Estratégias para manter o foco e a consistência mesmo nos dias difíceis.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section class="methodology">
        <div class="container">
            <h2 class="section-title">Conheça o Método P.A.R.A.</h2>
            <p style="text-align: center; margin-bottom: 40px; max-width: 800px; margin-left: auto; margin-right: auto;">
                Este é o método exclusivo que norteia o ebook "Produtividade Máxima" e garante transformação real na vida de quem aplica. Não é só teoria: é um sistema passo a passo, testado e validado por profissionais e empreendedores.
            </p>
            <div class="method-cards">
                <div class="method-card">
                    <div class="method-letter">P</div>
                    <h3>Planejamento Inteligente</h3>
                    <p>Aprenda a definir metas claras e alcançáveis usando a metodologia SMART e técnicas de priorização.</p>
                </div>
                <div class="method-card">
                    <div class="method-letter">A</div>
                    <h3>Ação com Foco</h3>
                    <p>Utilize a Técnica Pomodoro e outras ferramentas comprovadas para eliminar distrações.</p>
                </div>
                <div class="method-card">
                    <div class="method-letter">R</div>
                    <h3>Rotinas Transformadoras</h3>
                    <p>Desenvolva hábitos matinais e noturnos que preparam seu corpo e mente para alta performance.</p>
                </div>
                <div class="method-card">
                    <div class="method-letter">A</div>
                    <h3>Autogestão Mental</h3>
                    <p>Fortaleça sua mentalidade, combata a procrastinação e mantenha a motivação.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="pricing" class="pricing">
        <div class="container">
            <h2 class="section-title">Transforme Sua Produtividade Agora!</h2>
            <div class="price-box">
                <p>Ebook completo em PDF</p>
                <div class="price">R$ 29,90</div>
                <p>Acesso imediato e vitalício após a compra</p>
                <p class="guarantee">✅ Garantia de 7 dias ou seu dinheiro de volta</p>
                <a href="#" class="cta-button">Quero Comprar Agora!</a>
            </div>
        </div>
    </section>
    
    <section class="faq">
        <div class="container">
            <h2 class="section-title">Perguntas Frequentes</h2>
            <div class="faq-list">
                <div class="faq-item">
                    <div class="faq-question">O que inclui o ebook?</div>
                    <div class="faq-answer">O ebook é um guia completo em PDF com 6 capítulos, incluindo métodos comprovados (SMART, Pomodoro, Eisenhower, GTD), exercícios práticos, questionários de autoavaliação, casos reais, rotinas matinais/noturnas e dicas de ferramentas digitais.</div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">Como recebo o ebook?</div>
                    <div class="faq-answer">Após a confirmação do pagamento, você receberá um link para download imediato do arquivo PDF. Não requer login ou senha.</div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">Há suporte ou garantia?</div>
                    <div class="faq-answer">Oferecemos garantia incondicional de 7 dias. Se não gostar, reembolsamos 100% do valor.</div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">É adequado para estudantes ou apenas profissionais?</div>
                    <div class="faq-answer">O conteúdo é universal! Aplica-se a profissionais, estudantes, empreendedores e qualquer pessoa que queira organizar sua vida e metas.</div>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>Produtividade Máxima - Todos os direitos reservados</p>
            <p>Made with GRANDAR</p>
        </div>
    </footer>
</body>
</html>
