<h1 align="center"> Projeto Banco faculdade </h1>

<b> introdução: </b><br>
    Este projeto foi feito durante um curso tecnico de DBA no SENAI, tudo neste 
projeto foi feito por mim (Emerson), incluindo modelo conceitual, modelo logico, script, alters, e inserts, consiste em um banco de dados para gerenciamento de uma faculdade. Os objetivos deste banco de dados são: Realizar controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar e turmas.

<b> Regras de negocio: </b><br>
    Uma faculdade de nome Universidade SENAI deseja mudar o seu siste-ma, e para isso
ela precisa criar e implementar um novo banco de dados que permi-ta a ela, realizar o 
controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar
e turmas. Após uma longa conversa com o cliente o analista de requisitos chegou nas
seguintes regras de negócio.

•Um aluno só pode estar matriculado em um curso por vez;<br> 
•Alunos possuem um código de identificação (RA);<br> 
•Cursos são compostos por várias disciplinas;<br> 
•Cada disciplina terá no máximo 30 alunos por turma;<br> 
•As disciplinas podem ser obrigatórias ou optativas, dependendo do curso;<br>
•As disciplinas pertencem a departamentos específicos;<br> 
•Cada disciplina possui um código de identificação;<br> 
•Alunos podem trancar matrícula, não estando então matriculados em nenhuma disciplina no semestre;<br> 
•Em cada semestre, cada aluno pode se matricular em no máximo 9 disciplinas;<br> 
•O aluno só pode ser reprovado no máximo 3 vezes na mesma disciplina;<br> 
•A facul-dade terá no máximo 3000 alunos matriculados simultaneamente, em 10 cursos;<br>
•Entram 300 alunos novos por ano;<br>
•Existem 90 disciplinas no total disponíveis;<br>
•Um histórico escolar traz todas as disciplinas cursadas por aluno. Incluindo nota final, Frequência e período do curso realizado;<br> 
•Professores podem ser cadastrados mesmo sem lecionar disciplinas;<br> 
•Existem 40 professores trabalhando na escola;<br> 
•Cada professor irá lecionar no máximo 4 disciplinas diferentes;<br>
•Cada professor é vinculado a um departamento;<br> 
•Professores são identificados por um código de professor;<br>

<b> Modelo ER: </b>
![modelo ER completo](https://user-images.githubusercontent.com/105245393/174910127-bb0ea57f-c417-463f-952e-fa9f5778b560.png)




<b> Normalização: </b>
![modelo Logico com formas normais](https://user-images.githubusercontent.com/105245393/174909588-e259aa67-59c2-4498-a3b4-f06efc089c24.png)


