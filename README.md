#  Matemáticas Simbólicas

> Un nuevo tipo de matemáticas donde los números se reemplazan por **símbolos compuestos de partes** (`+`, `-`, `x`, `/`).
> Cada operación produce un único símbolo existente… o **No definido**.

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="Sin dependencias" src="https://img.shields.io/badge/dependencias-0-brightgreen?style=for-the-badge">
  <img alt="Idiomas" src="https://img.shields.io/badge/idiomas-50-blueviolet?style=for-the-badge">
  <img alt="Licencia MIT" src="https://img.shields.io/badge/licencia-MIT-yellow?style=for-the-badge">
</p>

---

##  ¿Qué es esto?

**Matemáticas Simbólicas** es una calculadora experimental que opera con **símbolos** en lugar de números. Cada símbolo está definido internamente por la cantidad de partes que contiene:

| Símbolo | Composición |
|:-------:|:-----------:|
| `+`     | 1 × `+`     |
| `++`    | 2 × `+`     |
| `#`     | 4 × `+`     |
| `##`    | 8 × `+`     |
| `-`     | 1 × `-`     |
| `--`    | 2 × `-`     |
| `≡`     | 4 × `-`     |
| `x`     | 1 × `x`     |
| `✖`     | 4 × `x`     |
| `/`     | 1 × `/`     |
| `÷`     | 4 × `/`     |
| `±`     | 1 × `+` y 1 × `-` |

La operación se realiza **parte por parte** y el resultado **debe ser un solo símbolo existente**. Si la composición resultante no coincide con ningún símbolo → **No definido**.

---

##  Características

-  **Motor simbólico** que opera componente a componente.
-  **Interfaz oscura** con resaltado visual de cada parte.
-  **50 idiomas** con selector y persistencia (`localStorage`).
-  **Catálogo editable**: puedes añadir símbolos nuevos desde la interfaz.
-  **Ejemplos predefinidos** con un clic.
-  **Validación completa** de sintaxis, símbolos desconocidos y operaciones inválidas.
-  **Cero dependencias**: un solo archivo HTML funciona offline.
-  **Diseño responsive** para móvil y escritorio.

---

## Otras alternativas

- Matemáticas normal

- Matemáticas 2.0

- Matematicas Computacionales
