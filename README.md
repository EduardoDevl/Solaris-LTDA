<!DOCTYPE html>
<html lang="pt-br">

	<head>

		<title>Solaris</title>
		<meta charset="utf-8">
		<link rel="shortcut icon" type="text/css" href="img/solaris.png">
		<link rel="stylesheet" type="text/css" href="reset.css">
		<link rel="stylesheet" type="text/css" media="screen and (min-width: 500px)" href="Style.css">
		<script type="text/javascript" src="node_modules/jquery/dist/jquery.min.js"></script>
		<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap" rel="stylesheet">
		<link href="https://fonts.googleapis.com/css2?family=Karla&display=swap" rel="stylesheet">
		<link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
		<link href="https://fonts.googleapis.com/css2?family=Abel&display=swap" rel="stylesheet">
		<script rel="stylesheet" type="text/javascript" src="script.js"></script>

	</head>

	<body>

		<div class="carregando" id="carregando"><img src="img/carregando.gif"></div>
		<div class="corpo" id="corpo">

			<div id="progressbar"></div>

			<header>
				
				<strong class="menu">
					<input type="checkbox" id="check">
					<label id="icone" for="check"><img draggable="false" src="img/icone.png"></label>
								
					<div class="barra">
									
						<nav>

							<a href="Maquininha.html"><div class="link">Maquininhas</div></a>
							<a href="Ajuda.html"><div class="link">Ajuda</div></a>
							<a href="Cadastro.html"><div class="link">Crie sua conta</div></a>
							<a href="Login.html"><div class="link">Já sou Solaris</div></a>
							<a href="Contato.html"><div class="link">Contato</div></a>

						</nav>

					</div>

					<nav class="menu-drop">

						<ul>
					    <a href="Conteúdo.html"><li>Conteúdo</li></a>

						<a href="Taxa.html" tabindex="0"><li>Taxa</li></a>
						<a href="maquininhas.html" tabindex="0"><li>Maquininhas

							<ul>

								<a href="VeroBlock.html"><li>Vero Block</li></a>
								<a href="Verosinha.html"><li>Verosinha</li></a>

							</ul>

						</li></a>

						</ul>		

					</nav>	
				</strong>

			</header>			

			<section class="img-SOlaris">

				<img alt="Logo da Solaris Maquininhas" src="img/solaris1.png" draggable="false" width="200" height="200" class="img-principal" href="solaris.html">

			</section>

			<article class="text center">

				<dd>

					<img alt="imagem de maquininhas da Vero" class="anuncio" draggable="false" src="img/vero.png">
					<h1 class="descontoh1"><p>Escolha a sua maquininha<br>com até 20% de desconto</h1>
					<h2 class="descontoh2">Temos todos os tipos de maquininhas,<br> que você desejar</p></h2>

					<a href="Compre.html" tabindex="0" class="compreaqui">Compre aqui</a>

				</dd>

			</article>

			<dd>

				<h1 class="h1text-propaganda">Trocas em até 2 dias</h1>
				<h2 class="h2text-propaganda">Nossa logística realiza entregas e manutenção da sua maquininha no dia seguinte.<br>Tudo sem cobrar nada a mais por isso, nós trabalhamos 24h por dia 7 dias<br> por semana, agilidade e eficiência é o nosso lema.</h2>
					
			</dd>

			<img alt="GIF de caixas sendo colocas dentr de um caminhão" src="img/caminhao.gif" draggable="false" class="gif-nego">

			<dd class="verosinha">

				<h1 class="apre-verosinha-pergunta">Você é um autônomo e procura uma solução<br> fácil para começar seu negócio?</h1>
				<h1 class="apre-verosinhah1">Conheça já a Verosinha!!</h1>
				<h2 class="apre-verosinhah2">Perfeita para quem está começando agora,<br> fácil de usar, eficiente e portatil junte<br>o util ao agradavel.</h2>

			</dd>

			<a href="Compre-verosinha.html" tabindex="0" draggable="false" class="compreaqui-verosinha">Compre aqui</a>

			<img alt="Imagem da verosinha maquininha pequena e portatil" class="verosinha-img" src="img/verosinha.png">


			<section class="btn-voltar jbtn-voltar">

				<img src="img/subir-btn.png" draggable="false" class="btn-voltar jbtn-voltar " width="30" height="30">

			</section>

			<script type="text/javascript" src="https://code.jquery.com/jquery-3.4.1.js"></script>
			<script type="text/javascript">
				$(window).scroll(function(){
					var scroll = $(window).scrollTop(),
					dh = $(document).height(),
					wh = $(window).height();
					scrollPercent = (scroll / (dh - wh)) * 100;
					$('#progressbar').css('height', scrollPercent + '%');
				})
			</script>

			<footer >

				<img src="img/solaris-trans.png" class="solaris-trans">
				<img src="img/fundo.png" class="rodape-pg" draggable="false">	

				<section id="redes-sociais">

					<div class="rede" id="facebook">
						<img class="icone" src="img/redimencionado/facebook.png" draggable="false">
					</div>
					<div class="rede" id="twitter">
						<img class="icone" src="img/redimencionado/twitter.png" draggable="false">
					</div>
					<div class="rede" id="instagram">
						<img class="icone" src="img/redimencionado/instagram.png" draggable="false">
					</div>
					<div class="rede" id="snap">
						<img class="icone" src="img/redimencionado/snap.png" draggable="false">
					</div>
					<div class="rede" id="plus">
						<img class="icone" src="img/redimencionado/plus.png" draggable="false">
					</div>
					<div class="rede" id="youtube">
						<img class="icone" src="img/redimencionado/youtube.png" draggable="false">
					</div>

				</section>			

			</footer>

		</div>

	</body>

</html>
