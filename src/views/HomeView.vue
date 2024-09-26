<template>
  <div class="cards">
    <div class="col">
      <a href="#">
        <img src="../assets/card-order.svg" alt="">
        <span class="opacity-50">Order Number</span>
      </a>
      <h2 class="text-dark">1000</h2>
      <p class="lead oo">SR</p>
    </div>

    <div class="col">
      <a href="#">
        <img src="../assets/card-company.svg" alt="">
        <span class="opacity-50">Company Number</span>
      </a>
      <h2 class="text-dark">1000000</h2>
      <p class="lead oo">SR</p>
    </div>

    <div class="col">
      <a href="#">
        <img src="../assets/card-driver.svg" alt="">
        <span class="opacity-50">Drivers Number</span>
      </a>
      <h2 class="text-dark">500</h2>
      <p class="lead oo">Driver</p>
    </div>

    <div class="col">
      <a href="#">
        <img src="../assets/card-sales.svg" alt="">
        <span class="opacity-50">Total Sales</span>
      </a>
      <h2 class="text-dark">500</h2>
      <p class="lead oo">Driver</p>
    </div>

    <div class="col-2 text-center position-relative">
      <p>Waiting For Loading</p>
      <a href="#">
        <img src="../assets/card-load1.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">80</div>
    </div>

    <div class="col-2 text-center position-relative">
      <p>Waiting For Arrive</p>
      <a href="#">
        <img src="../assets/card-load1.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">80</div>
    </div>

    <div class="col-2 text-center position-relative">
      <p>Completed</p>
      <a href="#">
        <img src="../assets/card-load1.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">80</div>
    </div>

    <div class="col-2 text-center position-relative">
      <p>Canceled</p>
      <a href="#">
        <img src="../assets/card-load1.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">80</div>
    </div>

    <div class="col-3 col-3r item1 opacity-100 ps-3">
      <h6>Top 5 Companies</h6>
      <table class="table table-borderless">
        <thead>
          <tr>
            <td class="text-secondary">Company Name</td>
            <td class="text-secondary">Order Qty</td>
            <td class="text-secondary" >Amount</td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Gillette</td>
            <td>5000</td>
            <td>50000 SR</td>
          </tr>
          <tr>
            <td>Louis Vuitton</td>
            <td>3000</td>
            <td>50000 SR</td>
          </tr>
          <tr>
            <td>Johnson & Johnson</td>
            <td>2000</td>
            <td>50000 SR</td>
          </tr>
          <tr>
            <td>Nintendo</td>
            <td>1000</td>
            <td>50000 SR</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="col-3 text-center position-relative">
      <p>Repeated Order</p>
      <a href="#">
        <img src="../assets/card-load1-80.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">80%</div>
    </div>

    <div class="col-3 text-center position-relative">
      <p>Commission</p>
      <a href="#">
        <img src="../assets/card-load2.svg" alt="">
      </a>
      <div class="position-absolute top-50 start-50 translate-middle fs-4 text-dark">127k</div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'HomeView',
};
</script>

<style scoped>
/* #app{
  border: 2px solid green;
} */
.date-x{
  width: 220px;
}
.oo{
  font-size: x-small;
  flex-direction: row;
  flex-wrap: wrap;
}
.col , .col-2 , .col-3{
border: 1px solid gray;

width: 270px;
border-radius: 5px;
padding-top: 15px;
padding-left: 10px;
font-family: 'Poppins',sans-serif;
font-weight:600;
}
.col-2 , .col-3{
  text-align: center;
  opacity: 100%;
  padding-left: 0%;
  
}
.col-3r{
text-align: start;
}

.col-3{
  grid-row: span 2;
}

.filter button{
margin: 10px;
position: relative;
left: 21%;
}
.filter input{
  position: relative;
left: 20%;
}


.item1{
  grid-column: 1/3;
  width: 560px;
}
.cards{
  display: grid;
  grid-template-columns:  repeat(4,270fr);
  grid-template-rows: 120px repeat(2,220px) ;
  gap: 1.5rem;
  position: absolute;
  margin-left: -120px;
  

  
}
/*
#stat{
}
*/

.container{
  display: flex;
  /*
  border: 2px solid red;
  */
  width: 1440px;
  height: 1115px;
  margin: 0;
  padding: 0;
  flex-direction: column;
  flex-wrap: wrap;

}
#side-bar{
  background-color: #F6F6F6;
  height: 1115px;
  width: 238px;
}
#side-bar img{
  position: relative;
  left: 15px;
  fill: orange;
  color: aqua;
}
#main{
  width: 1115px;
  height: 50px;
  display: flex;
justify-content: space-between;


}
a{
  color: #353535;
  text-decoration: none;
}

</style>