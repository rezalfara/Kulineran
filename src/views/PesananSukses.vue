<template>
  <div class="pesanan-sukses">
    <MainNavbar />
    <div class="container">
        <div class="row justify-content-center mt-5">
            <div class="col text-center">
                <img src="../assets/images/menunggu.png" width="300px"/>
                <h2><strong>Sukses!!</strong></h2>
                <h4>Pesanan Anda segera diproses <br> Selamat Menunggu</h4>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
import MainNavbar from "@/components/MainNavbar.vue";

export default {
  name: "PesananSukses",
  components: {
    MainNavbar,
  },
};
</script>

<style>
</style>