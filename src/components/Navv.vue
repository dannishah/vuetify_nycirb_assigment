<template>
  <v-navbar class="bg-grey-lighten-1 navbar">
    <v-row class="nav" justify="center" no-gutters>
      <div class="logo"></div>
      <v-btn
        v-for="link in links"
        :key="link"
        color="black"
        variant="text"
        class="mx-0.2 my-6 nav-data"
      >
        {{ link }}
      </v-btn>
    </v-row>
  </v-navbar>
</template>

<script>
/*eslint-disable*/
export default {
  data: () => ({
    links: [
      "INSURANCE CARRIER",
      "BROKER & EMPLOYER",
      "RESEARCH & REPORT",
      "FORMS",
      "MANUALS",
      "FORUMS",
      "RC BULLETINS",
      "ABOUT",
    ],
  }),
};
</script>

<style scoped>
.nav {
  height: 80px;
  background: white;
  z-index: 200;
  position: fixed;
  top: 0;
  left: 0;
}

.nav-data {
  font-size: 12px;
  font-weight: 400;
  letter-spacing: 0;
}
.logo {
  height: 45px;
  width: 160px;
  margin-top: 15px;
  margin-right: 70px;
  background: url("/icon.png");
  background-size: cover;
  object-fit: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.logo:hover {
  cursor: pointer;
}
</style>
