# Replica de Revista

## Objetivo
Reforzar los aprendizajes adquiridos referente al HTML y CSS, sobre todo vincular conocimiento de construcción de estilos en editorial tradicional al digital.

## Tecnologías Utilizadas
- HTML5
- CSS3
- JavaScript
- Astro.js

## Cambios Implementados
Durante el desarrollo del proyecto se realizaron diversos ajustes en el diseño y en la estructura del código con el objetivo de mejorar tanto la organización visual como la eficiencia técnica del sitio. Uno de los cambios más relevantes fue la decisión de no emplear listas tradicionales dentro del marcado HTML para la construcción de los módulos de contenido, optando en su lugar por componentes reutilizables desarrollados en Astro.

Inicialmente, el contenido podía resolverse mediante estructuras repetitivas basadas en listas, sin embargo, este enfoque generaba redundancia en el código y limitaba la escalabilidad del proyecto. Al tratarse de una interfaz compuesta por elementos visualmente similares —como los bloques informativos o “tips”— resultaba más conveniente abstraer dichos elementos en componentes parametrizables capaces de recibir propiedades dinámicas, tales como número, título, contenido e imagen. Esta decisión permitió mantener una coherencia visual constante mientras se reducía significativamente la repetición estructural.

Desde una perspectiva de diseño para la comunicación gráfica, este ajuste también favorece la modularidad del sistema visual, ya que cada componente funciona como una unidad independiente que puede reutilizarse, reorganizarse o ampliarse sin alterar la arquitectura general del sitio. En consecuencia, el diseño deja de depender de una disposición rígida y se convierte en un sistema adaptable.

En síntesis, la eliminación del uso de listas respondió no únicamente a una decisión técnica, sino a una estrategia orientada a la reutilización, mantenimiento y escalabilidad del proyecto, alineando el desarrollo del código con principios contemporáneos de diseño modular y producción web eficiente.
