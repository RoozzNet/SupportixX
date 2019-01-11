<template lang='pug'>
  footer.p2.bg--off-white
    .contain
      p
        em Use Supportix at your own risk.
      p © All Right Reserved 2018 Supportix.net
</template>

<script>
const gekkoPackage = require('../../../../../package.json');
const uiPackage = require('../../../package.json');

export default {
  data: () => {
    return {
      version: {
        gekko: gekkoPackage.version,
        ui: uiPackage.version
      }
    }
  }
}
</script>
