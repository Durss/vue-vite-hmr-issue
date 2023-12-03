<template>
	<div class="app">Hello world!</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-facing-decorator';

@Component
export default class App extends Vue {

}
</script>

<style scoped>
.app{
}
</style>

<!-- HMR Works with the following component declaration instead of the above
<template>
	<div>Hello World</div>
</template>
<script setup lang="ts">
</script>
<style scoped></style>
 -->