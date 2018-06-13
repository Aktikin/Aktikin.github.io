<?php
      function Determinant($razmer){
        $A = array();
        for($i=0; $i<$razmer; $i++){
          $A[$i] = array();
          for($j=0; $j<$razmer; $j++)
            $A[$i][$j]=$_POST['$'.$i.'$'.$j.'$'];}
        $N = count($A);
        $sum= 1;
        if ($N == 1)
          return $A[0][0];
        else if ($N== 2)
          return $A[0][0] * $A[1][1] - $A[0][1] * $A[1][0];
        else if($N==3)
          return $A[0][0] * $A[1][1] * $A[2][2] + $A[0][1]*$A[1][2]*$A[2][0]+ $A[0][2]*$A[1][0]*$A[2][1]- $A[0][2]*$A[1][1]*$A[2][0]-$A[0][0]*$A[1][2]*$A[2][1]-$A[0][1]*$A[1][0]*$A[2][2];
        else{
          for ($i = 0; $i < $N-1; $i++){ 
            $value1 = $A[$i][$i];
            for ($j = $i+1; $j < $N; ++$j){ 
              $value2 = $A[$j][$i];
              $A[$j][$i] = 0;
            if (abs($value1) == abs($value2)){
              if ($value1 == $value2)
                for ($k = $i+1; $k < $N; ++$k) 
                  $A[$j][$k] = $A[$j][$k] - $A[$i][$k];
              else
                for ($k = $i+1; $k < $N; ++$k) 
                  $A[$j][$k] = $A[$j][$k] + $A[$i][$k];
            }
            else {
              $raz = abs($value2) / abs($value1);
              for ($k = $i+1; $k < $N; ++$k)
                if ($A[$j][$k] * $A[$i][$k] < 0)
                  $A[$j][$k] += $A[$i][$k]*$raz;
                else 
                  $A[$j][$k] -= $A[$i][$k]*$raz;
              }
            }
          }
        }
      for ($i = 0; $i < $N; ++$i)
        $sum*=$A[$i][$i];
      return round($sum);
    }
?>
<!doctype html>
<html>
  <head>
    <title>Зачетная работа по Web-технологиям</title>
    <meta charset="utf-8">
    <link rel="shortcut icon" href="icon.png" type="x-icon">
    <link href="task.css" rel="stylesheet"/> 
    <script type="text/javascript">
      var x = true;
      var razmer;
      var arr
      function newform(bool, i, j){//Создает одну новую ячейку, поле для ввода, на форму  
        var index = document.getElementById("end");
        var x = document.createElement("INPUT");
        var br = document.createElement("br");
        x.setAttribute("type", "number");
        x.setAttribute("value", "0");
        x.setAttribute("style", "width: 3em");
        x.setAttribute("name", ("$"+i+"$"+j+"$"));
        if (bool)
          index.appendChild(x);
        else
          index.appendChild(br);
        }
        function newtable(sizetable){//Создаём матрицу для ввода значений на форму, вызывая фуункцию "newform"
        document.getElementById("result").innerHTML = "";
        razmer = sizetable;
        var exist = document.getElementById("end");
        if (exist != null)
          cleartable();
        inputlabel();
        var f = false;
        for (var i = 0; i < sizetable;i++){
          newform(false);
        for (var j = 0; j < sizetable;j++)
          newform(true, i, j);
        }
      }
      function cleartable(){// Удаляем полностью матрицу, избавившись от метки по id и соответственно всего его содержимого
        var qwe = document.getElementById("end");
        qwe.parentNode.removeChild(qwe);
      }
      function inputlabel(){//Создаем новую метку необходимую для размещения там нашей матрицы 
        var xc = document.createElement("p"),
        wrapoi = document.getElementById("startplace");
        xc.id = "end"; 
        wrapoi.parentNode.appendChild(xc);
      }
    </script>
  </head> 
  <body>
    <style> body{
      color: black;
      background: #DAFABD;
      font-family: Helvetica, sans-serif;
    }
    option{
      color: black;
    }
    input[type="text"], input[type="number"], input[type="radio"] { 
    padding: 3px 5px; 
    margin: 5px 0; 
    color: #2c2c2c; 
    font-size: 1.2em; 
    background-color: #fff2c6; 
    border: 1px solid #2c2c2c; 
    border-radius: 5px; 
    } 
    fieldset{
      background: #BDFACE;
      color: black;
      width: 70%;
      height: 500px;
      padding: 10px;
      margin: auto;
      border-style: double;
      border-width: 20px;
      border-color: #FF4500
    }
    .letter { 
      color: red; 
      font-size: 200%;  
      font-family: serif; 
      position: relative; 
      top: 5px; 
    }
    .Button{ 
      font-weight: bold; 
      text-align: center; 
      color: #2c2c2c; 
      background:#FFD700; 
      display: inline-block; 
      box-sizing: border-box; 
      padding: 0.6em 1.0em; 
      margin: 7px 5px 7px 0; 
      border-radius: 5px; 
      text-decoration: none; 
    }
    </style>
    <h2 align="center" >Проект по теме: "Вычисление определителя матрицы".</h2> 
    <h3 align="center">Выполнил Попков В.С., студент 1 курса ВГУ ФКН, 3.1 группы </h3>
    <ul>
      <li><font size="5" face="Calibri"><b>Цель работы</b>: нахождение детерминанта заданной матрицы</font></li>
      <li><font size="5" face="Calibri"><b>Требования к проекту</b>: корректная работа, вне зависимости от входных данных, а также получение правильного ответа</font></li>
      <li><font size="5" face="Calibri"><b>Описание возможностей</b>: есть право установить собственный размер матрицы и ввести любые целые числа в неё</font></li>
      <li><font size="5" face="Calibri"><b>Формат входных и выходных данных</b>: целый</font></li>
    </ul>
    <form method="POST" name ="form" action="task.php?action=determinant">
    <fieldset>
      <legend><font size="5" color="red" face="Arial"><b>Работа с матрицей</b></font></legend>
      <label><b>Укажите размер матрицы:</b></label>
        <select onchange="newtable(this.value)" id="usrstrcol" name="usrstrcol" >
          <option disabled selected >Размер</option>
          <option value="2">2 x 2</option>
          <option value="3">3 x 3</option>
          <option value="4">4 x 4</option>
          <option value="5">5 x 5</option>
          <option value="6">6 x 6</option>
          <option value="7">7 x 7</option>
        </select>
      <p>
        <input type="submit" value="Детерминант" class="Button">
        <input style="margin-left: 25px;" class = "Button" type="reset" value="Очистить"><!--очищает ячейки от значений-->
      </p>
      <div> <font size="4" color="red" face="Arial"><u>Результат:</u> 
	  <span id="result">
	  <?php if (!empty($_REQUEST['action']) && $_REQUEST['action'] == 'determinant' && !empty($_REQUEST['usrstrcol'])) : ?>
		<?php echo determinant((int)$_REQUEST['usrstrcol']); ?>
	  <?php endif; ?>
	  </span>
	  </font></div>
      <div class="curves"><span class="letter" id = "startplace">Матрица</span><hr></div>
      </fieldset>
    </form>
  </body>
</html>