<template>
<div class="main">

   <div class="first" id="ch"><br>
<div>

<span class="check text-dark">Che</span>
<span id="sp">ckout</span>
</div>


<h2 class="Bdetails text-dark">Billing Details</h2><br>
<hr><br>
<form>
<label class="lb text-dark" for="Email">Email Address</label><br>
<input  type="email"  value="prospercollins@gmail.com" id="email"/><br><br>
<label class="lb text-dark" for="Name">Name</label><br>
<input type="text" value="Prosper Collins" id="name"/><br><br>
<label class="lb text-dark" for="Address">Address</label><br>
<input type="text" value="21, church str, ikorodu,lagos,Nigeria." id="address"/><br><br><br>
<hr>

<hr><br>

<div class="flexD"><br>

<div class="gris">
<div>
<label class="lb text-dark" for="City">City</label><br>
<input type="text" value="Lagos" id="city"/><br><br>
</div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div>
<label class="lb text-dark" for="Province">Province</label><br>
<input type="text" value="22" id="province"/><br><br>
</div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</div>

<div class="frid">
<div>
<label class="lb text-dark" for="postal Code">Postal Code</label><br>
<input type="text" value="104101" id="Postal_Code"/><br><br>
</div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div>
<label class="lb text-dark" for="Phone">Phone</label><br>
<input type="text" value="+2348034206320" id="Phone"/><br><br>
</div>




</div>





</div><br>
<hr><br>
<h1 class="PD text-dark">Payment Details</h1><br>
<hr><br>

<label for="Name on Card">Name on Card</label><br>
<input type="text" value="Prosper Collins" id="NoC"/><br><br>
<label for="Address">Address</label><br>
<input type="text" value="21, church str, ikorodu,lagos,Nigeria." id="pAddress"/><br><br>
<label for="Credit Card Number">Credit Card Number</label><br>
<input type="text" value="2341289473" id="CCN"/><br><br><br>
<hr>
<hr><br>
<div class="flexPy"><br>

<div>
<label for="Expiry">Expiry</label><br> 
<input type="text" placeholder="MM/YY" value="03/24" id="expire"/>

</div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div>
<label for="CVC Code">CVC Code</label><br> 
<input type="text" value="626" id="CVC_Code"/><br><br><br>

</div>

</div>
<button class="btn btn-success mb-5px" >Complete Order</button><br><br>
<hr>




<hr>






<hr>


</form>
    </div>
    <div class="second ">
    
    <h1 class="order">Your Order</h1>
      <hr><br>
  <div class="LM">
  <div  class="l1">
  <img src="../Images/lappys.jpg" alt="Laptop"/>
  </div>
  <div class="l2">
   <P class="lappy">Laptop 7</P>
   <P class="Inc">15 inc, 1 TB SSD 16GB, RAM.</P>
   <P class="money">$1499.99</P><br>
  </div><br>
  <div class="l3">
  <h3 class="one">1</h3>
  
  </div>
  </div>
   <hr><br>
   <div class="mF">
   <div class="innerF">
   <P class="subtotal">Subtotal</P>
   <P class="tax">Tax</P>
    <P class="total">Total</P>
   </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   <div class="outerF">
   <P class="m-1">$1499.99</P>
   <P class="m-2">$195.00</P>
   <P class="ms-3">$1694.99</P>
   </div>
   </div><br>
    <hr><br>
    </div><br>

  

</div>

 
</template>

<script>
    export default {
        name: 'CheckForm',
        
    }
</script>

<style lang="css" scoped>
.l1{
 width:100px;
 height:80px;
 margin-right: 25px;
}
img{
 margin-top: 15px;

height:60px;
width: 80px;
 
}
h3 {
    border: solid #ccc 1px;
    padding: 8px;
    margin-top: 20px;
    margin-left: 15px;
}
.lappy{
    font-weight: 600;
}
.Inc{
    color: gray;
    font-size:15px ;
 
}
.ms-3{
    font-family: Arial, Helvetica, sans-serif;
    color: #000;
    font-weight: bold;
}
.subtotal{
    margin-top: 8px;
     font-family: Arial, Helvetica, sans-serif;
     color: #000;
}
.tax{
     font-family: Arial, Helvetica, sans-serif;
     color: #000;
     margin-top: 8px;
}
.total{
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 5px;

}
.flexPy{
    display: flex;
}
.gris{
    display: flex;
    
}

   
.second{
  margin-right: 250px;
}

@media(max-width:900px) {
    .second{
        display: none;
    }
}
.frid{
    display: flex;
}
.LM{
    display: flex;
}

.mF{
    display: flex;
    
}
.main{
    display: flex;
 
}
.order{
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 110px;
}
.check{
    font-size: 40px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
    text-decoration: overline underline 2px;
}
#sp{
    font-size: 40px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif
}
#ch{
    margin-left: 95px;
}
.Bdetails{
 font-size: 20px;
 margin-top: 20px;
 font-weight: bold;

}
#email{
    border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #email{
         border: solid  grey#ccc 1px;
          width: 310px;
        }
        
    }
#name{
        border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #name{
           border: solid  #ccc 1px;
          width: 310px;
        }
        
    }
#address{
       border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #address{
          border: solid #ccc 1px;
          width: 310px;
        }
        
    }

 .PD{
 font-size: 20px;
 font-weight: bold;
     }

     #NoC{
   border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #NoC{
  border: solid  #ccc 1px;
          width: 310px;
        }
        
    }

    #pAddress{
       border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #pAddress{
         border: solid  #ccc 1px;
          width: 310px;
        }
        
    }
    #CCN{
      border: solid  #ccc 1px;
      width: 520px;
}

 @media(max-width:700px) {
        #CCN{
          border: solid  #ccc 1px;
          width: 310px;
        }
        
    }

       .btn{
    
      width: 520px;
          border-radius: 10px 10px 10px 10px;
    
}

 @media(max-width:700px) {
        .btn{
         
          width: 315px;
          border-radius: 10px 10px 10px 10px;
       
        }
        
    }

    

       #expire{
    
      width: 246px;
         border: solid  #ccc 1px;
    
}

 @media(max-width:700px) {
        #expire{
         
          width: 140px;
         border: solid  #ccc 1px;
       
        }
        
    }
    
       #CVC_Code{
    
      width: 246px;
     
        border: solid #ccc 1px;
}

 @media(max-width:700px) {
        #CVC_Code{
         
          width: 140px;
          border: solid  #ccc 1px;
          
     
       
        }
        
    }
.flexD{
 display:flex;
 flex-wrap: wrap;
 


}

#city{

 border: solid  #ccc 1px;
 width: 247px;

}
 @media(max-width:700px) {
        #city{
         
          width: 140px;
          border: solid  #ccc 1px;
          
     
       
        }
 }
#province{
  
     border: solid  #ccc 1px;
     width: 247px;
}
  @media(max-width:700px) {
        #province{
         
          width: 140px;
          border: solid  #ccc 1px;
          
     
       
        }
 }
 #Postal_Code{
     
       width: 247px;
      border: solid  #ccc 1px;

 }
   @media(max-width:700px) {
        #Postal_Code{
         
          width: 140px;
          border: solid  #ccc 1px;
          
     
       
        }
 }
 #Phone{  
      width: 247px;
      border: solid  #ccc 1px;
 }
   @media(max-width:700px) {
        #Phone{
         
          width: 140px;
          border: solid  #ccc 1px;
          
     
       
        }
 }
 body{
     background-color: #f4f4f4;
 }
</style>