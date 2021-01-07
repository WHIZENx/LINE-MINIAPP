<template>
  <v-bottom-navigation app fixed grow color="primary">
    <v-btn value="code" :to="{ name: 'News' }">
      <span>ข่าว</span>
      <v-icon>mdi-newspaper</v-icon>
    </v-btn>
    <v-btn value="favorites" :to="{ name: 'Qrkeep' }">
      <span>เก็บ</span>
      <v-icon>mdi-heart</v-icon>
    </v-btn>
    <v-btn value="Scan" :to="{ name: 'Scan' }">
      <span>สแกน</span>
      <v-icon>mdi-qrcode</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  name: "BottomNav",
  data: () => ({
    drawer: null,
  }),
};
</script>
