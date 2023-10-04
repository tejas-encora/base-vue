<script setup>
import { VButton } from 'iodine-lib'
import { NonVuetify } from 'iodine-lib'
import { VTextInput } from 'iodine-lib'
import { VDatePick } from 'iodine-lib'
import 'vuetify/dist/vuetify.min.css'
</script>

<template>
  <v-app>
    <v-main>
      <VTextInput />
      <VButton />
      <NonVuetify/>
      <VDatePick />
    </v-main>
  </v-app>
</template>

