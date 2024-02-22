
# Test Camp (Core)

Test Camp é um encontro quinzenal projetado para fornecer suporte e orientação para as estudantes que estão nos primeiros 3 projetos de bootcamp para que elas possam atingir os objetivos de aprendizagem relacionados ao teste. Neste espaço, nos reunimos para discutir dúvidas, ver estratégias de criação de teste e compartilhar informações relacionadas com as ferramentas de teste. A sessão é liderada por treinadores que compartilharão feedback sobre boas práticas, bem como recomendações para que as estudantes possam abordar os testes na fase core do bootcamp. Como resultado, espera-se cultivar as habilidades nas estudantes e maximizar o aproveitamento dessas técnicas fundamentais no desenvolvimento de software.

## Sessão de ativação

O espaço de ativação tem como objetivo transmitir a importância de fazer testes em seus projetos e comunicar como é a dinâmica que ocorre no test camp, bem como o convite para o espaço. Podemos nos apoiar nos seguintes slides: [Link para os slides](https://laboratoria.github.io/test-camp-docs/#/title-slide)

### Considerações na sessão de ativação:

- Duração: 1h
- O exercício começa a partir do exemplo da soma
- Acomodar, Atuar, Afirmar
- Suíte + Teste
- Aserção + Matcher

## Alinhamento como treinadores

A importância dos testes no bootcamp:
- Permite ter um código mantível
- Garantir a qualidade do código desde o início.
- Prevenir erros antes que o código vá para produção.
- Facilitar a integração e implantação contínua de forma segura.
- Ajuda a não ter código espaguete

O que os testes trazem para o código das estudantes:
- Verificação de que as funções realizam o que se espera delas (Validação de que o código cumpre os requisitos funcionais).
- Servir como documentação detalhada dos casos de uso e comportamentos esperados.
- Facilidade para fazer alterações e refatorações com a segurança de que não estão sendo introduzidos erros.

### Que testes contemplam os projetos no bootcamp

Existem diferentes tipos de testes previamente configurados nos projetos e testes como estudantes vale a pena investir tempo para garantir a qualidade do código.

#### Testes unitários

Um teste unitário é uma pequena peça de código que verifica se uma parte do código, (geralmente uma função), funciona corretamente, os testes unitários são usados para garantir que cada parte individual de um programa faça o que se supõe que deve fazer.

#### Testes de integração

Um teste de integração é um teste que verifica se todas as diferentes partes de um programa funcionam bem juntas. Imagine que você está construindo um quebra-cabeça e quer ter certeza de que todas as peças se encaixam corretamente. Ao contrário do teste unitário, o teste de integração não olha para cada peça individualmente, pelo contrário, um teste de integração se concentra em como todas essas peças se comportam quando trabalham juntas.

#### Testes e2e

Um teste de ponta a ponta (E2E) é um teste que testa a experiência completa do usuário, do início ao fim, como se fosse um usuário real interagindo com um aplicativo. Imagine que você é um cliente usando um aplicativo: você clica em botões, preenche formulários e navega por diferentes páginas, o teste E2E verifica se o aplicativo funciona como deveria do ponto de vista do usuário. Semelhante a ter alguém que testa cada parte do aplicativo, do início ao fim, para garantir que tudo funcione corretamente.

## Boas práticas

- Falar sobre a diferença entre o teste vs executar o pré-teste a relevância que tem eslint no ciclo de vida do seu projeto.
- Falar sobre o padrão AAA no teste
"Arrange, Act, Assert":
  - Arrange (organizar o ambiente): Nesta fase, são estabelecidas as condições iniciais e são configurados os objetos necessários para o teste. Isso pode incluir a criação de objetos, a configuração de variáveis e a preparação do ambiente de teste.
  - Act (Atuar): Nesta fase, é realizada a ação ou o comportamento que está sendo testado. É a execução do código que está sendo avaliado.
  - Assert (Afirmar): Aqui é verificado o resultado esperado da ação realizada na etapa anterior. Verifica-se se o resultado coincide com o que se espera de acordo com a lógica do teste. Se a afirmação for verdadeira, o teste passa; caso contrário, falha.
- Falar sobre convenções utilizando jest
  - Estruturação de testes utilizando describe e it.
  - Implementação de asserções com expect.
  - String com afirmações completas do que deveria fazer
- Gravar a sessão
- Alguns Mantras sobre Testes no Laboratória
  - AAA: Organizar o Ambiente, executar Ação. Finalmente Afirmar o esperado.
  - Evitar testar detalhes de implementação (testar o que faz, não tanto como faz)
  - É melhor pedir perdão do que permissão (ex.: executar a função, em vez de verificar se é uma função).
  - Os testes devem refletir as histórias dos usuários (da especificação, spec).
