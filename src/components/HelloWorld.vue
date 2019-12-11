<template>
  <div class="hello">
    <h1>Hello ? {{ usr }}</h1>
    <article>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Expedita cupiditate nesciunt optio eos temporibus iste aut, dolorum quod molestiae aperiam reprehenderit possimus velit voluptatum consequatur, voluptatibus doloribus quibusdam consequuntur voluptates.</p>
      <h3>{{ article.subheading }}</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut similique dicta omnis quis placeat quaerat nostrum dolorum, explicabo iusto soluta officiis, impedit possimus nihil aperiam adipisci nobis voluptates sapiente? Repellat!</p>
    </article>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    usr: String
  },
  data() {
    return {
      article: {
        subheading: 'SOmething something'
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
