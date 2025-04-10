1. Criar o sec c div container borda > com a div do accordion e dentro o button com a class acc button e borda, dentro do botao o titulo. > Depois a ultima div do acc content e com border tb. > p com lorem.

2. No css, estilizar a borda com red, pra ser visível >> acc button Display tem que ser block (procurar saber o pq) com largura 100%. Colocar o cursos com bg transparente, padding e margin top >> acc cont, onde vai ter o overflow hidden e a altura (0 ou auto)

3. JS: criar a const e select todos os botoes, para cada item (button =>{ = adicionar o evento do click para executar > criar uma const com cada accordionContent e button.nextelementsibling > adiciona a classe com toggle nos botoes ('active') >> if dentro do botao contains active = acccontent.style.maxheight = acccontent.scrollheight + px [ALTURA AUTOMATICO DO SCROLL, volta a altura da dimensao da div] >> else >> acccont.style.maxheight = 0

4. E pra ficar correto a forma de comeco, esta todos fechados assim que abre, no comeco do arquivo selecionar todos os .acccontent, e para cada item fazer um arrow function e colocar o item.style.maxheight no 0.

se estiver ativo tem que estar na altura automatica 