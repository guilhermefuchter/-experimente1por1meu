# -experimente1por1meu


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>/experimente</title>

    <link rel="stylesheet" href="mobile.css" media="only screen and (max-width: 768px)">
    <link rel="stylesheet" href="desktop.css" media="only screen and (min-width: 769px)">

    <style>
        @media only screen and (max-width: 768px) {
            body {
                font-family: Arial, sans-serif;
                background-color: #f4f4f4;
                margin: 0;
                padding: 0;
                display: flex;
                justify-content: center;
                align-items: center;
                background: url('topoadv.png') no-repeat center center fixed;
                background-size: cover;
                
                
            }
            .a h2 {
                font-size: 40px;
                margin-top: 30px;
            }

          
            .a {
                background-color: white;
                width: 650px;
                margin: -10px auto;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                border-radius: 8px;
                height: 1000px;
             
            }
            .form img {
                display: block;
                margin: 0 auto 20px;
                max-width: 100%;
                height: auto;
            }
            h2 {
                text-align: center;
                color: #11c23d;
                margin-bottom: 20px;
                font-size: 40px;
                margin-top: -10px;
            }
            .lead {
                text-align: center;
                color: #555;
                margin-bottom: 45px;
            }
            .alert {
                display: none;
                margin-bottom: 20px;
            }
            .form-canvas {
                margin: 0 auto;
                max-width: 500px;
            }
            .form-group {
                margin-bottom: 15px;
            }
            .form-group label {
                display: block;
                margin-bottom: 5px;
                color: #333;
            }
            .form-control {
                width: 100%;
                padding: 10px;
                border: 1px solid #ccc;
                border-radius: 4px;
                box-sizing: border-box;
            }
            .form-control:focus {
                border-color: #11c23d;
                box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
            }
            .btn {
                display: block;
                width: 100%;
                padding: 15px;
                font-size: 18px;
                color: #fff;
                background-color: #11c23d;
                border: none;
                border-radius: 4px;
                cursor: pointer;
                margin-top: 10px;
            }
            .btn:hover {
                background-color: #0056b3;
            }
            .avisos {
                margin-top: 40px;
            }
            .aviso-criacao {
                font-size: 14px;
                color: #666;
                margin-bottom: 10px;
            }
            .aviso-criacao a {
                color: #007bff;
                text-decoration: none;
            }
            .aviso-criacao a:hover {
                text-decoration: underline;
            }
            .text-center {
                text-align: center;
            }
            .mt-2 {
                margin-top: 20px;
            }
            .pt-4 {
                padding-top: 40px;
                padding-left:10px;
                padding-right:10px;
            }
            .close {
                float: right;
                font-size: 20px;
                font-weight: bold;
                line-height: 1;
                color: #000;
                text-shadow: 0 1px 0 #fff;
                opacity: 0.5;
            }
            .close:hover {
                color: #000;
                text-decoration: none;
                cursor: pointer;
                opacity: 0.75;
            }

            .barra-topo {
                display:none;
            }
            .logotopo {
                display:none;
            }

            .form-page {    display: block;
                margin-bottom: 30px;}

            .passo1{  margin-left: 187px; margin-top: -161px;margin-bottom: 180px; color: green;font-style: italic;}  
            .passo2{  margin-left: 187px; margin-top: -161px;margin-bottom: 180px; color: green;font-style: italic;}
            .passo3{  margin-left: 187px; margin-top: -238px;margin-bottom: 245px; color: green;font-style: italic;}
            .passo4{  margin-left: 187px; margin-top: -189px;margin-bottom: 180px; color: green;font-style: italic;}


        }

        @media only screen and (min-width: 769px) {
            body {
                font-family: Arial, sans-serif;
                background-color: #f4f4f4;
                margin: 0;
                padding: 0;
                display: flex;
                justify-content: center;
                align-items: center;
                background: url('topoadvcopia1.png') no-repeat center center fixed;
                background-size: cover;
            }
            .a {
                background-color: #f7f4e9;
                width: 650px;
                margin: 50px auto;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                border-radius: 8px;
                margin-top: 200px;
            }
            .form img {
                display: block;
                margin: 0 auto 20px;
                max-width: 100%;
                height: auto;
            }
            h2 {
                text-align: center;
                color: #11c23d;
                margin-bottom: 20px;
                font-size: 40px;
                margin-top: -10px;
            }
            .lead {
                text-align: center;
                color: #555;
                margin-bottom: 20px;
            }
            .alert {
                display: none;
                margin-bottom: 20px;
            }
            .form-canvas {
                margin: 0 auto;
                max-width: 600px;
            }
            .form-group {
                margin-bottom: 15px;
            }
            .form-group label {
                display: block;
                margin-bottom: 5px;
                color: #333;
            }
            .form-control {
                width: 100%;
                padding: 10px;
                border: 1px solid #ccc;
                border-radius: 4px;
                box-sizing: border-box;
            }
            .form-control:focus {
                border-color: #11c23d;
                box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
            }
            .btn {
                display: block;
                width: 100%;
                padding: 15px;
                font-size: 18px;
                color: #fff;
                background-color: #11c23d;
                border: none;
                border-radius: 4px;
                cursor: pointer;
                margin-top: 10px;
            }
            .btn:hover {
                background-color: #0056b3;
            }
            .avisos {
                margin-top: 20px;
            }
            .aviso-criacao {
                font-size: 14px;
                color: #666;
                margin-bottom: 10px;
            }
            .aviso-criacao a {
                color: #007bff;
                text-decoration: none;
            }
            .aviso-criacao a:hover {
                text-decoration: underline;
            }
            .text-center {
                text-align: center;
            }
            .mt-2 {
                margin-top: 20px;
            }
            .pt-4 {
                padding-top: 40px;
            }
            .close {
                float: right;
                font-size: 20px;
                font-weight: bold;
                line-height: 1;
                color: #000;
                text-shadow: 0 1px 0 #fff;
                opacity: 0.5;
            }
            .close:hover {
                color: #000;
                text-decoration: none;
                cursor: pointer;
                opacity: 0.75;
            }
            .barra-topo {
                background: #FFF;
                float: left;
                width: 100%;
                height: 100px;
                padding: 15px 0;
                position: fixed;
                z-index: 99;
                transition: all .5s;
                margin-top: -445px;
            }
            .logotopo {
                width: 166px;
                margin-top: 26px;
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
            }

            .passo4{margin-left: 472px; margin-top: -191px; margin-bottom: 160px;font-size: 17px;font-style: oblique;color: green;
            }
            .passo3{margin-left: 475px; font-size: 17px;font-style: oblique;color: green;    margin-top: -240px; margin-bottom: 230px;}

            .passo2{margin-left: 476px;margin-top: -164px; margin-bottom: 160px;font-size: 17px; font-style: oblique;color: green;}

            .passo1{margin-left: 476px;margin-top: -164px; margin-bottom: 160px;font-size: 17px;font-style: oblique;color: green;}
        }
    </style>
 <script>
    document.addEventListener('DOMContentLoaded', function () {
        const formPages = document.querySelectorAll('.form-page');
        const nextButtons = document.querySelectorAll('.next-btn');
        const submitButton = document.querySelector('#btSubmitExperimente');

        let currentPage = 0;

        function showPage(page) {
            formPages.forEach((formPage, index) => {
                if (index === page) {
                    formPage.style.display = 'block';
                } else {
                    formPage.style.display = 'none';
                }
            });

            if (page === formPages.length - 1) {
                submitButton.style.display = 'block';
            } else {
                submitButton.style.display = 'none';
            }
        }

        function validatePage(page) {
            const inputs = formPages[page].querySelectorAll('.required');
            let valid = true;

            inputs.forEach(input => {
                if (!input.value) {
                    valid = false;
                    input.classList.add('is-invalid');
                } else {
                    input.classList.remove('is-invalid');
                }
            });

            return valid;
        }

        nextButtons.forEach((button, index) => {
            button.addEventListener('click', function () {
                if (validatePage(currentPage)) {
                    currentPage++;
                    showPage(currentPage);
                }
            });
        });

        showPage(currentPage);
    });
</script>
</head>

<body>
<heather>
    <div class="barra-topo">
        <img class="logotopo" src="https://www.projuris.com.br/wp-content/themes/projuris/assets/img/logo-projuris-adv-experimente.png" alt="Logo Projuris">
    </div>
</heather>

<div class="a">
    <section class="form pt-4">
        <img class="d-block mx-auto" src="https://www.projuris.com.br/wp-content/themes/projuris/assets/img/logo-projuris-adv-experimente.png" alt="Logo Projuris">
          
        <h2 style="text-align: center;">Teste grátis por 7 dias</h2>

        <p class="lead">Preencha os campos abaixo para iniciar agora</p>

        <div class="alert alert-warning alert-dismissable" style="display:none;" id="msg">
            <a href="#" class="close" onclick="$('#msg').hide()">×</a>
            <ul id="lista-msg"></ul>
        </div>
        <div class="form-canvas">
            <div class="form-offset p-4">
                <form name="trial_NovoArrendatario" id="formAssinante" autocomplete="off" method="post">
                    <input type="hidden" name="identificador" value="experimente-2020">

                    <div class="form-page lead-data active">
                        <div class="form-group">
                            <label for="company" data-bs-toggle="tooltip" data-bs-placement="top">Nome do seu escritório: <strong>*</strong></label>
                            <input name="company" type="text" class="required form-control" id="empresa" placeholder="Nome do seu escritório" required="">
                        </div>
                        <button type="button" class="btn next-btn">Próximo</button>
                        <p class="passo1">1/6</p>
                    </div>

                    <div class="form-page lead-data">
                        <div class="form-group">
                            <label for="Número de processos ativos" data-bs-toggle="tooltip" data-bs-placement="top">Quantos processos ativos a sua equipe gerencia? <strong>*</strong></label>
                            <select name="Número de processos ativos" id="custom_fields_185190" class="form-control required" placeholder="" data-bs-use-type="STRING" required="required">
                                <option value="" disabled="" selected="">Quantos processos ativos a sua equipe gerencia?</option>
                                <option value="5 mil ou mais">5 mil ou mais</option>
                                <option value="1 mil a 5 mil">1 mil a 5 mil</option>
                                <option value="500 a 1 mil">500 a 1 mil</option>
                                <option value="300 a 500">300 a 500</option>
                                <option value="50 a 300">50 a 300</option>
                                <option value="Menos de 50">Menos de 50</option>
                            </select>
                        </div>
                        <button type="button" class="btn next-btn">Próximo</button>
                        <p class="passo2">2/6</p>
                    </div>

                    <div class="form-page lead-data">
                        <div class="row">
                            <div class="form-group col-md-6 pl-0">
                                <label for="firstname" data-bs-toggle="tooltip" data-bs-placement="top">Seu nome completo: <strong>*</strong></label>
                                <input name="firstname" required="" type="text" class="required form-control" id="nome" aria-describedby="Antonio da Silva" placeholder="Seu nome completo">
                            </div>

                            <div class="form-group col-md-6">
                                <label for="Phone number">WhatsApp: <strong>*</strong></label>
                                <input name="Phone number" required="" type="text" class="required form-control maskTel" id="telefone" aria-describedby="WhatsApp" placeholder="WhatsApp" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-original-title="Campo obrigatório. Digite seu número completo com DDD." maxlength="15">
                            </div>
                        </div>
                        <button type="button" class="btn next-btn">Próximo</button>
                        <p class="passo3">4/6</p>
                    </div>

                    <div class="form-page lead-data">
                        <div class="row">
                            <div class="form-group col-md-6">
                                <label for="email" data-bs-toggle="tooltip" data-bs-placement="top">Email profissional: <strong>*</strong></label>
                                <input name="email" required="" type="email" class="required form-control" id="email" aria-describedby="Email profissional" placeholder="Email profissional">
                            </div>

                            <div class="form-group col-md-6">
                                <label for="senha" data-bs-toggle="tooltip" data-bs-placement="top">Senha: <strong>*</strong></label>
                                <input name="senha" data-bs-toggle="tooltip" data-bs-placement="top" required="" type="password" class="required form-control" id="senha" aria-describedby="Sua senha" placeholder="Sua senha">
                               
                            </div>
                            <p class="passo4 ">6/6</p>
                        </div>
                      
                    </div>

                    <input type="hidden" name="current_url" value="https://www.projuris.com.br/experimente">
                    
                    <button type="submit" id="btSubmitExperimente" class="btn btn-primary btn-block btn-lg" style="display:none;">Iniciar teste gratuito</button>
                      

                    <div class="avisos">
                        <p class="aviso-criacao">Ao criar uma conta do Projuris ADV - Software Jurídico, você concorda em aceitar nossos <a href="https://www.projuris.com.br/privacidade/" target="_blank">termos de serviço.</a></p>
                        <p class="aviso-criacao">Não será cobrada taxa automática após os 7 dias de teste gratuito, dispensado o cadastro de cartão de crédito para o teste. Você somente receberá cobrança caso prossiga com a contratação do sistema.</p>
                        <p class="aviso-criacao">O nome informado será utilizado para a captura de intimações durante o teste grátis. Busque colocar o nome completo para garantir que as intimações trazidas sejam apenas as de seu interesse</p>
                    </div>
                </form>
            </div>
        </div>
        <p class="text-center mt-2">Já possui cadastro?
            <a href="https://login.projurisadv.com.br/adv-bouncer-server/login">Entre agora</a>
        </p>


        
    </section>

    

</div>

 <!--<a href="https://api.whatsapp.com/send?phone=5511996602062&text=Ol%C3%A1%21+Tenho+interesse+em+conhecer+o+Projuris.+Podem+me+enviar+mais+informa%C3%A7%C3%B5es%3F" target="_blank" class="wpplink"></a>
            <div id="wpplogo" class="wpplogo" style="box-sizing:content-box;display:inline-block;text-align:center"><div class="onaway-icone-content onaway-IconsElement--content" style="color:green;line-height:10px;box-sizing:content-box;display:inline-block;text-align:center;height:10px;width:10px;font-size:19.5px"><svg aria-hidden="true" focusable="false" data-prefix="fab" data-icon="whatsapp" class="svg-inline--fa fa-whatsapp fa-w-14 " role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" style="width:150"><path fill="currentColor" d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"></path></svg></div></div>
</div>
-->



</body>
</html>




