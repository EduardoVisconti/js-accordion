1. Criar o sec c div container borda > com a div do accordion e dentro o button com a class acc button e borda, dentro do botao o titulo. > Depois a ultima div do acc content e com border tb. > p com lorem.

2. No css, estilizar a borda com red, pra ser visível >> acc button Display tem que ser block (procurar saber o pq) com largura 100%. Colocar o cursos com bg transparente, padding e margin top >> acc cont, onde vai ter o overflow hidden e a altura (0 ou auto)

3. JS: pegar o document. e selecionar todas as tags do botao, e para cada item (button =>{ = adicionar o evento do click em uma arrow function V

- criar uma const accordionContent com button.nextElementSibling (seleciona o próximo "irmão")
- no botao adicionar a classe toggle ('active')

- if no botao classList contains active = accordionContent.style.maxHeight = accordionContent.scrollHeight + px [ALTURA AUTOMÁTICO DO SCROLL, volta a altura da dimensão da div]

- else > accordionContent.style.maxHeight = 0

4. E pra ficar correto a forma de começo, esta todos fechados assim que abre, no começo do arquivo selecionar todos os .accordionContent, e para cada item fazer um arrow function e colocar o item.style.maxHeight no 0.

se estiver ativo tem que estar na altura automática
