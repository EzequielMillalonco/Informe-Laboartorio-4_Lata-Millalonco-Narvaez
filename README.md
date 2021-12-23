# Informe-Laboratorio-4

## 1. OBJETIVOS
 
        General: 
        
Analizar y comprobar de forma experiemntal - práctica y teorica el teorema de superposición, mediante análisis de circuitos en serie - paralelo determinando el método más factible de resolución.



        Específicos: 
 
1. Reconocer circuito abierto o cerrado, a reemplazar en fuente de voltaje y/o corriente, analizando el valor de su resistencia interna.
        
2. Deducir e identificar la manera de convertir circuitos en serie - paralelo complejos en sencillos.
        
3. Comprobar el teorema de superposición y la funcionabilidad de las fórmulas para divisor de corriente y voltaje, mediante la comparación de resultados teóricos y los encontrados en el laboratorio virtual THINKERCAD.

## 2. MARCO TEÓRICO

![Lab 4](https://user-images.githubusercontent.com/93396250/147175998-48f9b56f-86c1-4c5e-9bae-ce6da09bbd62.jpg)

**EJEMPLO:**

En el circuito mostrado en la siguiente figura, encontrar la corriente que atraviesa cada resistencia mediante el teorema de superposición.

![superposición-1](https://user-images.githubusercontent.com/93396250/147176040-b74ebfda-19ce-4df2-a716-2ba69864121c.jpg)

**Solución**
**Contribución de la fuente de voltaje**
Para comenzar se elimina la fuente de corriente, con lo cual el circuito queda de esta forma:

![superposicion-2](https://user-images.githubusercontent.com/93396250/147176056-973d4389-a1d7-491e-aad9-ff0655f2d8d6.jpg)

La resistencia equivalente se encuentra sumando el valor de cada resistencia, ya que todas están en serie:

 <p align=center> 7500 +600 +400 + 1500 Ω = 10.000 Ω

Aplicando la ley de Ohm V = I.R y despejando la corriente:

 <p align=center> I = V/R = 7 / 10.000 A = 0.0007 A = 0.7 mA

Esta corriente es la misma para todas las resistencias.

Contribución de la fuente de corriente
Enseguida se elimina la fuente de voltaje, para trabajar únicamente con la fuente de corriente. El circuito resultante se muestra a continuación:

![superposicion-3](https://user-images.githubusercontent.com/93396250/147176086-b96643c1-1f5d-4ec1-8343-1973e38ae7ab.jpg)

Las resistencias en la malla de la derecha están en serie y se pueden sustituir por una sola:

 <p align=center> 600 +400 + 1500 Ω =2500 Ω

El circuito resultante queda así:

![superoposicion-4](https://user-images.githubusercontent.com/93396250/147176102-751d8d68-7fcf-4629-af41-63d133620037.jpg)


La corriente de 2 mA = 0.002 A se divide entre las dos resistencias de la figura, por lo tanto es válida la ecuación del divisor de corriente:

 <p align=center> Ix = (Req/Rx)IT
        
Donde Ix es la corriente en la resistencia Rx, Req simboliza la resistencia equivalente e IT es la corriente total. Es preciso encontrar la resistencia equivalente entre ambas, sabiendo que:        
        
 <p align=center> 1/Req = (1/ R1) + (1/ R2)

Por lo tanto:

 <p align=center> 1/Req = (1/7500) + (1/2500) = 1 / 1875 → Req = 1875 Ω

Para este otro circuito, la corriente que pasa a través de la resistencia de 7500 Ω se encuentra sustituyendo valores en la ecuación del divisor de corriente:

 <p align=center> I7500 Ω = (1875/7500). 0.002 A = 0.0005 A = 0.5 mA

Mientras que la que pasa a través de la resistencia de 2500 Ω es:

 <p align=center> I2500 Ω = 2 mA – 0.5 mA = 1.5 mA

Aplicación del teorema de superposición
Ahora se aplica el teorema de superposición para cada resistencia, comenzando por la de 400 Ω:

 <p align=center> I400 Ω = 1.5 mA – 0.7 mA = 0.8 mA        
        
**Importante:** para esta resistencia, las corrientes se restan, pues circulan en sentido contrario, según se desprende de la observación cuidadosa de las figuras, en las cuales los sentidos de las corrientes tienen colores diferentes.

Esta misma corriente atraviesa por igual a las resistencias de 1500 Ω y 600 Ω, puesto que todas están en serie.       
Seguidamente se aplica el teorema para encontrar la corriente a través de la resistencia de 7500 Ω:

 <p align=center> I7500 Ω = 0.7 mA + 0.5 mA = 1.2 mA
         
**Importante:** en el caso de la resistencia de 7500 Ω obsérvese que las corrientes se suman, porque en ambos circuitos circulan en el mismo sentido al pasar por esta resistencia. De nuevo es preciso observar atentamente los sentidos de las corrientes.
         
         
Una vez entendido esto se procede con el laboratorio #4, en el cual se comprobara experimentalmente el Teorema de Superposición. 
  
## 3. MATERIAL Y EQUIPO REQUERIDO
  
Para este laboratorio necesitaremos los siguientes materiales:
  
  ![image](https://user-images.githubusercontent.com/93396250/147176912-5ed8bcdb-9f07-4c2c-bedc-7d52f54c840d.png)

## 4. EXPLICACIÓN DEL PROCEDIMIENTO

	4.4.1 Arme el circuito que se muestra en la figura 4.1  

<p align=center> Circuito de la figura 4.1
	 
![image](https://user-images.githubusercontent.com/93396250/147179111-e64e68c8-6eae-4e16-a50b-90980c6f3712.png)

	 
<p align=center> Circuito implementado en ThinerCAD: 
	 
![image](https://user-images.githubusercontent.com/93396250/147179041-0c3150cd-b16a-4e1e-820e-959ef19d810a.png)
 
	 
	4.4.2  Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, 
	 respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. 
	 
![4 5 1](https://user-images.githubusercontent.com/93396250/147181159-eea6e8d0-8418-4238-bef0-0d93640c7360.JPG)

	4.4.3 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente Ix, 
	 respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan.
  
Se reemplaza la funete de voltaje de 12 V por un cable (cable morado) para causar un cortocircuito, entonces se mide el voltaje y la intensidad Ix 
  
![Thinker cad](https://user-images.githubusercontent.com/93396250/147178713-b3a96b66-400d-49ed-9399-542e9f59689f.JPG)
  

  
  
	4.4.4 Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, 
	 respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan.



	4.4.5 Verifique el cumplimiento del Teorema de Superposición y compare los 
	resultados obtenidos prácticamente con los obtenidos analíticamente. 
	
*Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan.*
	
	
![Screenshot 2021-12-22 202621](https://user-images.githubusercontent.com/93826527/147173683-e3daad9f-4271-417d-8d65-f516267376fa.png)

La resistencia de 470 (Ω) no se toma en cuenta para el cálculo del voltaje VA, ya que va a tener el mismo voltaje que la resistencia de 820 (Ω), esto debido a que se encuentran en paralelo y el voltaje VA requerido es el que pasa por la resistencia de 820 (Ω).

Primero procedemos a determinar que la fuente de voltaje de 20 (V), va a ser reemplazad por un cortocircuito, es decir un circuito cerrado. Posterior a eso se debe encontrar, la resistencia equivalente entre las resistencias de 1 (kΩ) y 2.2 (kΩ). 

 <p align=center> R12= (1000*2200)/3200 = 687.5 (Ω)

![image](https://user-images.githubusercontent.com/93826527/147174035-891e921e-aece-4a71-badc-0ba352c4a2a2.png)

Posterior a eso vamos a aplicar la fórmula de divisor de voltaje entre la resistencia R12 y R3, no se debe tomar en cuenta R4, por lo antes mencionado.

![Screenshot 2021-12-22 203308](https://user-images.githubusercontent.com/93826527/147174146-c37dcfa7-6d0d-4083-87b9-70bd56fc4a1b.png)

 <p align=center> Va = V2 * (R3/R3+R12)

 <p align=center> Va= -6.52 (signo negativo por la polaridad del voltaje) 
	
	
	
	
*Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan.*	
	
Para calcular el voltaje cuando V2 = 0V primero se saca las resistencias equivalentes.
  
![image](https://user-images.githubusercontent.com/93834732/147179332-a22dbd70-44b2-40e4-b710-8182b29873da.png)

Luego se aplica un divisor de voltaje y se calcula el Va 
  
![image](https://user-images.githubusercontent.com/93834732/147179436-977b84b4-6af1-4e37-aecc-28450d119760.png)

**Haciendo la sumatoria de los 2 voltajes obtenidos podemos sacar el voltaje total**
  
![image](https://user-images.githubusercontent.com/93396250/147181778-08648d62-10ed-46ee-af40-917a516e58e8.png)

**Para obtener Ix cuando V2 = 0 simplemente calculamos la corriente en base a la fuente de 12V**
  
 ![image](https://user-images.githubusercontent.com/93834732/147179637-15024150-67e8-440b-9dcb-9a66e11b890b.png)
  
**Ix cuando V1 = 0, va a ser 0 A debido a que V1 va a esatr en cortocircuito y esto va hacer que la intensidad sea de 0.**
	
	
## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

	4.5.2 Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente
  
	4.5.3 Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente

	4.5.4 Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente
	
  
 <p align=center> Tabla 4.1 . Medición de voltaje aplicando superposición.
  
![image](https://user-images.githubusercontent.com/93396250/147180679-8025ab21-c966-4619-88c1-738e2b271084.png)


 <p align=center> Tabla 4.2. Medición de corriente aplicando superposición.
  
![image](https://user-images.githubusercontent.com/93396250/147183561-5d1899ee-b12c-4d61-95eb-301567d87710.png)



	
**CALCULO DE ERROR**
	 
![image](https://user-images.githubusercontent.com/93396250/147183469-f9c8fa25-40bc-40ee-b7c3-30cee12a86e5.png)

## 5. VIDEO

        Link del video ¨Informe de laboratorio 4¨ en donde se explica 
 
 https://youtu.be/iyJIL712wRU
 
[![Presentación Informe 1](https://img.youtube.com/vi/iyJIL712wRU/0.jpg)](https://www.youtube.com/watch?v=iyJIL712wRU)


 
## 6. CONCLUSIONES

   1. Se logró comprobar, mediante resultados prácticos en el laboratorio virtual, que en el teorema de superposición, una fuente de voltaje debe ser reemplazada por un circuito cerrado (cortocircuito) y una fuente de corriente debe sustituirse por un circuito abierto (resistencia tiende a infinito).
   
   2. En esta práctica, se pudo indentificar que el reducir o convertir un circuito complejo en uno sencillo, calculando resistencia equivalentes, tanto en serrie y paralelo, facilita la resolución del mismo, ya sea para encontrar valores de corriente y/o voltaje, en un punto o resistencia específica.
        
   3. A través del teorema de superposición antes comprobado, se comprobo la utilidad de las fórmulas para divisor de corriente y voltaje, mismas que fueron usadas para determinar valores teóricos, posteriormente comparados con los valores medidos en el laboratorio virtual y resolviendo así la veracidad de las fórmulas antes mencionadas.
        
 
  
## 7. BIBLIOGRAFÍA

Alulema Darwin. Guías Segundo Parcial https://classroom.google.com/w/NDEyOTg4NDk2MDQx/t/all
  
MiElectrónicaFácil. (2019, diciembre 8). Teorema de Superposición. MiElectrónicaFácil.com. https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-superposicion/
  
Superposición. (s/f). Khan Academy. Recuperado el 23 de diciembre de 2021, de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition

Teorema de superposición: explicación, aplicaciones, ejercicios resueltos. (2020, enero 18). Lifeder. https://www.lifeder.com/teorema-de-superposicion/
