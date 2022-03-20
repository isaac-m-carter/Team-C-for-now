   <template>
   <div class="top-bit">
    <img alt="Yvonne Test" class="logo" src="../assets/logo.svg" width="85" />

    <h1>MONDAY <br> <span>MARCH 21</span></h1>
    </div>

    <div class="nav-class">
            <div class="nav1">Trending</div>
            <div class="nav">Technology</div>
            <div class="nav">Entertainment</div>
            <div class="nav">Business</div>
            <div class="nav">Design</div>
        </div>

    <h2>FOR YOU</h2>
<br>
    <div class = "wrapper-top">
    <div class="maintop">
        <img class="mainimage" src="https://pm1.narvii.com/7119/b0abdf491cffde4bdf95850956c1b15a5591a4b5r1-712-707v2_hq.jpg">

    </div>
    </div>

<br>
<h3>Today's Latest News</h3>

    <div class = "wrapper-bottom">

    <div class="mainbottom">
        <div class="left">
            <img class="leftimage" src="http://www.dumpaday.com/wp-content/uploads/2019/08/the-random-pics-495.jpg">
        </div>

        <div class="right">
            <div class="title">this is a test</div>
        </div>
    </div> 
    </div>

    </template> 

    <style scoped>

   .top-bit{
      margin:2.5%;
      display:flex;
      justify-content: space-between;
   }
   
   h1{
      line-height: normal;
      font-size: 33px;
      font-weight: 800;
      text-align: end;
   }

   span{
      font-size: 28px;
      
   }

   .nav-class{
      margin: 20px 0;
      display:flex;
      padding: 2%;
      justify-content: space-around;
      
   }

.nav{
   font-size: 13px;
   font-weight: 700;
   border-bottom: 5px solid rgb(204, 204, 204);
   
}
   .nav:hover {

      font-weight: 700;
      color:#CA2D2D;
      border-bottom: 5px solid #CA2D2D;
      
    
}

.nav1{
   font-size: 13px;
   font-weight: 700;
   color:#CA2D2D;
      border-bottom: 5px solid #CA2D2D;
}
h2{
    font-size: 20px;
    text-align: center;
    font-weight: 700;
}

h3{
    font-weight: 800;
}

.wrapper-top{
  min-width: 95%;
  -webkit-box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
          box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
  border-radius: 4px;
  text-decoration: none;
  padding-right: 70px;
  height: 180px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  overflow-x: auto;
}

.wrapper-top ::-webkit-scrollbar {
  width: 0;
  }
  
  .wrapper-bottom{
      min-width: 95%;
      border-radius: 9px;
      margin-bottom: 20%;
  }

  .maintop{
        position: relative;
        min-width: 270px;
        margin-right: 10px;
        color:white;
        height: 180px;

        
    }

    .mainbottom{
            background-color: white;
    border-radius:9px;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
    height:150px;
    margin:10px;
    display:flex;
    }

        .mainimage{
        border-radius:4px;
        position:absolute;
        top:0;
        z-index: -1;
        object-fit: cover;
        object-position: center;
        width: 270px;
        height:180px;
    } 
    .leftimage{
    border-radius:9px 0 0 9px;
    height: 150px;
    width: 150px;
    object-fit: cover;
    object-position: center;
}

.right{
    padding: 1em;
    overflow:hidden;
}

.title{
    font-size: 14px;
    color:black;
    font-weight:700;
}
    </style>