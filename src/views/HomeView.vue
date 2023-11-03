<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Contoh Tugas Akhir</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Bersama Membangun Desa Cimanggu II Maju, Mandiri, berkeadaban dan Berkesholehah Sosial"
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Pelayanan Masyarakat yang Optimal;
        </li>
        <li>
          2. Peningkatan Mutu Sumberdaya Manusia dan Perangkat Desa;
        </li>
        <li>
          3. Menumbuh Kembangkan Kepekaan dan Kepedulian Sosial;
        </li>
        <li>
          4. Pemberdayaan Masyarakat Dalam Bidang Ekonomi;
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
