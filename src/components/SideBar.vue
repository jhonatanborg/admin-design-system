<template>
  <div id="parentx"></div>
</template>

<script>
export default {
  data: () => ({
    active: true
  })
};
</script>

<style>
.header-sidebar {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 100%;
}

h4 {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}

h4 button {
  margin-left: 10px;
}

/* .footer-sidebar
  display flex
  align-items center
  justify-content space-between
  width 100%
  > button
      border 0px solid rgba(0,0,0,0) !important
      border-left 1px solid rgba(0,0,0,.07) !important
      border-radius 0px !important */
</style>
