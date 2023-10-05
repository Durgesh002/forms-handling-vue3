<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <p class="h3 text-success">App Component</p>
        <p class="fw-italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ipsa eligendi natus pariatur eaque sit ullam, error earum cupiditate maiores, nihil distinctio veritatis blanditiis! Aperiam quam quisquam reprehenderit corporis accusantium.</p>
      </div>
    </div>

    <Register/>

  </div>
</template>


<script>
import Register from './components/Register.vue';

export default{
  name: 'App',
  components: {
    Register,
  },
  data: function(){
    return{

    }
  }
}
</script>


<style></style>