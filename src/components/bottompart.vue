<template>
  <div class="main">
      <div class="drops">
        <div class="dropdown">About Lendbox
          <div class="items About">
          <div class="item1">Home</div>
          <div class="item1">How it works</div>
          <div class="item1">About Us</div>
          <div class="item1">Team</div>
          <div class="item1">RBI's NBFC-P2P License</div>
          <div class="item1">Blogs</div>
          <div class="item1">Calculate EMI</div>
          <div class="item1">Broad Business Model</div>
          <div class="item1">Overview of Credit Methodology</div>
          </div>
        </div>
        <div class="dropdown">Investors
         <div class="items investor">
          <div class="item2">Why Invest</div>
          <div class="item2">Investors Eligibility</div>
          <div class="item2">How to invest</div>
          <div class="item2">Return and fees</div>
          <div class="item2">Investor code of conduct</div>
          <div class="item2">Investor's FAQ</div>
          <div class="item2">Low risk alternate investments</div>
          <div class="item2">Tutorial for investors</div>
          </div>
        </div>
        <div class="dropdown">Borrowers
          <div class="items borrower">
          <div class="item3">Why Borrow</div>
          <div class="item3">Borrowers Eligibility</div>
          <div class="item3">How to create effective listing</div>
          <div class="item3">Purpose of Loan</div>
          <div class="item3">Repayament, Interest Rates</div>
          <div class="item3">Borrower FAQ</div>
          <div class="item3">Tutorial for Borrowers</div>
          </div>
        </div>
        <div class="dropdown">Legal
         <div class="items legal">
          <div class="item4">Term of use</div>
          <div class="item4">Privacy policy</div>
          <div class="item4">Fair practice Code</div>
          <div class="item4">RBI Disclaimer</div>
          <div class="item4">Grievence Redressal</div>
          </div>
        </div>
      </div>
       <div class="contains">
          <div class="form">
           <p class="subscribe">Subscribe Now</p>
            <div class="inputs">
              <input placeholder="Enter your name"/>
              <input placeholder="Enter your email address"/>
              <button>Submit</button>
            </div>
            <p class="stayup">Stay up to date with the latest news and offers from lendbox </p>
            </div>
            <div class="social">
                <p class="followus">Follow Us</p>
                <div class="img">
                  <img src="@/images/instagram.png"/>
                  <img src="@/images/facebook.jpg"/>
                  <img src="@/images/twitter.png"/>
                </div>
            </div>
       </div>
          <div class="foot">
            <p class="address">
              <b>Address : </b>Empowerers Coworking City, Saira Tower, Gulmohar Commercial Complex, Yusuf Sarai, Green Park Metro Exit 2, New Delhi, Delhi 110049 India
            </p>
            <div class="contact">
                <div class="cont">
                  <img src ="@/images/msgbox.png" class="icon"/>support@lendbox.in
                </div>
                <div class="phon">
                  <img src="@/images/phone.png" class="icon"/>+91-7291027919
                </div>
            </div>
            <p style="font-size:15px; text-align:center;">Copyright © Transactree Technologies Pvt Ltd 2019. All Rights Reserved.</p>
          </div>       
  </div>
</template>

<script>
export default {
  
}
</script>

<style>

.main{
    margin:16px;
}
.drops{
    border-bottom:2px solid #C8C7CC;    
    margin-bottom:10px;
    padding-bottom:10px;
}
.dropdown{
    border:1px solid #C8C7CC;
    border-radius: 4px;
    padding:10px;
    font-size:14px;
    font-weight: bold;
    margin-top:10px;
    margin-bottom:10px;
}
.items{
  display: none;
  font-weight: normal;
  color:#8A8A8F;
  margin-top: 5px;
}
.contains{
    display: flex;
    flex-direction: column;
}
.form{
     display: flex;
     flex-direction: column;
     margin-bottom:5px;
}
.inputs{
  display: flex;
  flex-direction: column;
}
.main input{
    border:1px solid gainsboro;
    margin-bottom:10px;
    padding:6px;
    border-radius: 4px;

}
.main button{
    border:1px solid;
    margin-bottom:10px;
    background-color: blue;
    color:white;
    padding:10px;
    border-radius: 4px;
}
.stayup{
  font-size:12px; 
  max-width:260px;
}
.social{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top:10px;
  padding-bottom:10px;
  font-weight: bold;
}
.img{
  margin-top:5px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height:36px;
  width:170px;
  
}
.foot{
  border-top:2px solid #C8C7CC;
  padding-top:10px;
 
}
.contact{
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-top:10px;
  padding-bottom:10px;
  font-size: 14px;
}
.subscribe{
  font-weight:bold; 
  font-size:14px; 
  margin-bottom:10px;
  padding-top: 10px;
}
.followus{
  font-size: 14px;
  font-weight: bold;
  margin-bottom:10px;
  padding-top:10px;
}
.address{
  font-size: 14px;
  text-align: center;
  
}
.cont{
  display: flex;
  justify-content: center;
  align-items: center;
}
.phon{
  display: flex;
  justify-content: center;
  align-items: center;
}
.icon{
  padding:8px;
}
@media only screen and (min-width: 786px) {
  .drops{
    display: flex;
  }
  .dropdown{
    font-weight: bold;
    flex-grow:1;
    border:none;
  }
  .items{
    display: inline;
    font-size: 14px;
    color:#8A8A8F;
    padding-top:5px;
    font-weight: normal;
  }
  .item1, .item2, .item3,.item4{
    padding-top:10px;
  }
  .contains{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-right:100px;
    align-items: flex-start;
  }
  .inputs{
    flex-direction: row;
  }
  .main input{
    margin-right:10px;
  }
  .social{
    display: block;
    margin-top:10px;
  }
  .form{
    margin-top: 10px;
  }
  .img{
    width:128px;
  }
  .stayup{
    max-width: 300px;
    padding-bottom:10px;
  }
  .drops{
    border-bottom:1px solid #C8C7CC; 
  }
  .foot{
  border-top:1px solid #C8C7CC;
  }
  .contact{
    margin:auto;
    width:350px;
  }
  .address{
    width:700px;
    margin:auto;
    padding-top:8px;
  }
}
</style>
