<template>
  <div id="app">

    <h1>Vue JS</h1>

    <Post>
      <h2 slot="cabecalho">Components no Vue</h2>
      <template slot="conteudo">
        <p>Components são uma das peças mais importantes no Vue</p>
        <span>...</span>
      </template>
      <small slot="rodape">por Diego</small>
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
