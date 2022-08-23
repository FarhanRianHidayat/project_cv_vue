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
    <template #heading>Personal Profile</template>
    <p>I'm a software engineering student. I beginner web developer with basic web skills, Always want to learn and improve</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Education</template>
    
    <p>
      2020-2023
    </p>
    <a href="https://smktarunabhakti.net/" target="_blank">SMK Taruna Bhakti</a>
    <p>
      Web Developer
    </p>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>

    <ul>
      <li>Make Hotel Booking Design</li>
      <li>Make Food Delivery Design</li>
      <li>Make Sarpras</li>
      <li>Make E-commerce Design</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Language</template>
    <ul>
      <li>Indonesia</li>
      <li>Bahasa</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>
    <ul>
      <li>
      (+62) 813-8127-2831
      </li>
      <li>
      farhanrian321@gmail.com
      </li>
      <li>
        <a target="_blank" href="https://github.com/FarhanRianHidayat">github.com/FarhanRianHidayat</a>
      </li>
      <li>
        Jl. Kamboja 5 No:35 RT:03 RW:04 Depok 2 Tengah, 16411
      </li>
    </ul>
  </WelcomeItem>
</template>
