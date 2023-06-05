# css-block-model-lecture
Блочная модель в CSS определяет, как элементы HTML располагаются и заполняют место на странице. Она определяет размеры и расположение элементов, используя принцип блока, состоящего из отступов, границ, внутренних и внешних размеров. В этом докладе рассмотрим, как работает блочная модель, схлопывание отступов и арифметика блока на примерах кода.

Блочная модель CSS включает в себя следующие свойства: 

- width — ширина блока;
- height — высота блока;
- padding — внутренние отступы;
- margin — внешние отступы;
- border — границы блока.

Суммарная ширина элемента равна сумме ширины, внутреннего отступа, границы и внешнего отступа. Например,
если у элемента задана ширина 200px, внутренний отступ 20px, граница 2px и внешний отступ 10px, 
то общая ширина элемента будет равна 234px (200 + 20 * 2 + 2 * 2 + 10 * 2).


Схлопывание отступов происходит, когда вертикальные отступы смежных элементов объединяются в один отступ равный большему из двух. 
Это происходит в случае, когда вертикальный отступ между двумя блоками меньше, чем размер крупнейшего отступа.
Другими словами, если у первого блока есть отступ в 10px, а у второго блока есть отступ в 20px, то вертикальный отступ между ними будет равен 20px.
В данном примере, верхний отступ у блока равен 10px, а отступ у текста внутри блока равен 20px. В результате, верхний отступ блока увеличивается до 20px.

Арифметика блока — это способ вычисления размеров блоков с помощью CSS. Для этого используются относительные размеры, такие как проценты и эмы.
В данном примере, элементы внутри блока занимают 50%, 30% и 20% от его ширины. В результате, эти элементы занимают всю ширину блока.

CSS блочная модель является важным инструментом, позволяющим задавать размеры и положение элементов на веб-странице. 
Используя широкий спектр свойств, таких как ширина, отступы и границы, можно создавать уникальные макеты и дизайны. 
Схлопывание отступов помогает управлять расстоянием между элементами, а арифметика блока дает возможность гибко управлять
размерами элементов с использованием относительных значений. Хорошее знание блочной модели и инструментов, которые она предоставляет,
помогает создавать красивые, оптимизированные и практичные веб-сайты.


