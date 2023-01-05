<template>
  <h1>User Info</h1>
  <ul>
    <li>Username: {{user.username }}</li>
    <li>Password: ******</li>
    <li>Email: {{ user.email }}</li>
    <li>Phone: {{ user.phone }}</li>
  </ul>
</template>

<script lang="ts" setup>
import User from 'tr-test-app';

const user: User = {
  username: "admin",
  password: "@dm1n",
  email: "admin@email.com",
  phone: 10980801
};
</script>
