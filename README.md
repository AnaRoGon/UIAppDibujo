# Diseño de interfaz de una Aplicación de dibujo
Proyecto Java enfocado en la práctica del diseño de interfaces gráficas utilizando la biblioteca Swing dentro del entorno de desarrollo NetBeans.
Esta aplicación no es funcional (no permite dibujar como tal), sino que ha sido diseñada con el objetivo de aprender y aplicar principios de diseño de GUI (disposición, botones, menús, paneles, etc.).

Si lo deseas puedes ver el PDF explicativo con las decisiones de diseño desde este enlace: <https://github.com/AnaRoGon/UIAppDibujo/blob/master/Decisones_UIUX.pdf>

# Características principales

## Pantalla principal

La ventana principal simula una aplicación de dibujo con una distribución intuitiva y clara.
Se ha reservado la mayor parte del espacio para dos zonas diferenciadas: 
una dedicada a mostrar una referencia visual de la obra y otra que representa el área de coloreado, simulando el lienzo donde se trabajaría en una aplicación funcional.

![00](https://github.com/user-attachments/assets/af93af8a-bf92-4d02-b912-95402ff6aac2)

## Menú principal

Se ha implementado una barra de menús con opciones como:

Archivo (Abrir, Cerrar, Guardar, Imprimir, Salir...) - Herramientas (Pincel, Goma, Color...) - Galeria - Ventana

![01](https://github.com/user-attachments/assets/3e668a91-1778-4d24-9c90-f924b76872f9)

## Barra de Herramientas

Debajo del menú principal se ha incluido una barra de herramientas con iconos representativos de las funciones rápidas más relevantes para este tipo de aplicación.
Esta barra es desacoplable, lo que permite al usuario moverla y reubicarla en otra parte de la ventana según su preferencia.

![02](https://github.com/user-attachments/assets/5714e254-0d34-4eff-9cce-7e138eb8f165)

## Simulación de Pantalla de ajustes de impresión

Esta ventana se activa al seleccionar la opción "Imprimir" en el menú principal de la aplicación. 
Está diseñada para simular un cuadro de diálogo de impresión típico en programas de diseño o edición de imágenes.

![03](https://github.com/user-attachments/assets/c29b6d6c-1883-4fcf-9fd3-ef5b5340d366)

## Simulación de diseño de un mensaje de error 

![04](https://github.com/user-attachments/assets/d444272b-3f8e-4b14-8e75-6efe6c89e1ed)

## Simulación de diseño de un mensaje de aviso de sobreescritura de archivo

![05](https://github.com/user-attachments/assets/a162782d-9699-4615-b1a1-2828558347e2)

# Tecnologías utilizadas

Para el diseño de esta interfaz se ha utilizado:

* Swing (javax.swing.*) para componentes gráficos.
* NetBeans GUI Builder para disposición y organización visual.
* Iconos e imágenes simulando herramientas reales de dibujo.

# Instrucciones de uso.

Para ejecutar la app copia el enlace del repositorio en GitHub: <https://github.com/AnaRoGon/UIAppDibujo.git>

1. Abre NetBeans y ve al menú:
2. Team -> Git -> Clone.
3. Pega la URL del repositorio y sigue las instrucciones para clonar el proyecto localmente.
4. Una vez clonado, NetBeans detectará el proyecto y podrás abrirlo y ejecutarlo directamente desde el IDE.
