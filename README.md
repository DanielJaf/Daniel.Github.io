<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>031921</title>
</head>
<body>
  <h1 id="resultText"></h1>
  <script>
    
    let response = prompt("Oo o hindi? Type Oo r Hindi");
    let outputText = "";
    
    if (response=="Yes"){
      outputText = "Oo Typo";
    }else if(response=="No"){
      outputText = "Hindi Typo";
    }else{
      outputText = "please type Oo or No!!";
    }
    
    document.getElementById("resultText").innerHTML = outputText;
  </script>
</body>
</html>
