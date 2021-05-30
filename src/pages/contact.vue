<template>
  <div class="container text-center">
    <h1>My Contact</h1>
  </div>
  <p style="color: #566573">E-Mail : {{ Email }}</p>
  <p style="color: #566573">Facebook : {{ facebook }}</p>
  <p style="color: #566573">Address : {{ Address }}</p>
  <p style="color: #566573">Phone : {{ Phone }}</p>

  <router-link :to="{ name: 'profile' }">Back to Profile</router-link>
</template>

<script>
export default {
  data: () => ({
    Email: "ke.ninrat_st@tni.ac.th",
    facebook: "NamZom N. Kettrakul",
    Address: "Bangkok",
    Phone: "080-066-1056",
    //DateofBirth: "",
    //Skill: "",
    //Softskill: "",
  }),
};
</script>

<style>
body {
  background-color: rgb(252, 243, 207);
}
</style>