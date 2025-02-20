# Fórum GEAM #1 - Introdução e apresentação

### Nessa primeira parte da nossa colaboração iremos explorar a ferramenta de edição e o banco de dados que iremos utilizar. Criaremos o nosso projeto e faremos a configuração para a conexão.

 - Você pode acompanhar o tutorial também em [vídeo](https://youtu.be/bcHBpEcdvq0).

## Criando a aplicação

 - Essa é a interface do nosso editor e onde iremos desenvolver nosso código. Na imagem já podemos ver a aba de ferramentas, onde podemos manipular a IDE e o projeto como arquivo (1); A aba de projeto no lado esquerdo, onde as pastas da aplicação ficam organizadas, podendo ser alterado o tipo de visualização (2); Onde adicionamos e selecionamos o tipo de emulador que iremos utilizar para a nossa aplicação (3); E por fim onde executamos o nosso projeto (4).

<img src="imagens/print 1.jpg">

 - Ao entrar na IDE, nosso primeiro passo é a criação do nosso projeto. Preenchemos com o nome da aplicação e com o nome do dominio para o projeto.

<img src="imagens/print 2.jpg" >

- O próximo passo é a escolha do layout inicial, no nosso caso, como iremos criar o design do zero no próximo episódio, não importa tanto. Iniciamos com uma actvity vazia e damos início a criação do projeto pela IDE.

<img src="imagens/print 3.jpg">

 - Após a criação do projeto, iremos definir qual emulador utilizar. Primeiramente selecionamos qual o hardware em que iremos reproduzir nossa aplicação, no caso, aparelho celular (1); O modelo do aparelho (2); E por fim seguimos (3).

<img src="imagens/print 5.jpg">  

 - Em seguida iremos seleciona o tipo de sistema a ser instalado (1). A escolha de um sistema android que cubra um número de usuários desejável é fundamental, assim nossa aplicação poderá ser utilizada por vários usuários e dispositivos sem conflitos. Selecionamos a versão desejada (2); Seguimos para o próximo (3).

<img src="imagens/print 6.jpg">

 - Por fim selecionamos a orientação em que a aplicação irá ser executada e checamos as informações do aparelho, bem como as dimensões e memória (1); Seguimos com a finalização (2).

<img src="imagens/print 7.jpg">

## Criação do Banco de Dados

 - Após a criação do projeto e do nosso emulador, iremos iniciar a configuração do nosso data base, no caso o Firebase. Com uma simples pesquisa no navegador conseguimos encontrar o Firebase

<img src="imagens/print 8.jpg">

 - Após entrar com a sua conta do google, temos a visão geral do Firebase, onde podemos acessar o console do gerenciador (1).

<img src="imagens/print 9.jpg">

 - No console temos os data bases já criados (1) e a opção de criar um novo data base (2).

<img src="imagens/print 10.jpg">

 - Escolhemos o nome do nosso data base.

<img src="imagens/print 11.jpg">

 - Fornecer o acesso ao Google Analytics é opcional.

<img src="imagens/print 12.jpg">

 - Caso queira dar acesso, selecione a conta padrão do Firebase.

<img src="imagens/print 13.jpg">

 - Após a criação do projeto, temos a visão geral do gerenciador. Podemos observar no lado esquerdo a aba de ferramentas, onde podemos gerenciar a autenticação (1), o próprio bando de dados (2) e o Storage, onde serão armazenadas as mídias da nossa aplicação (3).

<img src="imagens/print 14.jpg"> 

 - Ao clicar na autenticação, iremos selecionar o tipo de verificação que teremos para o login.

<img src="imagens/print 15.jpg">

 - Após clicar na configuração do método de login, iremos selecionar o tipo de entrada. No caso, e-mail e senha (1).

<img src="imagens/print 16.jpg">

 - Ao selecionar o meio, ativamos a sua entrada (1) e salvamos.

<img src="imagens/print 17.jpg"> 

 - Pronto, nosso banco de dados no Firebase está criado. Voltamos para a IDE.

## Conexão com o Firebase

 - Primeiramente iremos conectar nossa conta do google com o Android Studio. O ícone do usuário fica localizado no canto superior direito, como mostra na figura abaixo:

<img src="imagens/Print 18.jpg">

 - Ao clicar e selecionar o login, o navegador será aberto e irá solicitar permissão para o acesso.

<img src="imagens/print 19.jpg"> 

 - Após conceder a permissão a sua aplicação já estará conectada.

<img src="imagens/print 20.jpg">

 - De volta a IDE, iremos solicitar a conexão com o Firebase. O próprio Android Studio já nos fornece essa ferramenta, o que facilita bastante nesse processo. Selecionamos o menu Tools e dentro dele a opção Firebase.

<img src="imagens/print 21.jpg">

 - Ao selecionarmos essa opção, uma aba de informações irá aparecer no lado direito. Buscamos a opção Firestore e em seguida a opção que aparecerá, "Read and write documents with Cloud Firestore" (1).

<img src="imagens/print 22.jpg"> 

 - Ao selecionar, outra aba de ajuda para a conexão irá aparecer com as opções de conectar ao Firebase (1) e adicioná-lo ao seu projeto (2).

<img src="imagens/print 24.jpg"> 

 - Ao selecionar a primeira opção, uma janela de conexão irá aparecer, onde você pode escolher entre criar um novo banco de dados (1) ou utilizar um já existente na sua conta (2). Como já criamos anteriormente, iremos selecionar o banco ForumGEAM e prosseguir.

<img src="imagens/print 25.jpg">

 - Ao selecionar a segunda opção, uma janela de permissão para alteração no projeto irá aparecer, onde a IDE irá adicionar linhas de conexão no arquivo Gradle do projeto, dando as permissões para conexão com o data base via rede.

<img src="imagens/print 26.jpg">

 - Após isso, ambas as opções estarão concluidas e o acesso ao data base configurado e liberado.

<img src="imagens/print 23.jpg">

 - Quando retornamos ao console do Firebase podemos observar que há um aplicativo já vinculado ao database e o nome condiz com o projeto criado.

<img src="imagens/print 27.jpg">

### Esse foi o nosso primeiro contato com a série de desenvolvimento da aplicação para o Fórum do GEAM, onde configuramos e preparamos o nosso ambiente de desenvolvimento. No próximo episódio iremos definir o layout e design da aplicação e formar a nossa primeira tela de login. Não deixem de assistir o vídeo no canal! Até a próxima!
