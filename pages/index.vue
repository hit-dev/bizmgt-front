<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <v-btn flat @click="login">
        ログイン
      </v-btn>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  layout: 'nologin',
  methods: {
    login: function () {
      // ログイン処理
      this.$router.push('/home')
    }
  }
}
</script>
