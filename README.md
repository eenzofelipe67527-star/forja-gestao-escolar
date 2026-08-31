# Sistema de Gestão Escolar

## Sistema para gerenciar funcionários, alunos, cursos e matrículas

1. Quem utilizará o sistema (usuários)?

    Funcionários

2. Quais os tipos de usuários e o que cada tipo consegue fazer?


    Colaboradores: Cadastrar alunos, cadastrar cursos, editar dados dos alunos, editar dados dos cursos, excluir alunos, excluir cursos, listar alunos, listar cursos, matricular alunos nos cursos, desmatricular alunos nos cursos e atualizar os próprios dados.

    Administradores: Todas as funções acima, mais: cadastrar outros funcionários, listar outros funcionários, editar dados dos outros funcionários e excluir outros funcionários.

3. Quais informações iremos armazenar?

    Funcionários: Nome, email, cpf, cargo, data de nascimento, senha, telefone, endereço.
    Alunos: Nome, email, cpf, matrícula, data de nascimento, telefone, endereço.
    Cursos: Descrição, carga horária, nome.
    Matrículas: Quais alunos estão cadastrados em quais cursos.

4. Quais regras ou restrições são necessárias?

    Apenas funcionários admin podem criar/deletar outros funcionários.
    Dados pessoais como cpf, email não podem ser cadastrados duas vezes no mesmo curso.
    A idade mínima para um funcionário deve ser 18 anos.
    As senhas dos funcionários devem ser criptografadas.

## PROBLEMA:
 - esse sistema é direcionado a funcionários de escolas
 - Permite cadastrar, editar, listar e deletar alunos, cursos, matriculas e funcionários.

 ## Modelo de Negócios:
  ![Business Model Canvas](images/Captura%20de%20tela%202026-08-25%20170634.png)

# REQUISITOS:

## Requisitos Funcionais:

- Cadastrar alunos
- Funcionários do cadastro
- Cursos cadastrais
- Listar alunos
- Listar cursos
- Listar funcionários
- Mostrar os dados do aluno
- Mostrar os dados do funcionário
- Mostrar os dados do curso
- Realizar as faixas
- eu os dados do aluno
- Editar os dados do funcionário
- eu os dados do curso
- Excluir os alunos
- Excluir os funcionários
- Excluir os cursos
- Excluir as matrículas
- Login de usuários
- Buscar aluno pelo nome
- Buscar aluno pelo CPF
- Buscar funcionário pelo nome
- Buscar funcionário pelo CPF
- Mostrar cursos em que cada aluno está matriculado
- Mostrar os alunos que estão matriculados em cada curso

## Requisitos Não Funcionais:

- Autenticação
- Interface com navegação padronizada e consistente entre as telas
- Interface responsiva e adaptável a diversas resoluções de tela e dispositivos diferentes, como computador, celular e tablet
- Interface deve ser compatível com os principais navegadores web
- Criptografar senhas antes de salvá-las no banco de dados
- Disponivel durante todo o horário de funcionamento da instituição
- Restringir acesso pelo tipo de usuário

## REGRAS DE NEGÓCIO:

- CPF de cada aluno deve ser único
- CPF de cada funcionário deve ser único
- o Email de cada funcionário deve ser único
- A matrícula de cada aluno deve ser única
- O nome de cada curso deve ser único
- Impedir exclusao de cursos que tenham alunos matriculados
- Impedir exclusão de alunos que estejam matriculados em 1 ou mais cursos
-
