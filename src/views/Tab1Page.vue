<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Quest</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Quest</ion-title>
        </ion-toolbar>
      </ion-header>
      
    
    <ion-fab slot="fixed" vertical="bottom" horizontal="end">
     <ion-fab-button id="open-modal" expand="block">
      <ion-icon aria-hidden="true" :icon="add" />
      </ion-fab-button>
    </ion-fab>

    <ion-modal trigger="open-modal" :initial-breakpoint="1" :breakpoints="[0, 1]">
      <ion-input class="block" label="Default label" placeholder="Enter your question"></ion-input>
    </ion-modal>

    <ion-card>
  <ion-card-header>
    <ion-card-title>Tittle Expo</ion-card-title>
  </ion-card-header>

  <ion-card-content>
   ¿Quest?
  </ion-card-content>

  <ion-button fill="clear">
    <ion-icon arial-hidde="true" :icon="happy"></ion-icon>
  </ion-button>
  <ion-button fill="clear">
  <ion-icon arial-hidde="true" :icon="sad"></ion-icon>
  </ion-button>
</ion-card>

    </ion-content>
  </ion-page>
</template>



<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonIcon, IonFabButton, IonFab, IonCardTitle, IonCardHeader, IonCardContent, IonButton, IonCard, IonModal, IonInput} from '@ionic/vue';
import { add, happy, sad } from 'ionicons/icons';


</script>
