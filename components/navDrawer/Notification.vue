<template>
  <v-list-item>
    <span></span>
    <v-list-item-content>
      <v-list-item-title>
        {{ notification.lineOne }}
      </v-list-item-title>
      <v-list-item-subtitle>
        {{ notification.lineTwo }}
      </v-list-item-subtitle>
      <v-list-item-subtitle>
        {{ notification.lineThree }}
      </v-list-item-subtitle>
    </v-list-item-content>
  </v-list-item>
</template>

<script>
export default {
  props: {
    notification: {
      type: Object,
      default: () => {},
    },
  },
}
</script>
