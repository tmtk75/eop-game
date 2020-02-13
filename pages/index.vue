<template>
  <v-row>
    <img
      v-for="p in images"
      :key="p"
      :src="`${staticBase}card-images/${p}`"
      width="96"
    />
  </v-row>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'

@Component
export default class extends Vue {
  get staticBase() {
    return process.env.STATIC_BASE
  }

  images = [
    'EoP_Card Game Images-01.png',
    'EoP_Card Game Images-02.png',
    'EoP_Card Game Images-03.png',
    'EoP_Card Game Images-04.png',
    'EoP_Card Game Images-05.png',
    'EoP_Card Game Images-06.png',
    'EoP_Card Game Images-07.png',
    'EoP_Card Game Images-08.png',
    'EoP_Card Game Images-09.png',
    'EoP_Card Game Images-10.png',
    'EoP_Card Game Images-11.png',
    'EoP_Card Game Images-12.png',
    'EoP_Card Game Images-13.png',
    'EoP_Card Game Images-14.png',
    'EoP_Card Game Images-15.png',
    'EoP_Card Game Images-16.png',
    'EoP_Card Game Images-17.png',
    'EoP_Card Game Images-18.png',
    'EoP_Card Game Images-19.png',
    'EoP_Card Game Images-20.png',
    'EoP_Card Game Images-21.png',
    'EoP_Card Game Images-22.png',
    'EoP_Card Game Images-23.png',
    'EoP_Card Game Images-24.png',
    'EoP_Card Game Images-25.png',
    'EoP_Card Game Images-26.png',
    'EoP_Card Game Images-27.png',
    'EoP_Card Game Images-28.png',
    'EoP_Card Game Images-29.png',
    'EoP_Card Game Images-30.png',
    'EoP_Card Game Images-31.png',
    'EoP_Card Game Images-32.png',
    'EoP_Card Game Images-33.png',
    'EoP_Card Game Images-34.png',
    'EoP_Card Game Images-35.png',
    'EoP_Card Game Images-36.png',
    'EoP_Card Game Images-37.png',
    'EoP_Card Game Images-38.png',
    'EoP_Card Game Images-39.png',
    'EoP_Card Game Images-40.png',
    'EoP_Card Game Images-41.png',
    'EoP_Card Game Images-42.png',
    'EoP_Card Game Images-43.png',
    'EoP_Card Game Images-44.png',
    'EoP_Card Game Images-45.png',
    'EoP_Card Game Images-46.png',
    'EoP_Card Game Images-47.png',
    'EoP_Card Game Images-48.png',
    'EoP_Card Game Images-49.png',
    'EoP_Card Game Images-50.png',
    'EoP_Card Game Images-51.png',
    'EoP_Card Game Images-52.png',
    'EoP_Card Game Images-53.png',
    'EoP_Card Game Images-54.png',
    'EoP_Card Game Images-55.png',
    'EoP_Card Game Images-56.png',
    'EoP_Card Game Images-57.png',
    'EoP_Card Game Images-58.png',
    'EoP_Card Game Images-59.png',
    'EoP_Card Game Images-60.png',
    'EoP_Card Game Images-61.png',
    'EoP_Card Game Images-62.png',
    'EoP_Card Game Images-63.png',
    'EoP_Card Game Images-64.png',
    'EoP_Card Game Images-65.png',
    'EoP_Card Game Images-66.png',
    'EoP_Card Game Images-67.png',
    'EoP_Card Game Images-68.png',
    'EoP_Card Game Images-69.png',
    'EoP_Card Game Images-70.png',
    'EoP_Card Game Images-71.png',
    'EoP_Card Game Images-72.png',
    'EoP_Card Game Images-73.png',
    'EoP_Card Game Images-74.png',
    'EoP_Card Game Images-75.png',
    'EoP_Card Game Images-76.png',
    'EoP_Card Game Images-77.png',
    'EoP_Card Game Images-78.png',
    'EoP_Card Game Images-79.png',
    'EoP_Card Game Images-80.png',
    'EoP_Card Game Images-81.png',
    'EoP_Card Game Images-82.png',
    'EoP_Card Game Images-83.png',
    'EoP_Card Game Images-84.png',
    'EoP_Card Game Images-85.png',
    'EoP_Card Game Images-86.png',
    'EoP_Card Game Images-87.png',
    'EoP_Card Game Images-88.png',
    'EoP_Card Game Images-89.png',
    'EoP_Card Game Images-90.png',
    'EoP_Card Game Images-91.png',
    'EoP_Card Game Images-92.png',
    'EoP_Card Game Images-93.png',
    'EoP_Card Game Images-94.png',
    'EoP_Card Game Images-95.png'
  ]
}
</script>
