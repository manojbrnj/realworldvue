<template>
  <div>
    <hello-world />
    <event-card></event-card>
    <div>HelloWorld</div>
  </div>
</template>
<script>
import HelloWorld from "../components/HelloWorld";
import EventCard from "@/components/EventCard.vue";
export default {
  name: "Home",
  props: {
    propName: {
      type: Number,
      default: 4,
    },
  },
  components: {
    HelloWorld,
    EventCard,
  },
};
</script>
