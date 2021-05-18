<template>
  <div class="card pizza">
    <h1>build a form entry for a pizza</h1>
    <h3>rating topics</h3>
    <li>how good</li>
    <li>toppings</li>
    <li>suace</li>
    <li>crust</li>
    <li>cheese</li>
    <li>spicy</li>
    <h4>
      enter picture of the pizza
    </h4>
  </div>
  <div>
    <form class="form card">
      <div>
        <label for="pizza">Pizza Name</label>
        <input type="text">
      </div>
      <div>
        <label for="toppings">Toppings</label>
        <input type="text">
      </div>
      <div>
        <label for="sauce">Sauce</label>
        <input type="text">
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: 'Pizza',
  setup() {
    return {}
  },
  components: {}
}
</script>

<style lang="scss" scoped>
// .pizza{
// height: 100;
// width: 200em;
// }
</style>
