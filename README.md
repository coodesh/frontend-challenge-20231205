# Front-end Challenge - Onfly 20231205

## Introdução

Este é o nosso case técnico para Front-end! A ideia é que você possa mostrar toda sua expertise técnica através dele :D
Estamos animados para te ver brilhar novamente!

[SPOILER] As instruções de entrega e apresentação do challenge estão no final deste Readme (=

### Antes de começar

- Prepare o projeto para ser disponibilizado no Github, copiando o conteúdo deste repositório para o seu (ou utilize o fork do projeto e aponte para o Github). Confirme que a visibilidade do projeto é pública (não esqueça de colocar no readme a referência a este challenge);
- O projeto deve utilizar a Linguagem específica na sua Vaga (caso esteja se candidatando). Por exempo: Vue.js, Quasar e entre outras;
- Considere como *deadline 5 dias a partir do início do desafio*. Caso tenha sido convidado a realizar o teste e não seja possível concluir dentro deste período, avise a pessoa que o convidou para receber instruções sobre o que fazer.
- Documentar todo o processo de investigação para o desenvolvimento da atividade (README.md no seu repositório); os resultados destas tarefas são tão importantes do que o seu processo de pensamento e decisões à medida que as completa, por isso tente documentar e apresentar os seus hipóteses e decisões na medida do possível.

### Instruções iniciais obrigatórias

- Utilizar o framework Vue.js (opte pela versão que preferir)
- Utilizar o framework Quasar para a UI (pode usar outros, porém, conta muito para nós usar o Quasar ) ♥
- Utilizar classes para os dados.
- Seguir o protótipo da tela
- Busca de **Destinos** com **autocomplete**
- Filtros de ordenação aplicáveis a listagem (**Recomendados** e **Melhor Avaliados**)
  - Filtro por **Nome** será considerado um **diferencial** no seu teste!
- Scroll infinito (ao chegar no final da página, carregar mais 10 itens)

### Será um enorme **diferencial** para a gente se você: 
- Optar por usar **TypeScript**.
- Aplicar **Testes Unitários** em Componentes.

### Instruções

Vamos disponibilizar para você dois JSONs como fonte de dados. 

- Um será o [place.json](./assets/place.json), que contém as informações de 5 cidades brasileiras. 
- O segundo será o [hotel.json](./assets/hotel.json), nele está o relacionamento cidade versus hotéis.

Também iremos disponibilizar o protótipo da tela que você deverá nos entregar.

### Listagem

![<img src="assets/images/Listagem.png" height="500" alt="Home" title="Home"/>](assets/images/Listagem.png)

#### Formulário
- O campo Destinos deverá listar as opções no formato 'Belo Horizonte, Minas Gerais'. Quando selecionada uma opção, ela deverá ser exibida como 'Belo Horizonte, BH'.
- O botão deverá exibir 'Buscar' quando a busca estiver vazia e 'Alterar Busca' quando já tiver sido efetuado uma pesquisa.

#### Filtros
- Desenvolva o filtro Recomendados que deverá ordenar os hotéis pelo preço. Desenvolva o filtro Melhor Avaliados que deverá ordenar os hotéis pelo número de estrelas.

#### Listagem
- Apresente as imagens do hotel em um carrossel.
- Ao chegar no final da página, carregue mais 10 hotéis. Informe quando não há hotéis para listar.

![<img src="assets/images/Detalhes.png" height="500" alt="Home" title="Home"/>](assets/images/Detalhes.png)


#### Drawer
- Crie um drawer com as informações detalhadas hotel.
- Utilize novamente um carrossel para exibir as imagens do hotel e agora será necessário mostrar um contador dessas imagens.

## Readme do Repositório

- Deve conter o título do projeto
- Uma descrição sobre o projeto em frase
- Deve conter uma lista com linguagem, framework e/ou tecnologias usadas
- Como instalar e usar o projeto (instruções)
- Não esqueça o [.gitignore](https://www.toptal.com/developers/gitignore)
- Se está usando github pessoal, referencie que é um challenge by coodesh:  

>  This is a challenge by [Coodesh](https://coodesh.com/)

## Finalização e Instruções para a Apresentação

1. Adicione o link do repositório com a sua solução no teste
2. Verifique se o Readme está bom e faça o commit final em seu repositório;
3. Envie e aguarde as instruções para seguir. Caso o teste tenha apresentação de vídeo, dentro da tela de entrega será possível gravar após adicionar o link do repositório. Sucesso e boa sorte. =)


## Suporte

Para tirar dúvidas sobre o processo envie uma mensagem diretamente a um especialista no chat da plataforma. 
