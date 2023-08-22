# bibliotecapedrobusko2023
pedrobuskobiblioteca
<!DOCTYPE html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Start</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com"&gt;
    <link rel="preconnect" href="https://fonts.gstatic.com&quot; crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&family=Poppins&display=swap&quot;
        rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class="cabecalho">
        <div class="conteiner">
            <input type="checkbox" id="menu" class="conteiner__botao">
            <label for="menu">
                <span class="cabecalho__menu conteiner__imagem"> </span>
            </label>


            <img class="cabecalho__logo conteiner__imagem " src="img/Logo.svg" alt="logo da biblioteca start">
           
            <h1 class="conteiner__titulo">Biblioteca<b class="conteiner__titulo--negrito">Start</b></h1>

            <ul class="lista__menu">

                <li class="lista__menu-titulo">Categorias</li>

                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="https://www.youtube.com/">Aventura</a&gt;
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Biografia</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Ficção Científica</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Romance</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Vestibular</a>
                </li>

            </ul>
        </div>
        <ul class="opcoes">
            <input type="checkbox"  id="opcoes-menu" class="opcoes__botao">
            <label for="opcoes-menu">
            <li class="opcoes__item">Categorias</li>
            </label>
            <ul class="lista-menu">
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Biografia</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Ficção Científica</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Romance</a>
                </li>
                <li class="lista__menu-item">
                    <a class="lista__menu-link" href="#">Vestibular</a>
                </li>  
            </ul>
            <li class="opcoes__item">
                <a href="" class="opcoes__link">Favoritos</a>
            </li>
            <li class="opcoes__item">
                <a href="" class="opcoes__link">Meus Empréstimos</a>
            </li>
        </ul>
        <div class="conteiner">
            <a href="#"><img class="conteiner__imagem conteiner__favorito" src="img/Favoritos.svg" alt="Favoritos"></a>
            <a href="#"class="conteiner__link"><img class="conteiner__imagem" src="img/Emprestimos.svg" alt="Emprestimos"></a>
            <p class="conteiner__texto">Meus Emprestimos</p>
            <a href="#"class="conteiner__link"><img class="conteiner__imagem" src="img/Usuario.svg" alt="usuario"></a>
            <p class="conteiner__texto">Meu Perfil</p>
        </div>
    </header>
</body>

</html>llll