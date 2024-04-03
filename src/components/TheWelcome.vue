<script setup lang="ts">
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
    <template #heading>Tentang saya</template>
 Nama saya Rifqi
 Saya berkuliah di universitas islam riau
 Saya lahir di pekanbaru
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi saya</template>
<ul>
<li> Bermain sepak bola</li>
<li>Bermain badminton</li>
<li>Mengoding</li>
</ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Cita-cita</template>
    <ul>
<li>menjadi pilot waktu sd</li>
<li>menjadi tni waktu smp</li>
<li>menjadi rektor</li>
</ul>
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>pendidikan</template>
    <ul>
<li>SDN 001 pekanbaru </li>
<li>SPMN 006 pekanbaru</li>
<li>SMKN 07 pekanbaru</li>
</ul>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Media sosial</template>
instagram: rifqifxkhrusy
  </WelcomeItem>
</template>
