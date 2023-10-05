"1A":
				ESCRIBIR "INGRESE SABOR DEL JUGO NATURAL QUE DESEA LLEVAR"
				ESCRIBIR "1. MORA"
				ESCRIBIR "2. NARANJA"
				ESCRIBIR "3. LULO"
				LEER NATURAL
				SEGUN JUGO_NATURAL HACER 
					1: ESCRIBIR "MORA"
						COSTO=2500
			2: ESCRIBIR "NARANJA"
				COSTO=2500
			3: ESCRIBIR "LULO"
				COSTO=2500
				escribir Sin Saltar "digite la cantidad de jugos naturales que desea llevar"
				leer cantidad 
				total = costo*cantidad 
				escribir Sin Saltar "digite el monto con el que desea pagar"
				leer monto
				si monto>2500 entonces 
					cambio=monto-total
					escribir "su cambio es" cambio 
				FinSi
				
				si cantidad>0 Entonces
					escribir "gracias por su compra"
				FinSi
		FINSEGUN 
			"2A":
				ESCRIBIR "INGRESE EL AGUA QUE DESEA LLEVAR"
				ESCRIBIR "1. AGUA"
				LEER AGUA 
				segun agua hacer
					1: escribir "agua"
						COSTO=1500
						escribir Sin Saltar "digite la cantidad de aguas que desea llevar"
						leer cantidad 
						total = costo*cantidad 
						escribir Sin Saltar "digite el monto con el que desea pagar"
						leer monto
						si monto>1500 entonces 
							cambio=monto-total
							escribir "su cambio es" cambio
						finsi 
						si cantidad>0 Entonces
							escribir "gracias por su compra"
						finsi 
				FINSEGUN 
		"3A":
			ESCRIBIR "INGRESE EL SABOR DEL JUGO HIT QUE DESEA LLEVAR"
				ESCRIBIR "1. TROPICAL"
				ESCRIBIR "2. MANGO"
				ESCRIBIR "3. MORA"
				ESCRIBIR "4. LULO"
				LEER HIT 
				SEGUN JUGO_HIT HACER 
					1: ESCRIBIR "TROPICAL"
						COSTO=3000
					2: ESCRIBIR "MANGO"
						COSTO=3000
					3: ESCRIBIR "MORA"
						COSTO=3000
					4: ESCRIBIR "LULO"
						COSTO=3000
						escribir Sin Saltar "digite la cantidad de jugos hit que desea llevar"
						leer cantidad 
						total = costo*cantidad 
						escribir Sin Saltar "digite el monto con el que desea pagar"
						leer monto
						si monto>3000 entonces 
							cambio=monto-total
							escribir "su cambio es" cambio
						finsi 
						si cantidad>0 Entonces
							escribir "gracias por su compra"
						finsi
				FINSEGUN 
			"4A":
				ESCRIBIR "INGRESE SABOR DE LA GASEOSA QUE DESEA LLEVAR"
				ESCRIBIR "1. MANZANA"
				ESCRIBIR "2. COLOMBIANA"
				ESCRIBIR "3. UVA"
				ESCRIBIR "4. PEPSI"
				ESCRIBIR "5. COCACOLA"
				LEER GASEOSA 
				SEGUN GASEOSA HACER 
					1: ESCRIBIR "MANZANA"
						COSTO=3500
					2: ESCRIBIR "COLOMBIANA"
						COSTO=3500
					3: ESCRIBIR "UVA"
						COSTO=3500
				    4:ESCRIBIR "PEPSI"
						COSTO=3500
					5: ESCRIBIR "COCACOLA"
						COSTO=3500
				FINSEGUN 
				escribir Sin Saltar "digite la cantidad de gaseosas que desea llevar"
				leer cantidad 
				total = costo*cantidad 
				escribir Sin Saltar "digite el monto con el que desea pagar"
				leer monto
				si monto>3500 entonces 
					cambio=monto-total
					escribir "su cambio es" cambio
				finsi 
				si cantidad>0 Entonces
					escribir "gracias por su compra"
				finsi 
			"5A":
				ESCRIBIR "INGRESE EL SABOR DEL TEA FRIO QUE DESEA LLEVAR"
				ESCRIBIR "1. DURAZNO"
				ESCRIBIR "2. FRUTOS ROJOS"
				LEER TEA_FRIO
				SEGUN TEA_FRIO HACER 
					1: ESCRIBIR "DURAZNO"
						COSTO=4000
					2: ESCRIBIR "FRUTOS ROJOS"
						COSTO=4000
				FINSEGUN 
				escribir Sin Saltar "digite la cantidad de teas frios que desea llevar"
				leer cantidad 
				total = costo*cantidad 
				escribir Sin Saltar "digite el monto con el que desea pagar"
				leer monto
				si monto>4000 entonces 
					cambio=monto-total
					escribir "su cambio es" cambio
				finsi 
				si cantidad>0 Entonces
					escribir "gracias por su compra"
				finsi 
			"1B":
				ESCRIBIR "INGRESE TIPO DE CAFE QUE DESEA LLEVAR"
				ESCRIBIR "1. CAFE NORMAL"
				ESCRIBIR "2. CAFE CON LECHE"
				LEER CAFE  
				SEGUN CAFE HACER 
					1: ESCRIBIR "CAFE NORMAL"
						COSTO=2600
					2: ESCRIBIR "CAFE CON LECHE"
						COSTO=2600
				FINSEGUN 
				escribir Sin Saltar "digite la cantidad de cafes que desea llevar"
				leer cantidad 
				total = costo*cantidad 
				escribir Sin Saltar "digite el monto con el que desea pagar"
				leer monto
				si monto>2600 entonces 
					cambio=monto-total
					escribir "su cambio es" cambio
				finsi 
				si cantidad>0 Entonces
					escribir "gracias por su compra"
				FinSi
				
			"3B":
				ESCRIBIR "INGRESE EL SABOR DE SU TEA CALIENTE QUE DESEA LLEVAR"
				ESCRIBIR "1. HIERVAS"
				ESCRIBIR "2. FRUTAS"
				LEER TEA_CALIENTE
				SEGUN TEA_CALIENTE HACER 
					1: ESCRIBIR "HIERVAS"
						COSTO=4000
					2: ESCRIBIR "FRUTAS"
						COSTO=4000
				FinSegun
				
				escribir Sin Saltar "digite la cantidad de teas calientes que desea llevar"
				leer cantidad 
				total = costo*cantidad 
				escribir Sin Saltar "digite el monto con el que desea pagar"
				leer monto
				si monto>4000 entonces 
					cambio=monto-total
					escribir "su cambio es" cambio
				finsi
				si cantidad>0 Entonces
					escribir "gracias por su compra"
				finsi 
			HASTA QUE SALIR=0
	FinSegun
	
FinAlgoritmo

--->
