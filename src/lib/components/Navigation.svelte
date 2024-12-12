<script lang="ts">
	import img1 from '$lib/img/logo-color.svg';
	export let logo = img1;
</script>

<nav class="flex flex-col items-center bg-[#010536]">
	<section class="z-0">
		<img class="h-full w-[180px] scale-125" src={logo} alt="logo-grocexpress" />
	</section>
	<ul
		class="z-10 flex flex-wrap items-center justify-center gap-2 font-medium text-slate-200 transition-all"
	>
		<li class="p-3"><a href="/" class="h-full w-full hover:text-[#ffdc00]"> Home</a></li>
		<li class="p-3"><a href="/" class="h-full w-full hover:text-[#ffdc00]"> Cek Tarif</a></li>
		<li class="p-3">
			<a href="/" class="h-full w-full hover:text-[#ffdc00]"> Servis & Layanan</a>
		</li>
		<li class="p-3"><a href="/" class="h-full w-full hover:text-[#ffdc00]"> Tracking</a></li>
		<li class="p-3"><a href="/" class="h-full w-full hover:text-[#ffdc00]"> Tentang Kami</a></li>
		<li class="p-3">
			<!-- <div
				class="rounded-md bg-gradient-to-r from-lime-700 to-lime-500 text-white hover:bg-gradient-to-r hover:from-lime-700/80 hover:to-lime-500/80"
			>
				<a href="/" class="h-full w-full">
					<div class=" p-1 px-4">Kirim Paket Sekarang</div>
				</a>
			</div> -->
			<div class="rounded-md bg-orange-600 text-white hover:bg-orange-600/80">
				<a href="/" class="h-full w-full">
					<div class=" p-2 px-4">Kirim Paket Sekarang</div>
				</a>
			</div>
		</li>
	</ul>
</nav>
