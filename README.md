# wangdefagufenjituan2
<!DOCTYPE html>
<html>
<head>
  <title>我的第一个App</title>

  <style>
    body{
      text-align:center;
      font-family:sans-serif;
      margin-top:100px;
    }

    button{
      font-size:30px;
      padding:20px;
    }

    h1{
      font-size:50px;
    }
  </style>
</head>

<body>

<h1 id="count">0</h1>

<button onclick="add()">
点击加1
</button>

<script>

let num = 0;

function add(){

  num++;

  document.getElementById("count").innerText = num;

}

</script>

</body>
</html>