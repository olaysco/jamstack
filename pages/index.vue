<template>
  <div class="container">
    <div class="header">
      <span>Welcome to my page</span>
    </div>
    <div class="body">

      <form action="post" data-netlify="true">
        <input type="text" name="name" id="" />
        <input type="text" name="message" id="" />
        <button>Submit</button>
      </form>
    </div>
    <div class="footer"></div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.header{
  display: flex;
  height: 100px;
  width: 100vw;
  justify-content: space-between;
  align-content: center;
  background-color: #526488;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;

}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
