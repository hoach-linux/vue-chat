<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Music</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-list>
        <ion-item>
          <ion-thumbnail slot="start">
            <img src="@/img/dawn-fm-the-weeknd.png" />
          </ion-thumbnail>
          <ion-label>
            <h2>Dawn FM</h2>
            <p>The Weeknd</p>
          </ion-label>
        </ion-item>
        <ion-item>
          <ion-thumbnail slot="start">
            <img src="@/img/future-nostalgia-dua-lipa.png" />
          </ion-thumbnail>
          <ion-label>
            <h2>Future Nostalgia</h2>
            <p>Dua Lipa</p>
          </ion-label>
        </ion-item>
        <ion-item>
          <ion-thumbnail slot="start">
            <img src="@/img/montero-lil-nas-x.png" />
          </ion-thumbnail>
          <ion-label>
            <h2>MONTERO</h2>
            <p>Lil Nas X</p>
          </ion-label>
        </ion-item>
        <ion-item>
          <ion-thumbnail slot="start">
            <img src="@/img/planet-her-doja-cat.png" />
          </ion-thumbnail>
          <ion-label>
            <h2>Planet Her</h2>
            <p>Doja Cat</p>
          </ion-label>
        </ion-item>
        <ion-item>
          <ion-thumbnail slot="start">
            <img src="@/img/sour-olivia-rodrigo.png" />
          </ion-thumbnail>
          <ion-label>
            <h2>SOUR</h2>
            <p>Olivia Rodrigo</p>
          </ion-label>
        </ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
} from "@ionic/vue";

export default defineComponent({
  name: "Tab2Page",
  components: {
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonPage,
  },
});
</script>
