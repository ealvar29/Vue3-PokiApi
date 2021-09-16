<template>
  <div class="home">
    <div>Hello World</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  setup(){
    fetch("https://pokeapi.co/api/v2/pokemon/ditto")
    .then((res) => res.json())
    .then((data) => {
      console.log(data);
    })
  }
};
</script>

