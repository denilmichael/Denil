# Denil
Portal HTML
<html>
	<head>
		<meta charset="utf-8">
		<!-- <meta id="viewport" name="viewport" content="widht=device-width, user-scalable=no" >-->
		<title>MEGA PORTAL</title>		
		<link rel="stylesheet" type="text/css" href="css/estilo.css" />
		<link rel="stylesheet" type="text/css" href="plugins/font/font-awesome/css/font-awesome.css" />
		<script type="text/javascript" src="/js/script.js"></script>
	</head>


	<body>
		<div class= "topo" >
			<div class="topoint">
				<div class="topoleft">
					
					<ul>
						<li><a href="./" class="ativo">Home</a></li>
						<li><a href="Quem-Somos">Quem Somos</a></li>
						<li><a href="Anucie-Aqui">Anucie Aqui</a></li>
						<li><a href="Contatos">Contatos</a></li>
					</ul>
				</div>
				<div class="toporight">
					<a href=""><i class="fa fa-search fa-2x" style="color:red; "></i></a>
					<input type="text" name="busca" placeholder="Busca..."/>
					
					<a href=""><i class="fa fa-youtube fa-2x" style="color:red;"></i></a>
					<a href=""><i class="fa fa-twitter-square fa-2x" style="color: #58ACFA;"></i></a>
					<a href=""><i class="fa fa-facebook-square fa-2x"  style="color:blue;"></i></a>
					<a href=""><i class="fa fa-google-plus-square fa-2x"style="color:red;" ></i></a>
					<a href=""> <i class="fa fa-rss-square fa-2x" style="color:orange; "></i></a>
				</div>
		</div>
		
		<div class="topo2">
			
			<div class="topo2int">	
				<div class="logo">
					<img src="img/logo.png" border="0" width="230"/>
					
				</div>
				
				<div class="banner"style="background-color:red"></div>
			</div>			
		</div>
		<div class="menu">
			<div class="menuint">
				<ul>
					<li><a href="./" class="ativo">Home</a></li>
					<li><a href="./" class="ativo">Economia</a></li>
					
					<li>
						<a href="./" class="ativo">Entretenimento</a>
						<img src="img/arrowdown.jpg" border="0" width="7"/>
						<div class="submenu">
							<a href="./"><div class="submenuitem">Submenu 1</div></a>
							<a href="./"><div class="submenuitem">Submenu 2</div></a>
							<a href="./"><div class="submenuitem">Submenu 3</div></a>
							<a href="./"><div class="submenuitem">Submenu 4</div></a>
							<a href="./"><div class="submenuitem">Submenu 5</div></a>
					</li>

					<li>
						<a href="./" class="ativo">Esporte</a>
						<img src="img/arrowdown.jpg" border="0" width="7"/>
						<div class="submenu">
							<a href="./"><div class="submenuitem">Submenu 1</div></a>
							<a href="./"><div class="submenuitem">Submenu 2</div></a>
							<a href="./"><div class="submenuitem">Submenu 3</div></a>
							
						</div>
					</li>	
						
					<li>
						<a href="./" class="ativo">Geral</a>
						<img src="img/arrowdown.jpg" border="0" width="7"/>
						<div class="submenu">
							<a href="./"><div class="submenuitem">Submenu 1</div></a>
							<a href="./"><div class="submenuitem">Submenu 2</div></a>
							<a href="./"><div class="submenuitem">Submenu 3</div></a>
							<a href="./"><div class="submenuitem">Submenu 4</div></a>
							<a href="./"><div class="submenuitem">Submenu 5</div></a>
							
						</div>
					</li>	
						
					<li><a href="./" class="ativo">Notícias</a></li>
					<li><a href="./" class="ativo">Polícia</a></li>
					<li><a href="./" class="ativo">vídeos</a></li>
				</ul>
			</div>
		</div>
		<div class="ultimasnoticias">
			<div class="ultimanoticiasint">
				<div class="ultnoticiasaerea">
					<div class="ultimanoticiastitulo">ÚLTIMAS NOTÍCIAS</div>
					<div class="ultnoticiasnoticia">notícias ficaram aqui mesmo para teste posteriores </div>
				</div>
			</div>
		</div>
		<div class="container">
			<div class="containerint">
				<div class="leftside">
					<div class="slideshow" id="slideshow">
						<div class="slidebolinhas">
							<div class="bolinha" onclick="mudarSlide(0)"></div>
							<div class="bolinha" onclick="mudarSlide(1)"></div>
							<div class="bolinha" onclick="mudarSlide(2)"></div>
							<div class="bolinha" onclick="mudarSlide(3)"></div>
						</div>
						<div class="slideshowarea">
							<a href="http://www.google.com.br/">
								<div class="slide" style="background-image:url('http://www.google.com.br/google.jpg')">
									<div class="slideinfo">
										<div class="slideinfo_titulo">Titulo de teste 1</div>
										<div class="slideinfo_subtitulo">Subtitulo de teste</div>
									</div>
								</div>
							</a>
							<div class="slide" style="background-image:url('http://www.google.com.br/google.jpg')">
								<div class="slideinfo">
									<div class="slideinfo_titulo">Titulo de teste 2</div>
									<div class="slideinfo_subtitulo">Subtitulo de teste</div>
								</div>
							</div>
							<div class="slide" style="background-image:url('http://www.google.com.br/google.jpg')">
								<div class="slideinfo">
									<div class="slideinfo_titulo">Titulo de teste 3</div>
									<div class="slideinfo_subtitulo">Subtitulo de teste</div>
								</div>
							</div>
							<div class="slide" style="background-image:url('http://www.google.com.br/google.jpg')">
								<div class="slideinfo">
									<div class="slideinfo_titulo">Titulo de teste 4</div>
									<div class="slideinfo_subtitulo">Subtitulo de teste</div>
								</div>
							</div>
						</div>
					</div>

					<div class="widget">
						<div class="widget_titulo">NOTÍCIAS</div>
						<div class="widget_conteudo">
							<div class="noticiaarea1">
								<div class="noticiaitem noticiabig">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer Algum titulo qualquer Algum titulo qualquer Algum titulo</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
							</div>
							<div class="noticiaarea2">
								<a href="http://www.google.com.br/">
									<div class="noticiaitem">
										<div class="noticiaimg">
											<img src="" border="0" width="80" height="80" />
										</div>
										<div class="noticiatitulo">Algum titulo qualquer</div>
										<div class="noticiainfo">500 comentários</div>
									</div>
								</a>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
							</div>
							<div style="clear:both"></div>
						</div>
					</div>

					<div class="widget">
						<div class="widget_titulo">NOTÍCIAS</div>
						<div class="widget_conteudo">
							<div class="noticiaarea1">
								<div class="noticiaitem noticiabig">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer Algum titulo qualquer Algum titulo qualquer Algum titulo</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
							</div>
							<div class="noticiaarea2">
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
								<div class="noticiaitem">
									<div class="noticiaimg">
										<img src="" border="0" width="80" height="80" />
									</div>
									<div class="noticiatitulo">Algum titulo qualquer</div>
									<div class="noticiainfo">500 comentários</div>
								</div>
							</div>
							<div style="clear:both"></div>
						</div>
					</div>

				</div>
				<div class="rightside">
					<div class="widget">
						<div class="widget_titulo">SOCIAL</div>
						<div class="toporight">
							<a href=""><i class="fa fa-youtube fa-2x" style="color:red;"></i></a>
							<a href=""><i class="fa fa-twitter-square fa-2x" style="color: #58ACFA;"></i></a>
							<a href=""><i class="fa fa-facebook-square fa-2x"  style="color:blue;"></i></a>
							<a href=""><i class="fa fa-google-plus-square fa-2x"style="color:red;" ></i></a>
							<a href=""> <i class="fa fa-rss-square fa-2x" style="color:orange; "></i></a>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">ÚLTIMAS NOTÍCIAS</div>
						<div class="widget_conteudo">
							<div class="noticia_item">
								<a href="./">Titulo da notícia para que fique com pelo menos duas linhas e eu possa exemplificar direito.</a>
							</div>
							<div class="noticia_item">
								<a href="./">Titulo da notícia para que fique com pelo menos duas linhas e eu possa exemplificar direito.</a>
							</div>
							<div class="noticia_item">
								<a href="./">Titulo da notícia para que fique com pelo menos duas linhas e eu possa exemplificar direito.</a>
							</div>
							<div class="noticia_item">
								<a href="./">Titulo da notícia para que fique com pelo menos duas linhas e eu possa exemplificar direito.</a>
							</div>
							<div class="noticia_item">
								<a href="./">Titulo da notícia para que fique com pelo menos duas linhas e eu possa exemplificar direito.</a>
							</div>
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">PUBLICIDADE</div>
						<div class="widget_conteudo">
							<img src="assets/images/banner.jpg" border="0" width="275" />
						</div>
					</div>
					<div class="widget">
						<div class="widget_titulo">ENCONTRE-NOS NO FACEBOOK</div>
						<div class="widget_conteudo">
							<iframe src=https://www.facebook.com/ width="275" height="154" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true">
							</iframe>
						</div>
					</div>
				</div>
			</div>
		</div>
	</body>


</html>
