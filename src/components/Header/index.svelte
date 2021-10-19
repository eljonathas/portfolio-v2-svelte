<script>
	import Navbar from '../../components/Navbar/index.svelte';

	import './styles.css';
</script>

<header data-aos="fade">
	<div class="container mx-auto header-container px-8 md:px-0">
		<main class="header-content mt-20 md:mt-28">
			<div
				class="header-content-wrapper flex flex-col-reverse md:flex-row items-center justify-between"
			>
				<div class="flex flex-col gap-4">
					<p class="text-gray-400 font-light" data-aos="fade-up">👋 #home</p>
					<h1
						class="text-5xl max-w-lg font-extrabold text-transparent bg-clip-text bg-gradient-to-b from-green-400 to-blue-400"
					>
						Olá, eu me chamo Jonathas Andrade.
					</h1>
					<h2 class="text-2xl font-semibold max-w-md">
						Desenvolvedor Full-Stack passionado por tecnologia, inovação...
					</h2>
					<p class="text-md font-normal max-w-lg text-gray-400">
						...e também estudante de Ciência da Computação na Universidade Federal do Estado do
						Pará. Tenho um interesse especial pela área de Inteligência Artificial e uma quedinha
						pela linguagem de programação JavaScript 👀
					</p>
					<div class="profile-buttons flex flex-col md:flex-row items-center gap-4 mt-8">
						<p class="text-sm min-w-max">Veja meus projetos:</p>
						<div class="buttons-wrapper w-full flex flex-col md:flex-row gap-4 items-center">
							<a
								href="https://github.com/eljonathas"
								target="_blank"
								rel="noopener noreferrer"
								class="flex gap-3 items-center bg-gray-800 font-semibold rounded-lg px-6 py-3 w-full md:w-auto justify-center hover:bg-gray-700"
							>
								<i class="fab fa-github" />
								Abrir no GitHub
							</a>
							<p class="text-sm">ou</p>
							<button
								class="flex gap-3 items-center w-full md:w-auto justify-center bg-gray-800 font-semibold rounded-lg px-6 py-3 hover:bg-gray-700"
							>
								Saiba mais
							</button>
						</div>
					</div>
				</div>

				<div
					class="profile-stats-image flex flex-col-reverse mb-16 md:mb-0 md:flex-row gap-12 md:gap-0"
				>
					<div class="github-stats-column hidden md:block">
						<div class="github-stats-wrapper flex flex-col items-end shadow-lg">
							<div class="max-w-xs md:-mr-44 z-10 rounded-xl overflow-hidden">
								<img
									class="rounded-xl scale-105"
									src="https://github-readme-stats.vercel.app/api?username=eljonathas&theme=tokyonight"
									alt="Github Stats"
								/>
							</div>
						</div>
					</div>

					<div class="profile-image-column flex justify-center md:-mt-20">
						<div class="profile-image-wrapper">
							<img src="/images/photo.png" alt="Jonathas Andrade" />
						</div>
					</div>
				</div>
			</div>
		</main>

		<footer class="header-footer mt-16 md:mt-28 w-full mb-24">
			<div class="footer-wrapper flex flex-col items-center gap-8">
				<p class="text-sm font-medium text-gray-500">Ferramentas já utilizadas</p>
				<div class="flex flex-col md:flex-row items-center gap-12 md:gap-20 tools-image">
					<img src="/images/react-logo.png" alt="React Logo" />
					<img src="/images/react-native-logo.png" alt="React Native Logo" />
					<img src="/images/nextjs-logo.png" alt="Nextjs Logo" />
					<img src="/images/svelte-logo.png" alt="Svelte Logo" />
					<img src="/images/node-logo.png" alt="Nodejs Logo" />
				</div>
			</div>
		</footer>
	</div>
</header>
