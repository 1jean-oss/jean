<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> tela de login</title>
    <style>
        body{
          font-family: Arial, Helvetica, sans-serif; 
          background-image:linear-gradient(45deg,cyan,yellow);
        }
        div{
            background-color: rgba(0, 0, 0, 0,9);
            position: absolute;
            top:50%;
            left:50%;
            transform: translate(-50%,-50%);
            padding: 80px;
            border-radius: 15px;
             color: #fff;
        }
        input{
            padding: 15px;
            border:none;
            outline: none;
            font-size: 15px;

        }
        button{
            background-color: dodgerblue;
            border: none;
            padding: 15px;
            width: 100%;
            border-radius: 10px;
            color: white;
            font-size:15px;
        }

    </style>
</head>
<body>
     <div>
         <h1>login</h1>
         <input type="text" placeholder="nome">
         <br><br>
         <input type="text" placeholder="senha">
         <br><br>
         <button>enviar</button>
     </div>
</body>
</html>

