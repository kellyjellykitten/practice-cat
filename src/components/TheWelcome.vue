<script setup>
import WelcomeItem from './WelcomeItem.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Doug</template>
    <template #photo>
      <img src="../assets/doug.png">
    </template>
    Doug is extroverted and intelligent. Doug talks quite a bit but he has a mild, though goofy, demeanor.
    Doug never bites or scratches, even when he is irritated. He's generally pretty happy.
    <br><br>
    Likes: belly rubs, treats, watching people use the bathroom
    <br>
    Dislikes: being held, tall people, vacuums
    <br><br>
    <i>For those with a whimsical nature.</i>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Margaret</template>
    <template #photo>
      <img src="../assets/margaret.png">
    </template>
    Margaret is a sweet cat. She does not scratch furniture and gets along with dogs.
    If anyone is sick, Margeret will sit with them, purr, and groom them to make them feel better.
    <br><br>
    Likes: ear scritches, grooming dogs, sleeping on laps
    <br>
    Dislikes: threats to her humans, thunder, getting wet
    <br><br>
    <i>For those with a caring nature.</i>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Billy</template>
    <template #photo>
      <img src="../assets/billy.png">
    </template>
    Billy is wild, reckless, and petty.
    Bold and determined, Billy requires constant attention and play. He does not apologize for his anger and is unafraid of conflict.
    <br><br>
    Likes: chewing plastic chip bags, catching mice, showing disdain
    <br>
    Dislikes: humans ignoring him, regular cat food, cat carriers
    <br><br>
    <i>For those with an adventurous nature.</i>
  </WelcomeItem>
</template>
