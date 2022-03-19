<template>
  <div class="home">
    <div id="header">
      <router-link style="text-decoration: none;" :to="{name: 'Home'}">
        &nbsp;Logo(home)
      </router-link>

      <router-link style="text-decoration: none;" :to="{name: 'Home'}">
        &nbsp;Home&nbsp;
      </router-link>
      <router-link style="text-decoration: none;" :to="{name: 'MyPage'}">
        &nbsp;MyPage&nbsp;
      </router-link>
      <router-link style="text-decoration: none;" :to="{name: 'AccountsEditPage'}">
        &nbsp;AccountsEditPage&nbsp;
      </router-link>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {

  }
}
</script>
