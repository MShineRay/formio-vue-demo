<script setup>
import { ref } from 'vue'
import { Form, FormBuilder } from '@formio/vue';
</script>

<template>
  <h1>Hello World</h1>
  <Form src="" url="" form="" submission="" options="" v-on:submit=""></Form>
  <FormBuilder v-bind:form="{display: 'form'}" v-bind:options="{}" v-on:change="(schema) => console.log(schema)"></FormBuilder>
</template>

<style scoped>
</style>
