<template>
  <div class="about">
    <h1>Hello, {{ user_name }}! This is an about page</h1>
    <p>
      Offices parties lasting outward nothing age few resolve. Impression to
      discretion understood to we interested he excellence. Him remarkably use
      projection collecting. Going about eat forty world has round miles.
      Attention affection at my preferred offending shameless me if agreeable.
      Life lain held calm and true neat she. Much feet each so went no from.
      Truth began maids linen an mr to after.
    </p>
  </div>
</template>

<script>
export default {
  name: "Skills",
  data() {
    return {
      user_name: this.$route.params.name
    }
  }
}
</script>
