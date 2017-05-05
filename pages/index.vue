<template>
  <section class="container">
    <el-date-picker
      v-model="date"
      type="date"
      placeholder="Pick a day"
      align="left"
      ref="eldatepicker">
    </el-date-picker>
  </section>
</template>

<script>
import Logo from '~components/Logo.vue'

export default {
  components: {
    Logo
  },

  data () {
    return {
      date: ''
    }
  }
}
</script>
