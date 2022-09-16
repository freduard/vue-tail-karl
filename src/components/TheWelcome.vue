<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="flex flex-col items-center h-screen justify-center">
      <WelcomeItem class="w-1/2">
      <template #icon>
        <DocumentationIcon />
      </template>
      <template #heading>Git init</template>

      Git init is one way to start a new project with Git. To start a repository, use either <code>git init</code> or <code>git clone</code> - not both.
    </WelcomeItem>

    <WelcomeItem class="w-1/2">
      <template #icon>
        <ToolingIcon />
      </template>
      <template #heading>Git add</template>

      The <code>git add</code> command adds new or changed files in your working directory to the Git staging area.
    </WelcomeItem>

    <WelcomeItem class="w-1/2">
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Git status</template>

      <code>git status</code> shows the current state of your Git working directory and staging area.
    </WelcomeItem>

    <WelcomeItem class="w-1/2">
      <template #icon>
        <CommunityIcon />
      </template>
      <template #heading>Git commit -m</template>

      <code>git commit</code> creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times. You should make new commits often, based around logical units of change.
    </WelcomeItem>

    <WelcomeItem class="w-1/2">
      <template #icon>
        <SupportIcon />
      </template>
      <template #heading>Git push</template>

      <code>git push</code> updates the remote branch with local commits. It is one of the four commands in Git that prompts interaction with the remote repository. You can also think of <code>git push</code> as update or publish.
    </WelcomeItem>

    <WelcomeItem class="w-1/2">
      <template #icon>
        <SupportIcon />
      </template>
      <template #heading>Git remote</template>

      <code>git remote</code> manages the set of remotes that you are tracking with your local repository.
    </WelcomeItem>
  </div>

</template>
