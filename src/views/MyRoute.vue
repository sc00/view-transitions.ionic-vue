<template>
  <IonPage>
    <IonHeader class="ion-no-border">
      <IonToolbar>
        <IonButtons slot="start">
          <IonBackButton />
        </IonButtons>
      </IonToolbar>
      <h1>My Route Heading</h1>
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
        >Another Item #1</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #2</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #3</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #4</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #5</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #6</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #7</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #8</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #9</IonItem
      >
      <IonItem
        button
        router-link="/my-route"
        router-direction="forward"
        lines="full"
        >Another Item #10</IonItem
      >
    </IonContent>
  </IonPage>
</template>

<script setup lang="ts">
import {
  IonButton,
  IonContent,
  IonBackButton,
  IonButtons,
  IonHeader,
  IonItem,
  IonPage,
  IonToolbar,
} from "@ionic/vue";
</script>
