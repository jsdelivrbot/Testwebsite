<template>
  <div type = "button" class = "buttonhome">
    <router-link :to="{name: 'Home'}" class = "cancerlink">
      <div class = "hometext">
        <p>CSGO</p>
        <p class = "p1">funbase</p>
      </div>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "buttonhome",
  data() {
    return {
      msg: "placeholder"
    };
  }
};
</script>


<style scoped>
.buttonhome {
  background-color: lightgray;
  border: 2px solid whitesmoke;
  color: white;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 25px;
  text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.5);
  line-height: 0px;
  //cursor: pointer;
  width: 80px;
  height: 51px;
  margin: 5px 5px;
  position: relative;
}

.buttonhome:hover {
  background-color: gainsboro;
  border: 2px solid whitesmoke;
  font-size: 25px;
  text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.5);
  width: 80px;
  height: 51px;
  margin: 5px 5px;
}

.hometext {
  margin: -10px 0px;
}

.p1 {
  font-size: 21px;
}

.cancerlink {
  text-decoration: none;
  color: white;
}
</style>
