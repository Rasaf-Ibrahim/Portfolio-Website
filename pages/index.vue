<template>
  <div >


<div  class="-fade-in-up mb-[3rem] md:mb-[2rem] lg-[5rem] " >

   <profileCard/>

</div>

  
  <div  class="-fade-in-right mb-[3rem] md:mb-[2rem] lg-[5rem]">

       <hireMe/>

  </div>


  </div>
</template>

<script>

import profileCard from '../components/profileCard.vue'
import hireMe from '../components/hireMe.vue'



  export default {
    
   components: {profileCard, hireMe },


    head: {
    title: 'Aditto Nahian',
    meta: [
      {
        hid: 'Aditto Nahian',
        name: 'Aditto Nahian',
        content: 'Hi, my name is Aditto Nahian. I am a singer. I live in Joypurhat, Bangladesh.'
      }
    ],
  }



}


  

</script>






