<template>
  <div class="about">
    <h1>Hello {{their_name}},This is an about page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus animi nisi explicabo vitae necessitatibus architecto, fugit, quos fuga ducimus sint iure numquam et sunt atque cupiditate deleniti sed hic aut.</p>
  </div>
</template>
<script>
export default {
  name: "Skills",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>
