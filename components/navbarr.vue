<template>
 
 <div class="headercontainer">


    <div class="menumobile">


        <div class="imgmobile">     <img src="@/public/images/logo.png" alt="logo menu"> </div>


        <div>
        <Icon name="system-uicons:menu-hamburger"  v-if="change" @click="OpenMenu" class="iconee"/>
      <Icon name="material-symbols:close"  v-else @click="OpenMenu"   class="iconee"/> 
        </div>

        <div class="menumobileelement"    :class="[change?'A':'B']">
        <li v-for="item in menuItems"  :key="item.id">
    <NuxtLink :to="item.path" :class="{ active: $route.path === item.path }" class="er" >{{ item.label }}</NuxtLink>

</li>

<div class="buton">

<button class="signin">Sign in</button>
<button class="signup">Sign up</button>

</div>

</div>
  
    </div>


<div class="menu">

<div class="imgmenu">
    <img src="@/public/images/logo.png" alt="logo menu">
</div>

<div class="menulist">


<li v-for="item in menuItems"  :key="item.id">
    <NuxtLink :to="item.path" :class="{ active: $route.path === item.path }" class="er" >{{ item.label }}</NuxtLink>

</li>

</div>

<div class="buton">

<button class="signin">Sign in</button>
<button class="signup">Sign up</button>

</div>


</div>
    
 </div>

</template>

<script setup>

const change=ref(true);

const OpenMenu =()=>{
    change.value=!change.value;
} 
const menuItems = [
{ id: 1, label: 'About',path: '/#section3' },
{ id: 2, label: 'Features',path: '/#section3' },
{ id: 3, label: 'Pricing',path: '/#section3' },
{ id: 4, label: 'Testimonials',path:'/#section3' },
{ id: 5, label: 'Help',path: '/#section3' }
]




// rubik


</script>

<style lang="scss">
.headercontainer{
    width: min(100%,1200PX);
       margin: 0 auto;
    position: relative;
}
.menu{
    padding: 20px 0;
    font-size: 20PX;
    display: flex;
    justify-content: space-around;
    align-items: center;
// border: 1px solid green;
    .menulist{
        // border: 1px solid black;
        width:40% ;
        display: flex;
        justify-content: space-between;
        .er{
            text-decoration: none;
            color:#0B132A;
        }
      
        li{
            list-style: none;
            text-decoration: none;
        }
    }

    .imgmenu{
        img{
            height: 36px;  
            margin-top: 3PX;
        }
      
        // border: 1px solid black;
    }
    .buton{
        display: flex;
        gap: 5PX;
        justify-content: space-between;
        MIN-width:12% ;
        // border: 1px solid black;
        button{
            background-color:transparent;
             padding: 7px 15px ;
            border-radius:20PX;
        }
        .signin{
            font-weight:bold ;
        }
        .signup{
            font-weight:bold ;
            border: 1px solid #F53855;
            color: #F53855;
        }
    }    




}


.menumobile{
position: relative;

    .menumobileelement{
   
        .buton{
            display: flex;
            gap: 9px;
            button{
                background-color: transparent;
                border: 1px solid #ffffff;
                padding: 7px;
                color: #ffffff;
                border-radius: 8PX;
            }
        }
       
        display: flex;
        flex-direction: column;
        gap: 25PX;
        padding-left: 12PX;
       
        position:fixed;
        background-color: #0B132A;
        top: 47px;
        right: 0px;
        width:50% ;
        height: 100VH;


        .A{
      display: none;    
  }

 .B {
            display: block;
            color:#1E201D;
          
           }        
        li{
            list-style: none;
            color: #ffffff;
        }
        .er{
            text-decoration: none;
            color: #F53855;

        }
        
    }
     background-color: #0B132A;
     color: #ffffff;
    position: fixed;
    display: flex;
    width:100% ;
    justify-content: space-around;
    padding-top: 11px;
    .iconee{
        font-size: 34px;
    }
    display:flex;
        .imgmobile{
            img{
           height: 30px; ;
            }
        }
    }






@media(max-width: 977px){

    .menu{
        font-size:15PX ;
        .menulist{
        width:48% ;
      
    }
    }
  
}


 @media(min-width: 767px){

 .menumobile{
     display: none;
   
  } 


}





   @media(max-width: 767px){

.headercontainer{
    .menumobile{
        .menumobileelement{
    
            li{
               margin-bottom: 20PX;
               gap: 50PX;
            }
         
        }
      
        .A{
      display: none;
      animation:sideslide  1s;
       
  }

 .B {
            display: block;
          
            animation:sideslide  1s;
          
           }
    }
}








     .menu{

  display: none;


    }
    
} 
    
    
    
@keyframes sideslide {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
} 

</style>