# clean-code-typescript[PT-BR] [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Clean%20Code%20Typescript&url=https://github.com/labs42io/clean-code-typescript)

Conceitos de código limpo adaptados para TypeScript.
Inspirado em [clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript).

## Índice

   1. [Introdução](#introdução)
   2. [Variáveis](#variáveis)
   3. [Funções](#funções)
   4. [Objetos e Estruturas de Dados](#objects-and-data-structures)
   5. [Aulas](#aulas)
   6. [SÓLIDO](#sólido)
   7. [Teste](#teste)
   8. [Simultaneidade](#simultaneidade)
   9. [Tratamento de erros](#error-handling)
   10. [Formatação](#formatação)
   11. [Comentários](#comments)
   12. [Traduções](#traduções)

## Introdução

![Imagem humorística da estimativa de qualidade de software como uma contagem de quantos palavrões
você grita ao ler o código](https://www.osnews.com/images/comics/wtfm.jpg)

Princípios de engenharia de software, do livro de Robert C. Martin
[*Código limpo*](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882),
adaptabilidade para TypeScript. Este não é um guia de estilo. É um guia para produzir
[legível, reutilizável e refatorável](https://github.com/ryanmcdermott/3rs-of-software-architecture) em TypeScript.

Nem todos os princípios aqui contidos devem ser seguidos à risca, e menos ainda serão
universalmente acordado. Estas são orientações e nada mais, mas são
codificados ao longo de muitos anos de experiência coletiva pelos autores de
*Código limpo*.

Nosso ofício de engenharia de software tem pouco mais de 50 anos, e estamos
ainda aprendendo muito. Quando a arquitetura de software é tão antiga quanto a arquitetura
em si, talvez então tenhamos regras mais difíceis de seguir. Por enquanto, deixe esses
diretrizes servem como uma pedra de toque para avaliar a qualidade do
Código TypeScript que você e sua equipe produzem.

Mais uma coisa: saber disso não fará de você imediatamente um desenvolvedor de software melhor, e trabalhar com eles por muitos anos não significa que você não fará erros. 
Cada pedaço de código começa como um primeiro rascunho, como argila molhada ficando
moldado em sua forma final. Finalmente, esculpimos as imperfeições quando
nós o revisamos com nossos pares. Não se martirize pelos primeiros rascunhos que precisam
melhoria. Melhore o código em vez disso!

**[⬆ voltar ao início](#table-of-contents)**
