<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>ข่าวสาร</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">ข่าวสาร</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ExploreContainer name="ข่าวสาร" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '../components/ExploreContainer.vue';

export default  {
  name: 'News',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>