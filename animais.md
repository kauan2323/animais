<!DOCTYPE html>
<html>
<head>
	<title>animais em extinçaõ</title>
	<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css"> 
<script type="text/javascript" arc="js/jquery-3.5.1.min.js"></script>
<script type="text/javascript" arc="js/bootstrap.min.js"></script>
<style type="text/css">
	div{
		background-color: #ccc;
		border: 1px solid #000;
		min-height: 100px;
	}
	#rowconteudo{
		min-height: 500px;
		
	}
	.flex-row{
		flex: 1 0 auto;
	}
	#rodape{
		min-height: 100px;
	}
</style>
</head>
<body>
	<div class="container-fluid">
		<div class="row justify-content-between">
			<div class="col-6">coluna1</div>
			<div class="col-6">coluna2</div>
		</div>
		<div class="row" id="rowconteudo">
			<div class="col-9 d-flex">
				<div class="d-flex flex-column w-100">
					<div>primeiro</div>
					<div class="flex-row">segundo</div>
					<div>terceiro</div>
				</div>
			</div>
			<div class="col-3 d-flex">
				<div class="d-flex flex-column w-100">
					<div>primeirão</div>
					<div class="flex-row">segundão</div>
				</div>
			</div>
		</div>
		<div class="row" id="rodape">
				<div class="col-12">rodape</div>
			</div>
	</div>

</body>
</html>
