<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> replace() </h2>
    <p id="out"> </p>
    <script>
        let text= "i love bhanu";
        let result = text.replace(/bhanu/,"jyothi");
        document.getElementId("out").innerText=result;
    </script>
    
</body>
</html>
