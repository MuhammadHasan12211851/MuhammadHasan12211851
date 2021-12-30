<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Belajar jQuery</title>
<script src="jquery-3.6.0.js"></script>
<script>
   $(document).ready(function() {  
	 $("#tombol").click(function() {
        
        var a = parseInt($("#nilai1").val());
        var b = parseInt($("#nilai2").val());
        var operasi = $("#operasi").val();
        var total = $("#hasil").val();

        if(isNaN(a) || isNaN(b)) {
			alert('isi form dengan angka!')					    
	    } else {
	    	if(operasi=="+") {
				$("#hasil").val(a+b);
			}else if(operasi=="-") {
				$("#hasil").val(a-b);
			}else if(operasi=="*") {
				$("#hasil").val(a*b);
			}else if(operasi=="/") {
				$("#hasil").val(a/b);
			}	
		}

     })
   });
   </script>
</head>
<body>
	Nilai 1	: <input type="text" id="nilai1"> 
	Operasi : <select id="operasi">
				<option value="+">Tambah</option>
				<option value="-">Kurang</option>
				<option value="*">Kali</option>
				<option value="/">Bagi</option>				
			  </select>		 
	Nilai 2	: <input type="text" id="nilai2"><br/>
	Hasil : <input type="text" id="hasil"><br/>
	<button id="tombol">Hitung</button>
</body>
</html>
