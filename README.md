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