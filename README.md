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
    
    let response = prompt("Pwede ba kitang maging girlfriend"Type Yes or No");
    let outputText = "";
    
    if (response=="Yes"){
      outputText = "Haha Swerte ko naman gago";
    }else if(response=="No"){
      outputText = "Thank You For Answering The Question";
    }else{
      outputText = "please type Yes or No!!";
    }
    
    document.getElementById("resultText").innerHTML = outputText;
  </script>
</body>
</html>
