<template>
  <div class="card shadow card-product">
    <img :src="'images/' + product.gambar" class="card-img-top" alt="..." />
    <div class="card-body">
      <h5 class="card-title">{{ product.nama }}</h5>
      <p class="card-text">Harga : {{ product.harga }}</p>
      <a href="#" class="btn btn-success">
        <b-icon-cart></b-icon-cart>
        Pesan
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardProductComponent",
  props: ["product"],
};
</script>

<style></style>
