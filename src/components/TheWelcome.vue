<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
// import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Profile</template>

    <p>Saya lahir di Depok, saya saat ini bersekolah
di SMK TARUNA BHAKTI Depok. Sebelumnya
saya berpengalaman dalam membuat dan
mendesain beberapa aplikasi web. Saya
mampu bekerja secara tim ataupun secara
individual.</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

   <h3 id="2020">2020 - 2023</h3>
    <h5><a target="_blank" href="https://smktarunabhakti.net/">SMK TARUNA BHAKTI</a></h5>

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>
    <ul>
      <li>Wedding Invitation Design</li>
      <li>Showroom Car Design</li>
      <li>Hotel Booking Design</li>
    </ul>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    <p>0857-7196-7251</p>
    <p>wsnuep@gmail.com</p>
    <a target="_blank" href="https://github.com/wisnuep">https://github.com/wisnuep</a>


  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a target="_blank" href="https://vuejs.org/sponsor/">becoming a sponsor</a>.
  </WelcomeItem> -->
</template>


<style>
  p{
    font-weight: 500;
  }

  li{
    font-weight: 500;
  }

  h3{
    font-weight: 500;
  }

</style>