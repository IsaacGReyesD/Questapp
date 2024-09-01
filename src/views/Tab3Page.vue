<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Look for</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 3</ion-title>
        </ion-toolbar>
      </ion-header>

      <ion-button expand="block" fill="outline" class="buttom_create">Create a room</ion-button>
      <ion-button expand="block" fill="outline" class="buttom_join">Join a room</ion-button>
      
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton } from '@ionic/vue';

</script>
