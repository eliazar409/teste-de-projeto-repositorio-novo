## O que é Teste de Software?

------

![img](https://www.portalgsti.com.br/media/uploads/marcomascarenhas/teste-de-software.jpg)**Teste de Software** é um processo que faz parte do [#desenvolvimento](https://www.portalgsti.com.br/categoria/desenvolvimento/) de software, e tem como principal objetivo revelar falhas/bugs para que sejam corrigidas até que o produto final atinja a qualidade desejada / acordada.



Profissionais que trabalham com testes (denominados [analistas de testes](https://www.portalgsti.com.br/profissoes-de-ti/analista-de-testes/), técnicos de testes, homologador, ou simplesmente testes) estão habituados a realizar uma bateria de testes de diferentes naturezas e propósitos, envolvendo não apenas os testes funcionais da aplicação, mas diversas outras atividades como:

- avaliação da especificação de requisitos,
- avaliação de projeto técnico,
- verificações em outros documentos,
- testes de performance e capacidade,
- avaliação de interface,
- dentre outros.

Para ter uma ideia a respeito da diversidade e abrangência de atividades que fazem parte do processo de testes, é apresentada a seguir uma tabela com alguns tipos de testes comuns.





## Tipos de Testes

------

Lista dos tipos de testes que podem ser feitos:

| **Tipo de Teste**             | **Descrição**                                                |
| ----------------------------- | ------------------------------------------------------------ |
| Teste de Unidade              | Teste em um nível de componente ou classe. É o teste cujo objetivo é um “pedaço do código”. |
| Teste de Integração           | Garante que um ou mais componentes combinados (ou unidades) funcionam. Podemos dizer que um teste de integração é composto por diversos testes de unidade. |
| Teste Operacional             | Garante que a aplicação pode rodar muito tempo sem falhar.   |
| Teste Positivo-negativo       | Garante que a aplicação vai funcionar no “caminho feliz” de sua execução e vai funcionar no seu fluxo de exceção. |
| Teste de Regressão            | Toda vez que algo for mudado, deve ser testada toda a aplicação novamente. |
| Teste de Caixa-preta          | Testar todas as entradas e saídas desejadas. Não se está preocupado com o código, cada saída indesejada é visto como um erro. |
| Teste Caixa-branca            | O objetivo é testar o código. Às vezes, existem partes do código que nunca foram testadas. |
| Teste Funcional               | Testar as funcionalidades, requerimentos, regras de negócio presentes na documentação. Validar as funcionalidades descritas na documentação (pode acontecer de a documentação estar inválida) |
| Teste de Interface            | Verifica se a navegabilidade e os objetivos da tela funcionam como especificados e se atendem da melhor forma ao usuário. |
| Teste de Performance          | Verifica se o tempo de resposta é o desejado para o momento de utilização da aplicação. |
| Teste de Carga                | Verifica o funcionamento da aplicação com a utilização de uma quantidade grande de usuários simultâneos. |
| Teste de Aceitação do usuário | Testa se a solução será bem vista pelo usuário. Ex: caso exista um botão pequeno demais para executar uma função, isso deve ser criticado em fase de testes. (aqui, cabem quesitos fora da interface, também). |
| Teste de Volume               | Testar a quantidade de dados envolvidos (pode ser pouca, normal, grande, ou além de grande). |
| Testes de Stress              | Testar a aplicação sem situações inesperadas. Testar caminhos, às vezes, antes não previstos no desenvolvimento/documentação. |
| Testes de Configuração        | Testar se a aplicação funciona corretamente em diferentes ambientes de hardware ou de software. |
| Testes de Instalação          | Testar se a instalação da aplicação foi OK.                  |
| Testes de Segurança           | Testar a segurança da aplicação das mais diversas formas. Utilizar os diversos papéis, perfis, permissões, para navegar no sistema. |

## TDD

------

O custo de correção de um bug aumenta até mais de 100x quando corrigido nas fases finais de [desenvolvimento](https://www.portalgsti.com.br/desenvolvimento/), quando comparado ao custo de corrigir a mesma falha em fases iniciais. Por reconhecer este fato e por entender a relevância dos testes no processo de desenvolvimento, muitas empresas, profissionais e equipes optam por um método de desenvolvimento denominado TDD (Test Driven Development) – Desenvolvimento Orientado a Testes.





A ideia é que funcionalidades de testes sejam escritas antes mesmo do desenvolvimento das funcionalidades do sistema. Desta forma, as funcionalidades desenvolvidas precisarão “passar no teste” para serem validadas. Para saber mais, recomendamos: [Programação Orientada a Testes](http://www.portalgsti.com.br/2011/09/curso-gratuito-online-de-tdd.html).