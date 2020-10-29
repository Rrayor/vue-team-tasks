<template>
  <v-card class="mx-auto my-12" max-width="50%">
    <v-container>
      <v-card-title> Register </v-card-title>
      <v-card-text>
        <v-form>
          <v-text-field label="E-mail"></v-text-field>
          <v-text-field label="Password"></v-text-field>
          <v-btn color="primary">Register</v-btn>
        </v-form>
      </v-card-text>
    </v-container>
  </v-card>
</template>

<script>
export default {
  name: 'Register'
}
</script>

<style>
</style>