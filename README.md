# Informe-Tarea-1-3P
 
# 1. OBJETIVOS #

**Objetivo General**

Analizar propiedades eléctricas y características de los inductores y su comportamiento en disposiciones de circuitos y corriente a traves de el estudio del capitulo 13 y su aplicación en ejercicio propuestos con el fin de tener una base para la revisión del capitulo 14 donde se hablará de los transformadores los cuales se basan en el principio de inductancia mutua.

**Objetivos Específicos**

- Describir como se construyen y las características básicas de un inductor, ademas de los varios tipos de inductores que existen.
- Analizar circuitos de inductores colocados en serie y paralelo, ya sean de cd o ca. 
- Explicar de manera detallada la definición de la inductancia mutua y cuales son sus características. 
- Describir los diferentes tipos de transformadores que existen y localizar sus fallas.
- Analizar que es una carga reflejada en un transformador y cual es la forma en la que los mismos reducen e icrementan el voltaje.
- Comprender la igualación de impedancias con transformadores y el efecto de una carga resistiva mediante un devano secundario
# 2. MARCO TEÓRICO #


**CAPITULO 13**

[![mapa-1314.jpg](https://i.postimg.cc/8k7TDY4b/mapa-1314.jpg)](https://postimg.cc/grbCHNfw)

**CAPITULO 14**

![png (2)](https://user-images.githubusercontent.com/93739242/153541575-872e36d1-c2bb-49ae-87de-9216645b1dd7.png)


![png (3)](https://user-images.githubusercontent.com/93739242/153541608-c3214bc8-990c-422f-b90e-f24b26ca9418.png)


# 3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS #


**CAPITULO 13**

**1. Convierta los siguientes valores en milihenries:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=a)1H%5Cleftrightarrow%201000mH%20%5C%5C%0Ab)250%5Cmu%20H%20%5Cleftrightarrow%200.025mH%20%5C%5C%0Ac)10%5Cmu%20H%5Cleftrightarrow%200.01mH%5C%5C%0Ad)0.0005%20H%5Cleftrightarrow%200.5mH%5C%5C">


**3.¿Cuál es el voltaje en una bobina cuando di/dt = 10 mA/micro s y L = 5 micro H?**

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7Bind%7D%3DL(%5Cfrac%7Bd_%7Bi%7D%7D%7Bd_%7Bt%7D%7D)">

Reemplazando datos:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7Bind%7D%3D5%20%5Cmu%20H(%5Cfrac%7B10mA%7D%7B%5Cmu%20s%7D)%3D50mV">


**5. La corriente a través de una bobina de 100 mH cambia a razón de 200 mA/s. ¿Cuánto voltaje se induce en la bobina?**
**El voltaje inducido a través de la bobina es:**

![lagrida_latex_editor](https://user-images.githubusercontent.com/93739242/153422786-05cfbbc2-4e9c-494a-b04f-b12a2cc07bef.png)

**7. ¿Qué cantidad de energía se guarda en un inductor de 4.7 mH cuando la corriente es de 20 mA?**
**La cantidad de energía que se guarda en el inductor es:**

![lagrida_latex_editor (1)](https://user-images.githubusercontent.com/93739242/153429267-db38e1ae-8c71-4ce9-b4a6-fae084ffa88e.png)

**9. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 está enrollado sobre un núcleo de hierro (permeabilidad relativa = 150) y el inductor 1 está enrollado sobre un núcleo de acero al bajo carbono (permeabilidad relativa = 200).**

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L%3D%5Cfrac%7BN%5E%7B2%7D%5Cmu%20A%7D%7Bl%7D">

Reemplazando datos y comparando:

En inductor 1:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L%3D%5Cfrac%7B(200)%5E%7B2%7D%5Cmu%20A%7D%7Bl%7D">

En inductor 2:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L%3D%5Cfrac%7B(150)%5E%7B2%7D%5Cmu%20A%7D%7Bl%7D">

Comparando:

El inductor 2 tiene tres cuartos de la inductancia del inductor 1.

**11. Se conectan cinco inductores en serie. El valor más bajo es de 5 mH. Si el valor de cada inductor es el doble del valor precedente, y si los inductores se conectan en orden de valores ascendentes, ¿cuál es la inductancia total?**

Inductancias:

[![01.png](https://i.postimg.cc/wxZqC3TT/01.png)](https://postimg.cc/WtmcrNkQ)

Suma de las inductancias:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D150%20%5Cmu%20H">

**13. Determine la inductancia total en la figura 13-44.**
 
 ![image](https://user-images.githubusercontent.com/93739242/153436082-45cf6404-a6d9-4782-a38f-be28a8e4b742.png)


![lagrida_latex_editor (2)](https://user-images.githubusercontent.com/93739242/153429305-26e6aef0-da0b-4f21-a807-a2314ecf9902.png)

**15. Determine la inductancia total en paralelo para las siguientes bobinas dispuestas en paralelo: 75 μH, 50 μH, 25 μH, y 15 μH.**

![lagrida_latex_editor (3)](https://user-images.githubusercontent.com/93739242/153429450-3f1a2f32-508b-4dda-88cd-ba034fcbf073.png)

**17. Determine la inductancia total de cada circuito mostrado en la figura 13-46.**

[![17.png](https://i.postimg.cc/qBLYK5Wf/17.png)](https://postimg.cc/148JhJ9M)

En a:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D%5BL_%7B3%7D%7C%7C%20L_%7B2%7D%5D%2BL_%7B1%7D%3D%5B5%7C%7C10%5D%2B1%3D4.33%20H">

En b:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D%5BL_%7B2%7D%2B%20L_%7B3%7D%5D%7C%7CL_%7B1%7D%3D%5B50%2B50%5D%7C%7C100%3D%5B100%7C%7C100%5D%3D50mH">

En c:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D%5BL_%7B1%7D%7C%7CL_%7B2%7D%7C%7CL_%7B3%7D%5D%3D%5B100%7C%7C400%7C%7C200%5D%3D57.14%20%5Cmu%20H">

**19. Determine la constante de tiempo para cada una de las siguientes combinaciones RL dispuestas en serie:**

En a:

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=%5Ctau%20%3D%5Cfrac%7BL%7D%7BR%7D">

En a:

Reemplazando datos en la formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=%5Ctau%20%3D%5Cfrac%7B0.0001%20H%7D%7B100%20%20%5COmega%20%7D%3D0.000001%20s%3D%201%20%5Cmu%20s">


En b:

Reemplazando datos en la formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=%5Ctau%20%3D%5Cfrac%7B10%20%5Cmu%20H%7D%7B4.7%20k%20%5COmega%20%7D%3D2.127%5Cmu%20s">

En c:

Reemplazando datos en la formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=%5Ctau%20%3D%5Cfrac%7B3%20H%7D%7B1.5%20M%20%5COmega%20%7D%3D2%5Cmu%20s">


**21. En el circuito de la figura 13-48, al inicio no hay corriente. Determine el voltaje en el inductor en los siguientes instantes tras de que se cierra el interruptor: (a) 10μs (b) 20μs (c) 30μs (d) 40μs (e) 50μs**
 
 ![image](https://user-images.githubusercontent.com/93739242/153436055-38624a75-0545-4155-bcde-df44554aa553.png)


![lagrida_latex_editor (4)](https://user-images.githubusercontent.com/93739242/153429628-697e8229-e367-4ff1-9f8b-f4cd7286d31d.png)


**23. Repita el problema 21 para los siguientes instantes:**

![lagrida_latex_editor (5)](https://user-images.githubusercontent.com/93739242/153429699-978f49b4-bf48-4ee4-9c0e-f0116af67c1f.png)

**25. En la figura 13-48, ¿en qué momento luego de que se cierra el interruptor el voltaje llega a 5 V?**

[![25.png](https://i.postimg.cc/50mPwX75/25.png)](https://postimg.cc/qhzXrvdg)

11 micro segundos


**27. Determine la constante de tiempo para el circuito de la figura 13-50.**

[![27.png](https://i.postimg.cc/3NSncPHd/27.png)](https://postimg.cc/N2X6yCFc)


0.722 micro segundos

**29. Para el circuito de la figura 13-50, suponga que el interruptor estuvo cerrado por más de 5t y se abre. ¿Cuál es la corriente en el inductor 1.0 ms después de que se abre el interruptor?**

![image](https://user-images.githubusercontent.com/93739242/153435967-89eb09bd-061f-47f9-bb7b-6c0115712b30.png)


![lagrida_latex_editor (6)](https://user-images.githubusercontent.com/93739242/153429772-4c277f45-a48b-47bf-9611-d79bfb1362d8.png)

![lagrida_latex_editor (7)](https://user-images.githubusercontent.com/93739242/153429802-52d8b28b-d002-4574-9f77-afc8342c145d.png)

![lagrida_latex_editor (8)](https://user-images.githubusercontent.com/93739242/153429831-cc35207b-0123-4eb8-98ae-afb2dbc5c949.png)

![lagrida_latex_editor (9)](https://user-images.githubusercontent.com/93739242/153429856-4abdcb70-2868-435a-8102-afece86cc1e3.png)

![lagrida_latex_editor (10)](https://user-images.githubusercontent.com/93739242/153429897-76f286d0-ca1d-4843-ba18-f56a008e9e6a.png)

![lagrida_latex_editor (11)](https://user-images.githubusercontent.com/93739242/153429992-207b9660-1a80-415b-9f0e-a87f37f050fd.png)

![lagrida_latex_editor (12)](https://user-images.githubusercontent.com/93739242/153430021-83a2927d-b76a-415f-bbf1-7c0e74698a01.png)

![lagrida_latex_editor (13)](https://user-images.githubusercontent.com/93739242/153430058-57e210de-71a2-486d-876f-10de71575528.png)

![lagrida_latex_editor (14)](https://user-images.githubusercontent.com/93739242/153430077-50452055-955c-486f-8d55-b2449a9cd29f.png)

![lagrida_latex_editor (15)](https://user-images.githubusercontent.com/93739242/153430091-7f53443b-df19-48f7-a5cd-614b66e3a202.png)

![lagrida_latex_editor (16)](https://user-images.githubusercontent.com/93739242/153430124-92e303ee-39e8-438c-a980-48c3059e6ae1.png)

![lagrida_latex_editor (17)](https://user-images.githubusercontent.com/93739242/153430148-2f399d5e-9ab9-4e83-9ae4-06c8949d752a.png)

![lagrida_latex_editor (18)](https://user-images.githubusercontent.com/93739242/153430164-53d8765b-9e5a-44e3-8533-2e3bcd9b6ea6.png)


**31. Determine la reactancia total para cada circuito de la figura 13-47 cuando se aplica voltaje a una frecuencia de 400 Hz.**
 
 ![image](https://user-images.githubusercontent.com/93739242/153435651-bdde6b16-d716-40d0-a711-edd83047cff0.png)

![image](https://user-images.githubusercontent.com/93739242/153435693-a7510bdd-3ea2-4958-a969-4c9fae769c37.png)


 ![lagrida_latex_editor](https://user-images.githubusercontent.com/93739242/153431576-94cd2d87-4b5c-4247-83aa-040ae92c84a9.png)



![lagrida_latex_editor (19)](https://user-images.githubusercontent.com/93739242/153431590-52c11644-9e3a-4588-bf1c-f711ed534d26.png)

![image](https://user-images.githubusercontent.com/93739242/153435896-11d11399-51f6-4c0a-8b03-39ff5cb29208.png)


![lagrida_latex_editor (20)](https://user-images.githubusercontent.com/93739242/153431630-cbc522e1-8bbd-4911-ae61-2757905c5029.png)

![lagrida_latex_editor (21)](https://user-images.githubusercontent.com/93739242/153431658-91751ab1-a818-4196-8d52-b1a547275aca.png)

![image](https://user-images.githubusercontent.com/93739242/153435597-3e666bdc-9fad-4db5-b947-9f9eb1df8b4e.png)

 
![lagrida_latex_editor (22)](https://user-images.githubusercontent.com/93739242/153431684-a0978121-0224-4bd1-99ad-7b5df172b535.png)

![lagrida_latex_editor (23)](https://user-images.githubusercontent.com/93739242/153431724-c13d0c40-20d2-419f-8197-0f752026d8c8.png)

 ![image](https://user-images.githubusercontent.com/93739242/153435557-6868cb52-289b-4fa3-a45d-672a4b3c4966.png)


![lagrida_latex_editor (24)](https://user-images.githubusercontent.com/93739242/153431751-9dfdbf21-fe35-4580-85d3-8c17bbc9e118.png)

![lagrida_latex_editor (25)](https://user-images.githubusercontent.com/93739242/153431774-0ad3208f-373a-4483-ba60-983a5c4f435f.png)
 
 ![image](https://user-images.githubusercontent.com/93739242/153435507-f43001c4-1734-41c8-96d4-20f41ea6b40c.png)


![lagrida_latex_editor (26)](https://user-images.githubusercontent.com/93739242/153431802-0463b5a6-fc95-4a8d-a0d3-fd7ce2b0aa85.png)

![lagrida_latex_editor (27)](https://user-images.githubusercontent.com/93739242/153431834-9b2d407c-2a04-491d-a3a4-8e62cb1fe56f.png)

 ![image](https://user-images.githubusercontent.com/93739242/153435479-f974c5d3-364a-4c3b-8c20-b20c5b895d2a.png)


![lagrida_latex_editor (28)](https://user-images.githubusercontent.com/93739242/153431865-bf1a94a3-bb39-4a40-a869-710fc72cda3b.png)

![image](https://user-images.githubusercontent.com/93739242/153435459-fbe6bc23-2574-47b4-8bb2-db224980c7dd.png)

 
![lagrida_latex_editor (29)](https://user-images.githubusercontent.com/93739242/153431892-3c48e7d7-122a-408b-9424-ec76c4b540ce.png)

![lagrida_latex_editor (30)](https://user-images.githubusercontent.com/93739242/153431970-08c34c95-9472-4402-b11c-e5aecb9719d5.png)

**33. ¿Qué frecuencia producirá una corriente rms total de 500 mA en cada circuito de la figura 13-47 con un voltaje de entrada rms de 10 V?**

[![33.png](https://i.postimg.cc/PqQb7BWT/33.png)](https://postimg.cc/HJj7cvvh)

***Fórmula que se usara:***

<img src="https://chart.apis.google.com/chart?cht=tx&chl=x_%7BL%7D%3D2%20%5Cpi%20fL%20%20%5Cleftrightarrow%20f%3D%5Cfrac%7Bx_%7BL%7D%7D%7B2%20%5Cpi%20L%7D">


***Hallar xl***

Fórmula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=I_%7Brms%7D%3D%5Cfrac%7BV_%7Bms%7D%7D%7Bx_%7BL%7D%7D%20%20%5Cleftrightarrow%20%20x_%7BL%7D%3D%5Cfrac%7BV_%7Bms%7D%7D%7BI_%7Brms%7D%7D">

Reemplazando en la fórmula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=x_%7BL%7D%3D%5Cfrac%7B10V%7D%7B0.5A%7D%3D20%20%20%5COmega%20">

***En a:***

**Inductancia equivalente:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D%5BL_%7B1%7D%7C%7CL_%7B2%7D%5D%2B%5BL_%7B3%7D%7C%7CL_%7B4%7D%5D%3D%5B100%7C%7C50%5D%2B%5B60%7C%7C40%5D%3D57.33mH">

**Reemplazando en la formula de la frecuencia:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=f%3D%5Cfrac%7B20%20%5COmega%20%7D%7B2%20%5Cpi%20(57%2C3mH)%7D%3D55.51Hz">


***En b:***

**Inductancia equivalente:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D(%5BL_%7B3%7D%2BL_%7B4%7D%5D%7C%7C%5BL_%7B1%7D%2BL_%7B2%7D%5D)%3D%5B6%5D%7C%7C%5B12%5D%3D4mH">

**Reemplazando en la formula de la frecuencia:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=f%3D%5Cfrac%7B20%20%5COmega%20%7D%7B2%20%5Cpi%20(4mH)%7D%3D795.7Hz">

***En c:***

**Inductancia equivalente:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7Btotal%7D%3D%5B(%5BL_%7B2%7D%2BL_%7B5%7D%5D%7C%7C%5BL_%7B4%7D%2BL_%7B3%7D%5D)%5D%2BL_%7B1%7D%3D(%5B4%5D%7C%7C%5B2%5D)%2B4%3D5.33mH">

**Reemplazando en la formula de la frecuencia:**

<img src="https://chart.apis.google.com/chart?cht=tx&chl=f%3D%5Cfrac%7B20%20%5COmega%20%7D%7B2%20%5Cpi%20(5.33mH)%7D%3D597.2Hz">



**35. Determine IL2 en la figura 13-52.**

 [![35.png](https://i.postimg.cc/CKhmHjtv/35.png)](https://postimg.cc/k2HQ7t78)
 
 26.1 mA
 
**CAPITULO 14**

**1. ¿Cuál es la inductancia mutua cuando k = 0.75, L1 = 1 micro H, y L2 = 4 micro H?**

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7BM%7D%3Dk%5Csqrt%7BL_%7B1%7DL_%7B2%7D%7D">


Reemplazar datos:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=L_%7BM%7D%3D(0.75)%5Csqrt%7B(1%20%5Cmu%20H)(4%5Cmu%20H)%7D%3D1.5%5Cmu%20H">

**3. ¿Cuál es la relación de vueltas de un transformador con 250 vueltas en el primario y 1000 en el secundario? ¿Cuál es la relación de vueltas cuando el devanado primario tiene 400 vueltas y el secundario 100?**

Formula que se usara:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%20%7BN_%7Bsec%7D%7D%7BN_%7Bpri%7D%7D">

Cuando inicia con 250 vueltas y termina en 1000:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%7B1000%7D%7B2500%7D%3D4">

Cuando inicia con 400 vuelts y termina con 100:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%7B100%7D%7B400%7D%3D0.25">


**5. Para cada transformador de la figura 14-42, trace el voltaje secundario que muestre su relación con el voltaje primario. Indique también la amplitud.**

![image](https://user-images.githubusercontent.com/93739242/153435100-d39050fa-6c02-4f43-90b9-0ed32ac73eb1.png)

 
(a) Las bobinas están en la misma dirección, es decir, el primario y el secundario los voltajes están en fase. La relación de vueltas es de 10, lo que significa que el voltaje secundario tiene un rms 10 veces mayor que la tensión de entrada (100V). 

![image](https://user-images.githubusercontent.com/93739242/153435217-91819ab3-7222-4a48-b504-88aa4cf8cd11.png)


(b) Las bobinas se enrollan en la dirección opuesta, lo que significa que los voltajes secundarios y primarios están fuera de fase en 180 grados. La relación de vueltas es 2, lo que significa que el voltaje en el secundario será el doble de la tensión en el primario (100V)

![image](https://user-images.githubusercontent.com/93739242/153435270-e5e9bfe7-0904-451a-bfa4-e5a84f58a6e2.png)


(c) Las bobinas se enrollan en la dirección opuesta, lo que significa que los voltajes secundarios y primarios están fuera de fase en 180 grados. El voltaje en el secundario será una quinta parte de la tensión en la primaria (20V)

![image](https://user-images.githubusercontent.com/93739242/153435320-e3c170be-ba68-417f-85d3-c8dcb0f5a1a4.png)


**7. El devanado primario de un transformador tiene 120 V de ca a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 5**

![lagrida_latex_editor (31)](https://user-images.githubusercontent.com/93739242/153433446-0eab9620-d037-4190-b8eb-367074a0f6f6.png)

**9. Para reducir 120 V a 30 V, ¿cuál debe ser la relación de vueltas?**

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%20%7BV_%7Bsec%7D%7D%7BV_%7Bpri%7D%7D">

Reemplazando datos:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%7B30V%7D%7B120V%7D%3D0.25">

**11. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 0.1 para obtener un voltaje secundario de 6 V de ca?**

Fórmula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Cfrac%7BV_%7Bsec%7D%7D%7BV_%7Bprin%7D%7D%20%5Cleftrightarrow%20V_%7Bprin%7D%3D%5Cfrac%7BV_%7Bsec%7D%7D%7Bn%7D">

Reemplazando en la fórmula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7Bprin%7D%3D%5Cfrac%7B6V%7D%7B0.1%7D%3D60V">

**13. Determine las lecturas de medidor no especificadas en la figura 14-44**

 ![image](https://user-images.githubusercontent.com/93739242/153435011-400467e8-259c-421a-a1de-862faf923cf8.png)


![lagrida_latex_editor (32)](https://user-images.githubusercontent.com/93739242/153433515-54284658-4189-4628-8d07-d35e7ef20cd4.png)

![image](https://user-images.githubusercontent.com/93739242/153435039-006ad465-7243-49af-b576-9af55628ccbb.png)


![lagrida_latex_editor (33)](https://user-images.githubusercontent.com/93739242/153433531-b28fe6af-3ea4-4cc1-9907-98cfa2127b3c.png)

**15. Determine las siguientes cantidades en la figura 14-46.**

**(a) Corriente primaria** 

**(b) Corriente secundaria** 

**(c) Voltaje secundario**

 **(d) Potencia en la carga**

 ![image](https://user-images.githubusercontent.com/93739242/153434906-0e80ece7-b422-43a7-b9f7-492f1701baf8.png)


(a)

![lagrida_latex_editor (34)](https://user-images.githubusercontent.com/93739242/153433563-f11fece9-7f9f-4394-a10e-ec1c7ab7033f.png)

(b)

![lagrida_latex_editor (35)](https://user-images.githubusercontent.com/93739242/153433632-de80bfe8-961f-403e-9a16-aaf7068f54e5.png)

(c)

![lagrida_latex_editor (36)](https://user-images.githubusercontent.com/93739242/153433660-e54752f3-39d8-41b3-ba96-8a661a55a003.png)

(d)

![lagrida_latex_editor (37)](https://user-images.githubusercontent.com/93739242/153433688-3d65d6a8-61b9-4382-9555-5e706dc8b8d0.png)

**17. ¿Cuál debe ser la relación de vueltas en la figura 14-48 para reflejar 300 Æ en el circuito primario?**

[![17.png](https://i.postimg.cc/J0nfTf22/17.png)](https://postimg.cc/njySrPZ4)

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Csqrt%7B%5Cfrac%20%7BR_%7BL%7D%7D%7BR_%7Bpri%7D%7D%7D">

Reemplazando datos:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=n%3D%5Csqrt%7B%5Cfrac%7B1000%20%5COmega%20%7D%7B300%20%5COmega%20%7D%7D%3D1.825W">

**19. En la figura 14-49, ¿cuál es la potencia máxima que puede ser suministrada al altavoz de 4 ohms?**

[![19.png](https://i.postimg.cc/pL8g1YsR/19.png)](https://postimg.cc/zyztyWmc)

**21. En cierto transformador, la potencia de entrada al primario es de 100 W, Si se pierden 5.5 W en las resistencias de devanado, ¿cuál es la potencia de salida hacia la carga, omitiendo cualesquiera otras pérdidas?**

![lagrida_latex_editor (38)](https://user-images.githubusercontent.com/93739242/153433731-e0452d2e-7df3-4788-8fc7-b7b62bfbd101.png)

**23. Determine el coeficiente de acoplamiento de un transformador en el cual un 2% del flujo total generado en el primario no pasa a través del secundario.**

El coeficiente de acoplamiento es el porcentaje del campo magnético generado por el primario eso pasa por la secundaria. Si el 2% no pasa por el medio secundario, el 98% restante debe pesar por él. Por lo tanto, el coeficiente de acoplamiento es k=0.98

**25. ¿Qué potencia nominal en kVA se requiere para un transformador que debe manejar una corriente máxima de 10 A a través de la carga con un voltaje secundario de 2.5 kV?**

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=P%3DIV">

Reemplazando datos:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=P%3D(10A)(2.5kV)%3D25kVA">

**27. Determine cada uno de los voltajes desconocidos indicados en la figura 14-51.**

[![27.png](https://i.postimg.cc/05BFkH39/27.png)](https://postimg.cc/CdbmJJS2)

Formula:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7Bsec%7D%3D(%5Cfrac%20%7BN_%7Bsec%7D%7D%7BN_%7Bpri%7D%7D)(V_%7Bpri%7D)">


En V1:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7B1%7D%3D(%5Cfrac%20%7B50%7D%7B500%7D)(115V)%3D11.5V">

En V2:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7B2%7D%3D(%5Cfrac%20%7B100%7D%7B500%7D)(115V)%3D23V">

En V3:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7B3%7D%3D(%5Cfrac%20%7B100%7D%7B500%7D)(115V)%3D23V">

En V4:

<img src="https://chart.apis.google.com/chart?cht=tx&chl=V_%7B4%7D%3D(%5Cfrac%20%7B200%7D%7B500%7D)(115V)%3D46V">

**29. Encuentre el voltaje secundario para cada uno de los autotransformadores mostrados en la figura 14-53.**

 ![image](https://user-images.githubusercontent.com/93739242/153434878-bad3b521-8ae7-4592-b2ab-e594f46571af.png)

 
(a)

![lagrida_latex_editor (39)](https://user-images.githubusercontent.com/93739242/153433766-cb54b2be-0849-4d1e-8881-db499b684fda.png)

(b)

![lagrida_latex_editor (40)](https://user-images.githubusercontent.com/93739242/153433791-ec4755ca-ec45-4022-8f34-c48e03dbba73.png)

**31. Para el transformador cargado con tomas que muestra la figura 14-55, determine lo siguiente:** 

**(a) Todos los voltajes y corrientes presentes en la carga** 

**(b) La resistencia reflejada en el primario**

 ![image](https://user-images.githubusercontent.com/93739242/153434854-81f9ad11-969b-4c6e-8efd-67beaa9d8ec5.png)


(a)

![lagrida_latex_editor (41)](https://user-images.githubusercontent.com/93739242/153433818-05e0922a-a9f1-473e-be13-1245c02a88bb.png)

(b)

![lagrida_latex_editor (42)](https://user-images.githubusercontent.com/93739242/153433844-80c4a595-82a1-46c0-99db-e689aa579a07.png)

**33. ¿Qué es probable que suceda si el devanado primario de un transformador se pone en cortocircuito?**

La corriente primaria se extrae y se quema la fuente si no se proteje el primario con un fusible


# 4. VIDEO #

https://www.youtube.com/watch?v=P0b_sMZWU0A

# 5. CONCLUSIONES #

- El análisis de los circuitos con los  inductores dependen de la fuente de voltaje, ya sea en CD o AC, los inductores cambian sus caracteísticas, cuando mas sea la corriente que lo atraviesa mas sera su campo magnético, es asi como actua un inductor.

- Las coracterísticas de un inductos son: longuitud del devanado, Area de la seccion transversal, material del núcleo, número de vueltas de la espira, es asi como un inductor basico se compone, existen varios tipos de inductores, como los inductores con recubrimiento como: plasticos, resina, metal; tambien existen inductores de altas frecuencias con mayor tamaño y se usan en los transformadores de energía eléctrica.

- El análisis de los circuitos en serie y paralelo con inductores se los realiza calculando la inductancia equivalente, si es paralelo es la suma de sus inversos al inverso de su suma, si es en serie se suman sus inductancias, para las fuentes de CA se usa la reactancia inductiva  y la ley de ohm para este tipo de fuente, si el análisis en fuentes CD, en estas fuentes no existe el voltaje inducido si no un divisor de voltaje queque provoca la resistencia del devanado y la inductancia se comporta como un corto y se puede calcular la constante de tiempo que determina el intervalo fijo de la inductancia a la resistencia.

# 6. BIBLIOGRAFÍA #

- Floyd, T. L. (2007). Principios de circuitos eléctricos. (8.ª ed.). México: PEARSON EDUCACIÓN.
- Valchev, V. C., & Van den Bossche, A. (2018). Inductors and transformers for power electronics. CRC press.
