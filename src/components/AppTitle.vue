<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppTitle",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <h1 class="green">La mia prima app con <span class="yellow">Vite!</span></h1>
</template>

<!-- Lo stile da applicare in QUESTO componente è il seguente -->
<!-- In style.css abbiamo invece lo stile generico -->
<style scoped>
h1>span.yellow {
    color: yellow;
    text-decoration: underline;
}
</style>