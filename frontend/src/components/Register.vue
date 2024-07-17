<script setup lang="ts"></script>

<template>
  <div class="container mx-auto">
    <div class="flex justify-center items-center text-center h-screen w-screen">
      <!-- Register -->
      <div class="flex justify-center items-center w-1/4 h-1/2 bg-yellow-500">
        <div class="">
          <h1 class="text-2xl">Hello</h1>
          <p>Have Account ? Let's Log In</p>
        </div>
      </div>
      <!-- Login -->
      <div class="flex justify-center items-center w-1/4 h-1/2 bg-red-500">
        <div class="">
          <h1 class="text-2xl">Register Form</h1>
          <div class="my-5">
            <label for="" class="block">Username</label>
            <input type="text" class="border w-full" />
          </div>
          <div class="my-5">
            <label for="" class="block">E-email</label>
            <input type="text" class="border w-full" />
          </div>
          <div class="my-5">
            <label for="" class="block">Password</label>
            <input type="text" class="border w-full" />
          </div>
          <div class="flex justify-between items-center">
            <p>Remember Me</p>
            <button>Submit</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
