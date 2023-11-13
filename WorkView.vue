<template>
  <div class="work">
    <h1>송기영의 Vue 실습 페이지</h1>
  </div>
  <hr />
  <TeamComponent name="송기영" food="마라탕" teamNum="1" srcUrl="../../public/images/image2.png"></TeamComponent>
  <TeamComponent name="유승희" food="아이스크림" teamNum="1" srcUrl="../../public/images/image4.png"></TeamComponent>+
  <TeamComponent name="이성수" food="순대국밥" teamNum="1" srcUrl="../../public/images/image3.png"></TeamComponent>
  <TeamComponent name="전승현" food="햄버거" teamNum="1" srcUrl="../../public/images/image1.png"></TeamComponent>
</template>

<script setup>
// @ is an alias to /src
import TeamComponent from '@/components/TeamCard.vue'
</script>

