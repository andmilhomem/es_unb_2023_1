# es_unb_2023_1

Diagrama Registro de Presença Engenharia de Software

Tela 1 – Login 

O usuário, pré-cadastrado em outro sistema, informa matrícula e senha. O usuário pode ser de dois tipos: professor ou aluno. O comportamento do sistema após o login varia conforme o tipo de usuário 

Tela 2 – Página inicial de aluno 

Após efetuar o login, o usuário aluno é direcionado para página inicial, que indica a turma cujo registro de presença está atualmente disponível (informação obtida a partir do confronto entre data e horário atuais e turmas em que o aluno está matriculado). Ao usuário aluno é dada a opção de registrar sua presença ou ausência justificada. No segundo caso, ele pode informar a justificativa e apresentar comprovante. 

Tela 3 – Consulta de frequência por aluno 

Na página inicial, é oferecida ao aluno a possibilidade de consultar, em outra tela, sua frequência até a data atual para todas as turmas em que está atualmente matriculado. Nessa segunda tela, ele pode registrar presença (caso esteja no horário) ou ausência justificada (mesmo mecanismo da tela anterior). 

Tela 4 – Página inicial de professor 

Na página inicial do usuário professor, são listadas todas as turmas para as quais ele leciona. Para cada item da lista, são oferecidas as opções de: alterar dias letivos; analisar ausências justificadas e consultar frequência de alunos. Para cada uma dessas opções, há uma tela específica. 

Tela 5 – Alterar dias letivos 

Para uma dada turma, são exibidos todos os dias letivos, gerados automaticamente quando do cadastro da disciplina, de acordo com o calendário letivo da universidade. Ao professor é dada a opção de indicar se determinado dia é ou não letivo e registrar observação a respeito. 

Tela 6 – Analisar ausências justificadas 

Para uma dada turma, são exibidos todos os casos ainda não validados em que alunos alegaram ausência justificada. O professor poder ler a justificativa, abrir o comprovante e decidir se se trata de ausência justificada ou não.  

Tela 7 – Consultar frequências dos alunos 

Para uma dada turma, é exibida lista de dias letivos. Após o usuário selecionar uma data, é exibida a lista de alunos matriculados, com a respectiva situação para aquele dia letivo. O professor por alterar essa situação. 
