 # Arquitectura moderna — A+B+C (sin lío de diagramas)
 **Alumno/a: Daniel Lorente Alarcón
 **Grupo: 1º ASIR
 **Arquitectura elegida: Intel Foveros
--
## A) Básico — Qué es y para qué sirve (3–5 líneas)- Intel Foveros es una tecnología de empaquetado 3D que permite apilar múltiples chips (chiplets)
verticalmente en lugar de colocarlos uno al lado del otro. Se utiliza en procesadores para portátiles, servidores y centros de datos, 
como Meteor Lake y Ponte Vecchio. Su principal ventaja es la integración heterogénea: combina CPU, GPU, aceleradores y memoria en un solo paquete,
mejorando la eficiencia energética y el rendimiento.
 ### Representación visual 

Este diagrama muestra los bloques principales de la arquitectura Intel Meteor Lake, basada en empaquetado Foveros:


**O1. Lista de bloques Ejemplo**- CPU (…)- GPU/NPU (…)- Memoria (DDR/HBM/unificada) (…)- E/S (PCIe/CXL/NoC) (…)
 ### CAPTURA 1 — Búsqueda avanzada (con tu nombre y grupo)
 ### CAPTURA 1 — Búsqueda avanzada (con tu nombre y grupo)

La siguiente captura muestra una búsqueda avanzada realizada en Google, incluyendo mi nombre y grupo,
para encontrar documentación oficial sobre la arquitectura Intel Foveros:


## B) Intermedio — Problema que mejora + comparativa
 **Problema que mejora (1–2 líneas):** …
**Tabla comparativa (≥3 filas)**
 | Aspecto | PC clásico monolítico | Arquitectura elegida |
 |---|---|---|
 | ISA(Instruction Set Architecture) |x86 tradicional | x86, pero distribuido en tiles especializados|
 | Memoria |DDR externa conectada por bus | LPDDR integrada en el paquete, más cercana al CPU|
 | Interconexión |Horizontal (bus tradicional) |Vertical (Die-to-Die con FDI, TSV, microbumps) |
 | Aceleradores |Limitados o externos | Integrados en tiles dedicados (GPU, NPU, etc.)|
 | Objetivo principal |Rendimiento general con diseño único |Modularidad, eficiencia energética y escalabilidad |
 Nota: Crea un glosario para explicar que teminos que no controles. Por si
 te pregunto.  
 GLOSARIO:
|-ISA (Instruction Set Architecture):| Conjunto de instrucciones que puede ejecutar un procesador. x86 es la más común en PCs.
|-DDR / LPDDR: Tipos de memoria RAM.| LPDDR es más eficiente y se usa en dispositivos móviles y empaquetados modernos.
|-Interconexión vertical (TSV, FDI):| Tecnología que permite conectar chips apilados en 3D, reduciendo latencia y consumo.
|-Chiplet / Tile:| Bloques funcionales independientes (CPU, GPU, etc.) que se ensamblan en un solo paquete.
|-Aceleradores:| Componentes especializados para tareas como gráficos (GPU) o inteligencia artificial (NPU).
|-Monolítico:| Diseño de chip único con todos los componentes integrados en una sola pieza de silicio.
|-Disgregado / Disaggregated:| Diseño modular con múltiples chips especializados conectados entre sí.
### CAPTURA 2 — Fuente oficial/técnica

 `![fuente](img/02_fuente.png)`--
## C) Curioso — Dato/cifra + evidencia
 **Dato/cifra (1 frase):** La fuente indica que la tecnología Foveros Direct utilizada en Meteor Lake alcanza una densidad de interconexión superior a 10,000 bumps por milímetro cuadrado con un consumo energético inferior a 0.05 picojulios por bit.
 “La fuente indica … (poner aquí la
 cifra/etiqueta y modelo).”
 ### CAPTURA 3 — Dato/diagrama señalado
 
 `![dato](img/03_dato.png)`--
## Fuentes (≥2 enlaces)
 1.https://www.hc34.hotchips.org/assets/program/conference/day2/Mobile%20and%20Edge/Meteor_Lake_Hotchips%20_%20Wilfred%20_%20final_submit%20(1).pdf
 2https://www.bing.com/search?pglt=299&q=site%3Aintel.com+Meteor+Lake+architecture&cvid=52e8d420c6f8410cafe140857b049c84&gs_lcrp=EgRlZGdlKgYIABBFGDkyBggAEEUYOTIGCAEQRRg60gEHNTY0ajBqMagCALACAA&FORM=ANNTA1&PC=U531
