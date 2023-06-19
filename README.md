# IA-al-dia
Ejercicio realizado dentro del master de Desarrollo de sitios y aplicaciones web de la UOC en la asignatura de HTML y CSS

- Organización de archivos
Los archivos que componen el sitio web están organizados de la siguiente manera:
  - raíz del sitio:
	  - archivos html
	  - carpeta "img" donde se almacenarán todas las imágenes
	  - carpeta "css" donde está el archivo único de la hoja de estilos.

Si se generan nuevas páginas, se tiene que respetar esta estructura. Para añadir otro tipo de archivos (por ejemplo, javascript) se creará una carpeta en la raíz del sitio y dentro de la carpeta irán los archivos correspondientes.


- Accesibilidad
El html utilizado sigue el estándar html 5 intentando construir un sitio lo más accesible posible.
  - Se priorizan etiquetas semánticas como section, article, etc. a otras etiquetas más genéricas como div o span.
  - Se aportan definiciones para palabras no comunes, como por ejemplo, abreviaturas o siglas (ejemplo: IA > Inteligencia Artificial).
  - Todas las imágenes tendrán su correspondiente descripción en la propiedad alt. Esta descripción tendrá como objetivo guiar a un usuario no vidente y la explicación no se ceñirá   a una descripción figurativa sino semántica (por ejemplo, si hubiese un campo para búsquedas, en la propiedad alt no pondrá "lupa" sino "buscar")
  - Uso de aria. Se intentará prestar atención al uso de arias. En especial, en las páginas de tercer nivel para el elemento breadcrumb.
  - El lenguaje principal del sitio web está especificado en el head del documento.


- Niveles de información en el sitio web
El sitio web consta de 4 páginas que muestran 3 niveles de información y estructura:
  - PRIMER NIVEL: Es la página de inicio del sitio que se corresponde con el archivo index.html. 
  - SEGUNDO NIVEL: Son las páginas principales a las que se accede a través del menú principal situado en la cabecera de la web (aplicaciones.html y en-el-cine.html)
  - TERCER NIVEL: Es la página a la que accedes a través de las páginas de segundo nivel, donde se expande la información (despacho-42.html)


- Arquitectura de la información
La información del sitio web está estructurado en tres grandes comunes:
  - CABECERA Y NAVEGACIÓN
  Aquí se situan el logotipo y la navegación principal. Los ítems representados en el menú, nos llevarían a las páginas de segundo nivel mencionadas anteriormente.
  - CONTENIDO
  Aquí se encuentra el contenido principal de cada página. Dependiendo del nivel de la página, tendrá una estructura u otra. 
  Aquí encontraremos también los menús secundarios como los breadcrumbs.
  - FOOTER
  Es la parte inferior de la página, común a todas las páginas. Desde aquí se accederá a información legal y redes sociales principalmente. 

El sitio web es responsive y se ha intentado que los elementos sean lo más fluidos posible para evitar en la medida de lo posible los media-queries. En la medida de lo posible se ha intentado:
1.	Utilización de tipografía fluida para que se adapte a diferentes anchos de pantalla
2.	Utilización de imágenes y vídeos fluidos
3.	Utilización de media-queries para adaptar el layout a diferentes dispositivos 

Dentro de este enfoque se ha seguido la metodología mobile first.


