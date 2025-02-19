<script setup>

import { faker } from '@faker-js/faker'
const firstname = faker.person.firstName()
const lastname = faker.person.lastName()


</script>

<template>
{{ fistname }} {{ lastname }} <br/>

</template>