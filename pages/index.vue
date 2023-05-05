
  <template>
    <!-- Navbar goes here -->
	<nav class="bg-white shadow-lg">
		<div class="max-w-6xl mx-auto px-4">
			<div class="flex justify-between">
				<div class="flex space-x-7">
					<!-- Website Logo -->
					<div>
						<NuxtLink to="/" class="flex items-center py-4 px-2">
							<a href="#" class="flex items-center py-4 px-2">
								<img src="../logo.svg" alt="Logo" class="h-8 w-8 mr-2" />
								<span class="font-semibold text-gray-500 text-lg">Navigation</span>
							</a>
						</NuxtLink>
					</div>
					<!-- Primary Navbar items -->
					<div class="hidden md:flex items-center space-x-1">
						<div class="hidden md:flex items-center space-x-1">
							<NuxtLink to="/" class="py-4 px-2 text-gray-500 border-b-4 border-green-500 font-semibold "> Home</NuxtLink>
							<NuxtLink to="/about" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300"> About</NuxtLink>
							<NuxtLink to="/services" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300"> services</NuxtLink>
							<NuxtLink to="/contact" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300"> Contact</NuxtLink>
						</div>
					</div>
				</div>
			</div>
		</div>
	</nav>
  <!-- Mobile menu button -->

<div class="md:hidden flex items-center">
	<button class="outline-none mobile-menu-button">
		<svg
			class="w-6 h-6 text-gray-500"
			x-show="!showMenu"
			fill="none"
			stroke-linecap="round"
			stroke-linejoin="round"
			stroke-width="2"
			viewBox="0 0 24 24"
			stroke="currentColor"
		>
		<path d="M4 6h16M4 12h16M4 18h16"></path>
		</svg>
	</button>
</div>
  </template>
  