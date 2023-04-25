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
    <template #heading>Education</template>
      <p>Licenciado en Ciencias de la Ingeniería</p> 
      <p>Titulado en Ingeniería de Ejecucion en computación e informática</p> 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Experience</template>
      <p>full stack Developer, Tenlove Spa, 2021-2022</p>
      <p>Software Developer, Talana linQ Spa, 2022 - present</p>
      <p>FullStack Developer, proyectos personales, 2016 - presente</p>
    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skills</template>
    <h3  class="miniTitle">Programming Languages:</h3>
    <p> Java, Python, JavaScript, C#, Dart, Kotlin, Swift</p>
    <h3 class="miniTitle">Web Development:</h3>
    <p> HTML, CSS, SCSS, Vue.js, JavaScript, TypeScript, Node.js</p>
    <h3 class="miniTitle">Database Management:</h3>
    <p> PostgreSQL, MongoDB, MySQL, GoogleCloud</p>
    <h3 class="miniTitle">Software Development Tools:</h3>
    <p> Git, Eclipse, Visual Studio, IntelliJ IDEA, Android Studio, Xcode</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Projects</template>

    Pueden revisar mis proyectos en 
    <a href="https://github.com/steffannunez/" target="_blank" rel="noopener">GitHub</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Habilidades</template>
    <p>Inglés Intermedio/Avanzado</p>
    <p></p>
  </WelcomeItem>
</template>
<style>
.miniTitle{
  color: rgb(238, 238, 238);
}
a{
  color: #008ab4;
}
a:hover{
  background: transparent;
  color: #0ec7ff;
   
}
</style>