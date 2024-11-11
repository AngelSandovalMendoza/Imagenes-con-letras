# Imagenes-con-letras
Programa que transforma una imagen que el usuario escoja a un archivo .doc o html, dependiendo de la selección.

## Requisitos

- Python 3.x
- Tkinter
- Pillow
- python-docx

## Uso

1. Ejecuta el script utilizando el comando "escalar.py".
2. Cargar la imagen con el boton "Cargar Imagen"
3. Con la barra escoger el factor de escala que se le aplicará a la imagen
4. Guardar la imagen en la ruta de preferencia

## Opciones disponibles

1. Guardar HTML (Color con 'M'): Genera un archivo HTML usando el carácter M para representar cada píxel en color.
2. Guardar HTML (Grises con 'M'): Igual que el anterior, pero en escala de grises.
3. Guardar HTML (Color con Especiales): Utiliza caracteres especiales para representar intensidades de color en el HTML.
4. Guardar HTML (Grises con Especiales): Igual que el anterior, pero en escala de grises.
5. Guardar HTML (Color con Frase): Permite ingresar una frase personalizada para crear la imagen HTML.
6. Guardar HTML (Grises con Frase): Igual que el anterior, pero en escala de grises.
7. Guardar .doc (Cartas): Genera un documento .docx donde cada píxel se representa con un carácter (necesario usar la fuente playcards).