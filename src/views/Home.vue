<template>
  <div class="home">
    <template>
      <div>
        <v-alert type="success">
          I'm a success alert.
        </v-alert>

        <v-alert type="info">
          I'm an info alert.
        </v-alert>

        <v-alert type="warning">
          I'm a warning alert.
        </v-alert>

        <v-alert type="error">
          I'm an error alert.
        </v-alert>
      </div>
    </template>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  data: () => ({
    active: true
  })
};
</script>
