<script>
import ImageComp from "./ImageComp.vue";
export default {
  name: "CardComp",
  props: {
    data: Object,
  },
  components: {
    ImageComp,
  },
};
</script>

<template>
<div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col">
        <div class="card h-100">
          <ImageComp :src="data.img" />
          <div class="card-body">
            <h5 class="card-title">Project 1</h5>
            <p>Membuat web Portopolio pribadi</p>
            <p class="card-text">Berikut adalah hasil project saya selama belajar basic web programming membuat Portopolio.</p>
            <a 
          href="https://dopaganteng.github.io/Basic-website-dova.github.io/home.html"
          class="btn btn-outline-primary"
          >More</a>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
</div>
</template>