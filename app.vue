<template>
  <div class="min-h-screen bg-brand-cream text-slate-800 font-sans selection:bg-brand-teal selection:text-white">
    <!-- Meta tags and head handled by Nuxt automatically if added here -->
    <Head>
      <Title>Lembar Nona - Print Online Cepat & Rapi</Title>
      <Meta name="description" content="Lembar Nona adalah solusi print online di Jombang. Cepat, rapi, dan bisa diantar ke tempatmu!" />
    </Head>

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 bg-white/70 backdrop-blur-xl border-b border-brand-teal/5">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
        <div class="flex items-center gap-3">
          <div class="w-10 h-10 bg-brand-teal rounded-xl flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-brand-teal/20">L</div>
          <span class="text-xl font-bold tracking-tight text-brand-teal">Lembar<span class="text-brand-rust italic">nona</span></span>
        </div>
        <div class="hidden md:flex items-center gap-8 font-medium">
          <a href="#services" class="hover:text-brand-teal transition-colors">Layanan</a>
          <a href="#prices" class="hover:text-brand-teal transition-colors">Daftar Harga</a>
          <a href="#location" class="hover:text-brand-teal transition-colors">Hubungi</a>
          <a href="https://wa.me/6285185950350" target="_blank" class="bg-brand-teal text-white px-6 py-2.5 rounded-full font-bold hover:scale-105 hover:shadow-lg hover:shadow-brand-teal/20 transition-all active:scale-95">
            Pesan Sekarang
          </a>
        </div>
        <!-- Mobile Menu Icon (Simplified for one page) -->
        <div class="md:hidden">
           <a href="https://wa.me/6285185950350" target="_blank" class="bg-brand-teal text-white w-10 h-10 rounded-xl flex items-center justify-center hover:bg-brand-teal/90 transition-colors">
             <Phone class="w-5 h-5" />
           </a>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative pt-16 pb-24 md:pt-32 md:pb-48 overflow-hidden">
      <!-- Background Decorative Elements -->
      <div class="absolute top-0 right-0 -mr-20 -mt-20 w-[600px] h-[600px] bg-brand-teal/5 rounded-full blur-[100px] -z-10"></div>
      <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-[600px] h-[600px] bg-brand-rust/5 rounded-full blur-[100px] -z-10"></div>
      
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex flex-col items-center text-center">
          <div class="inline-flex items-center gap-2 px-4 py-2 bg-brand-teal/10 rounded-full text-brand-teal text-sm font-bold mb-8 animate-fade-in">
            <Sparkles class="w-4 h-4 text-brand-gold animate-pulse" />
            <span class="tracking-wide uppercase">Print Online • Cepat • Rapi</span>
          </div>
          
          <h1 class="text-5xl md:text-8xl font-black mb-8 tracking-tighter leading-tight">
            Cetak Dokumen <br class="hidden md:block"/>
            <span class="text-brand-teal underline decoration-brand-gold/30">Tanpa Ribet</span> di <span class="text-brand-rust italic">Lembar Nona</span>
          </h1>
          
          <p class="text-xl md:text-2xl text-slate-500 max-w-3xl mx-auto mb-12 leading-relaxed font-medium">
            Pusing cari tempat print pagi-pagi? Lupa print pas udah di sekolah? 
            <span class="text-brand-teal font-bold">Lembar Nona</span> solusinya! Bisa kirim file via WA/Email dan kami antar ke tempatmu.
          </p>

          <div class="flex flex-col sm:flex-row justify-center gap-6 w-full max-w-lg">
            <a href="https://wa.me/6285185950350" target="_blank" class="group flex items-center justify-center px-10 py-5 bg-brand-teal text-white rounded-[2rem] font-black text-xl hover:shadow-2xl hover:shadow-brand-teal/30 transition-all gap-3 hover:-translate-y-1">
              <MessageSquare class="w-6 h-6" />
              WhatsApp Admin
              <ArrowUpRight class="w-5 h-5 group-hover:translate-x-1 group-hover:-translate-y-1 transition-transform" />
            </a>
            <a href="#services" class="flex items-center justify-center px-10 py-5 bg-white border-2 border-slate-100 rounded-[2rem] font-black text-xl hover:bg-slate-50 transition-all hover:border-brand-teal/20">
              Lihat Harga
            </a>
          </div>

          <!-- Trust Badges -->
          <div class="mt-20 grid grid-cols-2 md:grid-cols-4 gap-8 opacity-60">
             <div class="flex items-center gap-2 grayscale hover:grayscale-0 transition cursor-default">
               <Zap class="w-5 h-5 text-brand-gold" />
               <span class="font-bold">Super Cepat</span>
             </div>
             <div class="flex items-center gap-2 grayscale hover:grayscale-0 transition cursor-default">
               <Truck class="w-5 h-5 text-brand-teal" />
               <span class="font-bold">Bisa Antar</span>
             </div>
             <div class="flex items-center gap-2 grayscale hover:grayscale-0 transition cursor-default">
               <ShieldCheck class="w-5 h-5 text-brand-rust" />
               <span class="font-bold">Kualitas Rapi</span>
             </div>
             <div class="flex items-center gap-2 grayscale hover:grayscale-0 transition cursor-default">
               <Smartphone class="w-5 h-5 text-brand-teal" />
               <span class="font-bold">Pesan via WA</span>
             </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Why Us Section -->
    <section class="py-24 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="group p-10 bg-brand-cream rounded-[3rem] transition-all hover:bg-white hover:shadow-2xl hover:shadow-brand-rust/5 border border-transparent hover:border-brand-rust/10">
            <div class="w-16 h-16 bg-brand-rust/10 text-brand-rust rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform">
              <Clock class="w-8 h-8" />
            </div>
            <h3 class="text-2xl font-bold mb-4">Butuh Cetak Pagi?</h3>
            <p class="text-slate-500 leading-relaxed font-medium">Banyak toko tutup saat pagi buta? Kami siap membantu kebutuhan cetak mendesak Anda dengan proses yang kilat.</p>
          </div>
          
          <div class="group p-10 bg-brand-teal/5 rounded-[3rem] transition-all hover:bg-white hover:shadow-2xl hover:shadow-brand-teal/5 border border-transparent hover:border-brand-teal/10">
            <div class="w-16 h-16 bg-brand-teal/10 text-brand-teal rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform">
              <School class="w-8 h-8" />
            </div>
            <h3 class="text-2xl font-bold mb-4">Lupa Print Tugas?</h3>
            <p class="text-slate-500 leading-relaxed font-medium">Sudah di sekolah baru teringat ada tugas? Cukup WA filenya, admin segera kerjakan dan kirim ke lokasi!</p>
          </div>

          <div class="group p-10 bg-brand-gold/5 rounded-[3rem] transition-all hover:bg-white hover:shadow-2xl hover:shadow-brand-gold/5 border border-transparent hover:border-brand-gold/10">
            <div class="w-16 h-16 bg-brand-gold/10 text-brand-gold rounded-2xl flex items-center justify-center mb-8 group-hover:scale-110 transition-transform">
              <Sparkles class="w-8 h-8" />
            </div>
            <h3 class="text-2xl font-bold mb-4">Laporan Berantakan?</h3>
            <p class="text-slate-500 leading-relaxed font-medium">Bingung format skripsi atau laporan tidak rapi? Kami bantu merapikan dokumen Anda hingga siap dikumpulkan!</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Services & Pricing -->
    <section id="services" class="py-24 relative">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex flex-col items-center mb-20">
          <h2 class="text-4xl md:text-5xl font-black mb-6">Layanan & <span class="text-brand-teal">Daftar Harga</span></h2>
          <p class="text-slate-500 font-medium text-center max-w-xl">Harga transparan dengan kualitas terbaik. Berbagai pilihan media cetak sesuai kebutuhan Anda.</p>
        </div>

        <div id="prices" class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-start">
          <!-- Main Table -->
          <div class="bg-white p-10 md:p-14 rounded-[4rem] shadow-xl shadow-slate-200/50 border border-slate-50">
            <div class="flex items-center gap-4 mb-12">
              <div class="p-3 bg-brand-teal/10 rounded-xl">
                <Printer class="w-8 h-8 text-brand-teal" />
              </div>
              <h3 class="text-3xl font-black">Cetak Dokumen & Foto</h3>
            </div>
            
            <div class="space-y-6">
              <div v-for="item in printingServices" :key="item.name" class="flex justify-between items-center group">
                <div class="flex flex-col">
                  <span class="text-lg font-bold text-slate-700 group-hover:text-brand-teal transition-colors">{{ item.name }}</span>
                  <span class="text-xs text-slate-400 font-bold uppercase tracking-widest">Ukuran A4/F4</span>
                </div>
                <div class="flex items-center gap-4 grow mx-8">
                   <div class="h-px bg-slate-100 grow"></div>
                </div>
                <div class="flex flex-col items-end">
                  <span class="text-sm text-slate-400">Rp / lembar</span>
                  <span class="text-xl font-black text-brand-teal">{{ item.price }}</span>
                </div>
              </div>
            </div>

            <div class="mt-12 p-6 bg-brand-cream rounded-3xl flex items-center gap-4">
               <Info class="w-6 h-6 text-brand-rust" />
               <p class="text-sm font-bold text-brand-rust/80">
                 File bisa dikirim melalui WhatsApp atau Email demi kemudahan Anda.
               </p>
            </div>
          </div>

          <!-- Right Column -->
          <div class="space-y-12">
            <!-- Jasa Section -->
            <div class="bg-brand-rust p-10 md:p-14 rounded-[4rem] text-white shadow-xl shadow-brand-rust/20">
              <div class="flex items-center gap-4 mb-10">
                <div class="p-3 bg-white/10 rounded-xl flex items-center justify-center">
                  <FileText class="w-8 h-8 text-white" />
                </div>
                <h3 class="text-3xl font-black">Jasa Khusus</h3>
              </div>
              
              <div class="space-y-8">
                <div v-for="item in otherServices" :key="item.name" class="flex justify-between items-start">
                  <div class="flex flex-col max-w-[60%]">
                    <span class="text-lg font-bold">{{ item.name }}</span>
                    <span class="text-sm text-white/70">{{ item.desc }}</span>
                  </div>
                  <span class="px-4 py-2 bg-white/10 rounded-full text-sm font-bold border border-white/10 shrink-0 text-center">
                    {{ item.price }}
                  </span>
                </div>
              </div>
            </div>

            <!-- Features Cards -->
            <div class="grid grid-cols-2 gap-6">
              <div class="bg-white p-8 rounded-[3rem] border border-slate-100 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 bg-brand-teal/10 rounded-2xl flex items-center justify-center mb-4">
                  <Truck class="w-6 h-6 text-brand-teal" />
                </div>
                <h4 class="font-black text-lg mb-1">Bisa Antar</h4>
                <p class="text-xs text-slate-500 leading-relaxed font-bold">Khusus wilayah <span class="text-brand-rust">Jombang Kota</span> saja.</p>
              </div>
              <div class="bg-white p-8 rounded-[3rem] border border-slate-100 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 bg-brand-gold/10 rounded-2xl flex items-center justify-center mb-4">
                  <Wallet class="w-6 h-6 text-brand-gold" />
                </div>
                <h4 class="font-black text-lg mb-1">Pembayaran</h4>
                <p class="text-xs text-slate-500 leading-relaxed font-bold">Cash, Bank Transfer, & <span class="text-brand-teal">ShopeePay</span>.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact & Map -->
    <section id="location" class="py-24 bg-brand-beige relative overflow-hidden">
      <!-- Decorative background -->
       <div class="absolute inset-0 opacity-40" style="background-image: radial-gradient(#007B8C 0.5px, transparent 0.5px); background-size: 24px 24px;"></div>

      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="bg-white rounded-[4rem] overflow-hidden shadow-2xl flex flex-col lg:flex-row">
          <div class="lg:w-1/2 p-10 md:p-20">
            <h2 class="text-4xl font-black mb-10 leading-tight">Mampir Ke Workshop <br/> Kami di <span class="text-brand-teal">Jombang</span></h2>
            
            <div class="space-y-10">
              <div class="flex gap-6 group">
                <div class="w-14 h-14 bg-slate-50 rounded-2xl flex items-center justify-center shrink-0 group-hover:bg-brand-rust/10 transition-colors">
                  <MapPin class="w-7 h-7 text-brand-rust" />
                </div>
                <div>
                  <h4 class="font-black text-xl mb-1">Alamat Pengambilan</h4>
                  <p class="text-slate-500 text-lg leading-relaxed">Jl. Gubernur Suryo VII/J-2 Jombang</p>
                </div>
              </div>

              <div class="flex gap-6 group">
                <div class="w-14 h-14 bg-slate-50 rounded-2xl flex items-center justify-center shrink-0 group-hover:bg-brand-teal/10 transition-colors">
                  <Phone class="w-7 h-7 text-brand-teal" />
                </div>
                <div>
                  <h4 class="font-black text-xl mb-1">WhatsApp Admin</h4>
                  <p class="text-slate-500 text-lg">0851-8595-0350</p>
                </div>
              </div>

              <div class="flex gap-6 group">
                <div class="w-14 h-14 bg-slate-50 rounded-2xl flex items-center justify-center shrink-0 group-hover:bg-brand-gold/10 transition-colors">
                  <Mail class="w-7 h-7 text-brand-gold" />
                </div>
                <div>
                  <h4 class="font-black text-xl mb-1">Email Dokumen</h4>
                  <p class="text-slate-500 text-lg">lembarnona@gmail.com</p>
                </div>
              </div>
            </div>
            
            <div class="mt-16 pt-10 border-t border-slate-100 flex flex-col sm:flex-row gap-6">
              <a href="https://wa.me/6285185950350" target="_blank" class="flex-1 inline-flex items-center justify-center gap-3 px-8 py-5 bg-brand-teal text-white rounded-3xl font-black hover:shadow-xl hover:shadow-brand-teal/20 transition-all active:scale-95">
                Chat via WhatsApp
                <ArrowRight class="w-5 h-5" />
              </a>
              <a href="https://www.google.com/maps" target="_blank" class="px-8 py-5 bg-slate-900 text-white rounded-3xl font-black hover:bg-black transition-all text-center">
                Buka Petunjuk Jalan
              </a>
            </div>
          </div>

          <div class="lg:w-1/2 min-h-[500px] relative bg-brand-teal/5 flex items-center justify-center overflow-hidden">
             <!-- Abstract Map Visual -->
             <div class="absolute inset-0 pointer-events-none opacity-20 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
             
             <!-- Floating Paper Element like Logo -->
             <div class="relative w-72 h-72 md:w-96 md:h-96">
                <!-- Shadow circle -->
                <div class="absolute inset-0 bg-brand-teal/10 rounded-full blur-[80px] animate-pulse"></div>
                
                <!-- The "Paper" card -->
                <div class="absolute inset-0 bg-white shadow-2xl rounded-[2rem] border border-slate-100 flex flex-col items-center justify-center p-10 transform -rotate-3 hover:rotate-0 transition-transform duration-700">
                    <div class="w-24 h-24 bg-brand-rust rounded-full flex items-center justify-center mb-6 shadow-xl animate-bounce-slow">
                        <MapPin class="w-12 h-12 text-white" />
                    </div>
                    <h3 class="text-3xl font-black text-brand-teal mb-2">Lembar<span class="text-brand-rust">nona</span></h3>
                    <p class="text-slate-400 font-bold tracking-widest uppercase text-xs text-center">Print Online Center</p>
                    
                    <div class="mt-8 flex gap-2">
                       <span class="px-3 py-1 bg-brand-gold/20 text-brand-gold text-[10px] font-black rounded-lg">RAHASIA</span>
                       <span class="px-3 py-1 bg-brand-teal/20 text-brand-teal text-[10px] font-black rounded-lg">CEPAT</span>
                       <span class="px-3 py-1 bg-brand-rust/20 text-brand-rust text-[10px] font-black rounded-lg">RAPI</span>
                    </div>

                    <!-- Paper Curl Effect -->
                    <div class="absolute bottom-0 right-0 w-24 h-24 bg-gradient-to-tl from-slate-200 to-transparent flex items-center justify-center" style="clip-path: polygon(100% 0, 0% 100%, 100% 100%);">
                         <div class="absolute inset-0 bg-white shadow-[-10px_-10px_20px_rgba(0,0,0,0.05)]" style="clip-path: polygon(0 100%, 100% 0, 100% 100%);"></div>
                    </div>
                </div>
             </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-16 bg-white border-t border-slate-100">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex flex-col md:flex-row justify-between items-center gap-8">
          <div class="flex items-center gap-3">
            <div class="w-8 h-8 bg-brand-teal rounded-lg flex items-center justify-center text-white font-bold">L</div>
            <span class="text-xl font-bold tracking-tight text-brand-teal">Lembar<span class="text-brand-rust italic">nona</span></span>
          </div>
          
          <div class="flex gap-8 text-slate-400 font-bold text-sm uppercase tracking-widest">
            <a href="#" class="hover:text-brand-teal transition">Beranda</a>
            <a href="#services" class="hover:text-brand-teal transition">Layanan</a>
            <a href="#prices" class="hover:text-brand-teal transition">Harga</a>
          </div>

          <div class="text-slate-400 text-sm font-bold">
            © 2024 Lembar Nona. Made with ❤️ in Jombang.
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { 
  Sparkles, MessageSquare, Clock, School, 
  Printer, FileText, Truck, Wallet, 
  MapPin, Phone, Mail, ArrowRight, ArrowUpRight,
  Zap, ShieldCheck, Smartphone, Info
} from 'lucide-vue-next'

const printingServices = [
  { name: 'Fotocopy', price: '250' },
  { name: 'Print Hitam Putih', price: '500' },
  { name: 'Print Warna Ringan', price: '1.000' },
  { name: 'Print Warna Full', price: '1.500' },
  { name: 'Print Kertas Foto', price: '2.500' },
  { name: 'Print Kertas Stiker', price: '2.000' },
]

const otherServices = [
  { name: 'Scan Dokumen A4', price: 'Rp 2.000', desc: 'Output PDF atau JPG berkualitas tinggi' },
  { name: 'Pengetikan', price: 'Variatif', desc: 'Bantuan pengetikan dokumen cepat & akurat' },
  { name: 'Desain Grafis', price: 'Variatif', desc: 'CV, Poster, Daftar Menu, dan lain-lain' },
  { name: 'Merapikan Dokumen', price: 'Variatif', desc: 'Format skripsi, laporan, atau tugas akhir' },
  { name: 'Convert File', price: 'Variatif', desc: 'Ubah PDF ke Word, atau sebaliknya' },
]
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800;900&display=swap');

html {
  scroll-behavior: smooth;
}

body {
  font-family: 'Plus Jakarta Sans', sans-serif;
  @apply selection:bg-brand-teal selection:text-white;
}

@keyframes fade-in {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}

.animate-fade-in {
  animation: fade-in 0.8s ease-out forwards;
}
</style>
