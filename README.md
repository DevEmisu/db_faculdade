<h1 align="center"> Projeto Banco faculdade </h1>

<b> introdução </b>
    Este projeto foi feito durante um curso tecnico de DBA no SENAI, tudo neste 
projeto foi feito por mim (Emerson), incluindo modelo logico, script e alters, consiste em um banco de dados para gerenciamento de uma faculdade. Os objetivos deste banco de dados são: Realizar controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar e turmas.

<b> Regras de negocio </b>
    Uma faculdade de nome Universidade SENAI deseja mudar o seu siste-ma, e para isso
ela precisa criar e implementar um novo banco de dados que permi-ta a ela, realizar o 
controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar
e turmas. Após uma longa conversa com o cliente o analista de requisitos chegou nas
seguintes regras de negócio.

•Um aluno só pode estar matriculado em um curso por vez; 
•Alunos possuem um código de identificação (RA); 
•Cursos são compostos por várias disciplinas; 
•Cada disciplina terá no máximo 30 alunos por turma; 
•As disciplinas podem ser obrigatórias ou optativas, dependendo do curso;
•As disciplinas pertencem a departamentos específicos; 
•Cada disciplina possui um código de identificação; 
•Alunos podem trancar matrícula, não estando então matriculados em nenhuma disciplina no semestre; 
•Em cada semestre, cada aluno pode se matricular em no máximo 9 disciplinas; 
•O aluno só pode ser reprovado no máximo 3 vezes na mesma disciplina; •A facul-dade terá no máximo 3000 alunos matriculados simultaneamente, em 10 cursos; 
•Entram 300 alunos novos por ano;
•Existem 90 disciplinas no total disponíveis; 
•Um histórico escolar traz todas as disciplinas cursadas por aluno. Incluindo nota final, Frequência e período do curso realizado; 
•Professores podem ser cadastrados mesmo sem lecionar disciplinas; 
•Existem 40 professores trabalhando na escola; 
•Cada professor irá lecionar no máximo 4 disciplinas diferentes;
•Cada professor é vinculado a um departamento; 
•Professores são identificados por um código de professor

<b> Modelo ER </b>



<b> Normalização </b>


