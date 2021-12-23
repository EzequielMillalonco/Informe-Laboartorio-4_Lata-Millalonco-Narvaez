# Informe-Laboratorio-4

## 1. OBJETIVOS
 
        General: 
        
Analizar y comprobar de forma experiemntal - práctica y teorica el teorema de superposición, mediante análisis de circuitos en serie - paralelo determinando el método más factible de resolución.



        Específicos: 
 
1. Reconocer circuito abierto o cerrado, a reemplazar en fuente de voltaje y/o corriente, analizando el valor de su resistencia interna.
        
2. Deducir e identificar la manera de convertir circuitos en serie - paralelo complejos en sencillos.
        
3. Comprobar el teorema de superposición y la funcionabilidad de las fórmulas para divisor de corriente y voltaje, mediante la comparación de resultados teóricos y los encontrados en el laboratorio virtual THINKERCAD.

## 2. MARCO TEÓRICO


## 3. EXPLICACIÓN DEL PROCEDIMIENTO

Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan.

![Screenshot 2021-12-22 202621](https://user-images.githubusercontent.com/93826527/147173683-e3daad9f-4271-417d-8d65-f516267376fa.png)


La resistencia de 470 (Ω) no se toma en cuenta para el cálculo del voltaje VA, ya que va a tener el mismo voltaje que la resistencia de 820 (Ω), esto debido a que se encuentran en paralelo y el voltaje VA requerido es el que pasa por la resistencia de 820 (Ω).

Primero procedemos a determinar que la fuente de voltaje de 20 (V), va a ser reemplazad por un cortocircuito, es decir un circuito cerrado. Posterior a eso se debe encontrar, la resistencia equivalente entre las resistencias de 1 (kΩ) y 2.2 (kΩ). 

R12= (1000*2200)/3200 = 687.5 (Ω)

![image](https://user-images.githubusercontent.com/93826527/147174035-891e921e-aece-4a71-badc-0ba352c4a2a2.png)

Posterior a eso vamos a aplicar la fórmula de divisor de voltaje entre la resistencia R12 y R3, no se debe tomar en cuenta R4, por lo antes mencionado.

![Screenshot 2021-12-22 203308](https://user-images.githubusercontent.com/93826527/147174146-c37dcfa7-6d0d-4083-87b9-70bd56fc4a1b.png)

Va = V2 * (R3/R3+R12)

Va= -6.52 (signo negativo por la polaridad del voltaje)

Para calcular la corriente Ix, se repite lo mismo que en el anterior caso, es decir se reemplaza la fuente de 20 (V), por un circuito cerrado, posterior a eso obtengo resistencias equivalentes hasta obtener RTotal.

R12 = (1000*2200)/3200 = 687.5 (Ω)

R123 = 687.5 + 820 = 1507.5 (Ω)

RT = (1507.5*470)/(1507.5+470) = 358.29 (Ω)

Procedemos a encontrar la corriente total IT.

IT = V2/RT = 12/358.29 = 33.49 (mV)

Aplicamos la fórmula de divisor de corriente, para encontrar Ix.

Ix = IT * (R4/R4+R123) = (33.49 * 10^{-3}) * (470/(470+1507.5) = 7.95 (mA)



## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR


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
