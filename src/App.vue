<template>
  <div class="container">

    <h1>Vue JS</h1>

    <Post>
      <h2 slot="cabecalho">Components no Vue</h2>

      <p>Components são uma das peças mais importantes no Vue</p>
      <span>...</span>

      <small slot="rodape">por Diego</small>

      <template slot="botao">Detalhes</template>
    </Post>
  </div>
</template>

<script>
import Post from './components/Post.vue'

export default {
  components: {
    Post
  }
}
</script>

<style scoped>
  
  .container {
    width: 990px;
    margin: auto;
  }

</style>
