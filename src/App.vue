<template>
  <Flagment>
    <Header></Header>
    <Tab></Tab>
    <router-view></router-view>
  </Flagment>
</template>

<script>
import Header from '@/components/header/Header'
import Tab from '@/components/tab/Tab'

export default {
  components: {
    Header,
    Tab
  }
}
</script>
