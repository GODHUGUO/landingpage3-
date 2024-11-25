<template>
  <div>
  <div class="section1">

    <div class="leftsection1">
<p class="firsp" >Want anything to be  <br> easy with   <span>LaslesVPN</span></p>
<p  class="secp">Provide a network for all your needs with ease and fun using LaslesVPN <br>    discover interesting features from us.</p>


<div><button> Get Started</button></div>

    </div>

    <div class="right">
      <img src="@/public/images/Illustration1.png" alt="logo menu"> 
    </div>



  </div>

  <div class="section2">
<div class="section2part">
<div class="ic1">
  <img src="@/public/images/user.png" alt="logo user"> 
  <p><span>90+</span>  <br>Users</p>
</div>

<div class="ic1">
  <img src="@/public/images/location.png" alt="location logo"> 
  <p><span>30+</span> <br>Location</p>
</div>

<div class="ic1">
  <img src="@/public/images/Server.png" alt="Server logo"> 
  <p><span>50+</span>  <br>Server</p>
</div>

  </div>

</div>





<div class="section3">
<div class="section3part">
  <div class="section3left">
    <img src="@/public/images/illustration2.png" alt="logo user"> 
  </div>

<div class="section3right">

<h2>We Provide Many   <br> Features You can Use</h2>
<p>You can explore the features that we provide with fun and  <br>have their own functions each feature.</p>

<div class="ic2">
  <img src="@/public/images/check.png" alt="logo user"> <span>Powerfull online protection.</span>
</div>
<div class="ic2">
  <img src="@/public/images/check.png" alt="logo user"> <span>Internet without borders..</span>
</div>

<div class="ic2">
  <img src="@/public/images/check.png" alt="logo user"> <span>Supercharged VPN</span>
</div>

<div class="ic2">
  <img src="@/public/images/check.png" alt="logo user"> <span>No specific time limits.</span>
</div>

</div>




</div>

</div>











<div class="section4">
<div class="section4part">

<h2>Choose your plan</h2>
<p>Let's choose the package that is best for you and explore it happily and <br>cheerfully. </p>

<div class="pricesection">

<div class="sect1">

<div class="freplan">  <img src="@/public/images/Free.png" alt="logo user"> <p>Free Plan</p>

<div>
  <div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Unlimited Bandwitch</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Encrypted Connection</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>No Traffic Logs</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Works on All Devices</span>
</div>
<div class="ic2 surplus">
 <span>Connect Anyware</span>
</div>

<div class="ic2 surplus">
 <span>Connect Anyware</span>
</div>
</div>

</div>


<div class="footerplan">
  <p>Free</p>
  <button>Select </button>
</div>



</div>
<div class="sect1">

<div class="freplan">  <img src="@/public/images/Free.png" alt="logo user"> <p>Standart Plan</p>

<div>
  <div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Unlimited Bandwitch</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Encrypted Connection</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>No Traffic Logs</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Works on All Devices</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Connect Anyware</span>
</div>
<div class="ic2 surplus">
 <span>Connect Anyware</span>
</div>
</div>

</div>


<div class="footerplan">
  <p>$9<span>/mo</span> </p>
  <button>Select </button>
</div>



</div>

<div class="sect1">

<div class="freplan">  <img src="@/public/images/Free.png" alt="logo user"> <p>Premium Plan</p>

<div>
  <div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Unlimited Bandwitch</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Encrypted Connection</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>No Traffic Logs</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Works on All Devices</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Get new features</span>
</div>
<div class="ic2">
  <img src="@/public/images/Group.png" alt="logo user"> <span>Connect Anyware</span>
</div>
</div>

</div>


<div class="footerplan">
  <p>$12   <span>/mo</span> </p>
  <button>Select </button>
</div>



</div>








</div>

</div>



</div>


<div class="section5">
  <div class="section5part">
  <h2>Huge Global Network <br>  of Fast VPN</h2>
<p>See LaslesVPN everywhere to make it easier for you when you move  <br>locations. </p>


<div class="glimg">
  <img src="@/public/images/global.png" alt="logo user"> 
</div>
</div>
</div>



<div class="section6">
  <div class="section6part">

    <h2>Trusted by Thousands of  <br> Happy Customer</h2>
    <p>These are the stories of our customers who have joined us with great  <br> pleasure when using this crazy feature. </p>



  </div>

<div class="temoignages">

<!-- pour le v-for j'ai mis (testi,index)parce que je veux recuperer l'index
de chaque element de la boucle -->

  <div v-for="testi in testimonials" :key="testi.id" class="temoi">
  
<div   class="gapp">
  <div  class="temoigngesheader  ">
    <div class="headertemoi">
  <img :src="testi.image" alt="Image du témoignage" />
   <h3>{{testi.name}}   <br> <span>{{testi.titre}}  </span> </h3>
  </div>
 <div class="temoignagesnote">
  <p>{{testi.note}}</p>
  <img :src="testi.noteicone" alt="Image du témoignage" />
 </div>
</div>
<div>
  <p>{{testi.feedback}}</p>
</div>


</div>

</div>

</div>






</div>



<div class="section7">

<div class="section7part">

  <div class="section7left">
<h2>Subscribe Now for <br> Get Special Features!</h2>
<p>Let's subscribe with us and find the fun.</p>

  </div>

  <div class="section7right">

<button>Subscribe Now</button>

  </div>

</div>

</div>

<div class="section8">
  
</div>



  </div>
</template>

<script setup>
import { ref } from 'vue';
const testimonials = ref([
  {
    id:1,
    name: "Viezh Robert",
    titre:"Warsaw, Poland",
    feedback: "Wow... I am very happy to use this VPN, it turned out to be more than my expectations and so far there have been no problems. LaslesVPN always the best.",
    image: "/images/temoi1.png",
    note:"4.5",
    noteicone:"/images/iconestar.png"
  },
  { id:2,
    name: "Marc joe",
    titre:"Shanxi, China",
    feedback: "I like it because I like to travel far and still can connect with high speed",
    image: "/images/temoi2.png",
      note:"4.5",
   noteicone:"/images/iconestar.png"
  },
  {
    id:3,
    titre:"Seoul, South Korea",
    name: "Claire Lefebvre",
    feedback: "“This is very unusual for my business that currently requires a virtual private network that has high security.”.",
    image: "/images/temoi3.png",
      note:"4.5",
    noteicone:"/images/iconestar.png"
  },
  

]);


const currentIndex = ref(0);
  


function previousTestimonial() {
  currentIndex.value = currentIndex.value === 0 ? testimonials.length - 1 : currentIndex.value - 1;
}

// Fonction pour afficher le témoignage suivant avec une boucle infinie
function nextTestimonial() {
  currentIndex.value = currentIndex.value === testimonials.length - 1 ? 0 : currentIndex.value + 1;
}





</script>

<style lang="scss">
.section1{
  //  border: 1px solid red;
  width: min(100%,1200PX);
       margin: 0 auto;
  display: flex;
  align-items: center;
 
  justify-content: space-around;
  padding: 35PX 0;
  .right{

    img{
      width:400px;
    }
  }
  
  
  .leftsection1{
  

    display: flex;
    flex-direction:column;
    gap:25px;
    button{
      color: #ffffff;
      background-color: #F53838;
      border: none;
      padding: 10px  25px;
      box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3);
      border-radius: 9PX;
    }

    .firsp{
        color:#0B132A;
        font-size:40px;
        span{
          font-weight: bold;
        }
      }

     
  }
}
// --------------------section2-----------------


.section2{
display: flex;
justify-content: center;
width: min(100%,1200PX);
margin: 0 auto;
  .section2part{
    margin-top: 45PX;
    color:#0B132A;
    width: 80%;
    padding: 30PX 0;
  display: flex;
  justify-content: space-around;
  box-shadow: 10px 10px 40px rgba(0, 0, 0, 0.2);
  }

  .ic1{
    display: flex;
    gap: 7px;
    align-items: center;
    span{
      font-weight: bold;
    }
    img{
      height: 45px;
    }
  }

}

// ---------------------------section3----------
.section3{
  display: flex;
justify-content: center;
.section3part{
display: flex;
justify-content: center;
align-items: center;

width: 78%;
padding: 50px 0;
gap: 95px;
.section3left{
  
img{
  width:400px ;
}
}
  .section3right{
   
    h2{
      color: #0B132A;
    }
    p{
      color:#4F5665;
      margin: 12px 0;
    }

    .ic2{
      
      display: flex;
      align-items: center;
      margin-bottom:15px;
      img{
        height: 22px;
      }
    }
  }
}

}
// --------------section4----------------

.section4{
  


  .section4part{
    h2{
      margin-bottom: 15px;
    }
    P{
      margin-bottom: 15px;
    }
    text-align: center;
     width: min(100%,1200PX);
 margin: 0 auto;

 
 width:75% ;
    .pricesection{
      display: flex;
      justify-content: space-between;
      width: min(100%,1200PX);
      margin: 0 auto;
      
      .sect1{
    
      display: flex;
      flex-direction: column;
      // height: fit-content;
      border: 1px solid #DDDDDD;
      border-radius: 10px;
       padding: 25px;
       gap: 40px;
        .freplan{
      
          display: flex;
      flex-direction: column;
      align-items: center;

         P{
          font-weight: bold;
          
         } 
         gap: 15px;
        }
        .footerplan{
          
          P{
            text-align: center;
            font-weight: bold;
            margin-bottom: 10px;

          span{
            font-weight: lighter;
          }

          }
          button{
            border-radius: 15px;
            background-color: transparent;
            border:1px solid  #F53838;
            padding: 5px 25PX; 
          }
        }
        img{
          width:90px ;
        }
        
        .surplus{
          color: transparent;
        }
      .ic2{
        margin-bottom: 6px;
        display: flex;
        gap: 10px;
        align-content: center;
        img{
width:15px ;
        }
      
      }



      }
    }
  }
}
//-------------------section5-----------------------------

.section5{
  margin-top:100px;
    
  .section5part{
    width: min(100%,1200PX);
    margin: 0 auto;
    text-align: center;
  h2{
    font-weight: bold;

    color: #0B132A;

  }

    p{
      color:#4F5665;
      margin: 12px 0;
      margin-bottom:100px;
    }


    .glimg{
      img{
        width:680px ;
      }
    }

  }
}
// --------------------section6----------------------------


.section6{
  text-align: center;
  display: flex;
 align-items: center;
 flex-direction: column;
  .temoignages{
    width: min(90%,1200PX);
    margin: 0 auto;
    display: flex;
    justify-content: center;
    flex-wrap:wrap;
.temoi{
border: 1px solid #DDDDDD;
border-radius: 12PX;
   flex-basis: 25%;
    padding: 10px;
     
  
      }
    margin-top: 55PX;
   
    .gapp{

border-radius: 10px;
 display: flex;
flex-direction: column;



    }
      // display: flex;
      // flex-wrap:wrap ;
      gap: 50PX;
      text-align: left;
      //  width: min(85%,1200PX);
      // margin: 65PX auto;
 
  
      .temoigngesheader{
  
        .headertemoi{
          display: flex;
          align-items: center;
          gap: 10PX;
          
          img{
            height: 75PX;
          }
        }
  
        display: flex;
        justify-content: space-between;
        align-items: center;
        text-align: left;
       
        
       
h3{
  font-size: 15px;
  font-weight: bolder;

  span{
    font-weight: lighter;
  }
}


        .temoignagesnote{
          display: flex;
          align-items: center;
          gap: 5px;
          img{
            height: 20PX;
          }
        }
      }
    }
  .section6part{

 
    width: min(100%,1200PX);
    margin: 0 auto;

    h2{
    font-weight: bold;
    color: #0B132A;
    margin-top:50px;

  }

    p{
      color:#4F5665;
      margin: 12px 0;
 
    }


  }
}

// ----------------------section7-------------------------------
.section7{
  margin-top: 75PX;
  margin-bottom: 75PX;
 
.section7part{
  padding: 38px 20px;
  display: flex;
  justify-content: space-around;
  box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3);
  width: min(80%,1200PX);
  margin: 0 auto;
  align-items: center;

  .section7left{
    h1{
      color: #0B132A;
    }
    P{
      color:#4F5665 ;
    }
  }

  .section7right{
    button{
      background-color: #F53838;
      padding: 10px 25px;
      color: #ffffff;
      border-radius: 9px;
      border: none;
      box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3);
    }
  }
}
}

@media(max-width: 425px){
  .section2part{
  flex-direction:column;
  align-items:center;
  justify-content: center;
  gap:20px;
  
}

.ic1{
  img{
   max-width: 65PX;
  }
}
}

@media(max-width: 769px){

  .section4{
  


  .section4part{ 
    // width:90% ;
  }
}
.sect1{
 margin: 5px auto;
border:1px solid red;
  width:90% ;
}

.glimg{
  
img{
 padding: 10PX 70PX;
  height:5% ;
}


}

.temoignages{
.section6{
  border: 1PX SOLID RED;
}
flex-direction: column;
margin: 0 auto;

}



}

@media(max-width: 769px){
  .glimg{
    // width:50px ;
      img{
        //  width:80px ;
        // border:1px solid red;
        display: none;
      }
    }
.section7{
  margin:15PX 5px;
  .section7part{
    flex-direction: column;
  }
}

.footercontain{
  .footcont{
    width:100% ;
   
padding: 0 10PX;
    .liste{
 
       width:100% ;
    }
  }
}

.cl1{
  margin-top: 20PX;
  margin-bottom: 20PX;
}

.section7{
  margin-top: 20PX;
  margin-bottom: 20PX;
}
}

</style>