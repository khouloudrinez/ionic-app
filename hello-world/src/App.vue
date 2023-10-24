<template>
  <IonApp>
      <IonRouterOutlet />
  </IonApp>
</template>

<script>
import { defineComponent } from 'vue'
import { IonApp, IonRouterOutlet } from '@ionic/vue'

export default defineComponent({
  name: 'App',
  components: {
      IonApp,
      IonRouterOutlet,
  },
})
</script>


