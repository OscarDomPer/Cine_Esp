<div align="center">

# La influencia de España en el cine español

</div>

<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/port.png?raw=true" width="60%">
  
</div>

<br>
<br>

## Tecnologías usadas

**Lenguaje:** Python.

**Librerias:** numpy, pandas, matplotlib, seaborn, plotly, requests, BeautifulSoup

<br>
<br>

## **Introducción**

Para este proyecto, decidimos usar la página web ***Filmaffinity*** como fuente de información para realizar un análisis enfocado en la interpretación de los datos obtenidos. A través de la técnica de web __scraping__, logramos extraer un primer DataFrame con la información que nos pareció relevante de todas las __películas españolas__ de la plataforma.
<br>
<br>
Para ver en detalle el código del scraping, vease la carpeta ["Scrapping"](https://github.com/OscarDomPer/Cine_Esp/tree/main/Cine_Espa%C3%B1ol/Scraping)

<br>
<br>
<br>
<br>

------------

<h2>
  
## Punto de partida

<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/pict1.png?raw=true" width="80%">
  
</div>


En una primera aproximación a los datos, __nos llamó la atención el pronunciado descenso en las
producciones que se vivió entre 1980 y 1990__. Decidimos intentar encontrar una explicación analizando
los datos obtenidos.
<br>
Para ver en detalle el código de las gráficas, vease la carpeta ["Gráficos"](https://github.com/OscarDomPer/Cine_Esp/tree/main/Cine_Espa%C3%B1ol/Gr%C3%A1ficos)
<br>
<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/pict2.png?raw=true" width="80%">
  
</div>


A nuestro entender no podemos analizar lo que ha sucedido en el periodo del valle en cuestión
de forma aislada,sino en el contexto de toda la historia del cine español. Así que decidimos
establecer una serie de __periodos temporales__, algunos puramente históricos y otros basados en
acontecimientos culturales o económicos.
<br>
<br>
<br>
<br>
## Etapa inicial
<br>

**Visión general**

<div align="center">


  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/Etapa%20inicial.png?raw=true" width="60%">
  
</div>

**La transición del cine mudo al sonoro en
España hacia finales de los años 20 fue
complicada**, causando una casi
paralización de la industria. La primera
película sonora, "El misterio de la puerta
del sol" de Francisco Elías, tuvo limitada
proyección debido a la falta de
equipamiento en las salas. Sin embargo,
una vez superada esta barrera técnica, se
produjeron exitosos films como "Morena
Clara", "El bailarín y el trabajador", "La
verbena de la Paloma" y "Don Quintín, el
amargao". Estos éxitos, durante la
Segunda República, contribuyeron a una
era referida como "la edad de oro del cine
español", que finalizó abruptamente
con el inicio de la guerra.
<br>
<br>
<br>
<br>

## Franquismo
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/vista_franq.png?raw=true" width="60%">
  
</div>

Durante el franquismo, el cine en España
estuvo fuertemente influenciado por la
__censura,__ que limitaba la libertad de
expresión y prohibía temas críticos con el
régimen. A pesar de esto, gradualmente
se produjo una apertura exterior con el
objetivo de mejorar la imagen
internacional de España. En términos de
géneros, en sus inicios predominaba la
__propaganda patriótica__, llegando el
propio Franco a guionizar la película
"Raza". Con el tiempo, el cine español
evolucionó para abordar temas más
variados, aunque evidentemente nunca
molestos para el régimen, destacando
especialmente el __musical__. En la última
etapa, se produjeron películas que
trataban cuestiones sociales, aunque
siempre, claro está, bajo la supervisión de
los censores
<br>
<br>
<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/copr_franq.png?raw=true" width="70%">
  
</div>

El régimen franquista enfrentó cierto
__aislamiento__ internacional en sus primeros
años, en parte debido a su anterior
alineación con el Eje durante la Segunda
Guerra Mundial. Sin embargo, en las
décadas subsiguientes, especialmente a
partir de la década de 1950 y en el
contexto de la Guerra Fría, España
experimentó una apertura gradual. __Esta
transición de aislamiento a apertura se
refleja en el número de coproducciones
internacionales por año__, las cuales fueron
anecdóticas en los primeros años de la
dictadura.
<br />
<br />
<br />
<br />
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/franq_musi.png?raw=true" width="70%">
  
</div>

A partir de 1960, podemos observar un fuerte incremento en las producciones
musicales, siendo __Marisol__ el máximo exponente de este auge del género musical.
Esto se puede explicar, en parte, porque las producciones musicales no tenían
cierta ventaja competitiva, al no sufrir los efectos de la censura a diferencia de
otros géneros 
<br>
<br>
<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/franq_social.png?raw=true" width="70%">
  
</div>

El riguroso control de la censura se manifiesta claramente en estas dos
temáticas: el __cine político, que no tuvo presencia en España hasta el
fallecimiento de Franco__, mientras que el cine social comenzó a ganar
terreno de manera cautelosa hacia el final del régimen, eludiendo la
censura en la medida de lo posible.
<br>
<br>
<br>
<br>

## Destape
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/vista_dest.png?raw=true" width="60%">
  
</div>

Franco falleció en 1975 y con él, también
se extinguió la censura. Esto propició la
emergencia de un __cine más contestatario__,
cuyas raíces ya se podían percibir en los
últimos años del Franquismo. En esta
línea, es imperativo mencionar al cine
__Quinqui__, que otorgaba voz a individuos
marginales, a menudo retratados como
antihéroes. Otro fenómeno notable de
esos años fue el __"destape"__, o cine
calificado como 'S'
<br />
<br />
<br />
<br />
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/quinqui.png?raw=true" width="70%">
  
</div>
El cine quinqui y el cine político surgieron
como dos manifestaciones
cinematográficas distintas en la España
post-franquista. Mientras que
el cine quinqui se centró en la
representación de la juventud marginal y
desfavorecida, el cine político abordó
cuestiones políticas y sociales de manera
crítica. 
<br>
<br>
<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/erotico.png?raw=true" width="70%">
  
</div>
El género cinematográfico erótico, que era
prácticamente inexistente hasta la muerte
de Franco en 1975, experimentó una era
de esplendor en los años posteriores,
periodo que se conoce popularmente
como el "Destape". 
<br>
<br>
<br>
<br>
<br>

## Ley Miró en adelante
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/vista_miro.png?raw=true" width="60%">
  
</div>

__Durante 1983 y 2007, España
experimentó una transición hacia la
modernidad__, marcada por la
consolidación de la democracia y la
celebración de la Exposición Universal de
Sevilla en 1992. Estos cambios influyeron
en el cine español, dando lugar a una
"nueva ola" cinematográfica que abordó
temas contemporáneos y diversificó la
producción.
<br>
<br>
<br>
<br>
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/miro.png?raw=true" width="70%">
  
</div>

En España durante los 60 y sobre todo los
70, las producciones de bajo presupuesto
no recibían el cariño de la crítica, pero las
salas de cine se llenaban. __Pilar Miró con
una ley en 1984 sentó las bases para
erradicar un cine que consideraba de
dudosa calidad y premiar al que pudiera
dar visibilidad al país en el exterior__.
Así, acabó con el cine de terror,
fantástico, aventuras, ciencia ficción,
acción y erótico y el supuesto *"cine de
calidad"* acabó con un descenso
abrupto de la taquilla. __Muchos
españoles dejaron de ver cine español.__
<br>
<br>
<br>
<br>
<br>
<div align="center">
  
  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/gene_miro.png?raw=true" width="70%">
  
</div>

En este gráfico se evidencia la crítica principal hacia
la ley, mostrando que ciertos géneros *"populares"*
vieron disminuida su frecuencia desde la
implementación de la ley, corroborando así las
objeciones hacia su impacto en la variedad genérica
del cine español.
<br>
<br>
<br>
<br>
<br>
<div align="center">
  
  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/gene_miro_2.png?raw=true" width="70%">
  
</div>

En la gráfica, hemos destacado los géneros adolescencia, thriller y romántico, ya que generalmente están
asociados al cine estadounidense. La entrada de la TV privada en los 90 en España afectó la
financiación del cine nacional. Para competir por audiencia, __se priorizó el cine comercial__, financiando
películas al estilo estadounidense en géneros y narrativas. Esto desvió la producción cinematográfica
española de temáticas artísticas o experimentales hacia una orientación más comercial y masiva.
<br>
<br>
<br>
<br>
<br>

------------

<h2>
  
## Estudio sobre el papel de la mujer en el cine
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/igu_1.png?raw=true" width="60%">
  
</div>
Durante la época dorada de los musicales
en España, a pesar de la prominencia de
Marisol, la relevancia de la mujer fue
limitada. Posteriormente, tras la muerte de
Franco y con la modernización de la
sociedad española, la mujer ganó
protagonismo.
Curiosamente, la Ley Miró inicialmente
redujo la participación femenina, pero en
los años siguientes, al adoptar modelos
narrativos americanos y con el impulso
del movimiento #MeToo, la
participación femenina se ha
equilibrado significativamente.
<br />
<br />
<br />
<br />
<br>
<div align="center">

  <img src="https://github.com/OscarDomPer/Cine_Esp/blob/main/Cine_Espa%C3%B1ol/Im%C3%A1genes/igu_2.png?raw=true" width="60%">
  
</div>
En la evolución de la nota media a lo largo
de los años, se destaca una valoración
más positiva por parte de las mujeres
durante el franquismo, posiblemente
debido al éxito de películas como las de
Marisol. Posteriormente, la valoración se
mantiene equilibrada hasta que, a partir
del 2000, se observa una apreciación más
positiva nuevamente.
En los últimos años, la gráfica podría
estar captando un fenómeno de
"review bombing", ya que a pesar de
que en esos años la presencia de la mujer
sigue aumentando la calificación media
presenta un descenso, afectando la
percepción general.
<br />
<br />
<br />
<br />
<br>

------------

<h2>
  
**Autores:**

- **Carlos Lara** - [Linkedin](https://www.linkedin.com/in/carloslarabarrera/)
- **Miguel Ortega**
- **Juan Pablo Aguilar**
- **Óscar Dominguez** - [Linkedin](https://www.linkedin.com/in/oscardominguezpereira/)

