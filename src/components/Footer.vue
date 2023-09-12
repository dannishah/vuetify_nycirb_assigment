<template>
  <v-footer class='main'>
    
 
     
     <div class='dv1'>
     <div class='img'>
     </div>
       
        <p> The New York Compensation Insurance Rating Board is a non-partisan, non-profit, unincorporated association of insurance carriers, including the State Insurance Fund.</p><br>
         <p><icon icon='material-symbols:location-on' color='#c8e8ff' font-size='15px' /> &nbsp;&nbsp;&nbsp; 733 Third Avenue, 5th Floor New York, NY 10017</p><br>
         <p><icon icon='material-symbols:call' color='#c8e8ff' font-size='15px'  /> &nbsp;&nbsp;&nbsp; 212-697-3535</p><br>
         <p><icon icon='mdi:email-newsletter' color='#c8e8ff' font-size='15px'  /> &nbsp;&nbsp;&nbsp; info@nycirb.org</p><br>

     
     </div>  
     <div class='dv2'>
     <h6>menu</h6>
     <a href="">INSURANCE CARRIER</a><br>
     <a href="">BROKER & EMPLOYER</a><br>
     <a href="">RESEARCH & REPORTS</a><br>
     <a href="">MANUALS</a><br>
     <a href="">FORUMS</a><br>
     <a href="">RC BULLETINS</a><br>

     </div>  
     <div class='dv3'>
      <h6>most viewed</h6>
      <a href="">DATA GENIE</a><br> 
      <a href="">FORMS</a> <br>
      <a href="">LOSS COST FILINGS</a><br> 
      <a href="">MANAGE DATA</a> <br>
      <a href="">MOD ESTIMATOR</a> <br>
     </div>  
     <div class='dv4'>
     <h6>about us</h6>
     <a href="">WHO WE ARE</a><br>
     <a href="">LEARNING CENTER</a><br>
     <a href="">TERMS OF USE</a><br>
     <a href="">OUR CONSTITUTION</a><br>
     <a href="">FEEDBACK</a><br>
     </div>  

 </v-footer>
           <hr>
           <div class='ls'>
           <p>Copyright NYCIRB 2023. All rights reserved.</p>
            <p>By using this website, you confirm your eligibility to access the NYCIRB website and content, and your agreement to the current version of our Terms of Use</p>
           </div>
</template>

<script setup>
import { Icon } from "@iconify/vue";
</script>


<style scoped>
.main{
width:100vw;
background:#004098;
}
.dv1{
height:50vh;
width:30%;
margin-left:50px;
margin-top:30px;
}
.dv2{
height:45vh;
width:20%;
text-transform:uppercase;
}
.dv3{
height:45vh;
width:20%;
text-transform:uppercase;
}
.dv4{
height:45vh;
width:20%;
text-transform:uppercase;
}
h6{
    color:#c8e8ff;
    font-weight:500;
    font-size:12px;
    margin-bottom:30px;
}
a{
    font-size:12px;
    color:white;
    text-decoration:none;
}
.img{
     height:45px;
  width:160px;
  background:url('/icon2.png');
  background-size:cover;
object-fit:cover;
background-position:center;
background-repeat:no-repeat;
margin-bottom:20px;
background-color:#c8e8ff;
}
p{
    width:90%;
    color:white;
    font-size:12px;
    margin-left:5px;

}
.ls{
    height:30px;
    background:#004098;
}
.ls p{
    margin-top:30px;
    margin-left:60px;
    display:inline;
}
</style>