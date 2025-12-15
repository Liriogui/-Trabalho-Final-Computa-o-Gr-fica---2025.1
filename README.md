#📘 Trabalho Final – Computação Gráfica #

Animação 3D com Three.js

Este trabalho consiste no desenvolvimento de uma cena 3D animada utilizando a biblioteca Three.js, com o objetivo de aplicar, na prática, os principais conceitos estudados na disciplina de Computação Gráfica.

A cena é composta por objetos tridimensionais simples, como cubos e um plano que representa o chão, organizados em diferentes posições no espaço tridimensional. Essa organização permite evidenciar a noção de profundidade e a percepção espacial do ambiente virtual.

A visualização da cena é realizada por meio de uma câmera com projeção perspectiva, que simula a forma como o olho humano percebe o mundo real. Nesse tipo de projeção, objetos mais distantes aparentam ser menores, enquanto objetos mais próximos aparentam ser maiores, conforme estudado em sala de aula.

A animação é obtida pela aplicação contínua de transformações geométricas, como rotações e translações, tanto nos objetos quanto na câmera. A câmera realiza um movimento orbital ao redor da cena, alterando o ponto de vista do observador e reforçando o conceito de visualização tridimensional.

Para o tratamento das superfícies ocultas, o sistema gráfico utiliza automaticamente o algoritmo de z-buffer, garantindo que apenas as faces visíveis ao observador sejam renderizadas corretamente. Além disso, o descarte de faces traseiras (back-face culling) contribui para a eficiência da renderização.

O modelo de iluminação empregado é o modelo local de Phong, composto pelas componentes ambiente, difusa e especular. A luz ambiente garante uma iluminação mínima da cena, enquanto a luz pontual calcula a contribuição difusa e especular com base no ângulo entre a normal da superfície, a direção da luz e a posição do observador, produzindo sombreamento realista.

Dessa forma, o trabalho demonstra, de maneira prática, a aplicação integrada dos conceitos fundamentais de computação gráfica, como projeção, transformações geométricas, iluminação, sombreamento e visualização 3D.
