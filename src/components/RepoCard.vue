<template>
  <div class="repo"> {{ repoName }}</div>
</template>

<script>
// import { Components, Prop, Vue } from "vue-property-decorator";

@Component
export default {
    name: 'RepoCard',

    props: {
        repoName: string,
        repoUrl: string,
        repoStartCount: number,
        repoDescription: string,
    }
}
</script>

<style>

</style>