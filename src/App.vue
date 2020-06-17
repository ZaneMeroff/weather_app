<template>
  <div id='app'>
    <main>
      <h1>weather app 🌦</h1>
      <div class='search-box'>
        <input type='text' class='search-bar' placeholder='search location...'/>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      apiKey: '06180462381b158b8bc01a1e9dff18a8'
    }
  }
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

body {
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold_background.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

</style>
