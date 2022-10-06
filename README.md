# Projetoemgrupo-Modulo1 
Nosso projeto foi criar uma site para ajudar um negócio local.
Surgiu no grupo a ideia de criarmos um e-commerce voltado para o publico feminino de sapatos.
Tínhamos como objetivo criar um site que tivesse ao menos 4 paginas, 
sendo elas “quem somos”, “nossos produtos/serviços”, “nossa equipe” e uma página de “formulário de contato”, dividimos as páginas entre os integrantes do grupo.
Eu fiquei responsável pela página de formulário de contato.
Na pagina o menu e o rodapé foram feitos pelo Boodstrap por outro integrante do Grupo.
Já o formulário de contato em si, a estruturação da página usei o HTML,
já para a estilização fiz pelo CSS e a responsividade também ficou por conta da Media Query também no CSS,
já a parte de de validação dos dados ficou por conta do JavaScript

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de contato</title>
</head>
<body>
    <div class="container">

        <div id ="contato_form">

            <div class="formulario">

             <form name="formulario" onsubmit="return validar(this);" action="enviar.html" method="post">
               <!--<input type="hidden" name="destino" value="kellyshoes@gmail.com" /> Serve para receber os dados quando a pagina estiver hospedada, por enquanto esta só de exemplo--->
           
               <input type="hidden" name="enviado" value="file:///C:/Users/Programador.Carioca/Desktop/M%C3%B3dulo%201/contatoteste.html" />
             
              
                <h2>Entre em contato:</h2><br>

                  <input name="nome" placeholder="Nome *"><br>

                  <input name="email" placeholder="E-mail *"><br>

                  <input name="assunto" placeholder="Assunto *"><br>

                  <textarea name="mensagem" cols="46" rows="8" placeholder="Mensagem *"></textarea><br>

                  <input type="submit" value="Enviar"><br><!--Botão para enviar a mensagem-->

              </form>
            </div> <!--Fechamento da div formulário-->            

      <div id="maps"> <!--Caminho pra inserir o Maps no Container-->
           <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d3783.057166357215!2d-43.559463866367274!3d-22.90005572324727!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1spt-BR!2sbr!4v1664743917340!5m2!1spt-BR!2sbr" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" width="380px" height="380px"></iframe>
           
    
      <div id="sociais"> <!--Caminho pra inserir os links de acesso as redes sociais da Kelly Shoes-->
        <h5>Conheça nossas redes sociais:</h5>
          <a href="https://instagram.com"><img src="img/slides/insta.png" width="15px" height="15px"></a> 
          <a href="https://facebook.com"><img src="img/slides/face.png" width="15px" height="15px"></a>

      </div><!--Fechamento da dic Contato_form-->
      </div><!--Fechamento da div Maps-->
      </div><!--Fechamento da div Sociais-->
    </div><!--Fechamento da div Container-->
</body>
</html>
