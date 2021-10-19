<script>
	const scrollTo = (event, elementId) => {
		event.preventDefault();

		window.scrollTo({
			top: document.getElementById(elementId).offsetTop,
			behavior: 'smooth'
		});
	};
</script>

<nav id="navbar" class="bg-gray-900">
	<div
		class="container mx-auto flex items-center justify-between md:justify-start py-8 mb-8 px-8 md:px-0"
	>
		<a href="/"
			><img
				class="w-32 md:w-28 object-contain"
				src="/images/logo.png"
				alt="Jonathas Andrade Logo"
			/></a
		>

		<div class="hidden md:flex flex-1 header-navbar justify-center">
			<ul class="list-none flex items-center gap-6 text-gray-400">
				<li class="hover:text-white">
					<a href="#top" on:click={() => scrollTo('top')}>Home</a>
				</li>
				<li class="hover:text-white">
					<a href="#projects" on:click={(e) => scrollTo(e, 'projects')}>Projetos</a>
				</li>
				<li class="hover:text-white">
					<a href="#certificates" on:click={(e) => scrollTo(e, 'certificates')}>Certificações</a>
				</li>
				<li class="hover:text-white">
					<a href="#contact" on:click={(e) => scrollTo(e, 'contact')}>Contato</a>
				</li>
			</ul>
		</div>

		<div class="header-actions flex items-center justify-end gap-6">
			<a href="https://www.linkedin.com/in/eljonathas" target="_blank" rel="noopener noreferrer"
				><i class="fab fa-linkedin text-2xl" /></a
			>
			<a href="https://www.facebook.com/thmrss/" target="_blank" rel="noopener noreferrer"
				><i class="fab fa-facebook text-2xl" /></a
			>
			<a href="https://github.com/eljonathas" target="_blank" rel="noopener noreferrer"
				><i class="fab fa-github text-2xl" /></a
			>
		</div>
	</div>
</nav>
