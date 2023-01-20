# DataBase Sistema_Resilia

## ✳ Proposta do projeto <br>
➥ A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.

Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo: <br>
➥ Existem outras entidades além dessas três? <br>
➥ Quais são os principais campos e tipos? <br>
➥ Como essas entidades estão relacionadas? 
<br>

### ✳ Respostas

### Existem outras entidades além dessas três?

1. Sim, foram adicionadas mais duas entidades que são dados que podem ser levados em consideração em um sistema de Banco de Dados para uma instituição de ensino, foram elas: 
Matricula e Professores.

### Quais são os principais campos e tipos?

2. curso_id, turma_id e alunos_id são do tipo Int PK
   "id" tipo : INT PK <br>
   "nome" tipo = VARCHAR (quantidade aproximada para caracteres de acordo com a informacao pedida) <br>

### Como essas entidades estão relacionadas?

3. Relação entre curso e aluno (N:M) <br>
Relação entre curso e matricula (N:M) <br>
Relação entre curso e turma (N:M) <br>
Relação entre turma e professores (N:1) <br>
Relação entre matricula e alunos (N:M) <br>


## ✳ Extras
➥ Criar o banco de dados proposto e adicionar uma pasta chamada SQL com os arquivos.
 
 
## ✳ Modelo do Banco de Dados.

![curso_database_png](https://user-images.githubusercontent.com/113525360/213592327-04a7e476-7638-4ede-a3dc-673cc8f0fd1b.png)
