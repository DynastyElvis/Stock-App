<template>
   <Navbar>
      <template v-slot:title-page>
         <h1 class="nav-title">Update</h1>
      </template>
   </Navbar>
   
   <FormProduct>
      <template v-slot:caption-form>
         <h1 class="show-slide  text-xl w-full text-prussian-blue">
            You can update information 
            <br />
            about your item here 👏
         </h1>
      </template>
   </FormProduct>
</template>

<script setup>
   
   import Navbar from '../components/Navbar.vue'
   import FormProduct from '../components/FormProduct.vue'
   
</script>