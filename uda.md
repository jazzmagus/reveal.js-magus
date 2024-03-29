<!doctype html>
<html lang="en">

	<head>
		<meta charset="utf-8">

		<title>reveal.js - Math Plugin</title>

		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

		<link rel="stylesheet" href="../dist/reveal.css">
		<link rel="stylesheet" href="../dist/theme/serif.css" id="theme">
		<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
	</head>

	<body>

		<div class="reveal">

			<div class="slides">

				<section data-transition="zoom" data-background-opacity="0.5" data-background="https://source.unsplash.com/1920x1080/?blurred">					
					<h2>Concorso Ordinario 2021</h2>
					<h1 class="fragment fade-in">Continuità e Derivabilità</h1>
					<h2 class="fragment fade-in">per funzioni reali di variabile reale</h2>
					</p>
					<br>
					<br>
					<br>
					<br>
					<p><small>candidato: <a href="mailto:diego.fantinelli@gmail.com">diego fantinelli</a> | <b>data: </b>20 agosto 2021 | C.d.C.: A026 | <a href="/img/reveal.js - Math Plugin.pdf"><span class="material-icons">download</span><b>pdf</b></a></small
					></p>
				</section>
				
				<section data-background-video-loop data-background-opacity="0.5" data-background-video="/slides/ooo.mp4">
                    <h2 class="fragment fade-in"><em>fears increase the nearer we get to the goal.</em></h2>
                    <h5 class="fragment fade-in"><cite>Johann Wolfgang von Goethe</cite></h5>
			
				</section>  
				

				<!-- Use external markdown resource, separate slides by three newlines; vertical slides by two newlines -->
				<section 	
					data-transition="fade-in"
					data-markdown="/slides/sli.md" 
					data-separator="^\n\n\n" 
					data-separator-vertical="^\n\n">
				</section>

				<section data-background-video-loop data-background-opacity="0.5" data-background-video="/slides/ooo.mp4">
					<h3>An Identity of Ramanujan</h3>
					<div class="fragment">
							\[ \frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} =
							1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
							{1+\frac{e^{-8\pi}} {1+\ldots} } } } \]
						</div>
				</section>

				<section>
					<h3>Doing two-column </h3>
					
						<div class='multiCol'>
							<div class='col'>
								<small> est omnis divisa in partes tres, quarum unam incolunt Belgae, aliam Aquitani, tertiam qui ipsorum lingua Celtae, nostra Galli appellantur.</small>
							</div>
							
							<div class='col'>
								<img src="/img/pdf-file.png"/></a>
							</div>
						</div><small>
						And simply more regular full-width text in the following. But hey, there is also:
						<div class='multiCol'>
							<div class='col'>Also works for 3 columns...</div>
							<div class='col'>...as we can show in...</div>
							<div class='col'>...this example here.</div></small>
						</div>
				</section>
			</div>
		</div>

		<script src="../dist/reveal.js"></script>
		<script src="../plugin/math/math.js"></script>
		<script src="../plugin/markdown/markdown.js"></script>
		<script src="../plugin/highlight/highlight.js"></script>
		<script src="../plugin/notes/notes.js"></script>
		<script>
			Reveal.initialize({
				history: true,
				transition: 'convex',
				backgroundTransition: 'none',

				math: {
					// mathjax: 'https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js',
					config: 'TeX-AMS_HTML-full',
					TeX: {
						Macros: {
							R: '\\mathbb{R}',
							set: [ '\\left\\{#1 \\; ; \\; #2\\right\\}', 2 ]
						}
					}
				},

				plugins: [ RevealMath, RevealMarkdown, RevealHighlight, RevealNotes ]
			});
		</script>
		
	</body>
</html>
