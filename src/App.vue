
<script>
//Importiamo i componenti da usare
import AppTitle from './components/AppTitle.vue'
import AppContent from './components/AppContent.vue'

//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
  components: {
    AppTitle,
    AppContent
  }
}
</script>

<!-- Qui inseriamo l'HTML della nostra App -->
<template>
  <header>
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <AppTitle />
  </header>

  <main>
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <AppContent />
  </main>
</template>

<!-- Qui abbiamo eventuale stile del componente "App", che è il contenitore generale -->
<style></style>
