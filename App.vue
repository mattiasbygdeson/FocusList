<template>
  <view class="container">
    <Header title="Header" />
    <MainFocusList />
    <MediumFocusList />
    <SmallFocusList />
  </view>
</template>

<script>
import Header from "./components/Header";
import MainFocusList from "./components/MainFocusList";
import MediumFocusList from "./components/MediumFocusList";
import SmallFocusList from "./components/SmallFocusList";

export default {
  components: {
    Header,
    MainFocusList,
    MediumFocusList,
    SmallFocusList
  }
}
</script>

<style>
.container {

}
</style>
