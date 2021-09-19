# Desafios ✨

Oiee Pessoal!

Bem vindos ao: Primerio Desafio da **Tech da Semana - MySQL**! Durante a semana iremos postar 3 Desafios/Incrementos, sendo eles: Fácil, Intermediário e Difícil.

Então chega de bate papo e boooooraaaaaaa codar </> 💻

---

### 1️⃣ Desafio - Fácil  - Cadastro de Livros

Deve ser montados queries SQL para a criação de uma tabela de livros na seguinte estrutura:

- [ ] id: inteiro auto-gerado (opcional utilizar uuid auto-gerado ou snowflake);
- [ ] name: texto (50 caracteres);
- [ ] description: texto (250 caracteres);
- [ ] author: texto (50 caracteres);

Depois as queries responsáveis por inserir um livro no banco, listar todos os livros, encontrar um livro, atualizar um livro e deletar um livro.

---

###  2️⃣ Desafio - Intermediário  - Usuários

Deve ser montado queries SQL para a criação de uma tabela de usuários na seguinte estrutura:

- [ ] id: inteiro auto-gerado (opcional utilizar uuid auto-gerado ou snowflake);
- [ ] name: texto (50 caracteres);
- [ ] age: inteiro;
- [ ] book: referência para um livro da tabela de livros ou pode estar vazio;

Além das queries para inserir, listar, encontrar, atualizar e deletar, deve haver uma query para definir um livro emprestado, atualizar o livro ou tirar o livro.

---

### 3️⃣ Desafio - Difícil -  Multi-Empréstimos

O empréstimo deve ser realizado através de uma tabela própria, a tabela deve ter a seguinte estrutura:

- [ ] id: inteiro auto-gerado (opcional utilizar uuid auto-gerado ou snowflake);
- [ ] user: referência para um usuário, não pode estar vazio, no caso de deleção, mantem o id;
- [ ] book: referência para um livro, não pode estar vazio, no caso de deleção, mantem o id;
- [ ] loan: data do empréstimo, hora que o empréstimo foi registrado no banco de dados;
- [ ] deadline: inteiro, dias que o empréstimo pode durar;

Como o empréstimo foi atualizado para uma tabela própria, a tabela de usuários deixa de ter a coluna book, e todos os livros já emprestados são registrados na tabela de empréstimos com deadline de 5 dias.

Agora um usuário pode emprestar mais de um livro por vez, e as queries devem ser para mostrar os empréstimos de um livro, de um usuário, ou organizar uma lista de livros e os empréstimos realizados, ou organizar uma lista de usuários e os empréstimos realizados.

---

- [ ] Envie no canal 🥇丨finalizados  seu repositório no Github com o resultado do Desafio

`OBS: Lembramos que esses Desafios são para estudo próprio sem nenhum tipo de revisão ou pontuação. Contudo, alguns projetos serão divulgados no Instagram da Rafa`

©️ **Comunidade Ballerini**
