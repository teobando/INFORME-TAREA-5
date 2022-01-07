# INFORME TAREA 5

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

**Nombres:** Martin Coronel, Jefferson Chicaiza, Tito Obando 

**Carrera:** Electrónica y Automatizacion 

**NRC:** 10133

**1. OBJETIVOS**

*1.1 Objetivo General:* 

Entender de forma precisa los conceptos básicos en lo que se refiere a analizis de ramas, nodos, lazos y a lo que se refiere ha magnetismo y electromagnetismio mediate una lectura profunda del texto guia para aplicar en los ejercicios  propuestos.  

*1.2 Objetivos Especificos*

1. Comprender la teoria de los elementos de los cicuitos como ramas, nodos, lazos.
2. Enteder la teoria ha magnetismo y electromagnetismio 
3. Resumir mediante mapas conceptuales todos conceptos que se abarcan analizis de ramas, nodos, lazos y ha magnetismo y electromagnetismio
4. Aplicar la teoria en los ejercicios Propuestos.

**2.MARCO TEORICO(RESUMEN)**
![image](https://user-images.githubusercontent.com/94098157/148387188-139bce09-fa48-4330-9d3f-1312c43ffdd1.png)
![image](https://user-images.githubusercontent.com/94098157/148387232-a60e940e-54dd-4347-af88-c2d4e3744973.png)

**3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**

***CAPITULO N° 9***

Martin 9

Ecuaciones simultáneas en el análisis de circuitos
1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2.
75I1 + 90I2 = 15  -ec1
100I1 + 50I2 = 30  -ec2

75I1 = 15 – 90I2
I1 = (15 – 90I2)/75
Reemplazo I1 en ec2
100((15 – 90I2)/75) + 50I2 = 30  
4(5-30I2) + 50I2 = 30
20-120I2 + 50I2 = 30
-70I2 = 10
I2 = 0.143 A = 143 mA
Reemplazo I2 en ec1
75I1 + 90(-0.143) = 15
75I1 – 12.87 = 15
75I1 = 27.87
I1 = 0.371 A = 371 mA  


3. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:
-I1 + 2I2 = 4
7I1 + 3I2 = 6

![image](https://user-images.githubusercontent.com/94182617/148566845-80dfd32b-3b0b-4d3b-a84f-9e2ad6a3ab8b.png)

5. Evalúe cada uno de los determinantes:

![image](https://user-images.githubusercontent.com/94182617/148566983-dc2be276-66ce-438e-971e-f2da15fa54ae.png)

![image](https://user-images.githubusercontent.com/94182617/148567056-c53ba447-5eb6-4133-ac9d-a0ce16a82c4a.png)

7. Resuelva para I1, I2, I3 en el siguiente conjunto de ecuaciones con determinantes:
2I1 - 6I2 + 10I3 = 9
3I1 + 7I2 - 8I3 = 3
10I1 + 5I2 - 12I3 = 0

![image](https://user-images.githubusercontent.com/94182617/148567310-58f0e341-58ed-4454-b137-152a71a535b3.png)
![image](https://user-images.githubusercontent.com/94182617/148567350-04e76ff5-0fc9-479d-af04-82ba394605a3.png)

9. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.
100I1 + 50I2 = 30
75I1 + 90I2 = 15

![image](https://user-images.githubusercontent.com/94182617/148567441-b631c6a2-c9a7-4953-8f29-1f444a877275.png)
![image](https://user-images.githubusercontent.com/94182617/148567451-64330395-636c-4dfe-8462-b2c5449bbc05.png)

Método de la corriente en ramas
11. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A en la figura.

![image](https://user-images.githubusercontent.com/94182617/148567506-1a36ce0e-5265-4f52-bd1d-c7f18b50bb2b.png)

Nodo A:
Ecuación => I1 – I2 – I3 = 0
La suma de las corrientes que entran al nodo es igual a cero.

![image](https://user-images.githubusercontent.com/94182617/148567891-178d2984-edb7-4ab1-9fcd-b938a8629e7c.png)
![image](https://user-images.githubusercontent.com/94182617/148567939-a09e2f10-822f-4b4e-958c-c5cfc9f7af0c.png)
![image](https://user-images.githubusercontent.com/94182617/148567977-8ec04728-fa6e-4f2c-9690-b04921c0b2a9.png)

15. En la figura, determine el voltaje entre las terminales de la fuente de corriente (puntos A y B).

![image](https://user-images.githubusercontent.com/94182617/148568019-f5835273-4d3e-4f22-8f31-64c1f55ed6f8.png)

VAB = V2 = (R2/(R1+R2))Vs
VAB = (100/147)12
VAB = 8.16V

VAB = V3 = I3 * R3 = (100)(68) = 6.8V

I2 = (R1/(R1 + R2))Is
I2 = (47/147)100
I2 = 31.97 mA

VAG = V2 = -(31.97mA)(100) = -3.197
VAB = VAG - VBG = -3.197 - 6.8 = -9.997 V

VAB = 8.16 + (-9.997) = -1.87 V

Método de la corriente en lazos
17. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura.

![image](https://user-images.githubusercontent.com/94182617/148569239-ceaa8c0f-7335-41de-8fc7-673f4875a7aa.png)

![image](https://user-images.githubusercontent.com/94182617/148569343-e0a14da1-b467-4016-aecd-b626fddd3cc3.png)


Tito 10 

19.Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura
9-28.
![image](https://user-images.githubusercontent.com/94098157/148310211-4c193690-612a-4e1f-8189-b94621f178c0.png)
![image](https://user-images.githubusercontent.com/94098157/148310249-466fe389-eeeb-460a-b64e-74f3ff671dd4.png)

21.Resuelva para las corrientes de lazo en la figura 9-29 con su calculadora.
![image](https://user-images.githubusercontent.com/94098157/148313700-f92f7914-954c-4180-b961-54cb977ff5e7.png)
![image](https://user-images.githubusercontent.com/94098157/148313745-b7c5b087-a16a-4e0f-945d-403ba902cbff.png)

23.Determine el voltaje entre las terminales del puente abierto, A y B, en la figura 9-30.
![image](https://user-images.githubusercontent.com/94098157/148315831-42439fe9-7496-4779-9f7f-735b9bb21f3e.png)
![image](https://user-images.githubusercontent.com/94098157/148317286-fd5e7eea-a8f8-45da-853c-8e284d649197.png)

25.Escriba las ecuaciones de lazo en la forma estándar para el circuito puente T mostrado en la figura 9-31.
![image](https://user-images.githubusercontent.com/94098157/148318449-d34ee840-cd19-48ee-9291-127c8a718653.png)
![image](https://user-images.githubusercontent.com/94098157/148319855-d9d9401a-abe3-409b-a4cb-d8e11b8b5afb.png)

27.¿Cuáles son los valores de corriente de rama en la figura 9-32? En cada rama, muestre la dirección real
de la corriente.
![image](https://user-images.githubusercontent.com/94098157/148320593-0e125181-325c-41bf-8c7e-93e5d30ef72e.png)
![image](https://user-images.githubusercontent.com/94098157/148320769-52416ec3-7291-4125-8ebe-94198563724b.png)

29.Use el análisis de nodos para determinar el voltaje en los puntos A y B con respecto a tierra en la figura
9-33.
![image](https://user-images.githubusercontent.com/94098157/148384826-cb1cba00-b6f3-4cca-ad0f-7e538107be85.png)
![image](https://user-images.githubusercontent.com/94098157/148384881-d70d4441-7d5c-4acd-951c-6a8ad1e62dfe.png)

31.Use el análisis de nodos, el de lazos, o cualquier otro procedimiento para determinar las corrientes y
los voltajes en cada nodo desconocido en la figura 9-35.

![image](https://user-images.githubusercontent.com/94098157/148552650-bdef12a7-2f12-4b99-ad03-eb121a2ed3ad.png)
![image](https://user-images.githubusercontent.com/94098157/148555620-6c723055-0211-49d5-89ce-6fdbd9291480.png)

***CAPITULO N° 10***

1. El área de sección transversal de un campo magnético se incrementa, pero el flujo no cambia. ¿La densidad de flujo aumenta o disminuye?

La densidad del flujo magnético se reduce a medida que aumenta la distancia.

3. ¿Cuál es el flujo en un material magnético cuando la densidad de flujo es de 2500   106 T y el área de sección transversal mide 150 cm2?

![image](https://user-images.githubusercontent.com/84757114/148374433-0d389575-b594-408d-9ce7-7301c149d4e6.png)

5. Un imán permanente muy fuerte tiene un campo magnético de 100,000 mT. Exprese esta densidad de flujo en gauss. 

![image](https://user-images.githubusercontent.com/84757114/148374486-aad4f53c-ae66-4a8d-9098-b874250652af.png)

7. ¿Cuál es la permeabilidad relativa de un material ferromagnético cuya permeabilidad absoluta es de 750   106 Wb/At·m?

![image](https://user-images.githubusercontent.com/84757114/148374547-b51ad481-8759-4ff3-8061-b33f12e2f6e7.png)

9. ¿Cuál es la fuerza magnetomotriz en una bobina de 50 vueltas de hilo cuando hay 3 A de corriente a través de él?

![image](https://user-images.githubusercontent.com/84757114/148374577-1967c34f-2b03-4b05-9725-57f8769a0321.png)

11. (a) ¿Qué fuerza mueve el émbolo de imán cuando se activa un solenoide? (b) ¿Qué fuerza hace que el émbolo de imán regrese a su posición de reposo?

* Es que la magnetización llega a cambiar drásticamente, haciendo que se produzca una reacción física molecular, atraviesa mayor flujo magnético al pasarlo por arriba.
* Cuando una corriente eléctrica fluye a través de un alambre conductor, éste genera un campo magnético cuyos polos están determinados por la dirección del flujo de la corriente en el embobinado.
* Si la corriente que circula por el embobinado se incrementa a tal grado que el contenedor queda completamente saturado, la fuerza de empuje del solenoide caerá abruptamente, incrementando a su vez la temperatura del embobinado.

13. ¿Qué ocasiona que la aguja instalada en un movimiento de d’Arsonval se deflexión cuando circula corriente a través de la bobina?

![image](https://user-images.githubusercontent.com/84757114/148374664-3bbfda2e-1ca5-4c19-8668-a25f893830f4.png)

15. ¿Cómo se puede cambiar la densidad de flujo en la figura 10-44 sin alterar las características físicas del núcleo?

![image](https://user-images.githubusercontent.com/84757114/148374729-b68b1aaa-2aa0-4d28-8b72-0c26895f3271.png)

![image](https://user-images.githubusercontent.com/84757114/148374774-daec3a15-bcb3-4d7f-b3d2-5ea60ff4ed49.png)


17. Determine a partir de las curvas de histéresis mostradas en la figura 10-45 qué material tiene más retentividad.

![image](https://user-images.githubusercontent.com/84757114/148374851-60d54f1a-2c88-4bdf-81bb-611cdb709f52.png)
![image](https://user-images.githubusercontent.com/84757114/148374869-7ba82b36-3bad-4f36-b047-53b402a3fd88.png)

19. ¿Cuáles son los tres factores que determinan el voltaje en un conductor que se mueve en dirección perpendicular al campo magnético?

Por tanto, para que aparezca una fuerza electromotriz (fem) inducida debe variar el flujo del campo magnético a través de la superficie delimitada por el conductor.
Se deduce que hay tres formas de variar el flujo del campo magnético: variar el módulo del campo, la superficie que lo atraviesa o el ángulo que forman ambos.

21. ¿Cómo complementa la ley de Lenz a la ley de Faraday?

La ley que explica esta interacción entre la fuerza electromotriz inducida y el campo magnético es la Ley de Faraday
   
![image](https://user-images.githubusercontent.com/84757114/148376343-64b0225c-3272-43f4-bfe0-175046d69ead.png)

En donde Φm es el flujo del campo magnético. Por tanto, para que aparezca una fuerza electromotriz (fem) inducida debe variar el flujo del campo magnético a través de la superficie delimitada por el conductor. De la definición de flujo:

Se deduce que hay tres formas de variar el flujo del campo magnético: variar el módulo del campo, la superficie que lo atraviesa o el ángulo que forman ambos.

**3.VIDEO**

**4.CONCLUSIONES**

1. Comprender la teoria es la base para aplicar los conceptos en la resolución de problemas, especialmente en el funcionamiento de los circuitos en serie y paralelo esto es muy importante dado que el analisis de ramas, nodos, lazos funiconan en base s alo mencioando. 
2. Los conceptos de analizis de ramas, nodos y lazos permiten calcular voltaje, corriente y resistencia de cualquier parte del circuito.
3. El analisis de ramas, nodos y lazos permiten calcular de forma precisa la corriente y voltaje de mallas y nodos.
4. En cuanto al electronmagnetismo cocimos la gran relacion entre el campó magnetico y electrico. 

**5.BIBLIOGRAFÍA**

Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION.
