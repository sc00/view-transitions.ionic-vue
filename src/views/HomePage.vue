<template>
  <IonPage>
    <IonHeader class="ion-no-border">
      <IonToolbar>
        <IonTitle>Blank</IonTitle>
      </IonToolbar>
      <h1>My Index Heading</h1>
      <div class="list-header">
        <h2>My List Header</h2>
        <IonButton>+</IonButton>
      </div>
    </IonHeader>

    <IonContent>
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Item #1</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Item #2</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Item #3</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Item #4</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Item #5</IonItem
      >
    </IonContent>
  </IonPage>
</template>

<script setup lang="ts">
import {
  IonButton,
  IonContent,
  IonHeader,
  IonItem,
  IonPage,
  IonTitle,
  IonToolbar,
} from "@ionic/vue";
</script>

<style>
ion-item {
  --background: transparent;
  --border-color: hsla(310, 20%, 80%, 0.15);
}
.list-header {
  display: flex;
  justify-content: space-between;
  padding-inline-start: var(--padding-start);
  padding-inline-end: var(--padding-end);
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: hsla(325, 27%, 20%, 0.5);
}
</style>
