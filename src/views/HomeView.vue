<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <SideBar />
    <RightSideBar />
  </v-app>
</template>

<script>
import RightSideBar from "../components/RightSideBar.vue";
import SideBar from "../components/SideBar.vue";
export default {
  name: "HomePage",
  data: () => ({
    selection: 1,
    drawer: true,
    shoes: [
      {
        image: "3.jpg",
        pic: "1.png",
        price: "$465",
        id: "ID: CK1911159967352",
        date: "02.12.2021, 3:34 AM",
        marque: "Nike Air MAx",
        pay1: "LUXEMBURG",
        pay2: "ITALY",
        avatar: "https://cdn.vuetifyjs.com/images/lists/1.jpg",
      },
      {
        image: "9.jfif",
        pic: "2.png",
        price: "$714",
        id: "ID: CK1911159967621",
        date: "02.12.2021, 4:12 AM",
        marque: "AIR Jordon",
        pay1: "FUTURE",
        pay2: "WAR",
        avatar: "https://cdn.vuetifyjs.com/images/lists/2.jpg",
      },
      {
        image: "8.jpg",
        pic: "3.png",
        price: "$982",
        id: "ID: CK1911159967532",
        date: "02.12.2021, 6:24 AM",
        marque: "Adidas GR",
        pay1: "LONDON",
        pay2: "ALGERIA",
        avatar: "https://cdn.vuetifyjs.com/images/lists/3.jpg",
      },
      {
        image: "7.jpg",
        pic: "4.png",
        price: "$394",
        id: "ID: CK1911159968663",
        date: "02.12.2021, 7:51 AM",
        marque: "Puma New",
        pay1: "SRILANKA",
        pay2: "PALAU",
        avatar: "https://cdn.vuetifyjs.com/images/lists/4.jpg",
      },
    ],
    orders: [
      {
        pic: "5.png",
        price: "€465",
      },
      {
        pic: "6.png",
        price: "€714",
      },
      {
        pic: "7.png",
        price: "€982",
      },
      {
        pic: "8.png",
        price: "€394",
      },
    ],
  }),
  components: {
    SideBar,
    RightSideBar,
  },
  methods: {},
};
</script>

<style scoped>
.v-tab.withoutupercase {
  text-transform: none !important;
}
.v-tabs {
  width: 50% !important;
}
.v-btn.withoutupercase {
  text-transform: none !important;
}
/*div{
  display:inline-block;
  float:left;
  color:#fff;
  font-size:10px;
}*/
.three {
  width: 50px;
  height: 50px;
}
.four {
  width: 50px;
  height: 25px;
  background: black;
}
.five {
  width: 50px;
  height: 25px;
  background: #042a0f;
}
.six {
  width: 50px;
  height: 25px;
  background: #2c2107;
}
</style>
