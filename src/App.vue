<template>
  <h1>Microphones can be used not only to pick up sound, but also to project sound similar to a speaker.</h1>

  <input type="radio" name="options" value="true">
  <label>True</label><br>

  <input type="radio" name="options" value="false">
  <label>False</label><br>

  <button type="button" class="send">Send</button>

</template>

<script>

export default {
  name: 'App',
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 60px auto;
  max-width: 960px;

  input {
    margin: 12px 4px;
  }

  button.send {
    margin-top: 12px;
    height: 40px;
    min-width: 120px;
    padding: 0 16px;
    color: #fff;
    background-color: #1867c0;
    border: 1px solid #1867c0;
    cursor: pointer;
  }
}
</style>
