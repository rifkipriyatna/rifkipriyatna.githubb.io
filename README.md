<!DOCTYPE html>
<html lang="in">
<head>
				<title>Jam Design</title>
				<link rel="stylesheet" href="ja.css">
				<style>
								.background{
				position:fixed;
				top:0;
				left:0;
				width:370px;
				height:620px;
				
}

.sd{
				font-size:25px;
				text-align:center;
				color:white;
				margin-top:-430px;
				
				
				
				
					
}

.kotak{
		
		display:inline-block;
		padding:7px;
		margin-top:-200px;
		
			
}

.aw{
				margin-bottom:-125px;
				border-radius:110px;
}

.name{
				color:White;
				text-align:center;
				margin-top:40px;
}

.isi{
				color:white;
				text-align:center;
}

.isi a{
				color:salmon;
}


				</style>
<body>
				<div class="background">
								<img class="back" src="https://raw.githubusercontent.com/rifkipriyatna/Welcome/main/giphy.gif" alt="tai" width="410
								" height="610">
				
				<div class="sd">
								<div class="ya">
								<img class="aw" src="https://raw.githubusercontent.com/rifkipriyatna/Welcome/main/back.gif" width="200" height="200">
								</div>
				<div class="kotak">
				<p id="jam"></p>
				</div>
				
				<div class="kotak">
				<p id="menit"></p>
				</div>
				
				<div class="kotak">
				<p id="detik"></p>
				</div>
				</div><br><br>
				<h1 class="name">Welcome</h1>
				<p class="isi">Selamat Datang di pages Rifki Priyatna,jika anda ingin mengetahui lebih lanjut klik <a href="https://rifkipriyatna.github.io/Dataku.github.io/">Disini</a> </p>
				</div>
				<script>
								window.setTimeout("waktu()", 1000);

 

	function waktu() {

		var waktu = new Date();

		setTimeout("waktu()", 1000);

		document.getElementById("jam").innerHTML = waktu.getHours();

		document.getElementById("menit").innerHTML = waktu.getMinutes();

		document.getElementById("detik").innerHTML = waktu.getSeconds();

	}
				</script>
				
				
</body>
</html>
