# La prueba Chi-cuadrado (χ²)

Sitio de la sesión del **1 de octubre de 2026** · Doctorado en Ciencias Económicas y Administrativas,
Universidad de Sonora · materia de Procesamiento y análisis de datos.
Tema del programa: *Chi cuadrada y tabulaciones cruzadas*. Software de los ejercicios: IBM SPSS.

Presentación de **Maritza Moreno Grano**. Versión web homologada por Eduardo Salas García
(esalas@eduardosalas.com), con el mismo formato que las presentaciones de las sesiones anteriores.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio **público** en GitHub. Un nombre corto ayuda porque será parte del link:
   por ejemplo `chi-cuadrada`.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (los archivos, no la carpeta
   que los contiene). Puedes arrastrarlos a la interfaz web de GitHub con *Add file → Upload files*.
3. En el repositorio ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**; en *Branch* elige **main** y la carpeta **/ (root)**.
   Guarda.
5. Espera uno o dos minutos. GitHub te mostrará el link, con la forma
   `https://TU-USUARIO.github.io/chi-cuadrada/`
6. Comparte ese link con el grupo.

## Estructura

```
index.html                              La presentación: 61 láminas en un solo archivo, funciona sin internet
assets/                                 Figuras y capturas de SPSS recortadas de las diapositivas originales (JPG)
datos/Cerveceria.sav                    150 consumidores: sexo × tipo de cerveza (caso Alber's)
datos/NYReform.sav                      100 entrevistas: Party, PayCut, Lobbyists, TermLimits
datos/Student_Performance.sav           649 estudiantes (base de la tarea)
docs/Presentacion_chi_cuadrada.pdf      La presentación original de la expositora (59 diapositivas)
docs/Guia_SPSS_Chi_Cuadrada.pdf         Guía práctica de la expositora: chi-cuadrada de independencia en SPSS
(no se incluye)                         Tabla chi-cuadrada: consúltala en Anderson et al., Apéndice B, Tabla 3 (material con derechos de autor)
docs/Hardwicke_2022_helmet_use.pdf      Artículo científico de la sesión
```

Los documentos se renombraron sin acentos ni espacios para que los enlaces funcionen en cualquier
servidor: `Presentación chi-cuadrada.pdf` → `Presentacion_chi_cuadrada.pdf`, `Tabla.pdf` →
`Tabla_chi_cuadrada.pdf`, `Artículo Hardwicke 2022 an investigation into helmet use.pdf` →
`Hardwicke_2022_helmet_use.pdf`. El contenido de los archivos no se modificó.

## Cómo descargan los archivos tus compañeros

En la lámina 60, **Materiales**, hay un botón por cada base y por cada documento. Al hacer clic, el
archivo se descarga directo a la carpeta de descargas, porque los enlaces llevan el atributo `download`.

Tres cosas que conviene cuidar:

1. **Sube las carpetas `datos/`, `docs/` y `assets/` completas.** Sin ellas los botones darán error 404
   y las capturas de SPSS no se verán.
2. **Comparte el link de Pages, no el del repositorio.** El de Pages tiene la forma
   `https://TU-USUARIO.github.io/repo/`.
3. **Respeta mayúsculas y minúsculas.** GitHub Pages distingue entre `NYReform.sav` y `nyreform.sav`.

## Cómo usar la presentación

| Acción | Cómo |
|---|---|
| Avanzar y retroceder | Flechas `→` `←`, barra espaciadora, o deslizar en móvil |
| Abrir el índice de bloques | Tecla `M` o botón **Bloques** |
| Saltar a un bloque | Teclas `1` a `7` |
| Ir a una lámina concreta | Agrega `#dN` al link, por ejemplo `#d44` |
| Cambiar entre tema claro y oscuro | Tecla `T` |
| Pantalla completa | Tecla `F` |
| Exportar a PDF | Botón **PDF** de la barra inferior |

Bloques (según la estructura de la expositora): Introducción (1–2) · Bloque 1, La distribución χ²
(3–14) · Bloque 2, Prueba de independencia (15–27) · Bloque 3, Práctica en SPSS (28–32) · Bloque 3,
Ejercicio de práctica NYReform (33–52) · Tarea (53–55) · Artículo científico (56–59) · Materiales e
índice (60–61).

## Ajustes de la versión web

Cada una de las 59 diapositivas originales es una lámina, en el mismo orden, con los mismos títulos y
textos (transcritos de las imágenes, no del OCR). Lo que cambió respecto al PDF:

- **Láminas agregadas:** 60 (Materiales, con los botones de descarga) y 61 (Índice final). La portada
  es la diapositiva 1 de la expositora, con su mismo texto; solo se le añadió la línea de atajos de
  teclado que llevan todas las presentaciones del curso.
- **Tablas** como tablas HTML reales, incluidas las salidas de SPSS de las diapositivas 44, 45, 47, 48,
  50 y 51 (procesamiento de casos, tablas cruzadas y pruebas de chi-cuadrado), con las mismas cifras.
- **Imágenes recortadas** de las diapositivas: escudo de la portada (1), gráficas de barras (3 y 4),
  curva χ² (9), las ocho capturas de SPSS (36 a 43) y los tres gráficos de barras de SPSS (45, 48 y 51).
- **Diapositiva 9:** en el original era un control deslizante para cambiar k. Aquí es estática: se
  muestra la curva tal como aparece en la diapositiva (k = 3) y la lista de valores del control.
- **Diapositiva 26:** la salida de texto (Expected counts…, Chi-Sq = 6.122…) se transcribió como texto.
- El encabezado repetido «CAPÍTULOS 11–12 · χ²» y el rótulo de sección de cada diapositiva pasaron a
  la barra inferior; las etiquetas de bloque («BLOQUE 1 · CAPÍTULO 11», «CAPTURA SPSS 01/17», etc.) se
  conservan arriba del título. Los colores siguen la paleta común del curso.

## Notas de revisión

Posibles errores del contenido original. **Se conservaron tal cual en las láminas**; quedan aquí para
que decidas si se corrigen.

1. **«No rechazar H₀ (independientes)».** Las láminas 13 («No se rechaza H₀ (no hay relación / se
   ajusta)»), 19, 20, 25 y 31, y la Guía de SPSS (p. 7), presentan el no rechazo de H₀ como prueba de
   independencia. No rechazar H₀ solo indica que no hay evidencia suficiente de asociación. La
   redacción correcta es la que la propia expositora usa en las láminas 49 y 52: «no existe evidencia
   estadística suficiente para afirmar que las dos variables analizadas estén asociadas». En la 20, la
   conclusión «la preferencia por el café no está relacionada con el género» tiene el mismo problema.
2. **Bloque 1 rotulado «Capítulo 11».** En Anderson, la prueba χ² de independencia y la de bondad de
   ajuste están en el **capítulo 12** (secs. 12.1 y 12.2); el capítulo 11 usa la χ² para inferencias
   sobre varianzas, que no se vieron en la sesión. El ejemplo del color favorito (lámina 14) es una
   prueba de bondad de ajuste (sec. 12.1). Afecta a las etiquetas de las láminas 2 a 14.
3. **Lámina 59, p = 0.001.** Para «Disciplina y uso voluntario del casco» el artículo reporta
   **p &lt; 0.001** (χ² = 39.956). En la misma tabla, la fila «Disciplina y percepción de protección
   cerebral» deja el hallazgo en blanco («—»); el artículo indica que BMX y audax/larga distancia
   respondieron correctamente con mayor frecuencia.
4. **Lámina 35, ruta para el .xlsx.** Indica `Archivo → Abrir → Datos` para NYReform.xlsx, mientras
   que las capturas 36–38 y la Guía usan `Archivo → Importar datos → Excel…`. Además nombra las
   variables «Afiliación» y «ReducirSueldo»; en la base se llaman `Party` y `PayCut`.
5. **Lámina 33, archivo NYReform.xlsx.** La lámina anuncia un .xlsx descargable; en `datos/` se
   entrega `NYReform.sav` (la base que se recibió), que abre directo con `Archivo → Abrir → Datos`.
6. **Lámina 25, valor p.** Da 0.0469 como valor exacto (calculado con χ² redondeado a 6.12); SPSS y la
   salida de la lámina 26 reportan 0.047. La diferencia es de redondeo.
7. **Lámina 44, esperado Republican–SI = 32.0.** El valor exacto es 31.95 (45 × 71 / 100); otras
   corridas de SPSS lo muestran como 31.9. Es redondeo, no error de cálculo.
8. **Lámina 57, versión de SPSS.** Dice v.26, como el texto del artículo (sec. 2.3); la referencia 45
   del mismo artículo dice 27.0.
9. **Lámina 31, «Sig. asintótica (bilateral)».** Aunque SPSS la rotule así, la prueba de independencia
   es de cola superior (como dice la lámina 25) y ese valor ya es el área a la derecha del χ²
   calculado: no se divide entre 2.

## Si falla el internet en el aula

`index.html` no carga nada de la red: solo usa los archivos de `assets/`. Descarga la carpeta completa
y abre `index.html` desde tu computadora. Como segundo respaldo está
`docs/Presentacion_chi_cuadrada.pdf`.

## Fuentes

- Anderson, D. R., Sweeney, D. J., & Williams, T. A. *Estadística para administración y economía*.
  Cengage Learning. Capítulo 12 (prueba de bondad de ajuste y prueba de independencia) y Apéndice B,
  Tabla 3.
- Hardwicke, J., Baxter, B. A., Gamble, T., & Hurst, H. T. (2022). An investigation into helmet use,
  perceptions of sports-related concussion, and seeking medical care for head injury amongst competitive
  cyclists. *International Journal of Environmental Research and Public Health, 19*(5), 2861.
  <https://doi.org/10.3390/ijerph19052861>
- Cortez, P. (2008). *Student Performance* [Dataset]. UCI Machine Learning Repository.
  <https://doi.org/10.24432/C5TG7T>
- Ejemplo del café: Lifeder, «Chi-cuadrado (χ²): distribución, cómo se calcula, ejemplos» (citado en
  la lámina 17).
