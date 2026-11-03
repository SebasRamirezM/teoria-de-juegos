# Guía de ejecución

Cómo abrir, preparar y manejar la página interactiva **Teoría de Juegos** durante la exposición.

## 1. Qué hay en este repositorio

| Archivo | Para qué sirve |
| :--- | :--- |
| `index.html` | La página interactiva. Es un solo archivo: no necesita instalar nada. |
| `teor_a_de_juegos_s_ntesis_te_rica.md` | El documento de síntesis teórica del que sale todo el contenido. |
| `GUIA_EJECUCION.md` | Esta guía. |
| `GUIA_EXPOSICION.md` | Qué decir en cada sección y cómo usar cada interacción. |

## 2. Formas de abrir la página

### Opción A: archivo local (recomendada para el día de la exposición)
1. Descarga el repositorio: botón verde **Code → Download ZIP** en GitHub, o `git clone`.
2. Descomprime la carpeta.
3. Haz doble clic en `index.html`. Se abre en el navegador predeterminado.

Usa **Chrome, Edge o Firefox** actualizados. Todo funciona sin servidor.

### Opción B: GitHub Pages (un enlace para toda la clase)
La página está publicada en <https://sebasramirezm.github.io/teoria-de-juegos/>. Cada cambio que se suba a la rama `main` se publica solo en uno o dos minutos.

Si algún día deja de funcionar, revisa **Settings → Pages** en el repositorio: *Source* debe ser **Deploy from a branch**, rama `main`, carpeta `/ (root)`. GitHub Pages en cuentas gratuitas solo funciona si el repositorio es **público**.

### Opción C: enlace de Claude
La versión publicada como artefacto está en <https://claude.ai/artifact/L8QiX2fk3LEnbyw2CmqzjQ>. Es privada: para que otros la abran hay que compartirla desde el menú **Share** de la página.

## 3. Requisitos

- **Internet:** solo para cargar las tipografías (Bricolage Grotesque, Figtree y JetBrains Mono) desde Google Fonts. Sin conexión la página funciona igual, con las fuentes del sistema.
- **Pantalla:** está pensada para proyector o pantalla grande en horizontal. También se adapta a celular.
- **Tema:** sigue el modo claro u oscuro del sistema. En proyector suele leerse mejor el **modo claro**.

## 4. Controles durante la exposición

| Acción | Cómo |
| :--- | :--- |
| Siguiente capítulo | Tecla `→` |
| Capítulo anterior | Tecla `←` |
| Ir a un capítulo concreto | Barra superior: `Inicio`, `Qué es`, `01` a `10`, `Resumen` |
| Ver el avance | Línea de color bajo la barra superior |
| Recorrer la línea de tiempo | Clic en un año, o enfocar la línea y usar `←` `→` |

Las flechas del teclado no cambian de capítulo mientras el cursor está dentro de un campo de texto (por ejemplo, el número del concurso de belleza). Haz clic fuera del campo para volver a navegar.

## 5. Ensayo previo (10 minutos antes)

1. Abre la página en el computador del salón y verifica que se vean las tildes y las tipografías.
2. Pulsa **F11** para pantalla completa y ajusta el zoom (`Ctrl` + `+` / `-`) hasta que la matriz de la portada y el título quepan en la pantalla.
3. Recorre todos los capítulos con `→` y prueba una vez cada interacción:
   - Portada: **Buscar el equilibrio**.
   - Cap. 3: una ronda del dilema, **Ver el torneo de Axelrod**, los controles de Rubinstein y los dos modos de la cadena de tiendas.
   - Cap. 4: **Simular 30 compañeros**.
   - Cap. 5: los controles de Halcón y Paloma y los dos botones de terapia.
   - Cap. 6: **Siguiente propuesta** hasta el final y luego **Reiniciar**.
   - Cap. 7: mover la puja de $10 a $5.
   - Cap. 8: los tres escenarios.
   - Cap. 9: **Con atajo** y **Sin atajo**.
   - Cap. 10: **Clásico** y **Cuántico**.
4. Recarga la página (`F5`) para dejar todo en su estado inicial.

## 6. Problemas frecuentes

| Problema | Solución |
| :--- | :--- |
| Aparecen símbolos raros en lugar de tildes | Abre `index.html` (incluye la codificación UTF-8), no una copia renombrada. |
| Las letras se ven con otra fuente | No hay internet; el contenido funciona igual. |
| Las animaciones no se mueven | El sistema tiene activado "reducir movimiento" (Windows: *Configuración → Accesibilidad → Efectos visuales → Efectos de animación*). Las simulaciones muestran el resultado final directamente. |
| Las flechas no cambian de capítulo | El foco está en un campo de texto. Haz clic en una zona vacía de la página. |
| Algo quedó a medias tras una demostración | `F5` recarga la página y reinicia todas las interacciones. |
