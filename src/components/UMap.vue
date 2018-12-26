<template>
  <div class="umap">
    <iframe
      width="100%"
      height="100%"
      frameBorder="0"
      allowfullscreen
      src="https://umap.openstreetmap.fr/fr/map/welcome-map-annecy_263447?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=true&searchControl=true&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=undefined&captionBar=false"
    ></iframe>
    <!--
        <p>
      <a href="https://umap.openstreetmap.fr/fr/map/welcome-map-annecy_263447"
        >Voir en plein écran</a
      >
    </p>
    -->
  </div>
</template>

<script>
export default {
  name: "UMap"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.umap {
  height: 100%;
  width: 100%;
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
