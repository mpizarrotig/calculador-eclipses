# Calculador de Eclipses de Philippe de La Hire

Este proyecto es una reconstrucción científica y digital de la "Máquina de Eclipses" concebida por el astrónomo y matemático francés **Philippe de La Hire** (1640-1718). El objetivo es doble: preservar el conocimiento histórico mediante una simulación interactiva y facilitar la fabricación de una réplica física funcional mediante una maqueta imprimible.

## 📜 Contexto Histórico
El predictor de eclipses de La Hire es un dispositivo mecánico analógico (volvelle) diseñado a principios del siglo XVIII para resolver el complejo problema de la predicción de eclipses solares y lunares. Documentado originalmente en sus *Tabulae Astronomicae* (1702/1718) y popularizado en las *Récréations mathématiques et physiques* de Jacques Ozanam (1778), este instrumento permitía a astrónomos determinar efemérides sin necesidad de complejos cálculos trigonométricos.

## 🚀 Características del Proyecto
* **Simulación Interactiva:** Interfaz web (`index.html`) que permite rotar los discos (volvelles) mediante interacción táctil o ratón, con controles para simular eclipses históricos y ajustar los parámetros astronómicos.
* **Maqueta imprimible:** Manual en formato PDF con instrucciones de uso, ejemplos y piezas para imprimir, recortar y ensamblar.
* **Precisión Astronómica:** Implementación de la constante histórica de La Hire (año de eclipse de 346 + 2/3 días), corregida para garantizar la alineación precisa de las fechas.

## 🛠 Estructura del Proyecto
* `/assets`: Contiene los archivos vectoriales (.svg) y grabados históricos.
* `index.html`: Simulador interactivo basado en JavaScript.
* `calculador_eclipse.pdf`: Manual de montaje y plantillas a escala.

## 📝 Uso
1. **Simulador Digital:** Abre el archivo `index.html` en cualquier navegador moderno para interactuar con la volvelle digital.
2. **Réplica Física:** Ejecuta el script de Python para actualizar las plantillas y genera el PDF. Imprime las piezas en cartulina, recórtalas siguiendo las líneas de corte (marcadas con `- - -`) y únelas mediante un encuadernador de latón.

## 📚 Referencias Bibliográficas
* Gislén, L., & Eade, C. (2016). *Philippe de la Hire’s eighteenth century eclipse predictor*. Journal of Astronomical History and Heritage.
* La Hire, P. de (1702). *Tabulae astronomicae*. Parisiis.
* Ozanam, J. (1778). *Récréations mathématiques et physiques*. Chez C.-A. Jombert.

## ✍️ Autoría
**Autor:** Manuel Pizarro, 2026.

---
*Este proyecto está licenciado bajo los términos de Creative Commons BY-NC-ND 4.0.*
