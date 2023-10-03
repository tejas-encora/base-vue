<script setup>
import { VButton } from 'iodine-vuetify-lib'
import { NonVuetify } from 'iodine-vuetify-lib'
import { VTextInput } from 'iodine-vuetify-lib'
import { VDatePicker } from 'vuetify/labs/VDatePicker'
import { VDatePick } from 'iodine-vuetify-lib'
// import 'iodine-vuetify-lib/style.css'
import 'vuetify/dist/vuetify.min.css'
</script>

<template>
  <v-app>
    <v-main>
      <VTextInput />
      <VButton />
      <NonVuetify/>
      <VDatePicker />
      <VDatePick />
    </v-main>
  </v-app>
</template>

