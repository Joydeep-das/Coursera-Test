<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>MENU</title>
    <style>
      *{
        box-sizing: border-box;
      }
  
  @media (min-width:992px){
      .col-lg-4{
        float:left;
        border: 1px solid black;
        background-color: grey;
        width:30%;
        margin:15px;
      }
  }

  @media (min-width:768px) and (max-width:991px){
      .col-md-6{
        float:left;
        border: 1px solid black;
        background-color: grey;
        width:48%;
        margin: 5px;
      }
      .col-md-12{
        float:left;
        border: 1px solid black;
        background-color: grey;
        width:97%;
        margin:10px;
      }
  }
  
  @media (max-width:767px){
      .col-sm-12{
        float:left;
        border: 1px solid black;
        background-color: grey;
        width:100%;
        margin:10px;
      }
  }
  
  .row{
    margin:20px;
  }
  
  p{
    font-weight: bold;
  }
  
  .row p{
    border-left: 2px solid black;
    border-bottom: 2px solid black;
    border-top: 2px solid black;
    border-right: 2px solid black;
    padding: 5px 10px;
    width: 100px;
    text-align: center;
    margin-top: 0;
    margin-right: 0;
    margin-left: auto;
    font-size: 20px;
  }
  
  #desc{
    margin: 10px;
    font-family: "Times New Roman";
  }
  
  #menu{
    text-align: center;
    font-family: "Georgia";
    font-size: 25px;
    padding: 15px;
  }
  
  #chicken{
    background-color: Red;
  }
  
  #beef{
    background-color: Pink;
    color:white;
  }
  
  #sushi{
    background-color: Yellow;
  }
</style>
  </head>
  <body>
    <div class="container">
      <p id="menu">Our Menu</p>
      <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12">
          <p id="chicken">Chicken</p>
          <div id="desc">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident, sunt in culpa
            qui officia deserunt mollit anim id est laborum.
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12">
          <p id="beef">Beef</p>
          <div id="desc">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident, sunt in culpa
            qui officia deserunt mollit anim id est laborum.
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-12 col-sm-12">
          <p id="sushi">Sushi</p>
          <div id="desc">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident, sunt in culpa
            qui officia deserunt mollit anim id est laborum.
          </div>
        </div>
      </div>
    </div>
  

</body>
</html>
