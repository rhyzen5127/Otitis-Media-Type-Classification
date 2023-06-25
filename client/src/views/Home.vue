<template>
  Test from Home.vue
  <br />
  <ComponentsTest />
  <br />
  <IconTests />
  <br />
  <v-btn> btn test </v-btn>
</template>

<script>
// Components
import ComponentsTest from '@/components/ComponentsTest.vue'
import IconTests from '@/components/icons/IconsTest.vue'

export default {
  name: 'Home',

  components: {
    ComponentsTest,
    IconTests,
  },

  data() {
  },

  methods: {

  },

  watch: {
  },




  computed: {
  },

  setup() {
  },

  mounted() {
  }


}
</script>