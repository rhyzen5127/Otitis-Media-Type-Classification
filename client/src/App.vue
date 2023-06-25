<template>
  <v-app>
    <v-main>
      <router-view :key="$route.path" />
    </v-main>
  </v-app>
</template>

<script>
// Components

export default {
  name: 'App',

  components: {
  },

  data: () => ({
  }),

  computed: {
  },

  setup() {
  },

  methods: {
  },

  mounted() {
  }
}
</script>
