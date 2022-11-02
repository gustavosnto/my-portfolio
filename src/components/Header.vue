<template>
    <header class="header">
      <strong>
        <g-link to="/">{{ $static.metadata.siteName }}</g-link>
      </strong>
      <nav class="nav">
        <g-link class="" to="/">Home</g-link>
        <g-link class="" to="/portfolio/">About</g-link>
        <g-link class="" to="/contato/">About</g-link>
      </nav>
    </header>
</template>

<script>
export default {
  metaInfo: {
    title: 'Contato'
  }
}
</script>