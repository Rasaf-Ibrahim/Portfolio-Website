<template>

<!--  🌙 ☀️ The above codes are related to Dark & Light Mode -->
<div :class="{dark:toggle} ">

  <div class="bg-s-t1a1 text-l1-a1 font-mono bg-cover  bg-fixed bg-center " style="background-image:url('https://raw.githubusercontent.com/Rasaf-Ibrahim/Portfolio-Website/Aditto/assets/image/background.jpg')">

<!-- End: 🌙 ☀️  -->



<!-- ⤵️ ⤵️ The following codes are related to Footer (To keep the footer at the bottom) -->


<div class="flex flex-col min-h-screen "> <!-- Wraper (Everything but dark,light mode <div> ) --->
  
    <div> <!-- Wraper (Everything but footer & dark,light mode <div>)  -->

    
<!-- End: ⤴️ ⤴️   -->






      

       


        <div >

            <ThemeSwitcher   @switch='themeSwitch()'/>

        </div>

   




    <Nuxt/>
     
 



     

<!-- ⤵️ ⤵️  The following codes are related to footer -->

    </div> <!-- End: Wraper (Everything but footer & dark,light mode) -->

    <!-- Footer -->
    <footer class="mt-auto">

      <Footer />

    </footer>

  </div> <!-- End: Wraper (Everything but dark,light mode) -->
 
<!-- End: ⤴️ ⤴️ -->



<!--  🌙 ☀️ The following codes are related to Dark & Light Mode -->
  </div>

</div> 

<!-- End: 🌙 ☀️  -->


</template>


<script>


import ThemeSwitcher from '../components/ThemeSwitcher.vue'
import Footer from '../components/Footer.vue'


  export default {
  components: {ThemeSwitcher, Footer },
  

 head: {
    title: 'Aditto Nahian',
    meta: [
      {
        hid: 'Aditto Nahian',
        name: 'Aditto Nahian',
        content: 'Hi, my name is Aditto Nahian. I am a singer. I live in Joypurhat, Bangladesh.'
      }
    ],
  },



 data() {
    return {
      toggle:true

    
    }
  },


  methods: {
      themeSwitch() {
          this.toggle = !this.toggle
        
      }
  }



  

  }




</script>


