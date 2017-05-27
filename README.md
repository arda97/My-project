<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
<h3 style="text-align:right;">Name :Ricard  </h3>
<h3 style="text-align:right;">NIM : 1515051063</h3>
<h3 style="text-align:right;">Class : 4D</h3>
<hr><h3 style="text-align:center;">TABEL PERKALIAN</h3></hr>

	<?php
		$n=100;
		echo"<table border=2>";
		for($baris=1;$baris<=$n;$baris++){
			echo"<tr>";
			for($kolom=1;$kolom<=$baris;$kolom++){
				echo "<td>";
				   $hasil=$baris*$kolom;
	            	if($hasil%7==0){
						//echo"<b><mark>".$hasil."</mark></b>";
					}else{
						echo $hasil;
					}
			}
								
								for ($kolom=$baris;$kolom<$n;$kolom++) {
				echo"<td>";

			}
		}
	?>
</body>
</html>
