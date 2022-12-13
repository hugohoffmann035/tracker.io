<template>
    <header class="has-background-primary">
        <div class="is-flex is-flex-direction-column is-align-items-center pt-6">
            <h1 class="has-text-white">Tracker.IO</h1>
            <p class="has-text-white">Ferramenta para controle de produtividade</p>
        </div>
    </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'BarraLateral'
})

</script>

<style scoped>
h1 {
    font-size: 50px;
    font-weight: 500;
}

header {
    width: 100%;
    height: 100vh;
}

@media only screen and (max-width: 768px) {
    header {
        padding: 2.5rem;
        height: auto;
    }
}
</style>