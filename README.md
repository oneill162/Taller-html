# Unidad V · Ajustes de color

**TESI 1104 – Diseño de Elementos para la Web** · Semana 8 · Adobe Photoshop CS6
Instituto Tecnológico de Puerto Rico · Recinto de Manatí
Prof. Eduardo O. De Jesús Arroyo

![Foto de práctica: mitad a color y mitad en escala de grises](img/s01-1.jpg)

*La misma foto: a la izquierda el original, a la derecha en escala de grises.*

## Contenido

1. [Objetivos](#objetivos)
2. [Mapa general](#mapa-general)
3. [Regla de trabajo: proteja el original](#regla-de-trabajo-proteja-el-original)
4. [01 · Blanco y negro](#01--blanco-y-negro)
5. [02 · Duotono](#02--duotono)
6. [03 · Niveles y Curvas](#03--niveles-y-curvas)
7. [04 · Degradados](#04--degradados)
8. [Guía rápida](#guía-rápida-qué-ajuste-uso)
9. [Laboratorio 8](#laboratorio-8-foto-de-perfil-profesional-en-duotono)
10. [Repaso rápido](#repaso-rápido)
11. [Referencias](#referencias)

---

## Objetivos

Alineado al prontuario: Unidad V (Ajustes de color) y objetivo específico 1, *utilizar diferentes técnicas para mejorar una imagen digital*.

1. **Convertir** una foto a blanco y negro controlando el gris de cada color.
2. **Aplicar** monotono, duotono y tritono para dar un estilo de color.
3. **Interpretar** el histograma para saber si una foto está oscura, clara o plana.
4. **Corregir** el contraste y el brillo con Niveles y con Curvas.
5. **Crear** degradados de los cinco tipos para fondos, banners y botones.
6. **Trabajar** con capas de ajuste para no dañar el original.

## Mapa general

Cuatro ajustes, una misma foto.

| ![Blanco y negro](img/s03-1.jpg) | ![Duotono](img/s03-2.jpg) | ![Niveles y Curvas](img/s03-3.jpg) | ![Degradados](img/s03-4.png) |
|:---:|:---:|:---:|:---:|
| **1. Blanco y negro**<br>Quitar el color y decidir qué gris recibe cada color. | **2. Duotono**<br>Mostrar la foto con una, dos, tres o cuatro tintas. | **3. Niveles y Curvas**<br>Ajustar sombras, medios tonos y luces. | **4. Degradados**<br>Transición suave entre colores para fondos y gráficos. |

> **Pregunta guía de la semana:** ¿qué problema tiene esta foto: color, tono o contraste? La respuesta decide qué ajuste usar.

## Regla de trabajo: proteja el original

| Ajuste directo | Capa de ajuste |
|---|---|
| `Image > Adjustments` | `Layer > New Adjustment Layer` |
| Cambia los píxeles de la capa. | Guarda el ajuste en una capa aparte. |
| Para deshacer, solo queda el panel History. | Se puede editar, ocultar o borrar cuando quiera. |
| Al cerrar el archivo, el cambio es permanente. | Los píxeles originales no se tocan. |

**En esta clase:** use el panel Adjustments (`Window > Adjustments`). Cada ícono crea una capa de ajuste; sus opciones aparecen en el panel Properties. Si un ajuste no está en el panel (Desaturate, Duotone), trabaje sobre una copia de la capa: `Ctrl + J`.

---

## 01 · Blanco y negro

Quitar el color es fácil. Lo importante es decidir cómo se ve cada color en gris.

![Foto en escala de grises](img/s05-1.jpg)

### Tres caminos al blanco y negro

| ![Desaturate](img/s06-1.jpg) | ![Modo Grayscale](img/s06-2.jpg) | ![Black & White](img/s06-3.jpg) |
|:---:|:---:|:---:|
| **Desaturate**<br>`Image > Adjustments > Desaturate`<br>`Shift+Ctrl+U`<br>Rápido, pero sin control. Colores distintos pueden quedar del mismo gris. | **Modo Grayscale**<br>`Image > Mode > Grayscale`<br>Cambia el archivo a 1 canal. Pesa menos, pero borra el color para siempre. | **Black & White**<br>`Image > Adjustments > Black & White`<br>`Alt+Shift+Ctrl+B`<br>El más profesional: un control por color. Disponible como capa de ajuste. |

### Black & White: usted decide el gris de cada color

| ![Original](img/s07-1.jpg) | ![Preset Red Filter](img/s07-2.jpg) | ![Preset Blue Filter](img/s07-3.jpg) |
|:---:|:---:|:---:|
| Original | Preset Red Filter: rojos claros, cielo oscuro | Preset Blue Filter: cielo claro, rojos oscuros |

- El cuadro trae seis controles: Reds, Yellows, Greens, Cyans, Blues y Magentas. A la derecha aclara ese color; a la izquierda lo oscurece.
- Con la mano (Targeted Adjustment) arrastre sobre la foto: Photoshop ajusta el color que está debajo del cursor.
- Los presets imitan los filtros de colores de la fotografía en película.

### Un paso más: tono sepia con Tint

![Foto en tono sepia](img/s08-1.jpg)

*Black & White con la opción Tint activada.*

1. Cree una capa de ajuste Black & White.
2. Marque la casilla **Tint** en el panel Properties.
3. Clic en la muestra de color: escoja un tono cálido (sepia) o frío (azulado).
4. Baje la opacidad de la capa si el tono es muy fuerte.

**Uso en la web:** fotos de historia, «nosotros» o productos con estilo antiguo.

---

## 02 · Duotono

Una foto en escala de grises reproducida con dos tintas. Da estilo y unidad de color a un sitio web.

![Foto en duotono negro y naranja](img/s09-1.jpg)

### Monotono, duotono y tritono

| ![Monotono](img/s10-1.jpg) | ![Duotono](img/s10-2.jpg) | ![Tritono](img/s10-3.jpg) |
|:---:|:---:|:---:|
| **Monotono**<br>1 tinta · azul marino del ITPR | **Duotono**<br>2 tintas · negro + naranja | **Tritono**<br>3 tintas · negro + azul + dorado |

El modo Duotone sirve para 1 a 4 tintas: Monotone, Duotone, Tritone y Quadtone. Nació en la imprenta; en la web se usa como estilo visual para que todas las fotos del sitio compartan la misma paleta.

### Cómo crear un duotono en Photoshop CS6

1. **`Image > Mode > Grayscale`**: el duotono solo se activa desde escala de grises. Trabaje en una copia del archivo.
2. **`Image > Mode > Duotone`**: abre el cuadro Duotone Options.
3. **Type**: escoja Monotone, Duotone, Tritone o Quadtone.
4. **Ink 1, Ink 2…**: clic en la muestra para escoger el color; clic en la curva para ajustar cuánta tinta va en cada tono.
5. **`Image > Mode > RGB Color`**: para publicar en la web, convierta a RGB antes de guardar en JPEG o PNG.

![Resultado en duotono](img/s11-1.jpg)

> **Atajo:** el menú Preset del cuadro Duotone trae combinaciones ya hechas para empezar.

---

## 03 · Niveles y Curvas

Las dos herramientas principales para corregir el tono. Antes de usarlas hay que saber leer el histograma.

![Foto con contraste mejorado](img/s12-1.jpg)

### El histograma: la radiografía de la foto

Se abre con `Window > Histogram`. El eje horizontal va de 0 (negro) a 255 (blanco); la altura indica cuántos píxeles tienen ese tono.

| ![Oscura](img/s13-1.jpg) | ![Plana](img/s13-3.jpg) | ![Bien expuesta](img/s13-5.jpg) |
|:---:|:---:|:---:|
| ![Histograma de la foto oscura](img/s13-2.png) | ![Histograma de la foto plana](img/s13-4.png) | ![Histograma de la foto bien expuesta](img/s13-6.png) |
| **Oscura**<br>Montaña pegada a la izquierda. Faltan luces. | **Plana (poco contraste)**<br>Montaña en el centro. No hay negros ni blancos. | **Bien expuesta**<br>Datos de un extremo a otro, sin cortes fuertes. |

> No existe un histograma «correcto»: una foto de noche debe estar a la izquierda.

### Levels: tres controles, tres zonas del tono

`Ctrl+L` · `Image > Adjustments > Levels`

| Antes | Después |
|:---:|:---:|
| ![Antes](img/s14-1.jpg) | ![Después](img/s14-3.jpg) |
| ![Histograma antes](img/s14-2.png) | ![Histograma después](img/s14-4.png) |
| | Negro y blanco al borde de los datos |

- ◀ **Negro (sombras):** lo que quede a la izquierda se vuelve negro puro.
- ◆ **Gris (gamma):** aclara u oscurece los medios tonos.
- ▶ **Blanco (luces):** lo que quede a la derecha se vuelve blanco puro.

> **Truco:** mantenga `Alt` mientras arrastra el control negro o blanco. Lo que aparece marcado es lo que se va a recortar.

**Regla práctica:** lleve el control negro y el blanco hasta donde empieza y termina la montaña del histograma. El histograma se estira de extremo a extremo y la foto recupera contraste.

### Curves: control punto por punto

`Ctrl+M` · `Image > Adjustments > Curves`

La diagonal significa «sin cambio». Si un punto se sube, ese tono sale más claro; si se baja, más oscuro.

| Curva en S | Subir el centro | Bajar el centro | Diagonal invertida |
|:---:|:---:|:---:|:---:|
| ![Diagrama: Curva en S](img/s15-1.png) | ![Diagrama: Subir el centro](img/s15-3.png) | ![Diagrama: Bajar el centro](img/s15-5.png) | ![Diagrama: Diagonal invertida](img/s15-7.png) |
| ![Curva en S](img/s15-2.jpg) | ![Subir el centro](img/s15-4.jpg) | ![Bajar el centro](img/s15-6.jpg) | ![Diagonal invertida](img/s15-8.jpg) |
| Más contraste | Aclara medios tonos | Oscurece medios tonos | Negativo (`Ctrl + I`) |

La curva en S oscurece sombras y aclara luces: es el ajuste de contraste más usado.

### Cómo trabajar en el cuadro Curves

![Curva en S con dos puntos](img/s16-1.png)

- **Agregar un punto:** clic sobre la línea. Arrastre hacia arriba o hacia abajo.
- **Quitar un punto:** arrástrelo fuera del cuadro o selecciónelo y oprima `Delete`.
- **Mano (Targeted Adjustment):** arrastre sobre la foto para mover el tono que está debajo.
- **Canales:** el menú Channel permite ajustar solo el rojo, el verde o el azul.
- **Cuadrícula de 10 × 10:** `Alt` + clic dentro del cuadro.

> Use pocos puntos: dos o tres bastan casi siempre. Muchos puntos producen saltos de tono (posterización).

### ¿Niveles o Curvas?

| | Levels (`Ctrl + L`) | Curves (`Ctrl + M`) |
|---|---|---|
| Controles | 3: negro, gris y blanco | Hasta 14 puntos en la curva |
| Lo hace muy bien | Fijar el punto negro y el blanco | Contraste fino por zonas (curva en S) |
| Dificultad | Fácil: ideal para empezar | Requiere práctica |
| Corregir color | Sí, por canal o con cuentagotas | Sí, por canal o con cuentagotas |
| Capa de ajuste | Sí | Sí |

**Flujo recomendado:** primero Levels para fijar negro y blanco; después Curves para afinar el contraste.

### Corregir una dominante de color

| Antes: todo se ve amarillento | Después: Levels canal por canal |
|:---:|:---:|
| ![Foto amarillenta](img/s18-1.jpg) | ![Foto corregida](img/s18-2.jpg) |

- **Cuentagotas negro:** clic en algo que deba ser negro.
- **Cuentagotas gris:** clic en algo que deba ser gris neutro.
- **Cuentagotas blanco:** clic en algo que deba ser blanco.

Una dominante es un color que tiñe toda la foto: amarillo por bombillas, azul por sombra, verde por fluorescentes. Levels y Curves traen tres cuentagotas; el gris es el más útil, pues con un clic neutraliza la dominante. También existe `Image > Auto Color` (`Shift + Ctrl + B`) como punto de partida.

---

## 04 · Degradados

Transición suave entre dos o más colores. Es la base de fondos, banners y botones en la web.

![Banner web con fondo degradado](img/s19-1.png)

### Gradient Tool: cinco tipos

| ![Linear](img/s20-1.png) | ![Radial](img/s20-2.png) | ![Angle](img/s20-3.png) | ![Reflected](img/s20-4.png) | ![Diamond](img/s20-5.png) |
|:---:|:---:|:---:|:---:|:---:|
| Linear | Radial | Angle | Reflected | Diamond |

- Atajo: `G` abre la herramienta Gradient. Comparte lugar con el balde de pintura (Paint Bucket): `Shift + G` alterna entre las dos.
- Escoja el tipo en la barra de opciones, haga clic donde empieza el degradado y arrastre hasta donde termina.
- Mantenga `Shift` mientras arrastra para trazar la línea recta (horizontal, vertical o a 45°).
- Los colores por defecto van del color frontal al color de fondo (`D` restaura negro y blanco).

### El editor de degradados

![Barra del editor de degradados](img/s21-1.png)

- Doble clic en la muestra de la barra de opciones abre el Gradient Editor.
- **Paradas de color** (debajo de la barra): clic para añadir, doble clic para cambiar el color.
- **Paradas de opacidad** (encima de la barra): hacen transparente una parte.
- El rombo entre dos paradas mueve el punto medio de la transición.
- Escriba un nombre y oprima New para guardarlo.

![Banner con degradado](img/s21-2.png)

*Banner con degradado lineal azul marino a azul ITPR.*

> **Accesibilidad:** el texto sobre un degradado debe contrastar en toda la zona, no solo en la parte oscura. Las pautas WCAG piden un contraste mínimo de 4.5 : 1 para texto normal.

### Gradient Map: degradados aplicados a una foto

| ![Foto en gris](img/s22-1.jpg) | ![Gradient Map azul marino a dorado](img/s22-2.jpg) | ![Gradient Map morado a turquesa](img/s22-3.jpg) |
|:---:|:---:|:---:|
| Tonos de la foto (gris) | Mapa azul marino → dorado | Mapa morado → turquesa |

- `Layer > New Adjustment Layer > Gradient Map` cambia cada tono por un color del degradado: las sombras toman el color de la izquierda y las luces el de la derecha.
- Logra un efecto de duotono sin salir del modo RGB: más rápido y listo para la web.
- Une los cuatro temas: parte del gris (01), imita el duotono (02), depende del tono (03) y usa un degradado (04).

---

## Guía rápida: ¿qué ajuste uso?

| Si la foto… | Use | Atajo o menú |
|---|---|---|
| Necesita verse en blanco y negro con control | Black & White | `Alt + Shift + Ctrl + B` |
| Debe combinar con los colores del sitio | Gradient Map o Duotone | `Layer > New Adjustment Layer` |
| Se ve gris y sin contraste | Levels (negro y blanco) | `Ctrl + L` |
| Necesita más «pegada» | Curves en S | `Ctrl + M` |
| Tiene un tinte de color | Cuentagotas gris en Levels o Curves | `Ctrl + L` / `Ctrl + M` |
| Necesita un fondo para texto o botón | Gradient Tool | `G` |

**Siempre:** capa de ajuste o copia de la capa · revise el histograma antes y después · exporte en RGB.

---

## Laboratorio 8: foto de perfil profesional en duotono

| Parte | Tarea | Detalle |
|:---:|---|---|
| A | Selfie | Luz de frente y pared lisa |
| B | Recorte y Levels | 4:5 · 1080 × 1350 px |
| C | Fondo limpio | Quick Selection + Refine Edge |
| D | Duotono | Azul marino + crema |
| ✓ | Exportar y entregar | RGB · JPEG 70–80 |

- **Traiga:** su teléfono (en iPhone: Ajustes > Cámara > Formatos > Más compatible, porque CS6 no abre HEIC).
- **Entrega:** carpeta `Apellido_Nombre_TESI1104_Lab08` (.zip) con el selfie original, el .PSD con capas y el JPG final, en OrbundSIS.

## Repaso rápido

1. ¿Por qué Black & White es mejor que Desaturate?
   <details><summary>Ver respuesta</summary>Controla el gris de cada color.</details>
2. ¿Qué paso es obligatorio antes de `Image > Mode > Duotone`?
   <details><summary>Ver respuesta</summary>Convertir a Grayscale.</details>
3. El histograma tiene toda la montaña en el centro. ¿Qué hago?
   <details><summary>Ver respuesta</summary>Levels: negro y blanco al borde de los datos.</details>
4. ¿Qué forma de curva aumenta el contraste?
   <details><summary>Ver respuesta</summary>La curva en S.</details>

## Cierre

**Primero el tono, después el estilo:** corrija con Niveles y Curvas; luego dé carácter con blanco y negro, duotono o degradados.

## Referencias

- Adobe. (2023). *Photoshop user guide*. Adobe Help Center. https://helpx.adobe.com/photoshop/user-guide.html
- Chavez, C. (2024). *Adobe Photoshop classroom in a book (2025 release)*. Adobe Press.
- Smith, S. A. (s.f.). *Getting started with Photoshop CS6: Reference guide*. Balfour.
- W3C. (2023). *Web content accessibility guidelines (WCAG) 2.1*. https://www.w3.org/TR/WCAG21/

*Imágenes de práctica generadas por computadora para este curso, sin derechos de terceros.*
