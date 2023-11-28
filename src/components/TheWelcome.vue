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
    <template #heading>Java Script</template>

    Web applications, APIs, and all kind of softwares. This is my expeciality
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>C#</template>

    Windows applications using WPF that have microsoft`s long term support. <br/>
    Web Applications using the .net core framework <br/>
    APIs using .net core framework <br/>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Python</template>

    Web Applications using Flask. <br/>
    AI training using TensorFlow and Pandas for data manipulation.<br/>
    All kinds of integrations. <br/>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>PHP</template>

    long term support for old applications that is still rentable.<br/>
    Web Services using Laravel.<br/>
  </WelcomeItem>

</template>
