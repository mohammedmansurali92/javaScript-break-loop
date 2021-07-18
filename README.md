# javaScript-break-loop
<body>
	
	<script>

	for(var i= 1; i<=100; i++){
		if(i==10){
			break;
		}
       document.write(" "+i);
	}
	document.write("End");
     </script>
	//continue
		<script>

	for(var i= 1; i<=20; i++){
		if(i==10){
			continue;
		}
       document.write(" "+i);
	}
	document.write("End");
     </script>
	&
			<script>

	for(var i= 1; i<=50; i++){
		if(i%2==0){
			continue;
		}
       document.write(" "+i);
	}
	document.write("End");
     </script>
	&&
				<script>

	for(var i= 1; i<=50; i++){
		if(i%2!=0){
			continue;
		}
       document.write(" "+i);
	}
	document.write("End");
     </script>
	
	</body>
