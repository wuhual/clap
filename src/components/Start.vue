<template>
  <div id="interface">
    <div id="sword" class="column">
      <div class="row">
        <button>sword</button>
      </div>
      <div class="row">
        <label>血量</label>
      </div>
      <div class="row">
        <label>初始能量</label>
      </div>
            <div class="row">
        <button>技能详情</button>
      </div>
    </div>
    <div id="mana" class="column">
      <div class="row">
        <button>mana</button>
      </div>
      <div class="row">
        <label>血量</label>
      </div>
      <div class="row">
        <label>初始能量</label>
      </div>
            <div class="row">
        <button>技能详情</button>
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
