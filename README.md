# Closer — Autocatálogo IA
Landing page académica en español. Frase: «Cada prenda en su lugar, automáticamente».

## Uso
Abrir `dist/index.html` en un navegador. Los archivos HTML, CSS, JavaScript e imágenes están en `dist/`. No requiere instalación ni backend. Para servirla localmente: `python3 -m http.server 8080 --directory dist`.

## Alcance
Presentación de una propuesta universitaria de Concepción, Región del Biobío, Chile. La demo usa tres fotografías generadas y datos predefinidos; NO ejecuta Machine Learning, no permite subir fotografías y no guarda inventarios reales. Atributos visuales y revisión humana se presentan como elementos propuestos. No se han inventado clientes, testimonios, resultados de rendimiento ni precios.

## Diseño
Fondos #000000, #09090B y #18181B; acento principal #2563EB, acento claro #60A5FA. Fuentes Plus Jakarta Sans e Inter mediante Google Fonts con alternativas locales. Seis tarjetas giratorias, menú móvil, sección de preguntas desplegables, partículas decorativas y movimiento reducido según preferencia del dispositivo. La clasificación es accesible con botones y select nativos.

## Recursos y créditos
Imágenes generadas con la herramienta integrada imagegen: `logo.png`, `hero_visual.png`, `service_1.png` a `service_6.png`. Copias WebP optimizadas para la página. Tres recortes de imágenes generadas se usan en la demo. No representan fotografías del producto real. Identidad y contenido basados en los datos proporcionados para Closer.

## Prompts utilizados
- Logo: icono C formado por etiquetas entrelazadas, azul #2563EB, fondo transparente, sin texto.
- Hero: polera clara flotante, marco de escaneo azul y fichas vacías, negro, render editorial 3D.
- Servicio 1: polera clara con marco de reconocimiento, fotografía oscura con luz azul.
- Servicio 2: camisa azul, sweater claro y pantalón negro separados por líneas azules.
- Servicio 3: prendas de punto dobladas, textura visible, crema, gris y azul.
- Servicio 4: polera junto a ficha translúcida de catálogo sin texto.
- Servicio 5: prendas dobladas en estantería negra con iluminación azul.
- Servicio 6: prenda clara en superficie de inspección y ficha de revisión vacía.

## Personalización
Modificar los textos en `dist/index.html`, las funciones y ejemplos en `dist/script.js`, y las variables de color en `dist/styles.css`. Para conectar un modelo real se necesita implementar y validar un servicio de inferencia; no basta con cambiar el texto de la demo.

## Verificación
Comprobación de sintaxis JavaScript, destinos de enlaces, archivos referenciados, dimensiones de imágenes y coherencia de los ejemplos de la demo. No se realizó revisión visual en navegador por falta de la habilidad de control del navegador en este entorno.
