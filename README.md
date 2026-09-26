<!DOCTYPE HTML>
<html lang="fr">
	<head>
		<title>Mélissa CAPO-CHICHI — Portfolio Digital Marketing & Design</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>

		<!-- STYLE SOMBRE & ÉLECTRIQUE PERSONNALISÉ -->
		<style>
			/* Fond général et police */
			body, #wrapper {
				background-color: #0b0d17 !important;
				color: #c5cbe3 !important;
			}

			/* Section d'accueil / Intro */
			#intro {
				background: linear-gradient(135deg, #0b0d17 0%, #1a1c2e 50%, #120e24 100%) !important;
			}

			#intro h1 {
				color: #ffffff !important;
				text-shadow: 0 0 15px rgba(114, 9, 183, 0.6), 0 0 30px rgba(67, 97, 238, 0.4);
			}

			#intro p {
				color: #4cc9f0 !important;
			}

			/* Titres et liens */
			h1, h2, h3, h2 a, h3 a {
				color: #ffffff !important;
			}

			h2 a:hover, h3 a:hover {
				color: #4cc9f0 !important;
			}

			/* Blocs principaux et cartes de projets */
			#main {
				background-color: #121526 !important;
				border: 1px solid rgba(76, 201, 240, 0.15) !important;
				box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5) !important;
			}

			#main > .post {
				border-bottom: 1px solid rgba(255, 255, 255, 0.08) !important;
			}

			.posts > article {
				border: 1px solid rgba(255, 255, 255, 0.08) !important;
				background: rgba(255, 255, 255, 0.02) !important;
				border-radius: 8px !important;
				transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease !important;
			}

			.posts > article:hover {
				transform: translateY(-5px);
				border-color: #7209b7 !important;
				box-shadow: 0 5px 20px rgba(114, 9, 183, 0.3) !important;
			}

			/* Dates / Sous-titres */
			.date {
				color: #4cc9f0 !important;
				font-weight: 600;
			}

			/* Boutons électrisés */
			input[type="submit"],
			input[type="reset"],
			input[type="button"],
			button,
			.button {
				background-color: transparent !important;
				box-shadow: inset 0 0 0 2px #4361ee !important;
				color: #ffffff !important;
				transition: all 0.3s ease !important;
			}

			input[type="submit"]:hover,
			input[type="reset"]:hover,
			input[type="button"]:hover,
			button:hover,
			.button:hover {
				background-color: #4361ee !important;
				box-shadow: 0 0 15px rgba(67, 97, 238, 0.6) !important;
				color: #ffffff !important;
			}

			/* Navigation */
			#nav {
				background-color: #0b0d17 !important;
				border-bottom: 1px solid rgba(255, 255, 255, 0.1) !important;
			}

			#nav ul.links li.active a {
				background-color: #121526 !important;
				color: #4cc9f0 !important;
			}

			/* Pied de page et Formulaire */
			#footer {
				background-color: #080910 !important;
				border-top: 1px solid rgba(255, 255, 255, 0.08) !important;
			}

			input[type="text"], input[type="password"], input[type="email"], select, textarea {
				background: rgba(255, 255, 255, 0.05) !important;
				border-color: rgba(255, 255, 255, 0.15) !important;
				color: #ffffff !important;
			}

			input[type="text"]:focus, textarea:focus {
				border-color: #4cc9f0 !important;
				box-shadow: 0 0 8px rgba(76, 201, 240, 0.4) !important;
			}
		</style>
	</head>
	<body class="is-preload">

		<!-- Wrapper -->
			<div id="wrapper" class="fade-in">

				<!-- Intro -->
					<div id="intro">
						<h1>Mélissa Nadia<br />CAPO-CHICHI</h1>
						<p>Digital Marketing, Brand Strategy & Design Multimédia</p>
						<ul class="actions">
							<li><a href="#header" class="button icon solid solo fa-arrow-down scrolly">Continuer</a></li>
						</ul>
					</div>

				<!-- Header -->
					<header id="header">
						<a href="index.html" class="logo">Mélissa Portfolio</a>
					</header>

				<!-- Nav -->
					<nav id="nav">
						<ul class="links">
							<li class="active"><a href="index.html">Projets Récents</a></li>
						</ul>
						<ul class="icons">
							<li><a href="#" class="icon brands fa-linkedin"><span class="label">LinkedIn</span></a></li>
							<li><a href="#" class="icon brands fa-instagram"><span class="label">Instagram</span></a></li>
							<li><a href="#" class="icon brands fa-github"><span class="label">GitHub</span></a></li>
						</ul>
					</nav>

				<!-- Main -->
					<div id="main">

						<!-- Featured Post (Projet Phare : Kreamarket) -->
							<article class="post featured">
								<header class="major">
									<span class="date">Projet Phare</span>
									<h2><a href="#">KREAMARKET<br />Identité Visuelle & Brand Book</a></h2>
									<p>Conception complète de la charte graphique, choix typographique et palette de couleurs pour la marque Kreamarket.</p>
								</header>
								<a href="#" class="image main"><img src="assets/PROJET_ENTREPRISE/README.md" alt="Projet Kreamarket" /></a>
								<ul class="actions special">
									<li><a href="#" class="button large">Découvrir le projet</a></li>
								</ul>
							</article>

						<!-- Posts (Grille de Projets) -->
							<section class="posts">
								<article>
									<header>
										<span class="date">Packaging & Branding</span>
										<h2><a href="#">Chez Nikita<br />Packaging Mockup</a></h2>
									</header>
									<a href="#" class="image fit"><img src="assets/PROJET_RESTAURANT/README.md" alt="Chez Nikita" /></a>
									<p>Design de mockups de packaging sur papier avec motifs ornementaux pour le Restaurant Chez Nikita.</p>
									<ul class="actions special">
										<li><a href="#" class="button">Voir le projet</a></li>
									</ul>
								</article>
								<article>
									<header>
										<span class="date">Design Produit</span>
										<h2><a href="#">Gammes Laitières<br />Nikita Yogurt</a></h2>
									</header>
									<a href="#" class="image fit"><img src="assets/PROJET_JUS/README.md" alt="Yaourt Nikita" /></a>
									<p>Création d'étiquettes produits pour "Yaourt de Nikita" et "Yaourt au couscous" avec intégration de QR Code TikTok.</p>
									<ul class="actions special">
										<li><a href="#" class="button">Voir le projet</a></li>
									</ul>
								</article>
								<article>
									<header>
										<span class="date">Communication Visuelle</span>
										<h2><a href="#">Affiches & Pubs<br />Campagnes Marketing</a></h2>
									</header>
									<a href="#" class="image fit"><img src="assets/PROJET_AFFICHE_PUB/README.md" alt="Affiches Pub" /></a>
									<p>Série de visuels publicitaires et d'affiches créatives développées sous Adobe Photoshop.</p>
									<ul class="actions special">
										<li><a href="#" class="button">Voir le projet</a></li>
									</ul>
								</article>
								<article>
									<header>
										<span class="date">Stratégie Digitale</span>
										<h2><a href="#">Projets Agence<br />& Édition Digital</a></h2>
									</header>
									<a href="#" class="image fit"><img src="assets/PROJET_AGENCE/README.md" alt="Projets Agence" /></a>
									<p>Conception d'e-books, de présentations stratégiques et d'identités de marque pour clients et agences.</p>
									<ul class="actions special">
										<li><a href="#" class="button">Voir le projet</a></li>
									</ul>
								</article>
							</section>

					</div>

				<!-- Footer -->
					<footer id="footer">
						<section>
							<form method="post" action="#">
								<div class="fields">
									<div class="field">
										<label for="name">Nom</label>
										<input type="text" name="name" id="name" />
									</div>
									<div class="field">
										<label for="email">Email</label>
										<input type="text" name="email" id="email" />
									</div>
									<div class="field">
										<label for="message">Message</label>
										<textarea name="message" id="message" rows="3"></textarea>
									</div>
								</div>
								<ul class="actions">
									<li><input type="submit" value="Envoyer le message" /></li>
								</ul>
							</form>
						</section>
						<section class="split contact">
							<section class="alt">
								<h3>Localisation</h3>
								<p>Bénin</p>
							</section>
							<section>
								<h3>Email</h3>
								<p><a href="#">contact@melissa.com</a></p>
							</section>
							<section>
								<h3>Réseaux Sociaux</h3>
								<ul class="icons alt">
									<li><a href="#" class="icon brands alt fa-linkedin"><span class="label">LinkedIn</span></a></li>
									<li><a href="#" class="icon brands alt fa-instagram"><span class="label">Instagram</span></a></li>
									<li><a href="#" class="icon brands alt fa-github"><span class="label">GitHub</span></a></li>
								</ul>
							</section>
						</section>
					</footer>

				<!-- Copyright -->
					<div id="copyright">
						<ul><li>&copy; Mélissa CAPO-CHICHI</li><li>Design: <a href="https://html5up.net">HTML5 UP</a></li></ul>
					</div>

			</div>

		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.scrollex.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

	</body>
</html>
