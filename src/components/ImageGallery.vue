<template>
  <div>
    <div v-for="(image, index) in images" :key="index">
      <img :src="image" alt="Slika">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: [] 
    };
  }
};
</script>
