# Teste-estagio-back: Criando um Catálogo de Filmes com a API OMDB

# Objetivo:
Criar um script Python que permita ao usuário pesquisar e catalogar filmes usando a API OMDB

# Requisitos:
### 1. Crie um Script Python que permita ao usuário realizar as seguintes operações:
  
  - Pesquisar um filme por título e exibir suas informações detalhadas.
  - Permitir adicionar filmes à lista de favoritos o filme pesquisado.
  - Listar todos os filmes favoritos.


### 2. Implemente um menu para que o usuário possa escolher entre as opções mencionadas no requisito 1.
 - O menu de seleção das operações pode ser implementado de forma simples, utilizando apenas o terminal e números para que o usuário escolha cada operação.
   
### 3. Use a API OMDB para obter informações sobre os filmes.
 - Site da API contendo as infromações para uso: (http://www.omdbapi.com/)
 - **Obs. É necessário uma api-key para usar a API**.<br>
![Captura de tela de 2023-09-27 10-42-31](https://github.com/Omnisaude/teste-estagio-back/assets/86317360/dbcf16b4-3d98-4267-8bc4-6fb896b764f1)
 - Para solicitar uma nova API-Key basta selecionar a opção "Free" e preecher com seu email.
![Captura de tela de 2023-09-27 11-00-21](https://github.com/Omnisaude/teste-estagio-back/assets/86317360/aaf129ec-7618-4f0e-aea0-d7f1e7f85f44)
 - Após solicitar sua API-Key ela chegará por email com orientação de uso e um link para ativação.
 - Agora é só usar a API. Ex. https://www.omdbapi.com/?apikey=<sua_api-key>&t=avatar
   
### 4. Ao pesquisar um filme, tente exibir pelo menos os seguintes detalhes:

  - Título do filme.
  - Ano de lançamento.
  - Classificação.
  - Sinopse.
  - Diretor.

### 5. Adicionar um filme à lista de favoritos:
 - Armazene as informações do filme em um arquivo de texto ou JSON para que os favoritos possam ser acessados posteriormente.

### 6. Documentação
   - Crie uma pequena documentação simples (arquivo README.md no repositório do github) descrevendo seu código.

### 7. Envio do Projeto
   - Envie o link do repositório no GitHub para o e-mail: weslley@omnisaude.co (lembrando que esse repositório deve ser público e deve ter um arquivo README.md onde estará a sua documentação citada no item 6)
   - O e-mail deve ter o assunto: "Teste para Estágio Back-end - [seu nome]"

### 8. Prazo
   - Você terá 3 dias a partir da data de recebimento deste e-mail para completar o projeto e enviar o link do repositório.

# Dicas:
- Use a biblioteca requests para fazer requisições HTTP à API OMDB.
- Considere criar uma classe para representar um filme, o que pode tornar mais fácil trabalhar com os dados.
- Pode ser útil usar um loop para permitir que o usuário execute várias operações em sequência até que escolha sair do programa.
- No site da API tem uma documentação sobre como utiliza-la. <br>
- Use a biblioteca requests para usar a API.


# Avaliação:

## O teste será avaliado com base nos seguintes critérios:

- Funcionalidade: O programa atende a todos os requisitos especificados?

- Qualidade do código: O código é organizado, legível e bem documentado?

- Armazenamento de favoritos: Os filmes favoritos são armazenados e acessados corretamente?
