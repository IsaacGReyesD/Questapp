<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Moderation</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Moderation</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-card>
  <ion-card-header>
    <ion-card-title>Tittle Expo</ion-card-title>
  </ion-card-header>

  <ion-card-content>
   ¿Quest?
  </ion-card-content>

  <ion-button fill="clear">
    <ion-icon arial-hidde="true" :icon="checkmark"></ion-icon>
  </ion-button>
  <ion-button fill="clear">
    <ion-icon arial-hidde="true" :icon="alert"></ion-icon>
  </ion-button>
</ion-card>
      
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonCardTitle, IonButton, IonCardContent, IonCardHeader, IonCard, IonIcon } from '@ionic/vue';
import { checkmark, alert } from 'ionicons/icons';

</script>
