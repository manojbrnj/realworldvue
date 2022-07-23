<template>
  <div cols="12" class="event">
    <v-card cols="12" elevation="4" outlined shaped tile>
      <v-card-title>
        {{ event.title }}
      </v-card-title>
      <v-card-subtitle>{{ event.date }} {{ event.time }}</v-card-subtitle>
      <v-card-text>
        <span>{{ event.attendees.length }}</span>
      </v-card-text>
    </v-card>
  </div>
</template>
<script>
export default {
  name: "EventCard",
  data: function () {
    return {
      event: {
        id: 1,
        title: "BeachCleanUp",
        date: "Tues Aug 19,2018",
        time: "6:00",
        attendees: [
          {
            id: "abcd123",
            name: "Adam Jahr",
          },
          {
            id: "abcd456",
            name: "Greff Pollack",
          },
        ],
      },
    };
  },
};
</script>

<style scoped>
h1 {
  color: #e0e0e0;
}
.event {
  display: flex;
  justify-content: space-around;
}
</style>
