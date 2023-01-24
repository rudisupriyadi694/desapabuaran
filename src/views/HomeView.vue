<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">

      <p class="text-3xl font-semibold">Sejarah Desa</p>
      <p>Tidak diketahui dengan pasti sejak kapan desa Pabuaran berdiri karena minimnya data yang dapat dijadikan acuan sebagai patokan sejarah berdirinya desa Pabuaran,
        Pada mulanya desa : Pabuaran dan desa : Cibadak adalah satu desa yaitu desa : Pabuaran sekitar tahun 1970 Kepala desanya dijabat oleh: KAHIN
        Tahun 1978 desa Pabuaran dimekarkan menjadi dua desa yaitu desa Pabuaran dan desa Cibadak setelah pemekaran menata pemerintahan sendiri dengan susunan sebagai berikut</p>
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p>Visi:</p>
      <p>"Melayani Masyarakat Desa untuk terwujudnya Masyarakat Religius dan Mandiri"</p>
      <p>Misi:</p>
      <p>a. Mewujudkan Pemerintahan desa yang yang Good Government dan mandiri dengan pelayanan yang efekif, efisien, dan transparan dan akuntabel serta berkeadilan.</p>
      <p>b. Menyediakan sumberdaya pemerintahan desa kelembagaan desa yang berkualitas dengan meningkatkan keahlian dan kinerja.</p>
      <p>c. Mewujudkan Masyarakat yang berpengetahuan dan berketerampilan melalui kegiatan pemberdayaan yang bersinergi dan terarah.</p>
      <p>d. Meningkatkan Kesejahtraan Masyaakat Melalui Penguatan Perekonomian dengan pembinaan dan pemberdayaan.</p>
      <p>e. Mewujudkan kualitas manusia sebagai sumberdaya pembangunan yang beriman dan bertaqwa kepada Tuhan yang maha kuasa.</p>
      <p>f. Menjadikan Pelayanan kebutuhan dasar masyarakat dengan memperioritaskan pembangunan dibidang kesehatan,pendidikan dan ketersediaan sandang, dan pangan bagi masyarakat miskin.</p>
      <p>g. Meningkatkan Peran Lembaga desa dalam rangka meningkatkan peran pembangunan desa melalui pembinaan yang terarah dan berkelanjutan.</p>
      <p>h. Meningkatkan pendapatan asli desa dengan menyiapkan SDM dalam mengembangkan BUMDesa melalui pelatihan pengelolaan dan penguatan modal BUMDesa.</p>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/Struktur-Desa.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
