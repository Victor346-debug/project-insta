# project-insta
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagran</title>
    <link rel="stylesheet" href="index.css">
</head>

<body>

    <div class="container-imagens">
        <img src="./IMG/celular.png" class="img-celular">
        <img src="./IMG/insta1.png" class="imagem-celular">
        <img src="./IMG/insta2.png" class="imagem-celular" id="troca-imagem">
    </div>

    <div class="container-itens">
        <div class="container-form">
            <Img src="./IMG/insta-logo.png" class="insta-logo">

            <input type="email" placeholder="Telefone, nome de usuário ou email">
            <input type="password" placeholder="Senha">

            <button>Entrar</button>
            <a href="#" class="facebook">Entrar com o facebook</a>
            <a href="#" class="esquece-senha">Esqueceu a senha?</a>
        </div>

        <div class="container-caastrod">
            <p class="paragrafo-conta">Não tem uma conta?<a href="#" class="link-cadastro">Cadastre-se</a></p>
        </div>

        <p class="paragrafo-app">Obtenha o aplicativo</p>

        <div class="container-app">

            <img src="./IMG/ios.png" alt="" class="logo-app">
            <img src="./IMG/google.png" alt="" class="logo-app">
        </div>
    </div>

</body>

<script>
    let imagem = document.getElementById("troca-imagem")



    function trocaImagem() {

        if (imagem.style.opacity == 0) {
            imagem.style.opacity = 1
        }
        else {
            imagem.style.opacity = 0
        }
    }

    setInterval(function () {
        trocaImagem()
    }, 4000);







</script>

</html>
