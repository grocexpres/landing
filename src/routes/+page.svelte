<script>
	import Navigation from '$lib/components/Navigation.svelte';
</script>

<svelte:head>
	<title>GrocExpress Indonesia</title>
</svelte:head>

<Navigation />
<main class="min-h-[calc(100vh-100px)] bg-slate-100">
	<div class="h-[60px] bg-[#010536]"></div>
	<div class="mx-auto max-w-4xl -translate-y-[40%] transform px-4">
		<div class="rounded-lg bg-white p-3 px-6 shadow-xl">
			<h5 class="font-medium">Lacak Pengiriman</h5>
			<div class="mt-3 flex gap-2">
				<div class="flex-1">
					<input
						class="w-full rounded-md border-slate-300 bg-[#010536]/10 p-2 px-4 placeholder:text-sm"
						type="text"
						placeholder="Masukkan Nomor Resi"
					/>
				</div>
				<div>
					<button
						class="rounded-md bg-orange-600/80 p-2 px-4 font-medium text-white hover:bg-orange-600"
						>Lacak Kiriman</button
					>
				</div>
			</div>
		</div>
	</div>

	<section class="py-12">
		<div class="container mx-auto px-6 lg:px-16">
			<!-- Header -->
			<header class="pb-6 text-center">
				<h2 class="text-3xl font-bold text-gray-800 lg:text-4xl">Selamat Datang di GrocExpress</h2>
				<p class="mt-4 text-gray-600 lg:text-lg">
					Kami hadir untuk membantu Anda mengirimkan paket ke seluruh dunia dengan mudah, cepat, dan
					terpercaya.
				</p>
			</header>

			<section class="rounded-lg bg-white py-12">
				<div class="container mx-auto px-6 lg:px-16">
					<header class="text-center">
						<h2 class="text-3xl font-bold text-gray-800 lg:text-4xl">Tentang Kami</h2>
					</header>
					<div class="mt-8 grid grid-cols-1 gap-8 md:grid-cols-2">
						<!-- Gambar -->
						<div>
							<img
								src="https://via.placeholder.com/600x400"
								alt="Tentang Kami"
								class="rounded-lg shadow-md"
							/>
						</div>
						<!-- Teks -->
						<div class="flex items-center">
							<p class="text-gray-600 lg:text-lg">
								Kami adalah perusahaan yang berkomitmen untuk menyediakan layanan pengiriman
								internasional terbaik. Dengan pengalaman bertahun-tahun dan jaringan yang luas, kami
								memastikan paket Anda sampai ke tujuan dengan aman, cepat, dan efisien.
							</p>
						</div>
					</div>
				</div>
			</section>
		</div>
	</section>

	<section class="bg-[#010536]/10 py-12">
		<div class="container mx-auto px-6 lg:px-16">
			<!-- Header -->
			<header class="mb-8 text-center">
				<h2 class="text-3xl font-bold text-slate-800 lg:text-4xl">
					Layanan Pengiriman Internasional
				</h2>
				<p class="mt-4 text-slate-600 lg:text-lg">
					Kami menyediakan solusi pengiriman paket ke luar negeri yang cepat, aman, dan terpercaya.
				</p>
			</header>

			<!-- Services Grid -->
			<div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
				<!-- Service Item 1 -->
				<div class="flex flex-col items-center rounded-lg bg-white p-6 text-center shadow-lg">
					<div class="rounded-full bg-slate-100 p-4">
						<svg
							class="h-12 w-12 text-slate-500"
							fill="none"
							stroke="currentColor"
							stroke-width="2"
							viewBox="0 0 24 24"
						>
							<path stroke-linecap="round" stroke-linejoin="round" d="M3 10l6 6m0 0l6-6m-6 6V4" />
						</svg>
					</div>
					<h3 class="mt-6 text-xl font-semibold text-slate-800">Pengiriman Ekspres</h3>
					<p class="mt-4 text-slate-600">
						Paket Anda akan tiba dengan cepat menggunakan layanan ekspres kami, bahkan ke
						negara-negara terjauh.
					</p>
				</div>

				<!-- Service Item 2 -->
				<div class="flex flex-col items-center rounded-lg bg-white p-6 text-center shadow-lg">
					<div class="rounded-full bg-green-100 p-4">
						<svg
							class="h-12 w-12 text-green-500"
							fill="none"
							stroke="currentColor"
							stroke-width="2"
							viewBox="0 0 24 24"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M12 8c-2.28 0-4 1.72-4 4s1.72 4 4 4 4-1.72 4-4-1.72-4-4-4zm0-4v2m0 12v2m-4-4h-2m12 0h2M4.22 4.22l1.42 1.42m12.36 12.36l1.42 1.42M4.22 19.78l1.42-1.42m12.36-12.36l1.42-1.42"
							/>
						</svg>
					</div>
					<h3 class="mt-6 text-xl font-semibold text-slate-800">Pelacakan Real-Time</h3>
					<p class="mt-4 text-slate-600">
						Pantau perjalanan paket Anda secara langsung hingga tiba di tujuan dengan sistem
						pelacakan kami.
					</p>
				</div>

				<!-- Service Item 3 -->
				<div class="flex flex-col items-center rounded-lg bg-white p-6 text-center shadow-lg">
					<div class="rounded-full bg-yellow-100 p-4">
						<svg
							class="h-12 w-12 text-yellow-500"
							fill="none"
							stroke="currentColor"
							stroke-width="2"
							viewBox="0 0 24 24"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M9 12l2 2 4-4M20 12v7a2 2 0 01-2 2H6a2 2 0 01-2-2v-7m16-2a9 9 0 11-18 0 9 9 0 0118 0z"
							/>
						</svg>
					</div>
					<h3 class="mt-6 text-xl font-semibold text-slate-800">Asuransi Pengiriman</h3>
					<p class="mt-4 text-slate-600">
						Kami melindungi paket Anda dengan layanan asuransi untuk memastikan keamanan selama
						pengiriman.
					</p>
				</div>
			</div>

			<!-- Call to Action -->
			<div class="mt-12 text-center">
				<a
					href="#learn-more"
					class="rounded-lg bg-slate-600 px-8 py-3 text-lg text-white shadow hover:bg-blue-500"
				>
					Pelajari Lebih Lanjut
				</a>
			</div>
		</div>
	</section>

	<section class="bg-white py-12">
		<div class="container mx-auto px-6 lg:px-16">
			<!-- Header -->
			<header class="mb-8 text-center">
				<h2 class="text-3xl font-bold text-gray-800 lg:text-4xl">Cara Penggunaan</h2>
				<p class="mt-4 text-gray-600 lg:text-lg">
					Ikuti langkah-langkah berikut untuk memanfaatkan aplikasi kami dengan mudah.
				</p>
			</header>

			<!-- Tutorial Steps -->
			<div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
				<!-- Step 1 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-blue-100 p-4">
						<span class="text-2xl font-bold text-blue-600">1</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Daftar atau Login</h3>
					<p class="mt-2 text-gray-600">
						Buat akun baru atau masuk ke aplikasi menggunakan email dan kata sandi Anda.
					</p>
				</div>

				<!-- Step 2 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-green-100 p-4">
						<span class="text-2xl font-bold text-green-600">2</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Masukkan Data Pengiriman</h3>
					<p class="mt-2 text-gray-600">
						Isi formulir dengan informasi lengkap seperti alamat pengirim dan penerima, serta detail
						paket.
					</p>
				</div>

				<!-- Step 3 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-yellow-100 p-4">
						<span class="text-2xl font-bold text-yellow-600">3</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Pilih Layanan</h3>
					<p class="mt-2 text-gray-600">
						Pilih jenis layanan yang sesuai, seperti pengiriman ekspres atau reguler.
					</p>
				</div>

				<!-- Step 4 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-purple-100 p-4">
						<span class="text-2xl font-bold text-purple-600">4</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Lakukan Pembayaran</h3>
					<p class="mt-2 text-gray-600">
						Bayar biaya pengiriman melalui metode pembayaran yang tersedia di aplikasi.
					</p>
				</div>

				<!-- Step 5 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-red-100 p-4">
						<span class="text-2xl font-bold text-red-600">5</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Cetak Label</h3>
					<p class="mt-2 text-gray-600">
						Unduh dan cetak label pengiriman untuk ditempelkan pada paket Anda.
					</p>
				</div>

				<!-- Step 6 -->
				<div class="flex flex-col items-center rounded-lg bg-gray-50 p-6 text-center shadow-lg">
					<div class="rounded-full bg-teal-100 p-4">
						<span class="text-2xl font-bold text-teal-600">6</span>
					</div>
					<h3 class="mt-4 text-xl font-semibold text-gray-800">Kirim Paket</h3>
					<p class="mt-2 text-gray-600">
						Antar paket ke lokasi drop-off terdekat atau tunggu kurir untuk menjemput.
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="bg-gray-50 py-12">
		<div class="container mx-auto px-6 lg:px-16">
			<!-- Header -->
			<header class="mb-8 text-center">
				<h2 class="text-3xl font-bold text-gray-800 lg:text-4xl">Cerita Pelanggan</h2>
				<p class="mt-4 text-gray-600 lg:text-lg">
					Dengarkan pengalaman pelanggan kami yang telah menggunakan layanan kami untuk mengirimkan
					paket ke seluruh dunia.
				</p>
			</header>

			<!-- Reviews -->
			<div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
				<!-- Review 1 -->
				<div class="rounded-lg bg-white p-6 shadow-md">
					<div class="mb-4 flex items-center">
						<img src="https://via.placeholder.com/50" alt="User 1" class="h-12 w-12 rounded-full" />
						<div class="ml-4">
							<h3 class="text-lg font-semibold text-gray-800">John Doe</h3>
							<p class="text-sm text-gray-500">Pengusaha</p>
						</div>
					</div>
					<p class="text-gray-600">
						"Pengiriman sangat cepat dan prosesnya sangat mudah! Saya tidak ragu untuk
						merekomendasikan layanan ini kepada siapa pun."
					</p>
				</div>

				<!-- Review 2 -->
				<div class="rounded-lg bg-white p-6 shadow-md">
					<div class="mb-4 flex items-center">
						<img src="https://via.placeholder.com/50" alt="User 2" class="h-12 w-12 rounded-full" />
						<div class="ml-4">
							<h3 class="text-lg font-semibold text-gray-800">Sarah Lee</h3>
							<p class="text-sm text-gray-500">Freelancer</p>
						</div>
					</div>
					<p class="text-gray-600">
						"Layanan ini membuat saya lebih percaya diri untuk mengirimkan barang ke klien di luar
						negeri. Pelayanan pelanggan juga sangat membantu!"
					</p>
				</div>

				<!-- Review 3 -->
				<div class="rounded-lg bg-white p-6 shadow-md">
					<div class="mb-4 flex items-center">
						<img src="https://via.placeholder.com/50" alt="User 3" class="h-12 w-12 rounded-full" />
						<div class="ml-4">
							<h3 class="text-lg font-semibold text-gray-800">Ahmad Faisal</h3>
							<p class="text-sm text-gray-500">Pemilik Toko Online</p>
						</div>
					</div>
					<p class="text-gray-600">
						"Saya sangat puas dengan ketepatan waktu dan keamanan barang selama proses pengiriman.
						Luar biasa!"
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="bg-white py-12">
		<div class="container mx-auto px-6 lg:px-16">
			<!-- Header -->
			<header class="mb-8 text-center">
				<h2 class="text-3xl font-bold text-gray-800 lg:text-4xl">Layanan Pelanggan</h2>
				<p class="mt-4 text-gray-600 lg:text-lg">
					Kami siap membantu Anda kapan pun Anda membutuhkan. Berikut adalah informasi kontak resmi
					kami.
				</p>
			</header>

			<!-- Contact Information -->
			<div class="grid grid-cols-1 gap-8 md:grid-cols-2">
				<!-- Contact Details -->
				<div class="rounded-lg bg-gray-50 p-6 shadow-md">
					<h3 class="mb-4 text-xl font-semibold text-gray-800">Hubungi Kami</h3>
					<ul class="space-y-2 text-gray-600">
						<li>
							<strong>Email:</strong>
							<a href="mailto:support@grocexpress.com" class="text-blue-600"
								>support@grocexpress.com</a
							>
						</li>
						<li>
							<strong>Telepon:</strong>
							<a href="tel:+62123456789" class="text-blue-600">+62 123-456-789</a>
						</li>
						<li>
							<strong>WhatsApp:</strong>
							<a href="https://wa.me/62123456789" class="text-blue-600">+62 123-456-789</a>
						</li>
					</ul>
				</div>

				<!-- Office Address -->
				<div class="rounded-lg bg-gray-50 p-6 shadow-md">
					<h3 class="mb-4 text-xl font-semibold text-gray-800">Alamat Resmi</h3>
					<p class="text-gray-600">
						<strong>GrocExpress HQ</strong><br />
						Jl. Raya Internasional No.123<br />
						Jakarta Selatan, Indonesia<br />
						Kode Pos 12345
					</p>
					<p class="mt-4 text-gray-600">Jam Operasional: Senin - Jumat, 09:00 - 17:00 WIB</p>
				</div>
			</div>

			<!-- Call to Action -->
			<div class="mt-12 text-center">
				<p class="text-gray-600 lg:text-lg">
					Jika Anda memiliki pertanyaan, jangan ragu untuk menghubungi kami. Kami akan dengan senang
					hati membantu Anda!
				</p>
				<a
					href="/contact"
					class="mt-6 inline-block rounded-lg bg-blue-600 px-6 py-3 font-semibold text-white shadow-lg hover:bg-blue-700"
				>
					Hubungi Kami Sekarang
				</a>
			</div>
		</div>

		<div class="container mx-auto px-6 lg:px-16">
			<!-- Kontak Kami -->
			<div>
				<h4 class="mb-4 text-lg font-semibold">Kontak Kami</h4>
				<p class="text-gray-400">
					<strong>Alamat:</strong><br />
					Jl. Raya Internasional No.123,<br />
					Jakarta Selatan, Indonesia
				</p>

				<!-- Google Maps Embed -->
				<div class="mt-4">
					<iframe
						src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12674.75365568478!2d-122.082211!3d37.420839!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fb9f9291ff8a1%3A0x223be8ea8c995cc4!2sGoogle%20Visitor%20Experience!5e0!3m2!1sen!2sus!4v1734016446465!5m2!1sen!2sus"
						width="100%"
						height="250"
						style="border:0;"
						allowfullscreen={false}
						title="grocexpress"
						loading="lazy"
						referrerpolicy="no-referrer-when-downgrade"
					></iframe>
				</div>
			</div>
		</div>
	</section>

	<section class="bg-[#010536] py-12">
		<div class="container mx-auto px-6 text-center text-white lg:px-16">
			<!-- Header -->
			<header class="mb-6">
				<h2 class="text-3xl font-bold lg:text-4xl">Bergabung dengan GrocExpress</h2>
				<p class="mt-4 text-lg">
					Dapatkan kemudahan dalam pengiriman paket ke seluruh dunia dengan layanan terpercaya kami.
				</p>
			</header>

			<!-- Buttons -->
			<div class="flex flex-col items-center justify-center gap-6 md:flex-row">
				<!-- Signup Button -->
				<a
					href="/signup"
					class="rounded-lg bg-orange-600 px-8 py-3 font-semibold text-white shadow-lg transition hover:bg-orange-700"
				>
					Daftar Sekarang
				</a>

				<!-- Login Button -->
				<a
					href="/login"
					class="rounded-lg border border-white bg-transparent px-8 py-3 font-semibold transition hover:bg-white hover:text-[#010536]"
				>
					Masuk
				</a>
			</div>
		</div>
	</section>
</main>

<footer class="bg-gradient-to-t from-[#060819] to-[#010536] py-12 text-white">
	<div class="container mx-auto px-6 lg:px-16">
		<!-- Top Section -->
		<div class="grid grid-cols-1 gap-8 md:grid-cols-3">
			<!-- About Us -->
			<div>
				<h4 class="mb-4 text-lg font-semibold">Tentang GrocExpress</h4>
				<p class="text-gray-400">
					GrocExpress adalah mitra pengiriman internasional terpercaya yang menghadirkan solusi
					cepat, aman, dan terjangkau untuk pengiriman paket Anda ke seluruh dunia.
				</p>

				<section class="mx-auto max-w-xl py-12">
					<div class="flex gap-2">
						<div class="flex-1">
							<input
								class="w-full rounded-md border-slate-300 bg-[#010536]/10 p-2 px-4 placeholder:text-sm"
								type="text"
								placeholder="Masukkan Nomor Resi"
							/>
						</div>
						<div>
							<button
								class="rounded-md bg-orange-600/80 p-2 px-4 font-medium text-white hover:bg-orange-600"
								>Lacak Kiriman</button
							>
						</div>
					</div>
				</section>
			</div>

			<!-- Quick Links -->
			<div>
				<h4 class="mb-4 text-lg font-semibold">Tautan Cepat</h4>
				<ul class="space-y-2 text-gray-400">
					<li><a href="/" class="hover:text-white">Beranda</a></li>
					<li><a href="/about" class="hover:text-white">Tentang Kami</a></li>
					<li><a href="/services" class="hover:text-white">Layanan</a></li>
					<li><a href="/contact" class="hover:text-white">Hubungi Kami</a></li>
					<li><a href="/faq" class="hover:text-white">FAQ</a></li>
				</ul>
			</div>

			<!-- Contact Information -->
			<div>
				<h4 class="mb-4 text-lg font-semibold">Kontak Kami</h4>
				<ul class="space-y-2 text-gray-400">
					<li>
						<strong>Email:</strong>
						<a href="mailto:support@grocexpress.com" class="hover:text-white"
							>support@grocexpress.com</a
						>
					</li>
					<li>
						<strong>Telepon:</strong>
						<a href="tel:+62123456789" class="hover:text-white">+62 123-456-789</a>
					</li>
					<li>
						<strong>Alamat:</strong><br />
						Jl. Raya Internasional No.123,<br />
						Jakarta Selatan, Indonesia
					</li>
				</ul>
			</div>
		</div>

		<!-- Divider -->
		<div class="my-8 border-t border-gray-700"></div>

		<!-- Bottom Section -->
		<div class="flex flex-col items-center justify-between md:flex-row">
			<p class="text-sm text-gray-400">&copy; 2024 GrocExpress. Semua Hak Dilindungi.</p>

			<div class="mt-4 flex space-x-4 md:mt-0">
				<a href="#" class="text-gray-400 hover:text-white">
					<span class="sr-only">Facebook</span>
					<svg
						class="h-6 w-6"
						fill="currentColor"
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
					>
						<path
							d="M22.675 0H1.325C.593 0 0 .593 0 1.326v21.348C0 23.406.593 24 1.325 24H12.82v-9.293H9.692v-3.622h3.129V8.412c0-3.1 1.894-4.788 4.66-4.788 1.325 0 2.463.098 2.794.142v3.24h-1.918c-1.505 0-1.796.716-1.796 1.766v2.315h3.59l-.468 3.622h-3.122V24h6.116c.732 0 1.325-.594 1.325-1.326V1.326C24 .593 23.406 0 22.675 0z"
						/>
					</svg>
				</a>
				<a href="#" class="text-gray-400 hover:text-white">
					<span class="sr-only">Twitter</span>
					<svg
						class="h-6 w-6"
						fill="currentColor"
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
					>
						<path
							d="M23.954 4.569c-.885.392-1.83.656-2.825.775 1.014-.611 1.794-1.574 2.163-2.723-.95.555-2.005.959-3.127 1.184-.897-.959-2.178-1.558-3.594-1.558-2.719 0-4.924 2.206-4.924 4.917 0 .386.045.762.127 1.124-4.09-.205-7.719-2.165-10.148-5.144-.424.729-.666 1.573-.666 2.475 0 1.708.87 3.216 2.188 4.099-.807-.026-1.566-.247-2.228-.616v.062c0 2.386 1.693 4.374 3.946 4.827-.413.111-.848.171-1.296.171-.314 0-.621-.03-.916-.086.631 1.953 2.445 3.376 4.604 3.416-1.68 1.316-3.809 2.102-6.102 2.102-.396 0-.787-.023-1.175-.067 2.179 1.397 4.768 2.209 7.557 2.209 9.054 0 14.001-7.498 14.001-13.986 0-.209 0-.42-.016-.63.961-.695 1.8-1.56 2.46-2.548l-.047-.02z"
						/>
					</svg>
				</a>
				<a href="#" class="text-gray-400 hover:text-white">
					<span class="sr-only">Instagram</span>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
						fill="currentColor"
						class="h-6 w-6"
					>
						<path
							d="M7.75 2C4.678 2 2 4.678 2 7.75v8.5C2 19.322 4.678 22 7.75 22h8.5C19.322 22 22 19.322 22 16.25v-8.5C22 4.678 19.322 2 16.25 2h-8.5zM3.5 7.75c0-2.35 1.9-4.25 4.25-4.25h8.5c2.35 0 4.25 1.9 4.25 4.25v8.5c0 2.35-1.9 4.25-4.25 4.25h-8.5c-2.35 0-4.25-1.9-4.25-4.25v-8.5zM12 7.75a4.25 4.25 0 110 8.5 4.25 4.25 0 010-8.5zm0 1.5a2.75 2.75 0 100 5.5 2.75 2.75 0 000-5.5zM17 6.875a.875.875 0 11-1.75 0 .875.875 0 011.75 0z"
						/>
					</svg>
				</a>
			</div>
		</div>
	</div>
</footer>
