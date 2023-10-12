<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    Mystics's
    <a href="https://mystics.vercel.app" target="_blank" rel="noopener">official website</a>
    provides you with all information you need to get started. (in development)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>MMAR</template>

    This project is created by
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>.
    Initially, the project website was named Malware Analysis and Archive. (Link will update soon)
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tetris</template>
    Our first project in Python. Made by
    <a href="https://github.com/minhtriet349" target="_blank" rel="noopener">Minhtriet349</a> and
    <a href="https://github.com/perasols" target="_blank" rel="noopener">Perasols</a>. Click
    <a href="https://github.com/MysticsGroup/tetris">here</a> for more details.
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>
    New samples or ideas? Put your answer on our official Discord server. We
    will answer it as should as possible.
  </WelcomeItem>
</template>
