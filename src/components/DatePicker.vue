<template>
  <v-app>
    <v-date-picker v-model="picker" />
  </v-app>
</template>

<script>
  import {VApp, VDatePicker} from 'vuetify'

  export default {
    data: () => ({
      picker: null,
    }),
    components: {
      VApp,
      VDatePicker,
    },
  }
</script>

<!-- <style scoped lang="stylus"> -->
<!--   @import('../../node_modules/vuetify/src/stylus/app'); -->
<!--   @import('../../node_modules/vuetify/src/stylus/components/_pickers'); -->
<!--   @import('../../node_modules/vuetify/src/stylus/components/_date&#45;picker'); -->
<!-- </style> -->
