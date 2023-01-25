<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fa fa-camera"></i><strong>&nbsp;Photo Album</strong></a
        >
      </div>
    </div>
  </header>
  <main role="main">
    <section class="jumbotron text-center">
      <div class="container">
        <h1>Feed</h1>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="row">
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
     
    </div>
  </footer>
</template>

<style scoped></style>
