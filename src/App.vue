<template>
  <list :items="items"/>
</template>

<script>

export default {
  name: "App",
  data:() => ({
    items: [
      {nombre: "Rick Sanchez",
      src:"https://rickandmortyapi.com/api/character/avatar/1.jpeg"},
      {nombre: "Morty Smith",
      src:"https://rickandmortyapi.com/api/character/avatar/2.jpeg"},
      {nombre: "Summer Smith",
      src:"https://rickandmortyapi.com/api/character/avatar/3.jpeg"},
      {nombre: "Beth Smith",
      src:"https://rickandmortyapi.com/api/character/avatar/4.jpeg"},
      {nombre: "Jerry Smith",
      src:"https://rickandmortyapi.com/api/character/avatar/5.jpeg"},
    ],
  })
};
</script>

<style lang="scss">
  body {
    background-image: url('https://rickandmortypod.com/wp-content/uploads/2018/11/cropped-RM_page-header_background1-3.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    height: 100vh;
  }
</style>
