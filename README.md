# Politeknik Assalaam Surakarta
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PMB 2026 - Politeknik Assalaam Surakarta</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            teal: '#1F7A6A',
                            gold: '#D4B04C',
                            dark: '#12483E',
                            light: '#F4F9F8'
                        }
                    }
                }
            }
        }
    </script>
    <!-- Font Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- NAVBAR -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <!-- Logo Politeknik Assalaam -->
                <img src="LOGO-POLITEKNIK-ASSALAAM-LANDSCAPE-TANPA-SURAKARTA.png" alt="Logo Politeknik Assalaam" class="h-12 w-auto">
                <div class="border-l-2 border-brand-teal pl-3 hidden sm:block">
                    <span class="block text-xs font-bold text-brand-teal tracking-wider uppercase">Surakarta</span>
                    <span class="block text-xs text-gray-500">PMB TA 2026/2027</span>
                </div>
            </div>
            
            <nav class="hidden md:flex space-x-8 font-medium text-gray-600">
                <a href="#home" class="hover:text-brand-teal transition">Beranda</a>
                <a href="#prodi" class="hover:text-brand-teal transition">Program Studi</a>
                <a href="#alur" class="hover:text-brand-teal transition">Alur Pendaftaran</a>
                <a href="#kontak" class="hover:text-brand-teal transition">Kontak</a>
            </nav>

            <div>
                <a href="#daftar" class="bg-brand-teal text-white font-semibold px-5 py-2.5 rounded-lg shadow hover:bg-brand-dark transition duration-250">
                    Daftar Sekarang
                </a>
            </div>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="relative bg-gradient-to-br from-brand-teal to-brand-dark text-white py-20 lg:py-28">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <span class="inline-block bg-brand-gold text-brand-dark font-bold text-xs uppercase tracking-widest px-3 py-1 rounded-full mb-4">
                    Penerimaan Mahasiswa Baru 2026
                </span>
                <h1 class="text-4xl lg:text-5xl font-extrabold leading-tight mb-6">
                    Wujudkan Masa Depan Vokasi Unggul & Berkarakter
                </h1>
                <p class="text-lg text-emerald-100 mb-8">
                    Bergabunglah bersama Politeknik Assalaam Surakarta. Siap kerja, terampil, berintegritas, dan berdaya saing di era digital.
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="#daftar" class="bg-brand-gold text-brand-dark font-bold px-8 py-3.5 rounded-lg text-center shadow-lg hover:bg-yellow-400 transition">
                        Formulir Pendaftaran
                    </a>
                    <a href="#prodi" class="border border-white text-white font-semibold px-8 py-3.5 rounded-lg text-center hover:bg-white/10 transition">
                        Lihat Program Studi
                    </a>
                </div>
            </div>
            
            <!-- Card Pendaftaran Cepat -->
            <div id="daftar" class="bg-white rounded-2xl shadow-2xl p-8 text-gray-800 border-t-8 border-brand-gold">
                <h3 class="text-2xl font-bold text-brand-teal mb-2">Registrasi Akun PMB 2026</h3>
                <p class="text-sm text-gray-500 mb-6">Isi data awal untuk memulai pendaftaran calon mahasiswa baru.</p>
                
                <form class="space-y-4">
                    <div>
                        <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Nama Lengkap</label>
                        <input type="text" placeholder="Sesuai Ijazah / KTP" class="w-full px-4 py-2.5 border rounded-lg focus:ring-2 focus:ring-brand-teal focus:outline-none">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Nomor WhatsApp</label>
                        <input type="tel" placeholder="08xxxxxxxxxx" class="w-full px-4 py-2.5 border rounded-lg focus:ring-2 focus:ring-brand-teal focus:outline-none">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Pilihan Program Studi</label>
                        <select class="w-full px-4 py-2.5 border rounded-lg focus:ring-2 focus:ring-brand-teal focus:outline-none bg-white">
                            <option value="">-- Pilih Program Studi --</option>
                            <option value="1">D3 Manajemen Informatika</option>
                            <option value="2">S1 Manajemen Informasi Kesehatan</option>
                            <option value="3">D3 Bahasa Inggris</option>
                        </select>
                    </div>
                    <button type="button" class="w-full bg-brand-teal text-white font-bold py-3 rounded-lg shadow-md hover:bg-brand-dark transition">
                        Lanjutkan Pendaftaran
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- PROGRAM STUDI -->
    <section id="prodi" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 mb-3">Program Studi Unggulan</h2>
                <div class="w-16 h-1 bg-brand-gold mx-auto rounded mb-4"></div>
                <p class="text-gray-600">Kurikulum berbasis industri dan kebutuhan pasar kerja masa depan.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Card Prodi 1 -->
                <div class="border rounded-2xl p-6 hover:shadow-xl transition border-gray-100 bg-brand-light flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-brand-teal text-white rounded-xl flex items-center justify-center font-bold text-xl mb-4">💻</div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">D3 Manajemen Informatika</h3>
                        <p class="text-sm text-gray-600 mb-6">menghasilkan lulusan yang terampil dalam merancang, mengembangkan, dan mengelola sistem informasi berbasis komputer untuk mendukung kebutuhan bisnis dan efisiensi operasional organisasi.</p>
                    </div>
                    <a href="#" class="text-brand-teal font-bold text-sm hover:underline">Detail Prodi &rarr;</a>
                </div>

                <!-- Card Prodi 2 -->
                <div class="border rounded-2xl p-6 hover:shadow-xl transition border-gray-100 bg-brand-light flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-brand-teal text-white rounded-xl flex items-center justify-center font-bold text-xl mb-4">⚙️</div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">S1 Manajemen Informasi Kesehatan</h3>
                        <p class="text-sm text-gray-600 mb-6">menghasilkan tenaga ahli yang terampil dalam mengelola, menganalisis, dan mengamankan data serta sistem informasi kesehatan untuk meningkatkan kualitas layanan medis dan efisiensi operasional di fasilitas kesehatan.</p>
                    </div>
                    <a href="#" class="text-brand-teal font-bold text-sm hover:underline">Detail Prodi &rarr;</a>
                </div>

                <!-- Card Prodi 3 -->
                <div class="border rounded-2xl p-6 hover:shadow-xl transition border-gray-100 bg-brand-light flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-brand-teal text-white rounded-xl flex items-center justify-center font-bold text-xl mb-4">🤖</div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">D3 Bahasa Inggris</h3>
                        <p class="text-sm text-gray-600 mb-6">menghasilkan lulusan yang memiliki kemahiran berbahasa Inggris tingkat lanjut (lisan dan tulisan) serta mampu mengaplikasikannya secara profesional dalam berbagai bidang, seperti komunikasi bisnis, penerjemahan, pengajaran, maupun industri kreatif.</p>
                    </div>
                    <a href="#" class="text-brand-teal font-bold text-sm hover:underline">Detail Prodi &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- ALUR PENDAFTARAN -->
    <section id="alur" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 mb-3">Alur Pendaftaran 2026</h2>
                <div class="w-16 h-1 bg-brand-gold mx-auto rounded mb-4"></div>
            </div>

            <div class="grid md:grid-cols-4 gap-6 text-center">
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="w-10 h-10 bg-brand-gold text-brand-dark rounded-full flex items-center justify-center font-bold mx-auto mb-4">1</div>
                    <h4 class="font-bold mb-2">Isi Formulir</h4>
                    <p class="text-xs text-gray-500">Lengkapi data diri secara online melalui form pendaftaran.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="w-10 h-10 bg-brand-gold text-brand-dark rounded-full flex items-center justify-center font-bold mx-auto mb-4">2</div>
                    <h4 class="font-bold mb-2">Upload Berkas</h4>
                    <p class="text-xs text-gray-500">Unggah kualifikasi nilai rapor / ijazah & identitas diri.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="w-10 h-10 bg-brand-gold text-brand-dark rounded-full flex items-center justify-center font-bold mx-auto mb-4">3</div>
                    <h4 class="font-bold mb-2">Seleksi / Tes</h4>
                    <p class="text-xs text-gray-500">Mengikuti tes potensi akademik / jalur bebas tes (prestasi).</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                    <div class="w-10 h-10 bg-brand-gold text-brand-dark rounded-full flex items-center justify-center font-bold mx-auto mb-4">4</div>
                    <h4 class="font-bold mb-2">Daftar Ulang</h4>
                    <p class="text-xs text-gray-500">Konfirmasi penerimaan dan pembayaran biaya pendidikan awal.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER & KONTAK -->
    <footer id="kontak" class="bg-brand-dark text-white pt-16 pb-8 border-t-4 border-brand-gold">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-3 gap-8 mb-12">
            <div>
                <img src="LOGO-POLITEKNIK-ASSALAAM-LANDSCAPE-TANPA-SURAKARTA.png" alt="Logo Footer" class="h-12 w-auto bg-white p-2 rounded-md mb-4">
                <p class="text-sm text-emerald-100 leading-relaxed">
                    Politeknik Assalaam Surakarta mencetak lulusan vokasi yang profesional, kompeten, dan berakhlaqul karimah.
                </p>
            </div>
            <div>
                <h4 class="text-lg font-bold mb-4 border-b border-emerald-700 pb-2">Kontak PMB</h4>
                <ul class="space-y-2 text-sm text-emerald-100">
                    <li>📍 Surakarta, Jawa Tengah, Indonesia</li>
                    <li>📞 WhatsApp: +62 812-3456-7890</li>
                    <li>✉️ Email: pmb@politeknikassalaam.ac.id</li>
                </ul>
            </div>
            <div>
                <h4 class="text-lg font-bold mb-4 border-b border-emerald-700 pb-2">Jam Operational PMB</h4>
                <p class="text-sm text-emerald-100">Senin - Jumat: 08.00 - 15.00 WIB</p>
                <p class="text-sm text-emerald-100">Sabtu: 08.00 - 12.00 WIB</p>
            </div>
        </div>
        <div class="text-center text-xs text-emerald-300 border-t border-emerald-800 pt-6">
            &copy; 2026 Politeknik Assalaam Surakarta. All Rights Reserved.
        </div>
    </footer>

</body>
</html>
