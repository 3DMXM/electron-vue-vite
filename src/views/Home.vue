<script lang='ts' setup>
import HelloWorld from '@src/components/HelloWorld.vue'

</script>
<template>
    <div class="flex-center">
        <a href="https://www.electronjs.org/" target="_blank">
            <img src="@src/assets/electron.svg" class="logo electron" alt="Electron logo" />
        </a>
        <a href="https://vitejs.dev/" target="_blank">
            <img src="/vite.svg" class="logo" alt="Vite logo" />
        </a>
        <a href="https://vuejs.org/" target="_blank">
            <img src="@src/assets/vue.svg" class="logo vue" alt="Vue logo" />
        </a>
    </div>
    <HelloWorld msg="Electron + Vite + Vue" />
</template>
<script lang='ts'>

export default {
    name: 'Home',
}
</script>
<style lang='less' scoped>
.flex-center {
    display: flex;
    align-items: center;
    justify-content: center;
}

.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;

    &:hover {
        filter: drop-shadow(0 0 2em #646cffaa);
    }

    &.electron:hover {
        filter: drop-shadow(0 0 2em #9FEAF9);
    }

    &.vue:hover {
        filter: drop-shadow(0 0 2em #42b883aa);
    }
}
</style>