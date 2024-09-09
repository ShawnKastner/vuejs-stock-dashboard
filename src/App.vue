<template>
  <div>
    <BaseCard>
      <h2>Title of the Card</h2>
      <p>This is some content inside the card.</p>
    </BaseCard>
  </div>
</template>

<script>
import BaseCard from "./components/BaseCard.vue";

export default {
  name: "App",
  components: {
    BaseCard,
  },
};
</script>

<style>
body {
  margin: 0;
  padding: 100px;
  background: radial-gradient(
    71.11% 100% at 50% 0%,
    #020204 14.6%,
    #011f35 100%
  );
  box-sizing: border-box;
  width: 100vw;
  height: 100vh;
}
</style>
