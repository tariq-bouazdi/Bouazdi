import "./styles.css";

document.getElementById("app").innerHTML = `
<!DOCTYPE html>
<html>

  <head>

    <title>TP JS YacineDRARENI TariqBOUAZDI</title>
    <charset="UTF-8">;

    <style>
    
      h1  { background-color: rgb(169, 169, 180);
            color: white  }
      
      .ville { color: rgb(100, 100, 130);}
      
      .divVille{ background-color: rgb(220, 220, 255);
                  border:solid 2px rgb(200,200,230);
                  width:200px ;
                  display :flex;
                  flex : 1;
                  margin-bottom:20px;
                  margin-left : 10px;
                  margin-right: 10px;
                  justify-content:space-around }

      #flex { display :flex;justify-content:space-around;
              flex-wrap:wrap}

      footer  { background-color: rgb(169, 169, 180);
                color: black; font-size:12px;opacity:0.5}
    
    </style>
  </head>
  

<body>
    <center>
      <h1>TP Météo HTML</h1>  
    </center>

  <div id="flex">
    <div class ="divVille">
      <div>
        <h2 class = "ville"> Lyon </h2>
        <p> 6° , Nuageux </p>
      </div>

      <div>
        <img src="/src/img/noun_clouds_653375.png"
        width="60" alt ="nuages">
        <br>
      </div>
    </div>

  <div class = "divVille">
    <div>
      <h2 class="ville"> Paris </h2>
      <p> 1° , Nuageux </p>
    </div>
    <div>
    <img src="/src/img/noun_clouds_653375.png"
      width="60" alt ="nuages">
      <br>
    </div>
  </div>
   
  <div class = "divVille">
    
    <div>
      <h2 class = "ville"> Alger </h2> 
      <p> 17° , couvert </p>
    </div>
    <div>    
      <img src="/src/img/noun_sun cloud_653897.png"
      width="60" alt ="partiellement couvert">
    </div>
  </div>
</div>

  <footer>
      <p> Tariq BOUAZDI - Yacine DRARENI<br>icones created by noun project </p>
  </footer>
      </body>
</html>
`;
