<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diagnósticos e Quando Utilizá-los</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>

       
        body{
            height: 98vh;
            border: 1px dashed black;
            background-image: url(file://172.14.0.250/Public/SAC/Kenndryl/Diagnostico/logotipo.png);
            background-size: 400px;
            background-repeat: no-repeat;
            background-position: right bottom;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #000;
            color: #fff;
            font-size: 29px;
            line-height: 1.6;
        }
        .container {
            margin-top: 50px;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 10px;
        }
        h1, h2 {
            color: #007bff;
            margin-bottom: 30px;
            text-align: center;
        }
        .section {
            display: none;
            text-align: center;
        }
        .section.active {
            display: block;
            animation: fadeIn 0.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .diagnostics-list, .notes-list {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }
        .diagnostics-list li, .notes-list li {
            background-color: #333;
            margin-bottom: 8px;
            padding: 10px;
            border-radius: 5px;
            text-align: left;
        }
        .menu {
            margin-bottom: 20px;
            text-align: center;
        }
        .menu button {
            margin: 5px;
            background-color: #007bff;
            border: none;
        }
        .menu button:hover {
            background-color: #0056b3;
        }
        .slide-controls {
            margin-top: 20px;
            text-align: center;
        }
        .slide-controls button {
            margin: 0 5px;
            background-color: #007bff;
            border: none;
        }
        .slide-controls button:hover {
            background-color: #0056b3;
        }
        .slide-controls button.paused {
            background-color: #dc3545;
        }
    </style>
</head>


<body>

    <div class="container">
        <h1>Finalização de O.S</h1>
        <div class="menu">
            <button class="btn btn-primary" onclick="showSection(0)">Serviço Especifico</button>
            <button class="btn btn-primary" onclick="showSection(1)">1º - 2º - 3º Contato</button>
            <button class="btn btn-primary" onclick="showSection(2)">Diagnósticos Gerais</button>
            <button class="btn btn-primary" onclick="showSection(3)">Diagnósticos específicos</button>
            <button class="btn btn-primary" onclick="showSection(4)">Retorno de conexão</button>
            <button class="btn btn-primary" onclick="showSection(5)">Sem contato</button>
            <button class="btn btn-primary" onclick="showSection(6)">Contato suporte</button>
            <button class="btn btn-primary" onclick="showSection(7)">Monitoria</button>
            <button class="btn btn-primary" onclick="showSection(8)">Pós Monitoria</button>
            <button class="btn btn-primary" onclick="showSection(9)">Insatisfação Tecnica</button>
        </div>

        <div class="section active">
            <h2 class="section-title">INFORMATIVO</h2>
            <div class="section-content">
                <p>
                    Cliente falou que um aplicativo ou serviço ou site não consegue conectar, mas durante o atendimento retorna, sem você fazer nada na conexão, nesse caso pode sim ser gerado como informativo serviço específico, visto que o problema não seria por conta da conexão, também pode ser utilizado quando o cliente somente faz testes de velocidade e resolve sem nenhum procedimento realizado ou entra em contato mas não informa o motivo. Esse diagnóstico é utilizado para quando o problema não é de fato por conta da conexão, sempre analisar o caso do cliente, exemplo quando o cliente fala que o serviço nao conecta na nossa rede mas na rede 4g sim, bom também verificar com o N2 caso haja dúvidas.
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">1º - 2º - 3º CONTATO - SEM NAVEGAÇÃO / LENTIDÃO / QUEDAS</h2>
            <div class="section-content">
                <p>
                    Utilizável quando o cliente relata problemas com a conexão em qualquer aparelho, exemplo : ''Somente minha TV - Computador - Celular não conecta ou fica lento quando conecta'', por mais que seja somente um aparelho, o cliente teve problemas e caso não seja resolvido, pode se tornar recorrente, verificar com o N2 caso haja dúvidas.
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">DIAGNOSTICOS GERAIS</h2>
            <div class="section-content">
                <ul class="diagnostics-list">
                    <li>Alcance Wi-Fi - IDs: 319, 320 e 321</li>
                    <li>Casa Conectada - Despareamento WiFi - IDs: 322, 323 e 324</li>
                    <li>Jogos, PSN e Xbox - IDs: 316, 317 e 318</li>
                    <li>Sem navegação, Lentidão e Quedas - IDs: 247, 248 e 249</li>
                    <li>Sinal acima do padrão - IDs: 265, 328 e 329</li>
                    <li>Sem sinal Óptico, Link Loss e Board Abort - IDs: 119, 325 e 326</li>
                    <li>Tv Box e Sky Gato - IDs: 313, 314 e 315</li>
                </ul>
                <p>O TEMPO DE USO DO DIAGNÓSTICO DE 1º 2º E 3º CONTATO SERIA DENTRO DO PRAZO DE 20 DIAS NO TOTAL, NÃO 20 DIAS DO 1º PRO 2º DEPOIS MAIS 20 DIAS DO 2º PRO 3º.</p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">DIAGNOSTICOS DIRECIONADOS</h2>
            <div class="section-content">
                <p>
                    São diagnósticos direcionados para um problema em especificado pelo cliente, exemplos:
                </p>
                <ul class="diagnostics-list">
                    <li>TV BOX / SKY GATO</li>
                    <li>JOGOS / PSN / XBOX</li>
                    <li>ALCANCE WIFI</li>
                    <li>CASA CONECTADA - DESPAREAMENTO WIFI</li>
                </ul>
                <p>
                    Utilizáveis somente quando o cliente informar que o problema é somente nesses serviços, caso ele fale sobre mais aparelhos ou serviços, utilizar o SEM NAVEGAÇÃO / LENTIDÃO / QUEDAS.
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Contato por retorno de conexão</h2>
            <div class="section-content">
                <p>
                    Pode utilizar mesmo sem contato com o cliente, mas lembrando sempre de realizar a análise e deixar bem descrito na ordem para trativas futuras.
                </p>
                <ul class="notes-list">
                    <li>FEEDBACK - CONEXÃO VOLTOU SEM PROCEDIMENTO : ID 333</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Sem contato na planilha de Retorno</h2>
            <div class="section-content">
                <p>
                    Utilizado para quando não conseguir contato com o cliente da planilha de retorno, mas lembrando de realizar a análise da conexão.
                </p>
                <ul class="notes-list">
                    <li>RETORNO - SEM CONTATO COM O CLIENTE : ID 334</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Planilha de Contato Suporte</h2>
            <div class="section-content">
                <p>
                    Realize três tentativas de contato ao longo do dia nos seguintes períodos: manhã (08:30-12:00), tarde(13:00-18:00), noite (19:00-20:30).
                </p>
                <p>
                    Em cada tentativa, faça três chamadas telefônicas e envie mensagens pelo Whatsapp até o final de cada turno, se não conseguir contato por telefone.
                </p>
                <p>
                    Se todas as três tentativas durante o dia não obtiverem sucesso, consulte um monitor para avaliar a possibilidade de encerrar a ordem de serviço.
                </p>
             
                <p>
                    Em todas as tentativas de contato, registre a análise realizada, tempo de conexão, sinal e quedas, não apenas o número de protocolo de tentativa de contato.
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Quando abrir ?</h2>
            <div class="section-content">
                <p>
                    Deve ser aberta após o cliente entra em contato pela terceira vez em um prazo de 20 dias
                </p>
                <p>
                    Após aberta, deve-se realizar uma analise da conexão por 48 horas e logo apos o prazo entrar em contato para colher um FEEDBACK da conexão
                </p>
                <p>
                    Caso o cliente tenha visita em aberta, após a visita ser realizada, realizar uma analise somente e entrar em contato com o cliente, pois na visita o problema ja foi resolvido, caso o cliente ainda relate problemas <strong>ANALISAR COM N2 O QUE DEVE SER REALIZADO</strong>
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">O que fazer ?</h2>
            <div class="section-content">
                <p>
                    Gerar quando o cliente entrar em contato apos a monitoria, dentro do prazo de 20 dias no fluxograma
                </p>
                <p>
                    Apos essa ordem de pós monitoria, o fluxograma é zerado, voltando ao contato primario EX : 1º Contato etc..
                </p>
                <p>
                    Lambrando sempre de <strong>ANALISAR COM N2 O QUE DEVE SER REALIZADO</strong>
                </p>
            </div>
        </div>

        <div class="section">
            <h2 class="section-title">Planilha de Insatisfeitos</h2>
            <div class="section-content">
                <p>
                    ID PARA FINALIZAR :
                </p>
                
                <ul class="diagnostics-list">
                    <li>CONTATO - INSATISFAÇÃO TÉCNICA - ID 246</li>
                </ul>

                <p>
                    São clientes que por algum motivo estão com alguma Insatisfação com a Raimax e relatam para o CX, ou dão notas baixas pelo atendimento que teve conosco
                </p>
                <p>
                    Os contatos devem ser realizados por 3 dias, um colaborador assume por dia e no terceiro dia de contato, deve ser finalizado a ordem com ou sem sucesso de contato
                </p>
                <p>
                    Caso cliente relate problemas e seja necessário visita, <strong>ANALISAR COM N2 O QUE DEVE SER REALIZADO</strong>
                </p>
            </div>
        </div>

        <div class="slide-controls text-center">
            <button class="btn btn-primary" onclick="changeSlide(-1)">Anterior</button>
            <button class="btn btn-primary" onclick="changeSlide(1)">Próximo</button>
            <button class="btn btn-primary" onclick="toggleSlide()">Pausar Slide</button>
        </div>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const sections = document.querySelectorAll(".section");
            let currentSlide = 0;
            let slideInterval;

            function showSlide(n) {
                sections[currentSlide].classList.remove("active");
                currentSlide = (n + sections.length) % sections.length;
                sections[currentSlide].classList.add("active");
            }

            function changeSlide(n) {
                clearInterval(slideInterval);
                showSlide(currentSlide + n);
                slideInterval = setInterval(() => {
                    changeSlide(1);
                }, 8000);
            }

            function showSection(index) {
                sections.forEach((section, i) => {
                    section.classList.remove("active");
                });
                sections[index].classList.add("active");
                currentSlide = index;
                clearInterval(slideInterval);
                slideInterval = setInterval(() => {
                    changeSlide(1);
                }, 8000);
            }

            function toggleSlide() {
                const pauseButton = document.querySelector(".slide-controls button:nth-child(3)");
                if (slideInterval) {
                    clearInterval(slideInterval);
                    slideInterval = null;
                    pauseButton.classList.add("paused");
                } else {
                    slideInterval = setInterval(() => {
                        changeSlide(1);
                    }, 8000);
                    pauseButton.classList.remove("paused");
                }
            }

            document.querySelectorAll(".menu button").forEach((button, index) => {
                button.addEventListener("click", () => {
                    showSection(index);
                });
            });

            document.querySelector(".slide-controls button:first-child").addEventListener("click", () => {
                changeSlide(-1);
            });

            document.querySelector(".slide-controls button:nth-child(2)").addEventListener("click", () => {
                changeSlide(1);
            });

            document.querySelector(".slide-controls button:last-child").addEventListener("click", () => {
                toggleSlide();
            });

            slideInterval = setInterval(() => {
                changeSlide(1);
            }, 8000);
        });
    </script>
</body>
</html>
