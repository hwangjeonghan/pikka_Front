<template>
  <div>
    <hero></hero>
    <basic-elements></basic-elements>
    <javascript-components></javascript-components>
    <carousel></carousel>
  </div>
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";

import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";

export default {
  name: "components",
  components: {
    Hero,
    BasicElements,
    JavascriptComponents,
    Carousel,
  },
};
</script>
