# biotipo

# ------------ CLASE ESQUELETAL --------------
# ----------- CONVEXIDAD FACIAL = 2 +/-2 ---------

print(" -------- CLASE ESQUELETAL ---------")
print (" ---------------------------------- ")
# 1)

def Convexidad_facial(num1):
	if num1 >= 5:
		print("Clase Esqueletal II")

	elif num1 >=0 and num1<=4:
		print("Clase Esqueletal I")

	elif num1 < 0:
		print("Clase Esqueletal III")

	else:
   		print("La opción que ingreso no es un numero, vuelva a intentarlo")
	
while True:		
	try: 
		num1 = float(input("Convexidad facial (2 +/-2): "))
		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

Convexidad_facial(num1)

# ----------------DISTANCIA A_B = 4 +/-2  ----------------

# 2)

print (" ")
def DistanciaA_B(num2):

	if num2 >=7:
		print("Clase Alveolar II")

	elif num2 >=0 and num2 <=6 :
		print("Clase Alveolar I")

	else:
		print("Clase Alveolar III")

while True:		
	try: 
		num2 = float(input("Distancia a_b (4 +/-2): "))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

valor2= DistanciaA_B(num2)


print (" ----------------------------------- ")
print(" -------- MAXILAR INFERIOR ---------")
print (" ----------------------------------- ")

#-------------- EJE FACIAL 90 +/-3 ---------------------
# 3)

def eje_facial(num3):
	
	if num3 >= 93:
		 
		print("Braquifacial")

	elif num3>=87 and num3<=92:
		 
		print("Mesofacial")

	else:
		
		print("Dolicofacial")
	
while True:		
	try: 
		num3=int(input("Eje facial (90 +/-3): " ))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

eje_facial(num3)
print (" ")

# ------------------PROFUNDIDAD FACIAL 87 +/- 3----------------------------

# 4)

def prof_fac(num4):
	
	if num4 >= 94:
		 
		print("Braquifacial")

	elif num4>=87 and num4<=93:
		 
		print("Mesofacial")

	else:
		
		print("Dolicofacial")
	
while True:		
	try: 
		num4=int(input("Profundidad facial: " ))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

prof_fac(num4)

print (" ")


# ---------------------ANGULO DE PLANO MANDIBULAR 26 +/- 4----------------------------

# 5)

def ang_pl_mandibular(num5):
	if num5 >= 30:
		 
		print("Dolicofacial")

	elif num5 >=22 and num5 <=29:
		 
		print("Mesofacial")
	
	else:
		
		print("Braquifacial")

while True:		
	try: 
		num5=int(input("Angulo de plano mandibular (26 +/- 4): " ))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")


ang_pl_mandibular(num5)

print (" ")

# ------------------ALTURA FACIAL INFERIOR 47 +/- 4----------------------------

# 6)

def h_facial_inf(num6):
	if num6 >= 50:
		 
		print("Braquifacial")

	elif num6 >=44 and num6<=49:
		 
		print("Mesofacial")

	else:
		
		print("Dolicofacial")

while True:		
	try: 
		num6=int(input("Altura facial inferior (47 +/- 4): " ))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

h_facial_inf(num6)
print (" ")

# --------------------ARCO MANDIBULAR 26 +/- 4----------------------------


# 7)

def arco_mand(num7):
	if num7 >= 30:
		 
		print("Braquifacial")

	elif num7 >=22 and num7<=29:
		 
		print("Mesofacial")

	else:
		
		print("Dolicofacial")

while True:		
	try: 
		num7=int(input("Arco mandibular (26 +/- 4): " ))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")
	

arco_mand(num7)

print (" ----------------------------------- ")
print(" -------- MAXILAR SUPERIOR ---------")
print (" -----------------------------------")

# ------------------ PROFUNDIDAD MAXILAR = 90 +/-3 ---------------
# 8)

def Prof_max(num8):
	if num8 >= 94:
		 
		print("Clase II")

	elif num8 >=87 and num8<=93:
		 
		print("Clase I")

	else:
		
		print("Clase III")

while True:		
	try: 
		num8=int(input("Profundidad maxilar (90 +/-3): "))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

Prof_max(num8)

# ------------------ DIENTES ------------------------
# ------------------ A-PO 1 +/-2 ---------------
# 9)

print (" ")
print(" -------- DIENTES ---------")
print (" ")

def A_Po(num9):
	if num9 >= 4:
		 
		print("Incisivo inferior protruido")

	elif num9 >=-1 and num9<=3:
		 
		print("Posicion normal del I. inferior" )

	else:
		
		print("Incisivo inferior retruido")

while True:		
	try: 		
		num9= float(input("A-Po (1 +/-2): "))
		break
	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

A_Po(num9)

# ------------------ PLANO OCLUSAL 1 +/-1 ---------------
# 10)

print (" ")
def plano_oclusal(num10):
	if num10 >= 3:
		 
		print("Incisivo inferior extruido")

	elif num10 >=0 and num10<=2:
		 
		print("Posicion normal al plano oclusal" )

	else:
		
		print("Incisivo inferior intruido")

while True:		
	try: 		
		num10=float(input("Plano oclusal (1 +/-1): " ))

		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

plano_oclusal(num10)

# ------------------ PLANO MANDIBULAR (ANGULO DEL II AL BASE MANDIBULAR)= 90 +/-5 ---------------
# 11)

print (" ")
def plano_mandibular(num11):
	if num11 >= 96:
		 
		print("Incisivo inferior pro-inclinado")

	elif num11 >=85 and num11<=95:
		 
		print("Posicion normal del I. inferior" )

	else:
		
		print("Incisivo inferior retro-inclinado")

while True:		
	try: 			
		num11=int(input("Plano mandibular (90 +/-5): " ))

		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

plano_mandibular(num11)

# ------------------ PLANO BA-NA (INCLINACION DEL I. SUPERIOR) = EJE FACIAL - 5 +/-3 ---------------
# 12)

print (" ")
def plano_BaNa(num12):
	if num12 > (num3-5):
		 
		print("Incisivo Superior pro-inclinado")

	elif num12 == (num3-5):
		 
		print("Posicion normal del I. Superior" )

	else:
		 
		print("Incisivo Superior retro-inclinado")

while True:		
	try: 		
		num12=int(input("Plano Ba_Na(eje facial -5 +/-3): "))

		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlos")

valor12=plano_BaNa(num12)

# -------------- ESTETICA -----------------------
# --------------- EXPOSICION DEL II = +2,5mm +/- 0.5 mm ------------
# 13)

print (" ")
print(" -------- ESTETICA ---------")
print (" ")

def Exposicion_I(num13):
	if num13 >= 3.5:
		 
		print("Incisivo inferior extruido")

	elif num13 >=1.5:
		 
		print("Incisivo inferior normal al plano oclusal" )

	else:
		 
		print("Incisivo inferior intruido")

while True:		
	try: 			
		num13=float(input("Exposicion del Incisivo inferior (+2,5mm +/- 0.5 mm): "))
		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlos")

valor13=Exposicion_I(num13)

# --------------- LABIO INF - PLANO ESTETICO = -2 mm +/- 2 mm ------------
# 14)

print (" ")
def Plano_E(num14):
	if num14 >= 1:
		 
		print("Labio inferior protruido con relacion al plano estetico")

	elif num14 < 1 and num14>= -4:
		 
		print("Labio inferior normal al plano estetico" )

	else:
		 
		print("Labio inferior retruido con relacion al plano estetico")

while True:		
	try: 		
		num14=float(input("Exposicion del labio inferior (-2 mm +/- 2 mm): "))
		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlos")

valor14=Plano_E(num14)

# --------------- ANGULO NASOLABIAL INF = 85 +/- 5  ------------
# 15)

print (" ")
def Angulo_NL(num15):
	if num15 >= 91:
		 
		print("Angulo nasolabial abierto")

	elif num15 >=80 and num15<=90:
		 
		print("Angulo nasolabial normal" )

	else:
		
		print("Angulo nasolabial cerrado")

while True:		
	try: 			
		num15=int(input("Angulo naso labial (85 +/- 5): " ))
		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlos")

valor15=Angulo_NL(num15)

# -------------- BIOTIPO -------------------------
print (" ")
print(" ------------------------- BIOTIPO ----------------------------------")
print (" ")

norma_Eje_fac = 90
norma_Prof_fac = 87	
norma_ang_pl_mand =26
norma_h_facial = 47
norma_arco_mand = 26


# 3)

suma_eje_fac = (num3 - norma_Eje_fac)/3	

def calcula_eje_fac(suma_eje_fac):

	if suma_eje_fac < 0:	
		print("Eje Facial: Dolicofacial " , "{:.2f}" .format(suma_eje_fac))

	else: 
		print("Eje Facial: Braquifacial: ", "{:.2f}" .format(suma_eje_fac))

	return suma_eje_fac

# -----------------------------------------------------------------------------------
# 4)

suma_Prof_fac = (num4 - norma_Prof_fac)/3

def calcula_Prof_fac(suma_Prof_fac):
	
	if suma_Prof_fac < 0:
		print("Profundiad facial: Dolicofacial: " , "{:.2f}" .format(suma_Prof_fac))
	else: 

		print("Profundiad facial: Braquifacial: ","{:.2f}" .format(suma_Prof_fac))

	return suma_Prof_fac

# -----------------------------------------------------------------------------------
# 5)

suma_ang_pl_mand = (norma_ang_pl_mand - num5)/4

def calcula_ang_pl_mand(suma_ang_pl_mand):
			
	if suma_ang_pl_mand < 0:

		print("Angulo del plano mandibular: Dolicofacial: " , "{:.2f}" .format (suma_ang_pl_mand))
	else: 

		print("Angulo del plano mandibular: Braquifacial: ", "{:.2f}" .format(suma_ang_pl_mand))

	return suma_ang_pl_mand


# -----------------------------------------------------------------------------------
# 6)

suma_h_facial = (norma_h_facial - num6)/4

def calcula_h_fac(suma_h_facial):
	
	if suma_h_facial < 0:
		print("Altura facial: Dolicofacial: " , "{:.2f}" .format(suma_h_facial))
	else: 
		print("Altura facial: Braquifacial: ", "{:.2f}" .format(suma_h_facial))

	return suma_h_facial

# -----------------------------------------------------------------------------------
# 7)

suma_arco_mand = (norma_arco_mand - num7)/4

def calcula_arco_mand(suma_arco_mand):
	
	if suma_arco_mand<0:

		print("Arco Mandibular: Dolicofacial: " , "{:.2f}" .format(suma_arco_mand))
	
	else: 
		print("Arco Mandibular: Braquifacial: ", "{:.2f}" .format(suma_arco_mand))

	return suma_arco_mand

# --------------------------- SUMA TOTAL BIOTIPO --------------------------------------


calcula_eje_fac(suma_eje_fac)	
print (" ")
calcula_Prof_fac(suma_Prof_fac)
print (" ")
calcula_ang_pl_mand(suma_ang_pl_mand)
print (" ")
calcula_h_fac(suma_h_facial)
print (" ")
calcula_arco_mand(suma_arco_mand)
print (" ")



# ---------------- SUMA TOTAL --------------------
# Biotipo del paciente es la suma de los angulos / 5 (VERT)

print(" ------------ RESULTADO BIOTIPO ----------------")
print()

suma_total = (suma_eje_fac + suma_Prof_fac + suma_ang_pl_mand + suma_h_facial + suma_arco_mand) / 5

def calcula_total (suma_total):

	if suma_total >= 1 :
		print("Paciente BRAQUIFACIAL SEVERO: ", "{:.2f}" .format(suma_total))

	elif suma_total >= 0.5 and suma_total <= 0.9:
		print("Paciente BRAQUIFACIAL: ", "{:.2f}" .format(suma_total))

	elif suma_total >= -0.4 and suma_total <= 0.4:
		print("Paciente MESOFACIAL: ", "{:.2f}" .format(suma_total))

	elif suma_total >= -0.9 and suma_total <= -0.4:
		print("Paciente DOLICOFACIAL: ", "{:.2f}" .format(suma_total))

	elif suma_total <= -1:
		print("Paciente DOLICOFACIAL SEVERO: ","{:.2f}" .format(suma_total))

calcula_total (suma_total)


# poner norma delante del valor, descripcion cefalometrica
