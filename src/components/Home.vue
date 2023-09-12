<template>

<div class='main'> 
 
  <div class="img">
    <div class="img-content">
    <h1>RC Bulletins <icon icon='mdi:email-newsletter' color='white' font-size='15px'  /></h1>
    <button type="" class='btn'>Subscribe to RC Bulletins</button>
    </div>
  </div>


   <input class=" form-control my-10 mx-6 px-4 py-2" placeholder="SEARCH" type="text">
 

<v-table class='mx-8 '>
    <thead>
      <tr>
        <th class="text-left">
          RC
        </th>
        <th class="text-left">
          Date
        </th>
        <th class="text-left">
          BULLETIN TITLE
        </th>
      </tr>
    </thead>
    <tbody class=''>
      <tr
        v-for="item in desserts"
        :key="item.RC"
        class='hover'
      >
        <td><p> {{ item.RC }} </p></td>
        <td><p> {{ item.Date }} </p> </td>
        <td><p> <a href=''> <icon icon='vscode-icons:file-type-pdf2' /> {{ item.bulletin }} </a> </p></td>
      </tr>
    </tbody>
  </v-table>

<icon icon='vscode-icons:file-type-pdf2' />
</div>


</template>

<script>

import { Icon } from "@iconify/vue";
  export default {
    data () {
      return {
        desserts: [
          {
            RC: '2586',
            Date: '08-01-2023',
            bulletin:'EXPIRING CLASSIFICATION CODES; EFFECTIVE OCTOBER 1, 2023',
          },
          {
            RC: '2584',
            Date: '03-04-2023',
            bulletin:'NYS WORKERS’ COMPENSATION LOSS COST FILING AND LOSS COSTS BY CLASSIFICATION; EFFECTIVE OCTOBER 1, 2023'
          },
          {
            RC: '2585',
            Date: '07-03-2023',
            bulletin:'NYS EXPERIENCE RATING VALUES; EFFECTIVE OCTOBER 1, 2023',
          },
          {
            RC: '2583',
            Date: '30-09-2023',
            bulletin:'WEBSITE REDESIGN AND LAUNCH OF NEW LEARNING CENTER',
          },
          {
            RC: '2582',
            Date: '05-02-2023',
            bulletin:'CLASSIFICATION CODE REVISIONS; EFFECTIVE JULY 1, 2023',
          },
          {
            RC: '2581',
            Date: '06-02-2023',
            bulletin:'EXPIRATION OF CATASTROPHE NUMBER 12; EFFECTIVE JANUARY 1, 2024',
          },
          {
            RC: '2580',
            Date: '04-07-2023',
            bulletin:'2023 LOSS COST FILING',
          },
          {
            RC: '2579',
            Date: '08-01-2023',
            bulletin:'NOTICE OF UPCOMING NEW YORK STATE WORKERS’ COMPENSATION LOSS COST FILING',
          },
          {
            RC: '2578',
            Date: '05-01-2023',
            bulletin:'CONSTRUCTION INDUSTRY PAYROLL LIMITATION AS OF JULY 1, 2023',
          },
          {
            RC: '2577',
            Date: '04-07-2023',
            bulletin:'EXPANSION OF THE NEW YORK MEDICAL AND INDEMNITY DATA CALLS',
          },

        ],
      }
    },
  }
  

</script>

<style scoped>

p{
  font-size:12px;
}


.img {
  margin-top:80px;
  height: 55vh;
  color:white;
  background: url(/img.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  object-fit: cover;
  position:relative;

}

.img-content{
  position:absolute;
  top: 50%;
  left: 50%;
  transform:translate(-50%,-50%);
  text-align:center;
}
h1{
  font-size:48px;
}
.btn{
  background:blue;
  border-radius:20px;
  padding:2px;
  padding-left:2px;
  font-size:14px;
}
input{
  border-radius:15px;
  outline-color: blue;
  background:white;
   width:95vw;
}
.main{
    background:#f6f7f9;
} 
.hover:hover{
background:#f6f7f9;
}

</style>


