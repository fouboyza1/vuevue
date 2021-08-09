<template>
<div>
<b-navbar type="dark" variant="dark">
  <b-navbar variant="faded" type="light">
    <b-navbar-brand href="#">
      <img src="https://placekitten.com/g/30/30" alt="Kitten">
    </b-navbar-brand>
  </b-navbar>

  <b-navbar-nav class="ml-auto">
<b-navbar-nav style="margin-right: 40px;">
<router-link class="nav-item nav-link" to="/">Home</router-link>
<router-link class="nav-item nav-link" to="/product">Product</router-link>
<router-link class="nav-item nav-link" to="/about">About</router-link>
</b-navbar-nav>
    
      <div>
           <b-button pill>เข้าสู่ระบบ</b-button>
           <b-button pill>ลงทะเบียน</b-button>
</div>
      </b-navbar-nav>
</b-navbar>
  </div>
</template>
<script>

export default {
  name: 'Navbar',
}

</script>

<style>


</style>