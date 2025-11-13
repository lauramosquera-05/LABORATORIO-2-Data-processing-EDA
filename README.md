# LABORATORIO-2-Data-processing-EDA
***Laboratorio N°2, presentado por Laura Mosquera y Celeste Isaza.***
1. *Análisis estadístico:*
   
   ¿Cuál es el promedio, mínimo y máximo de los atributos base (HP, Attack, Defense, Speed) de todos los Pokémon?
   
   Básicamente, se observa que en promedio los pokemon tienen alrededor de 71 HP (Hit points); el más debil tiene solo 1 HP, el mas fuerte llega 255 HP.
   Por otro lado, se observa que los pokemon tienen alrededor de 81 puntos en Attack Base, el mas debil tiene 5 puntos y el mayor 190.
   Además, en Defense Base el promedio es de 75 puntos, el minimo es de 5 y el maximo es de 250.
   Finalmente, en Speed Base el promedio es de 70, el minimo es de 5 y el maximo es de 200.
   
2. *Análisis gráfico:*
   
   Cree un histograma para visualizar la distribución de los valores de Base Exp. Interprete si la distribución es simétrica o sesgada.
   
   <img width="571" height="467" alt="image" src="https://github.com/user-attachments/assets/6a21f1e7-e58b-4caf-8175-277a0a296a4a" />
   
   Se observa que la grafica esta sesgada a la derecha, porque desciende de izquierda a derecha. Además, no se puede interpretar muy bien ya que las etiquetas en el eje x estan muy          unidas.
3. *Análisis gráfico:*
   
   Realice un boxplot comparando los valores de Attack Base entre los tipos principales (Type1). Identifique qué tipo tiene Pokémon con ataques más altos en promedio.
   
   <img width="698" height="506" alt="image" src="https://github.com/user-attachments/assets/4a791a33-31ba-40ca-904f-0021b319fb26" />
   
   La linea negra del medio en cada caja es la mediana o sea el valor central del ataque para este tipo. La caja muestra el rango donde se encuantra el 50% de los pokemon de ese tipo,       desde el cuartil 1 (Q1) hasta el el cuartil 3 (Q3). Las lineas que salen de cada cajita muestran los valores minimos y maximos sin contar los valores atipicos. Y los circulos             representan a los valores atipicos.
   Por ejemplo, Fairy tiene mediana mas baja junto con Grass, Water, Normal.


4. ¿Cuál es el top 5 de especies (Species) más frecuentes en el dataset?
   
   Top 5 especies más frecuentes: {Paradox Pokémon, Mouse Pokémon, Fox Pokémon, Dragon Pokémon, Pumpkin Pokémon} 

5. *Análisis gráfico:*
   
   Genere un gráfico de barras que muestre la cantidad de Pokémon por tipo principal (Type1). ¿Qué tipo es el más común?

   <img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a2ec8a9a-f247-41ed-8415-1427219afe48" />

   Esta gragica representa la cantidad de pokemon segun su tipo principal (Type1), en el eje x estan los tipos principales de pokemon, mientras que en el eje y esta l acantidad de           pokemon que pertenece a un tipo especifico. Por ejemplo, el tipo Water es el mas comun con alrededor de 150 pokemon.

   
6. *Análisis estadístico:*
   
   Calcule la correlación entre los atributos HP Base, Attack Base, Defense Base y Speed Base. ¿Qué atributos están más correlacionados entre sí?

   Esta matriz de correlacion muestra qué tan relacionados estan las variables numericas entre sí, en este caso los atributos base de los pokemon. Las correlaciones son positivas, es        decir que los atributos tienden a crecer juntos.
   
   
7. *Análisis gráfico:*
   
   Cree un heatmap (mapa de calor) con la matriz de correlaciones obtenida en el punto anterior. Interprete los resultados.

   <img width="735" height="590" alt="image" src="https://github.com/user-attachments/assets/8b12ec72-cdb4-4c11-bbc8-1c0b9f16fb64" />

   El siguente HeatMap muestra la fuerza de la relacion entre los atributos numericos, los colores indican la intensidad de esa correlacion.
   Así:
   Rojo = correlacion alta o positiva (variables crecen juntas).
   
   Azul oscuro = correlacion baja o negativa (variables no crecen juntas).
   
   Tonos claros = correlacion media o debil.
   

8. *Análisis gráfico:*
   
   Realice un diagrama de dispersión (scatter plot) entre Weight_kg y Attack Base. ¿Existe relación entre el peso de un Pokémon y su capacidad de ataque?

   <img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/40715ca1-95a8-43a0-a30a-556e433c18b7" />

   

9. *Análisis estadístico:*
    
    Determine el promedio de altura y peso por tipo principal (Type1). Interprete cuál tipo tiende a tener Pokémon más grandes.

   Hay valores faltantes o nulos.


10. *Análisis gráfico:*
    
    Construya un gráfico de violín o boxplot múltiple comparando el atributo Speed Base entre los tipos Flying, Electric y Ground.
    ¿Qué tipo de Pokémon tiende a ser más rápido?

    <img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/937cebb6-0dfc-4538-9be2-93dff1d06224" />

    La grafica representa la velocidad base de los pokemon segun su tipo (Electric, Ground, Flying)
    El eje y representa la velocidad base de cada pokemon es decir, qué tan rapido es ese tipo en promedio.
    La forma de violin representa la cantidad de pokemon que tienen esa velocidad, si es ancha hay muchos y si es angosta hay pocos.
    La linea blanca central representa la mediana de la velocidad base del tipo. La caja negra representa el rango intercuartilico donde esta el 50% central de los datos.
    En este caso, ELECTRIC tiene velocidades mas altas en general.

***Conclusionnes***

Se podria decir que los factores que mas influyen son tipo principal (Type1), peso (Weight), altura (Height), tipo secundario (Type2). 
El Type1 es uno de los mas influyentes porque tiende a tener patrones caracteristicos. Weight y Height se correlacionan parcialmente con algunos atributos (HP, Defense, Speed)
    

    
    

    


   



