<template>
  <div class="app">
    <div class="row">
      <mc-button>按钮</mc-button>
      <mc-button type="primary">按钮</mc-button>
      <mc-button type="success">按钮</mc-button>
      <mc-button type="info">按钮</mc-button>
      <mc-button type="warning">按钮</mc-button>
    </div>
    <div class="row">
      <mc-button plain>按钮</mc-button>
      <mc-button plain type="primary">按钮</mc-button>
      <mc-button plain type="success">按钮</mc-button>
      <mc-button plain type="info">按钮</mc-button>
      <mc-button plain type="warning">按钮</mc-button>
    </div>
    <div class="row">
      <mc-button round plain>按钮</mc-button>
      <mc-button round plain type="primary">按钮</mc-button>
      <mc-button round plain type="success">按钮</mc-button>
      <mc-button round plain type="info">按钮</mc-button>
      <mc-button round plain type="warning">按钮</mc-button>
    </div>
    <div class="row">
      <mc-button circle>OK</mc-button>
      <mc-button circle type="primary">OK</mc-button>
      <mc-button circle type="success">OK</mc-button>
      <mc-button circle type="info">OK</mc-button>
      <mc-button circle type="warning">OK</mc-button>
    </div>
    <div class="row">
      <mc-button plain>字体</mc-button>
      <mc-button icon="mc-icon-check" circle plain type="primary"></mc-button>
      <mc-button icon="mc-icon-message" circle plain type="success"></mc-button>
      <mc-button icon="mc-icon-search" circle plain type="info"></mc-button>
      <mc-button icon="mc-icon-star-off"  plain type="warning">字体图标</mc-button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    jump (e) {
      console.log(e)
      alert(123)
    }
  }
}
</script>

<style lang="scss" scoped>
.app {
    width: 600px;
    height: 200px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 100px;
}
.row {
  padding: 10px 0;
}
.mc-button {
  margin-left: 10px;
}
</style>
