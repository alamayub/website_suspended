<template>
  <v-app>
    <v-main>
      <div class="suspended">
        <div class="content pa-6 pa-sm-8 pa-md-10 pa-lg-12">
          <img :src="require('./assets/warning.png')" alt="website suspended">
          <div class="text-h3">Website Suspended</div>
          <div class="text-h6">Your website has beeen suspended, Please contact your service provider.</div>
        </div>
      </div> 
    </v-main>
  </v-app>
</template>

<style lang="scss">
.suspended {
  background-image: url('./assets/3747371.jpg');  
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center center;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 12px;
  .content {
    max-width: 500px;
    display: flex; 
    flex-direction: column;
    align-items: center;
    gap: 12px;
    text-align: center;
    justify-content: center; 
    background: rgba(255, 255, 255, .2);
    border-radius: 6px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(5.9px);
    -webkit-backdrop-filter: blur(5.9px);
    img { height: 100px; }
  }
}
</style>