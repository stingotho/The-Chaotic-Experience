<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who is Chaos?</template>

    A
    <a class="text-orange-600" target="_blank" href="">potato</a>
    human being who loves eating food. Tries different cuisines and loves to
    blend and mix flavors.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-6 w-6"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        stroke-width="2"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
        />
      </svg>
    </template>
    <template #heading>Why Chaos?</template>

    One day woke up and just decided to be chaotic. After the countless hours of
    contemplation and meditation,
    <a class="text-orange-600" target="_blank" href="">The Legendary Chaos</a> ,
    was born.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <img src="https://img.icons8.com/small/16/FFFFFF/kawaii-sushi.png" />
    </template>
    <template #heading
      >What was the most chaotic dish or drink created?</template
    >

    Forget the chocolate with beef or steak or a dessert made out of chicken
    meat and let's not forget we already have pineapples on pizzas. So I had to
    innovate and take it to next level what could possibly beat any of these
    infamous cuisines with the most creative flavor mixture for your pallete
    tasting buds? Definitely the most chaotic one would be watermelon with
    shrimp. I mean people alraedy have shrimps with pineapple so why not with
    watermelon?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>How to contact me?</template>

    Got curious and wonder about
    <span class="text-orange-600">the chaotic experience? </span>
    You can contact me directly on Instagram,
    <a
      class="text-orange-600"
      target="_blank"
      href="https://instagram.com/chaoshel?igshid=YmMyMTA2M2Y="
      >here</a
    >. You can also join my discord server,
    <a class="text-orange-600" target="_blank" href="">The Chaotic Experience</a
    >. You can consider following me on other platforms aswell such as my
    <a class="text-orange-600" target="_blank" href="">Youtube</a> channel and
    follow the official
    <a class="text-orange-600" target="_blank" href="">Chaos</a>
    twitter account to be upto date with me.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Me</template>

    We are very ambitious and have so much to do and offer. The chaotic experience is not only about mixing weird food and drinks combinations we actually care about the pallete and inventing new dishes.
    We also care about people that need help and cannot afford proper healthy food. In order for us to continue consider
    <a class="text-orange-600" target="_blank" href="">becoming a sponsor</a>.
  </WelcomeItem>
</template>
