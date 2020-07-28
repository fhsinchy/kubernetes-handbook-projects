<template>
  <h1>{{ msg }}</h1>
  <p>A folow-up to <a href="https://www.freecodecamp.org/news/the-docker-handbook/" target="_blank">The Docker Handbook</a></p>
  <hr>
  <p>
    <strong>Author:</strong> <a href="https://www.freecodecamp.org/news/author/farhanhasin/" target="_blank">Farhan Hasin Chowdhury</a>
    <br>
    <strong>Website:</strong> <a href="https://www.farhan.info/" target="_blank">https://farhan.info/</a>
    <br>
    <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/farhanhasin/" target="_blank">/in/farhanhasin</a>
    <br>
    <strong>Twitter:</strong> <a href="https://twitter.com/frhnhsin" target="_blank">@frhnhsin</a>
  </p>
</template>

<script>
export default {
  name: 'HelloKube',
  props: {
    msg: String
  },
}
</script>
