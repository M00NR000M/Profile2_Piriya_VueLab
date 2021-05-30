<template>
  <ul v-for="contact in contacts" :key="contact.id">
    <li>
      {{ contact.id }}
      {{ contact.Email }}
      {{ contact.Phone }}
      {{ contact.Home }}
    </li>
  </ul>
</template>

<script>
export default {
  data: () => ({
    contacts: [
      { id: "----------------------------" },
      { id: "Contact" },
      { id: "Email :", Email: "piriya.yo@ku.th" },
      { id: "Phone :", Phone: "0659284021" },
      { id: "Home :", Home: "กรุงเทพ เขตดินแดง แขวนดินแดง" },
    ],
  }),
};
</script>