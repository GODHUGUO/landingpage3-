<template>
  <div>


<div class="footercontain">
<div class="footcont">
<div class="cl1">
<img src="@/public/images/logo.png" alt="logo menu">
<p>LaslesVPN is a private virtual network that <br> has unique features and has high security.</p>

<div class="footerimg">

    <Icon name="ic:sharp-facebook" class="iconee"/> 
    <Icon name="mdi:twitter-circle" class="iconee"/> 
    <Icon name="ant-design:instagram-filled" class="iconee"/> 
     
   
</div>




</div>
<div class="liste">
<div class="cl2">
<h5>Product</h5>
<li>Download</li>
<li>Pricing</li>
<li>Download</li>
<li>Locations</li>
<li>Countries</li>
<li>Blog</li>
</div>


<div class="cl2">
<h5>Engage</h5>
<li>LaslesVPN ? </li>
<li>FAQ</li>
<li>Tutorials</li>
<li>About Us</li>
<li>Privacy Policy</li>
<li>Terms of Service</li>
</div>


<div class="cl2">
<h5>Earn Money</h5>
<li>Affilate</li>
<li>Become Partner</li>
</div>
</div>
</div>
</div>





  </div>
</template>

<script setup>

</script>

<style lang="scss">
.footercontain{

    width: min(100%,1200PX);
    margin: 0 auto;
    .footcont{
        .liste{
            display: flex;
            justify-content: space-between;
          
            width: 60%;
        }
        margin-top:60px;
        display: flex;
         justify-content: space-between;
    .cl1{
     img{
        height: 36px;
     }
        .footerimg{
            margin-top: 15PX;
            .iconee{
                color:#F53838;

            }
        }   

    }
    .cl2{
        h5{
            color:#0B132A;
            margin-bottom: 9PX;
        }
        li{
            color:#4F5665;
            list-style: none;
            margin-bottom: 15PX;
        }
    }
    }
}




@media(max-width: 769px){

.section1{
   
    padding:  0 15PX;
    flex-direction: column;

    .leftsection1{
        margin-top: 65PX;
    }
}

.section3{
    .section3part{
        flex-direction: column;
    }
    
}


.section4{
    .section4part{
        .pricesection{
            flex-direction: column;
        }
    }
}


.footercontain{  

   

.footcont{

    .liste{
        width:100% ;
        gap: 20px;
    }
    display: flex;
    gap: 20PX;
    flex-direction: column;
  align-items: center;


margin: 0 auto;
width: 80%;
 
}
.cl2{
 
    li{
        margin-bottom: 5PX;
    }
}
}

}



</style>