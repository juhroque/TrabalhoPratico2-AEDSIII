# TP02

## Relatório:

### Funções implementadas:
- menuBuscar (MenuLivros.java): Função onde damos a possibilidade ao usuário escolher se deseja buscar pelo ISBN ou por palavras relacionadas.
  
- buscarLivroByTitle (MenuLivros.java): Intermedia o menu de livros com a função "searchByTitle" da lista invertida e printa os resultados na tela.
  
- set (MenuLivros.java): Retira os livros repetidos.
  
- searchByTitle (ArquivoLivros.java): Essa função primeiramente recebe uma String (palavras chave) que será tratada removendo suas stopwords e separadas
  por espaço em um array de Strings. Em segundo plano, é iniciado um array de livros e um array de ids. Para cada palavra chave será realizada uma busca
  onde será retornada os ids dos livros com essa palavra e serão adicionados no array de ids. A função "countExpection" será chamada onde terá uma lógica
  para realizar a intersseção dos ids. Por último, é retornado um array de livros com os ids após a intersseção.
  
- countExpection (ArquivoLivros.java): Função que recebe o array de ids e um inteiro com a quantidade de palavras chave (logo, quantidade esperada que um id
  apareça), conta cada um deles e separa apenas os que aparecem na quantidade esperada.

### Experiência do grupo:
- A maior dificuldade enfrentada pelo grupo foi o entendimento do código inicial que usamos para implementar a busca por títulos. A partir do momento em que
  fomos compreendendo o código como um todo, a implementação se tornou mais fácil. Foram gastos muito tempo tentando solucionar a falta de caracteres especiais
  pelo scanner/system.out, até percebermos que se tratava da configuração do terminal onde o código estava sendo compilado (mesmo com esse problema, o código
  funciona normalmente). obs: recomendamos compilar o código pelo compilador diretamente de uma IDE (como o próprio vscode).

### Checklist:
- [x] A inclusão de um livro acrescenta os termos do seu título à lista invertida?
- [x] A alteração de um livro modifica a lista invertida removendo ou acrescentando termos do título?
- [x] A remoção de um livro gera a remoção dos termos do seu título na lista invertida?
- [x] Há uma busca por palavras que retorna os livros que possuam essas palavras?
- [x] Essa busca pode ser feita com mais de uma palavra?
- [x] As stop words foram removidas de todo o processo?
- [ ] Que modificação, se alguma, você fez para além dos requisitos mínimos desta tarefa?
- [x] O trabalho está funcionando corretamente?
- [x] O trabalho está completo?
- [x] O trabalho é original e não a cópia de um trabalho de um colega?

## Nomes
- Guilherme Otávio de Oliveira
- Gabriel Praes Bernardes Nunes
- Ana Fernanda Souza Cancado
- Júlia Pinheiro Roque
