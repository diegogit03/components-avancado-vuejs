<template>
  <div :class="$style.post">

    <div :class="$style['post-cabecalho']">
      <slot name="cabecalho"></slot>
    </div>

    <div :class="$style['post-conteudo']">
      <slot name="conteudo"></slot>
    </div>

    <div :class="$style['post-rodape']">
      <slot name="rodape"></slot>
    </div>

  </div>
</template>

<style module>
    .post {
      margin: 15px auto;
    }

    .post-cabecalho {
      padding: 5px 12px;
      background-color: #eee;
    }

    .post-conteudo {
      font-size: 16px;
    }

    .post-rodape {
      font-style: italic;
    }
</style>
