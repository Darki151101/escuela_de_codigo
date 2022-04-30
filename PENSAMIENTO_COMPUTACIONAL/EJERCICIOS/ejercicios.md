Algoritmo de promedio 
hacer un algortimo que te pida las 4 claificacion para promediarlas 

* 1 Inicio 
* 2 Declara (num1, num2, num3, num4, resultado)
* 3 Mostrar "ingrese la calificación de su primer periodo"
* 4 Asignar a num1 
* 5 Mostrar ""ingrese la calificación de su segundo periodo"
* 6 Asignar a num2
* 7 Mostra ""ingrese la calificación de su tercer periodo"
* 8 Asignar a num3
* 9 Mostrar ""ingrese la calificación de su cuarto periodo"
* 10 Asignar a num4
* 11 Operacion (resultado=num1+num2+num3+num4/4)
* 12 Asignar a resultado 
* 13 mostrar ""Tu promedio es de:"
* 14 Fin 

![image](https://user-images.githubusercontent.com/99523872/163237103-a25cb161-7c66-468e-af0c-989209d5d35c.png)

* 1 Inicio 
* 2 Declarar (i,j,Result)
* 3 asignar i=1 j=1
* 3 para(i>0 y i<=10)
    para(j>0 y j<=10)
    mostrar i*j
    j=j+1
    fin para
    i=i+1 
    finpara  
* 4 fin
 
 ![image](https://user-images.githubusercontent.com/99523872/165803918-29f93d74-5bf6-4857-ac08-05bfb4268d2a.png)


 



          Inicio

          Cali<-0, i<-0,mayor 7<-0, menor<-0 

           Minetras i<10 i=i + 1
           Escribir "Ingresar la calificaciom"
           Leer cal
      
          SI cal<7
        
           Menor<-menor +1
           
           SiNo
           
			Mayo7<-Mayo7 + 1
            
		FinSi
        
        Si cal<=10 y cal>0 Entonces
        
			i=i + 1
            
		SiNo
			Escribir "Dato erroneo
            "
		Fin Si
        
	   Fin Mientras  
    
       Escribir "El total de calificaciones mayoar a 7 es: ",Mayo7 
 
	   Escribir "El total de calificaciones menor a 7 es: " ,meno   
       
       Fin

![image](https://user-images.githubusercontent.com/99523872/165597396-6c9a5efb-5ca2-4ee9-9032-bf7c50ca3bb6.png)

      Inico

      Promi<-0, Num_pr<-0,Altura<-0,i<-0,sum<-0

      Escribir "Cuantas Personas quieres saber su altura"

       Leer Num_pr

        Mientras i<Num_pr Hacer

		i=i + 1
        
		Escribir "Ingresa la altura ", i
        
		Leer Altura
        
		sum<-sum + Altura
        
		Promi<-sum/Num_pr
        
		Fin Mientras
    
        Escribir "El promedio de altura de ", Num_pr " personas es ", Promi
        
        Fin

![image](https://user-images.githubusercontent.com/99523872/165597529-0b2d5c55-5379-4c66-aa3b-281bada0b762.png)


    Inicio
    
    Num<-0
    
    Repetir
    
      Escribir "Ingres un numero de 0 al 999"
      
      Si Num>0 y Num<999
      
        Si Num>0 y Num<=9
	  Escribir "Tu numero es de una de Cifra "
	  
	  Si NuSi Num>9 y Num<=91
	  
	   Escribir "Tu numero es de dos de Cifra "
	   
	   SiNO
             Escribir "Tu numero es de tres de Cifra"
      
      SiNO
       Escribir "Dato invalido"
       
       Hata que Num=0
   
        Fin

![image](https://user-images.githubusercontent.com/99523872/165812789-08e51119-7765-4e17-a244-208e715bd81e.png)


      Num_sec<-azar(100) + 1
	Num<-0
	i<-10
	Escribir "ADIVINA EL NUMERO"
	Leer Num
	Mientras Num=Num_sec y i>0 Hacer
		i=i - 1
		
		Si Num>Num_sec
			Escribir "El numero es mayor"
		SiNO 
			Escribir "El numero es menor"
		FinSi
		Escribir "Te quedan " , i " intentos"
		Escribir "Ingresa otro numero del 1 al 100"
		Leer Num
		
	Fin Mientras
	Si Num==Num_sec Entonces
		Escribir "Felicidades le atinaste en ", i "Intentos"
	SiNo
		Escribir "Se terminaron las oportunidades, el numero secreto era ", Num_sec
	FinSi

