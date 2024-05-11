# Alura_WonderWorld
Projeto feito para a imersão IA Gemini da Alura.

O projeto consiste em entrar com o nome de um lugar, e obter informações como a melhor época para visitar, curiosidades, e previsão do tempo na época sugerida. Se existir mais de um lugar contendo o nome informado, exibirá um dropdown com as opções disponíveis. Ao clicar em uma das opções, retorna as informações. Se houver somente um lugar com o nome informado, já exibe as informações direto.

Observação: Por mais que eu tenha insistido no prompt inicial de diversas formas para não incluir itens na lista quando não for possível obter todas as propriedades, ainda pode ocorrer do modelo incluir estes itens na lista, com propriedades com valor 'None'.

Criei um "Helper" em outro trecho de código, para não precisar ficar mudando de aba para fazer perguntas ao Gemini. Estava usando para me auxiliar na construção do projeto. Este Helper foi criado baseado no que foi ensinado na Aula 4, mas fiz algumas modificações como substituir o input por um textarea, com o objetivo de obter uma melhor visualização de prompts longos. Também deixei o código para exibir histórico, da Aula 4.

.

p.s.: Minha idéia inicial para o projeto não era essa, porém não consegui fazer o que queria. Envolvia integração com outra(s) API(s), e obtenção de keys para usar eram burocráticas e não haveria tempo hábil para obter, usar e desenvolver o proejto até o prazo final da entrega. 
