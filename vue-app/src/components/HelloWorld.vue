<template>
  <h1>User Info</h1>
  <ul>
    <li>Username: {{ user.username }}</li>
    <li>Password: ******</li>
    <li>Email: {{ user.email }}</li>
    <li>Phone: {{ user.phone }}</li>
  </ul>
</template>

<script lang="ts" setup>
import UserModel from 'tr-test-app';
import User from 'tr-test-app/user';

const user: UserModel = {
  username: "admin",
  password: "@dm1n",
  email: "admin@email.com",
  phone: 10980801
};

const user2: User = {
  name: 'Kok dara'
}
console.log(user2)
</script>
