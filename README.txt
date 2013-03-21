Constituciones del Perú

	CC-BY-SA-3.0 (a Free Culture License)
	Attribution-ShareAlike 3.0 Unported 
	http://creativecommons.org/licenses/by-sa/3.0/

El texto de las constituciones ha sido normalizado de la siguiente forma:

- s/Art\./Artículo/
- s/art\./artículo/
- convertido a UTF-8
- los EOL convertidos a \n

Análisis usando DeducerText y tm

- Convertido todo a minúsculas
- Removido los signos de puntuación
- Removido los números
- Removidos los stopwords "es"
- Creado un Word Cloud

- Adicionalemente, se removieron los stopwords "es" y los términos "artículo" y
  "art": c(stopwords("es"), "artículo", "art")
- Se creó otro Word Cloud

Fuentes:

$ head -5 txt/*txt

==> txt/cnp1836.txt <==
Constitución del Estado Nor - Peruano 
(6 de agosto de 1836) 


EL CIUDADANO LUIS JOSÉ ORBEGOSO

==> txt/cons1812.txt <==
Constitución Política de la Monarquía Española 
Promulgada en Cádiz el 19 de Marzo de 1812


 En el nombre de Dios Todopoderoso, Padre Hijo y Espíritu Santo, autor y supremo legislador de la 

==> txt/cons1823.txt <==
Constitución Política de la República Peruana 
Sancionada por el Primer Congreso Constituyente el 12 
de Noviembre de 1823 

CONSTITUCIÓN POLÍTICA DE LA REPÚBLICA PERUANA SANCIONADA POR EL PRIMER 

==> txt/cons1826.txt <==
Constitución Política de 1826 
(1 de julio de 1826) 

CONSTITUCIÓN POLÍTICA PARA LA REPÚBLICA PERUANA 


==> txt/cons1828.txt <==
Constitución Política de la República Peruana 1828 
(18 de marzo de 1828) 

Dada por el Congreso General Constituyente el día 18 de marzo de 1828 


==> txt/cons1834.txt <==
Constitución Política de la República Peruana 
Dada por la Convención Nacional el día 10 de Junio de 1834 


EL CIUDADANO LUIS JOSÉ ORBEGOSO 

==> txt/cons1839.txt <==
CONSTITUCIÓN POLÍTICA DE LA REPÚBLICA PERUANA


 Dada por el Congreso General el día 10 de noviembre de 1839 en 
Huancayo 

==> txt/cons1856.txt <==
CONSTITUCIÓN DE LA REPÚBLICA PERUANA 


DADA EL 13 DE OCTUBRE DE 1856 Y PROMULGADA EN 19 DEL MISMO MES. 


==> txt/cons1860.txt <==
Constitución Política del Perú 
10 de Noviembre de 1860 

El Libertador Ramón Castilla, 
Presidente Constitucional de la República.

==> txt/cons1867.txt <==
Constitución Política del Perú 
Sancionada por el Congreso Constituyente de 1867 
(29 de agosto de 1867) 



==> txt/cons1920.txt <==
Constitución para la República del Perú 

Dictada por la Asamblea Nacional de 1919 y promulgada el 18 de Enero 

de 1920 

==> txt/cons1933.txt <==
Constitución Política del Perú (29 de Marzo de 1933) 

TITULO I 

EL ESTADO, EL TERRITORIO Y LA NACIONALIDAD 

==> txt/cons1979.txt <==
Constitución para la República del Perú 
(12 de Julio de 1979) 

FERNANDO BELAUNDE TERRY 
Presidente Constitucional de la República

==> txt/cons1993.txt <==
CONSTITUCIÓN POLÍTICA DEL PERÚ 

P R E Á M B U L O 

EL CONGRESO CONSTITUYENTE DEMOCRÁTICO, INVOCANDO A DIOS 

==> txt/csp1836.txt <==
Constitución del Estado Sud - Peruano (1836) 

La Asamblea Nacional del Sud del Perú a nombre de los departamentos 
de Arequipa, Ayacucho, Cuzco y Puno 


==> txt/ecpb1836.txt <==
Decreto del 28 de Octubre de 1836 (Establecimiento de la 
Confederación Perú - Boliviana) 


ANDRÉS SANTA-CRUZ, 

==> txt/lcpb1837.txt <==
Ley Fundamental de la Confederación Perú - Boliviana 
(1837) 

(1 ° de Mayo de 1837) 

