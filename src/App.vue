<template>
  <profiles></profiles>
  <contacts></contacts>
</template>

<script>
import Profiles from "./page/Profiles.vue";
import Contacts from "./page/Contacts.vue";
export default {
  name: "App",
  components: {
    Profiles: Profiles,
    Contacts: Contacts,
  },
};
</script>