ARQUIVO INDEX.... ESTRUTURA DO CODIGO.


<!DOCTYPE html>
<html lang="pt-br">  <!--LINGUAGEM DA PAGINA-->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio</title>
    <link rel="stylesheet" href="style.css">  <!-- SERVE PARA LINKAR A PAGINA HML COM A CSS-->
</head>
<body>
      <header></header>
      <main class="apresentacao">
            <section class="apresentacao__conteudo">
                <h1 class="apresentacao__titulo">Eleve seu negócio digital a outro nível <strong class="Destaque-do-titulo"> com um Front-end de qualidade!</strong> </h1> <!--ADCIONAR O CLASS NO STRONG PARA ESPECIFICAR O LOCAL QUE SERA EDITADO-->

                <p class="apresentacao__conteudo__texto">Olá! Sou o Ryan Pelais, desenvolvedor Front-end com especialidade em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos conversar?</p>
                <div class="apresentacao__links">
                    <a class="apresentacao__links__links" href="https://Instagram.com/ryanpelais">Instagram</a>
                    <a class="apresentacao__links__links" href="https://github.com/ryanpelais">Github</a>
                </div>
            </section>
            <img src="img2.png" alt="Foto de Perfil do Ryan">

      </main>
</body>
</html>


ARQUIVO STYLE.....ESTILO DO SITE

 @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:wght@400;600&display=swap'); 

/** O procedimento acima esta importando uma fonte do google**/

* { 
    margin: 0;    /** MARGIN SERVE PARA CONFIGURAR A O TAMANHO DA MARGEM DA PAGINA**/
    padding: 0;   /** SERVE PARA CONFIGURAR O ESPAÇAMENTO DA BORDA ATÉ O CONTEUDO **/   
}

body {
    height: 100vh; /** ALTURA DA TELA, DEIXANDO 100% DA TELA DO NAVEGADOR**/
    box-sizing: border-box; /** SERVE PARA LIMITAR O ATE ONDE AS INFOMRÇÕES PODEM IR NA PAGINA PESQUISAR BOX SIZE MONZILA PARA TER REFERENCIA**/
    background: #000000; /**COR DO FUNDO DA PAGINA**/
    color: #f6f6f6; /** COR DA LETRA DA PAGINA**/
}

.Destaque-do-titulo{   /**SERVE PARA CHAMAR A CLASSE ESPECIFICADA NA PAGINA HTML**/
    color: #22d4fd; /**COR DA LETRA DA CLASSE**/
}

.apresentacao{
     display: flex;
     align-items: center; /*alinhamento do texto**/
     justify-content: space-between;
     margin: 10% 15% 
     
}

.apresentacao__conteudo{
    width: 615px;  /** PX SEGUINIFICA QUE VOCE QUER A CONFIGURAÇÃO EM PIXELS**/
    display: flex;
    flex-direction: column;
    gap: 40px;
}
.apresentacao__titulo{
    font-size: 36px;
    font-family: "Krona One", sans-serif;
}

.apresentacao__conteudo__texto{
    font-size: 22px;
    font-family:  "Montserrat", sans-serif;
}
.apresentacao__links{
    display: flex;
    justify-content:space-between;
}
.apresentacao__links__links{
    background-color: #22d4fd;
    width: 280px; /*espaçamento entre os botoes*/
    text-align: center;
    border-radius: 60px; /*borda do botão*/
    font-size: 25px;
    font-weight: 600;
    padding: 21.5px 0;  /*grossura do botão*/
    text-decoration: none;
    color:#000000;
    font-family:  "Montserrat", sans-serif;
    
}




