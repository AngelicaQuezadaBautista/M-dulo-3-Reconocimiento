# M-dulo-3-Reconocimiento
En este repositorio se encuentra la tarea del módulo 3
Parte 1 – Reconocimiento Pasivo con Google Dorks
En esta sección se realizaron diferentes búsquedas avanzadas utilizando operadores de Google conocidos como Google Dorks. Estos operadores permiten encontrar información específica dentro de páginas web y documentos publicados en Internet.
Se desarrollaron 8 búsquedas distintas utilizando operadores como:
site: para buscar dentro de un dominio específico
filetype: para localizar tipos específicos de archivos
inurl: para buscar palabras dentro de la URL
intitle: para localizar palabras en el título de las páginas
"frase exacta" para encontrar coincidencias exactas
OR para combinar búsquedas
- para excluir resultados
Cada búsqueda fue documentada indicando:
El dork utilizado
Qué tipo de información buscaba
Qué resultados se encontraron
Si la información encontrada representa un posible riesgo de seguridad
Capturas de pantalla de los resultados obtenidos
Este ejercicio permitió identificar cómo algunos documentos o configuraciones pueden quedar expuestos públicamente.

Parte 2 – Investigación en GHDB
En esta parte se investigaron tres búsquedas dentro de la Google Hacking Database, disponible en Exploit Database. Esta base de datos recopila consultas avanzadas que permiten localizar información sensible o mal configurada en Internet.
Para cada dork encontrado se analizó:
Qué tipo de información busca la consulta
Qué tipo de exposición de datos puede revelar
La categoría dentro de la GHDB (por ejemplo: archivos sensibles, portales de login, configuraciones expuestas)
Esta investigación permitió comprender cómo algunas búsquedas pueden detectar errores de configuración que podrían representar riesgos de seguridad.

Parte 3 – Mapa Visual de Infraestructura con Maltego
En esta sección se utilizó la herramienta Maltego para visualizar las relaciones entre diferentes elementos de la infraestructura de un dominio.
Se creó un grafo nuevo y se agregó un dominio de prueba como example.com. Posteriormente se ejecutaron diferentes transformaciones para identificar información relacionada.
Las transformaciones realizadas fueron:
Domain → DNS para obtener registros DNS del dominio
DNS → IP para identificar la dirección IP asociada
IP → Location para determinar la ubicación aproximada del servidor
El resultado fue un grafo visual que muestra la relación entre:
Domain 
DNS Record 
IP Address
Location
Esto permite comprender cómo un dominio se conecta con servidores y ubicaciones dentro de la infraestructura de Internet.

En la última parte se elaboró una reflexión sobre los conceptos aprendidos durante la práctica. Se analizaron temas como:
La diferencia entre reconocimiento pasivo y reconocimiento activo
Las razones por las que realizar análisis sin autorización puede ser ilegal
La importancia de proteger la información para evitar su exposición pública
Esta reflexión permitió comprender que muchas veces la información sensible puede encontrarse fácilmente en Internet si los sistemas no están correctamente configurados.
