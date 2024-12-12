<script>
	import Navigation from '$lib/components/Navigation.svelte';
	import img from '$lib/img/bg-001.jpg';
</script>

<header>
	<Navigation />
</header>
<section class="min-h-[calc(100vh-100px)] bg-slate-100">
	<div class="h-[60px] bg-[#010536]"></div>
	<div class="mx-auto max-w-4xl -translate-y-[40%] transform px-4">
		<div class="rounded-lg bg-white p-3 px-6 shadow-xl">
			<h5 class="font-medium">Lacak Pengiriman</h5>
			<div class="mt-3 flex gap-2">
				<div class="flex-1">
					<input
						class="w-full rounded-md border-slate-300 p-2 px-4 placeholder:text-sm"
						type="text"
						placeholder="Masukkan Nomor Resi"
					/>
				</div>
				<div>
					<button
						class="rounded-md bg-orange-600/80 p-2 px-4 font-medium text-white hover:bg-orange-600"
						>Lacak</button
					>
				</div>
			</div>
		</div>
	</div>

	<div class="mx-auto mt-2 max-w-6xl px-4">
		<h3 class="text-xl font-medium">Why choose us?</h3>
		<div class="mt-4">
			<div class="h-[300px] w-full rounded-lg bg-slate-200"></div>
		</div>
	</div>

	<div class="mt-6 h-[20px]"></div>
	<div class="mt-6 h-screen bg-white py-6">
		<div class="mx-auto h-full max-w-5xl px-4">
			<div class="flex h-full items-center justify-center gap-4">
				<div class="flex-1">
					<img src={img} alt="okn" />
					<!-- <div class="h-[250px] w-full rounded-xl bg-slate-200 p-4">
					</div> -->
				</div>
				<div class="flex-1 p-4">
					<div
						class="col-lg-6 wow fadeInUp pt-lg-0 pt-5"
						style="visibility: visible; animation-name: fadeInUp;"
					>
						<h4 style="margin: 0 0 0 0 !important;">Contact Us</h4>
						<h5 style="margin: 0 0 0 0 !important;">
							Whatsapp : 0815-8722-203
							<a href="https://wa.me/628158722203?text=Hallo DND, saya ingin bertanya" target="_blank">
								<i class="fab fa-whatsapp" style="color:green"></i>
							</a>
						</h5>
						<h5>Call Center : 0813-8262-9689</h5>
						<p>
							Layanan call center kami siap membantu anda untuk menjawab seluruh pertanyaan anda di
							office hour 09:00 - 17:00. Pelayanan cepat seputar pengiriman bisa di akses juga lewat
							whatsapp kami di nomor 0815-8722-203. Untuk informasi atau berita seputar DND Kirim
							bisa anda kunjungi juga di Sosial media, Email dan Blog kami. Pertanyaan detail
							seputar layanan kami juga bisa anda kirimkan lewat email official kami di
							cs@dndkirim.id
						</p>
						<p>
							Jika Anda memiliki penawaran atau tertarik untuk bekerja sama dengan kami, silakan <a
								href="https://api.whatsapp.com/send/?phone=628158722203&amp;text=Hallo+DND%2C+saya+butuh+bantuan&amp;type=phone_number&amp;app_absent=0"
								style="text-decoration: none; color: #337ab7;"><strong>Hubungi Kami</strong></a
							>
							atau Anda dapat mengisi form penawaran
							<a
								href="https://forms.gle/vgpi5ibMGmG5JKHy8"
								style="text-decoration: none; color: #337ab7;"><strong>Klik Link Here</strong></a
							>
						</p>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- <div class="mt-6 h-[20px]"></div> -->
</section>

<footer class="min-h-[300px] bg-[#010536]"></footer>
