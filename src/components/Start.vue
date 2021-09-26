<template>
  <div id="interface" class="dualframe">
    <div id="sword" class="charaterframe">
      <div class="row">
        <button class="mainbutton">sword</button>
      </div>
      <div class="row">
        <label>血量</label>
      </div>
      <div class="row">
        <label>初始能量</label>
      </div>
      <div class="row">
        <button class="mainbutton">技能详情</button>
      </div>
    </div>
    <div id="mana" class="charaterframe">
      <div class="row">
        <button class="mainbutton">mana</button>
      </div>
      <div class="row">
        <label>血量</label>
      </div>
      <div class="row">
        <label>初始能量</label>
      </div>
      <div class="row">
        <button class="mainbutton">技能详情</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Start",
};
</script>

<style scoped>
.column {
  float: left;
  width: 50%;
}
</style>
