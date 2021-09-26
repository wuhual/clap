<template>
  <div
    id="app"
    style="display: flex; align-items: center; justify-content: center"
  >
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.mainbutton {
  margin: 0.5rem 1rem 1rem;
  padding: 0.5rem 1.5rem;
  background-color: #393e46;
  border: 1px #eeeeee solid;
  border-radius: 0.2rem;
  color: #eeeeee;
  font-size: 1.6rem;
  white-space: nowrap;
  cursor: pointer;
}
.charaterframe {
  display: flex;
  flex-direction: column;
  max-width: 30rem;
  text-align: center;
  box-sizing: border-box;
  position: relative;
}
.dualframe {
  display: flex;
  flex-direction: row;
  max-width: 30rem;
  min-width: 5rem;
  text-align: center;
  box-sizing: border-box;
  position: relative;
}
</style>
