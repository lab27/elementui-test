<template lang="pug">
    div
      mt-cell(
        title="About"
        to="/about"
        is-link)
      mt-cell-swipe(title="Message" :right="[{content:'doodle', style:{background: 'red', color: 'white'}},{content:'poodle', style:{background: 'dodgerblue', color:'white'}}]")

</template>

<script>

export default {

  data () {
    return {
      // date: '',
      // checked: true,
      // value1: 0
    }
  }
}
</script>

<style scoped>
.el-col {
  padding: 23px;
}
  .red {
    background-color: red;
  }

.blue {
  background: dodgerblue;
}

.yellow {
  background: lemonchiffon;
}

.green {
  background: lime;
}

.orange {
  background:orange;
}

.gray {
  background:#f9f9f9;
}

.mint-cell {
  border-bottom: 1px solid #bbb;
}

</style>
