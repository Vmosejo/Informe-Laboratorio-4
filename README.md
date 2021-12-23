# Informe-Laboratorio-4
## 1. OBJETIVOS
  ## 1.1 GENERAL
  Analizar experimentalmente el teorema de superposición mediante la elaboración del laboratorio N°4 en base a las leyes fundamentales,a su vez realizar la respectiva simulación del circuito eléctrico.
  
  ## 1.2 ESPECÍFICOS  
  * Resolver mediante el teorema de superposición el circuito eléctrico expuesto en el presente laboratorio.
  * Realizar las comparaciones necesarias entre las mediciones experimentales,mediciones mediante la simulación y el análisis matemático.
  * Comprobar los resultados obtenidos teoricamente mediante la simulacion en Tinkercad y Proteus.
## 2. MARCO TEÓRICO
### TEOREMA DE SUPERPOSICIÓN
![Untitled](https://user-images.githubusercontent.com/93666408/147167988-d2bb93ef-87e1-4efc-a01f-41721b6cb63d.jpg)
![Untitled (1)](https://user-images.githubusercontent.com/93666408/147170971-54e377f0-3e4f-430d-bff4-7996b0665da2.jpg)

## 3. EXPLICACIÓN DEL PROCEDIMIENTO
En primer lugar, armamos nuestro circuito y procedemos a identificar cada uno de sus componentes.
![circuito-L4](https://user-images.githubusercontent.com/93681159/147176618-91ba0c32-9177-4b47-8acd-1895cbf70e15.jpeg)

Un vez tengamos el circuito armado procedemos a medir el voltaje VA y la corriente Ix con las dos fuentes de voltaje conectadas. 
![image](https://user-images.githubusercontent.com/93681159/147130054-78681cb2-a315-449f-b1b2-9a9e79cb6eac.png)

Ahora procedemos a medir la corriente Ix y el voltaje Va en cada uno de los casos, cuando V1=0 y cuando V2=0.
* Voltaje Va cuando V2=0
![image](https://user-images.githubusercontent.com/93681159/147185274-0a6bdb80-9ca3-417d-875c-758ecda2f8ca.png)
* Voltaje Va cuando V1=0
![image](https://user-images.githubusercontent.com/93681159/147186307-93a63297-effb-4c64-a14d-24cbeed524b3.png)
* Corriente Ix cuando V2=0
![image](https://user-images.githubusercontent.com/93681159/147186459-fd37ff3c-c0e8-4a73-a265-9e8fadd532e0.png)
* Corriente Ix cuando V1=0
![image](https://user-images.githubusercontent.com/93681159/147186538-375fcaf5-c42b-4945-87a5-8ee43eafccff.png)
### Análisis del primer circuito
Para realizar el proceso analítico por medio del teorema de superposición procedemos a hacer “cero” la fuente de voltaje de 12 V.
![Diagrama en blanco](https://user-images.githubusercontent.com/93681159/147137068-11737dc1-47aa-42fb-abac-af5a7636b50f.jpeg)
Procedemos a realizar el análisis del nuevo circuito, en primer lugar, encontramos la resistencia equivalente para hallar la corriente total que pasa por el circuito y finalmente determinar Ix.
![Diagrama en blanco (2)](https://user-images.githubusercontent.com/93681159/147136183-1202071e-a53c-4c17-8fe5-b9b8da08159e.jpeg)
Con la resistencia equivalente procedemos a encontrar la corriente total del circuito. 
![Diagrama en blanco (1)](https://user-images.githubusercontent.com/93681159/147136042-ef4f5f70-55f2-4c98-bc5b-b6a2c02eb045.jpeg)

Finalmente procedemos a encontrar Ix
![Diagrama en blanco (3)](https://user-images.githubusercontent.com/93681159/147136752-2d404ba0-cd1a-4d0a-95e7-9b67d591e99e.jpeg)
Es importante tener en cuenta que, dado que la corriente no circula por R4, por lo tanto el valor de la corriente Ix del primer circuito es cero.
Para determinar el voltaje Va utilizamos la fórmula del divisor de voltaje, dado que no se toma en cuenta la resistencia R4, procedemos a calcular la resistencia equivalente entre R2||R3.
![Diagrama en blanco](https://user-images.githubusercontent.com/93681159/147176677-399afb6b-ffc1-470e-9d5b-13b3f3815f84.jpeg)
Una vez determinada la resistencia equivalente, aplicamos el divisor de voltaje para hallar Va
![Diagrama en blanco (5)](https://user-images.githubusercontent.com/93681159/147178036-29d71d89-9183-4c95-9a2c-01b833855b5a.jpeg)
### Análisis del segundo circuito
Para continuar con el Teorema se superposición procedemos a hacer “cero” la fuente de voltaje de 20 V.
![Diagrama en blanco (1)](https://user-images.githubusercontent.com/93681159/147137603-51b4ec8b-efc9-4fda-92ab-40ce458f4e21.jpeg)
Procedemos a realizar el análisis del segundo circuito, en primer lugar, encontramos la resistencia equivalente para hallar la corriente total que pasa por el circuito y finalmente determinar Ix.
![Diagrama en blanco (2)](https://user-images.githubusercontent.com/93681159/147138447-a4e0617d-2de5-41bc-8da9-aa6b7b91ff29.jpeg)
Con la resistencia equivalente procedemos a encontrar la corriente total del circuito.
![Diagrama en blanco (3)](https://user-images.githubusercontent.com/93681159/147138862-fb5c2c3b-d6bf-4f9b-9442-0605222ca952.jpeg)

Finalmente procedemos a encontrar Ix
![Diagrama en blanco (4)](https://user-images.githubusercontent.com/93681159/147139919-76537ef7-1720-41a9-b640-8502e70df87b.jpeg)
Para determinar el voltaje Va utilizamos la fórmula del divisor de voltaje, donde R1||R2 + R3, con estas relaciones y tomando en cuenta la dirección de la corriente usamos la fórmula del divisor de corriente.
![Diagrama en blanco (6)](https://user-images.githubusercontent.com/93681159/147178599-56b1ed70-e642-4d17-99e3-3f0256e2955c.jpeg)
Por ultimo hacemos la suma algebraica de los voltajes obtenidos en los dos circuitos analizados para encontrar el voltaje total Va que pasa por R3.

![Diagrama en blanco (7)](https://user-images.githubusercontent.com/93681159/147179138-e6978bf5-70b2-434a-8674-c4642dd91a8b.jpeg)
## Circuito en tinkercad:
### Preparamos los componentes.
![e43d6714-69c1-4676-863f-1164ece5612b](https://user-images.githubusercontent.com/93893919/147180848-0f921fac-5ae3-4328-924a-e19b76a8ad3e.jpg)
### Construimos el circuito.
![2fe42dad-25f8-49ba-8b64-cf686044ef59](https://user-images.githubusercontent.com/93893919/147180885-b617223b-8ced-45e4-ad91-9f659941c0c0.jpg)
### Medimos los valores.
![ee3ea0ee-30ac-4c31-b010-0dca7e6b459c](https://user-images.githubusercontent.com/93893919/147180938-6f54365a-28f2-45ee-a714-4f0dbfa9bef8.jpg)
### Tablas de resultados
* Tabla 4.1. Medición de voltaje aplicando superposición.
![image](https://user-images.githubusercontent.com/93681159/147183948-20d15ab3-6534-4692-8962-fdb237f034e1.png)

* Tabla 4.2. Medición de corriente aplicando superposición.
![image](https://user-images.githubusercontent.com/93681159/147184025-c17f7629-43c7-443f-8b75-de94a73c37fe.png)

## 4. CALCULO DEL ERROR
* Voltaje Va:
![Diagrama en blanco (8)](https://user-images.githubusercontent.com/93681159/147181534-a93d9822-19ee-4063-b3e3-26e342882a88.jpeg)
* Corriente Ix:
![Diagrama en blanco (9)](https://user-images.githubusercontent.com/93681159/147181690-19b9efd2-32c1-486f-9e1c-fde74a228fac.jpeg)
## 5. VIDEO
## 6. CONCLUSIONES
## 7. BIBLIOGRAFÍA 
