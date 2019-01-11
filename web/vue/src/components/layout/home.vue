<template lang='pug'>
  section.contain.grd-row
    .grd-row-col-3-6(v-html='left')
    .grd-row-col-3-6.txt--center
      img(src='static/supportix.png')
      p
        em Increase your Portfilio | Supportix Bot
</template>





<script>
import marked from '../../tools/marked';

const left = marked(`

## Supportix Bot.

Automated Trading and Arbitrage Software.
Supportix is a Bitcoin trading bot and backtesting platform that
connects to popular Bitcoin exchanges. 

[Find out more](https://supportix.net/).
[Knowledge Base](https://knowledge.supportix.net/).
[Community](https://forum.supportix.net/).


`);

export default {
  data: () => {
    return {
      left
    }
  }
}
</script>
