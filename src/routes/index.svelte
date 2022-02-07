<script>
	import Navbar from '../components/Navbar/index.svelte';
	import Header from '../components/Header/index.svelte';
</script>

<svelte:head>
	<title>Jonathas Andrade - Desenvolvedor Full-Stack</title>
</svelte:head>

<Navbar />

<Header />

<section id="projects" class="bg-gray-800">
	<div class="container mx-auto py-28 px-8 md:px-0">
		<div class="section-wrapper flex flex-col md:flex-row items-center gap-16">
			<div class="section-description flex-1 flex flex-col gap-4" data-aos="fade">
				<p class="text-gray-400 font-light" data-aos="fade-up">🚀 #projetos</p>
				<h1 class="max-w-lg text-5xl font-bold">
					Confira alguns de <span
						class="bg-clip-text text-transparent bg-gradient-to-b from-green-400 to-blue-400 font-extrabold"
						>meus projetos</span
					> mais recentes.
				</h1>
				<p class="max-w-md text-gray-400 font-medium mb-6">
					Toda a minha paixão por desenvolvimento aplicada nos projetos seguintes construídos com as
					bibliotecas que mais utilizo no dia-a-dia.
				</p>
				<a
					href="https://github.com/eljonathas?tab=repositories"
					target="_blank"
					rel="noopener noreferrer"
					class="flex bg-gray-700 w-full md:w-max py-3 px-6 justify-center items-center rounded-lg font-medium transition-all ease-linear hover:bg-gray-600 active:bg-gray-700"
					><i class="fab fa-github mr-2" /> Veja todos os projetos</a
				>
			</div>
			<div class="section-content flex-1">
				<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
					<div class="project-card flex flex-col gap-4" data-aos="fade">
						<div class="project-card-image">
							<a
								class="ease-linear hover:brightness-75"
								href="https://burnout.jandrade.dev/"
								target="_blank"
								rel="noopener noreferrer"
							>
								<img
									src="/images/burnout.png"
									alt="Burnout website"
									class="rounded-lg object-cover h-40 w-full"
								/>
							</a>
						</div>
						<div class="project-card-description flex flex-col">
							<h2 class="font-semibold">Burnout nas Empresas</h2>
						</div>
					</div>
					<div class="project-card flex flex-col gap-4" data-aos="fade">
						<div class="project-card-image">
							<a
								class="ease-linear hover:brightness-75"
								href="https://devspaidegua.com/"
								target="_blank"
								rel="noopener noreferrer"
							>
								<img
									src="/images/devspaidegua.png"
									alt="Devs Pai D'égua website"
									class="rounded-lg object-cover h-40 w-full"
								/>
							</a>
						</div>
						<div class="project-card-description flex flex-col">
							<h2 class="font-semibold">Devs Pai D'égua</h2>
						</div>
					</div>
					<div class="project-card flex flex-col gap-4" data-aos="fade">
						<div class="project-card-image">
							<a
								class="ease-linear hover:brightness-75"
								href="https://cryptowl-app.herokuapp.com/"
								target="_blank"
								rel="noopener noreferrer"
							>
								<img
									src="/images/cryptowl.png"
									alt="random"
									class="rounded-lg object-cover h-40 w-full"
								/>
							</a>
						</div>
						<div class="project-card-description flex flex-col">
							<h2 class="font-semibold">Cryptowl</h2>
						</div>
					</div>
					<div class="project-card flex flex-col gap-4" data-aos="fade">
						<div class="project-card-image">
							<a
								class="ease-linear hover:brightness-75"
								href="https://marvel.jandrade.dev/"
								target="_blank"
								rel="noopener noreferrer"
							>
								<img
									src="/images/marvel-catalog.png"
									alt="Marvel Catalog"
									class="rounded-lg object-cover h-40 w-full"
								/>
							</a>
						</div>
						<div class="project-card-description flex flex-col">
							<h2 class="font-semibold">Marvel Catalog</h2>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<section id="certificates">
	<div class="container mx-auto py-28 px-8 md:px-0">
		<div class="section-wrapper flex flex-col-reverse md:flex-row items-center gap-16">
			<div class="section-content flex-1 grid grid-cols-1 md:grid-cols-2 gap-8">
				<div
					class="course-box rounded-lg bg-gradient-to-b from-green-400 to-blue-400 p-1"
					data-aos="fade"
				>
					<div class="course-box-wrapper rounded-lg bg-gray-800 p-6 h-full">
						<h1 class="text-lg font-semibold">DoWhile 2020</h1>
						<p class="text-md text-gray-400">
							Conferência com diversas apresentações sobre as principais tecnologias utilizadas pelo
							mercado de trabalho.
						</p>
					</div>
				</div>
				<div
					class="course-box rounded-lg bg-gradient-to-b from-green-400 to-blue-400 p-1"
					data-aos="fade"
				>
					<div class="course-box-wrapper rounded-lg bg-gray-800 p-6 h-full">
						<h1 class="text-lg font-semibold">Semana Omnistack 11</h1>
						<p class="text-md text-gray-400">
							Curso de desenvolvimento com foco em Node.js, React.js e React Native.
						</p>
					</div>
				</div>
				<div
					class="course-box rounded-lg bg-gradient-to-b from-green-400 to-blue-400 p-1"
					data-aos="fade"
				>
					<div class="course-box-wrapper rounded-lg bg-gray-800 p-6 h-full">
						<h1 class="text-lg font-semibold">Machine Learning e Deep Learning com Python</h1>
						<p class="text-md text-gray-400">
							Curso de Machine Learning e Deep Learning com foco em Python.
						</p>
					</div>
				</div>
				<div
					class="course-box rounded-lg bg-gradient-to-b from-green-400 to-blue-400 p-1"
					data-aos="fade"
				>
					<div class="course-box-wrapper rounded-lg bg-gray-800 p-6 h-full">
						<h1 class="text-lg font-semibold">
							Machine Learning e Deep Learning com Python para Ciência de Dados
						</h1>
						<p class="text-md text-gray-400">
							Curso de Machine Learning e Deep Learning com foco em Python para Ciência de Dados.
						</p>
					</div>
				</div>
			</div>
			<div class="section-description flex-1 flex flex-col gap-4" data-aos="fade">
				<p class="text-gray-400 font-light" data-aos="fade-up">🎓 #certificações</p>
				<h1 class="max-w-lg text-5xl font-bold">
					Meus cursos e
					<span
						class="bg-clip-text text-transparent bg-gradient-to-b from-green-400 to-blue-400 font-extrabold"
						>certificados</span
					> como desenvolvedor
				</h1>
				<p class="max-w-md text-gray-400 font-medium mb-6">
					Durante a minha carreira, tive a oportunidade de conhecer diferentes tipos de tecnologias
					e aprender variadas formas de se trabalhar com elas através de cursos e treinamentos.
				</p>
				<a
					href="https://drive.google.com/file/d/1hDUli4rFIuPNGIcW6rBmbQoJPK4JCCev/view?usp=sharing"
					target="_blank"
					rel="noopener noreferrer"
					class="flex bg-gray-700 w-full md:w-max justify-center items-center py-3 px-6 rounded-lg font-medium transition-all ease-linear hover:bg-gray-600 active:bg-gray-700"
					><i class="fas fa-graduation-cap mr-2" /> Veja meu resumo</a
				>
			</div>
		</div>
	</div>
</section>

<section id="contact" class="bg-gray-800">
	<div class="container mx-auto py-28 px-8 md:px-0">
		<div class="section-wrapper flex flex-col items-center gap-16">
			<div class="section-description flex flex-col items-center gap-4" data-aos="fade">
				<p class="text-gray-400 font-light" data-aos="fade-up">💬 #contato</p>
				<h1 class="max-w-xl text-5xl font-bold text-center">
					Entre em
					<span
						class="bg-clip-text text-transparent bg-gradient-to-b from-green-400 to-blue-400 font-extrabold"
						>contato</span
					> comigo pelas redes 😁
				</h1>
				<p class="max-w-lg text-gray-400 font-medium mb-6 text-center">
					Se tiver interesse em me conhecer melhor, você pode entrar em contato comigo pelo linkedin
					ou por meio das minhas redes sociais.
				</p>
				<a
					class="flex items-center justify-center w-full md:w-max px-6 py-3 rounded-lg bg-gray-700 font-medium transition-all ease-linear hover:bg-gray-600 active:bg-gray-700"
					href="https://www.linkedin.com/in/eljonathas"
					target="_blank"
					rel="noopener noreferrer"
				>
					<i class="fab fa-linkedin mr-2" />
					Abrir no Linkedin
				</a>
			</div>
		</div>
	</div>
</section>

<footer>
	<div class="container mx-auto py-16 px-8 md:px-0">
		<div class="footer-wrapper flex flex-col items-center gap-3">
			<p class="text-sm text-gray-400 text-center">
				Projeto desenvolvido com 💘 por <a
					class="text-white"
					href="https://github.com/eljonathas"
					target="_blank"
					rel="noopener noreferrer">Jonathas Andrade</a
				>
			</p>
			<div class="socials-icons-row flex items-center gap-3 text-2xl md:text-xl">
				<a href="https://www.instagram.com/jonathassx/" target="_blank" rel="noopener noreferrer"
					><i class="fab fa-instagram-square" /></a
				>
				<a href="https://twitter.com/jonathassx" target="_blank" rel="noopener noreferrer"
					><i class="fab fa-twitter-square" /></a
				>
				<a href="https://github.com/eljonathas" target="_blank" rel="noopener noreferrer"
					><i class="fab fa-github-square" /></a
				>
				<a href="https://www.linkedin.com/in/eljonathas/" target="_blank" rel="noopener noreferrer"
					><i class="fab fa-linkedin" /></a
				>
			</div>
		</div>
	</div>
</footer>
