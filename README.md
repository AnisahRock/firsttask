<!DOCTYPE html>
<html>
<head>
<style>
p.thicker {
    font-weight: 900;
}
.alert {
    padding: 20px;
    background-color: #f44336;
    color: white;
}

.closebtn {
    margin-left: 15px;
    color: white;
    font-weight: bold;
    float: right;
    font-size: 22px;
    line-height: 20px;
    cursor: pointer;
    transition: 0.3s;
}

.closebtn:hover {
    color: black;
}
</style>
</head>
<body>
<h2> Borang Pengesahan </h2>
<p><span class="error">* Butiran yang diperlukan.</span></p>
<div align="center">
<p class="thicker">	TASEK NAGA</p>
<p class="thicker">	RESIT TIMBANGAN</p>		
</div>

<form action="Terima kasih.php" method="post">
TAG:<input type="text" name="name"><span class="error"> * <?php echo $nameErr;?></span><br>
MASA:<input type="text" name="name" placeholder="				am"><input type="text" name="name" placeholder="				pm"><span class="error"> * <?php echo $nameErr;?></span><br>
BERAT TANGKAPAN:<input type="text" name="name" placeholder=" 				   kg"><span class="error"> * <?php echo $nameErr;?></span><br>
ZON:<input type="text" name="name"><span class="error"> * <?php echo $nameErr;?></span><br>
TARIKH: <input type="date" name="dateday"><span class="error"> * <?php echo $nameErr;?></span><br>
NAMA KERANI BERTUGAS:<input type="text" name="name"><span class="error"> * <?php echo $nameErr;?></span><br>



<p>Sila klik pada simbol "x" untuk menutup mesej amaran.</p>
<div class="alert">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span> 
  <strong>Perhatian!</strong> Sila semak dan pastikan butir-butir di resit timbangan adalah betul.
</div>
<input type="submit" name="submit" value="Submit">
</form> 

</body>
</html>
