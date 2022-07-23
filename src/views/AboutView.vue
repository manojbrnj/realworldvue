<template>
  <div>
    <EventCard></EventCard>
  </div>
</template>
<script>
import EventCard from "@/components/EventCard.vue";
export default {
  name: "AboutView",
  components: {
    EventCard,
  },
  data: function () {
    return {
      dat: "",
    };
  },
};
</script>
<style lang=""></style>
