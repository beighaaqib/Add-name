# Add-name
add name using HTML
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Document</title>
</head>
<body>
          <input type="text"id="txt">
          <button type="button"onclick="add()">Add</button>
          <ul id="ull"></ul>
   <script>
       function add()
       {
        var txt = document.getElementById("txt");
        document.getElementById("ull").innerHTML+="<li>"+txt.value+"</li>";
       }
   </script>
</body>
</html>
