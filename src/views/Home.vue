<template>
  <ion-page>
   <ion-content>
    <ion-header :translucent="true">
     <ion-toolbar style="width:100%" >
       <div class="barra">
        <ion-title id="whatapp">WhatsApp    </ion-title>       
      <img src="./procurabranco.svg">
      <img src="./3branco.svg">
      


       </div>
      </ion-toolbar>
      <ion-toolbar style="width:100%">
       <div class="barra">
        <img src ="./camera.svg" class="imgcamera">
        <ion-title id="titulo1">CONVERSAS    </ion-title>       
      <ion-title id="titulo2">STATUS    </ion-title>
      <ion-title id="titulo3">CHAMADAS  </ion-title>
       </div>
      </ion-toolbar>

    </ion-header>
    
    <ion-content :fullscreen="true" >
      
     
    
      
      <div id="container">
      
       <ion-list>
       <ion-item>
     
      <ion-avatar  >
        <img src="./pedrao.png">
      </ion-avatar>
      <ion-label class="texto">Vendedor de lança</ion-label>
      <ion-badge color="success">11</ion-badge>
    </ion-item>
     <ion-item>
      <ion-avatar >
        <img src="./bot_flitzz.png">
      </ion-avatar>
      <ion-label class="texto">BOT Medio</ion-label>
      <ion-badge color="success">6</ion-badge>
    </ion-item>
    <ion-item>
      <ion-avatar >
        <img src="./peixopauta.png">
      </ion-avatar>
      <ion-label class="texto">Cara Estranho</ion-label>
      <ion-badge color="success">9</ion-badge>
    </ion-item>
    <ion-item>
      <ion-avatar >
        <img src="./vitao.png">
      </ion-avatar>
      <ion-label class="texto">Tio do pavê</ion-label>
      <ion-badge color="success">17</ion-badge>
    </ion-item>
     <ion-item>
      <ion-avatar >
        <img src="./thigas.png">
      </ion-avatar>
      <ion-label class="texto">Suspeito de Assassinato</ion-label>
      <ion-badge color="success">4</ion-badge>
    </ion-item>
    <ion-item>
      <ion-avatar >
        <img src="./toso.png">
      </ion-avatar>
      <ion-label class="texto">Amigo do Ryan</ion-label>
      <ion-badge color="success">2</ion-badge>
    </ion-item>
    <ion-item>
      <ion-avatar >
        <img src="data:image/jpeg;base64,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">
      </ion-avatar>
      <ion-label class="texto">Jafe Besus</ion-label>
      <ion-badge color="success">1</ion-badge>
    </ion-item>
    <ion-item>
      <ion-avatar >
        <img src="./cr7.png">
      </ion-avatar>
      <ion-label class="texto">Pai</ion-label>
      <ion-badge color="success">7</ion-badge>
    </ion-item>
     
     
      </ion-list>
      </div>
    
    </ion-content>
  </ion-content>
  </ion-page>

</template>

<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Home',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar
  }
});
</script>



<style scoped>

ion-content{
--background-color: #ffff;
}

.imgcamera{
width:25px ;
height:25px ;
margin:0px ;
 }
 
 .barra{
   display: flex;
 justify-content: center;
 align-items: center;
 gap: 7px;
 }

 .texto{
   margin-left:10px ;
 }

 #whatapp{
   font-size:20px;
color: #ffff;
}

 #titulo1 {
color: #ffff;
font-size:11px;
 transition: all 0.5s;


  /* left: -20%;
  right: 0%;
  top: 30%; */
  
}
 #titulo1:hover {
box-shadow:0px 2px 0px #2be422;
 }
 #titulo2:hover {
box-shadow:0px 2px 0px #2be422;
 }
 #titulo3:hover {
box-shadow:0px 2px 0px #2be422;
 }
 
 #titulo2 {
color: #ffff;
font-size:11px;


  /* left: 10%;
  right: 0%;
  top: 30%; */
  
}

 #titulo3 {
color: #ffff;
font-size:11px;

  /* left: 35%;
  right: 0%;
  top: 30%;
   */
}

#container ion-item {
margin-top:10px;
}

#container {
  
  
  position: relative;
  left: 0%;
  right: 0%;
  top: 0%;
  
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #ffff;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>