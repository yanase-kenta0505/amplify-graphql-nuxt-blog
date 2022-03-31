<template>
  <amplify-authenticator>
    <CreateBlog />
    <amplify-sign-out></amplify-sign-out>
  </amplify-authenticator>
</template>

<script>
// import Vue from 'vue';
import CreateBlog from '../../components/writeBlog/create';
// Vue.config.ignoredElements = [/amplify-\w*/];


export default {
  name: 'Create',
  components: {
    CreateBlog,
  },
}
</script>

