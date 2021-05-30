<template>
  <ul v-for="profile in profiles" :key="profile.id">
    <li>
      <button>
        {{ profile.id }}
        {{ profile.Fname }}S
        {{ profile.Lname }}
        {{ profile.Day }}
        {{ profile.Old }}
        {{ profile.Title }}
      </button>
    </li>
  </ul>
</template>

<script>
export default {
  data: () => ({
    profiles: [
      { id: "Profile" },
      { id: "ชื่อ", Fname: "พิรยะ" },
      { id: "นามสกุล", Lname: "ยอดแก้ว" },
      { id: "วันเกิด", Day: "2/05/2000" },
      { id: "อายุ", Old: "21" },
      { id: "ทักษะ" },
      { Title: "C#,C++,Java,SQL,HTML" },
    ],
  }),
};
</script>