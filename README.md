# Desafio-testes-manuais-Beedoo

## User Stories
**1. Cadastro Básico de Curso:**
```
Como usuário interessado em cadastrar o curso,
Eu quero poder cadastrar um curso,
Para que ele esteja disponível na plataforma para os usuários.
```

Critérios de Aceitação:<br>
- Deve haver campos para o:
    - Nome do curso 
    - Descrição
    - Instrutor
    - URL da imagem de capa
    - Data de início
    - Data de fim
    - Quantidade de vagas
    - Tipo de curso (presencial/online)

- Todos os campos são obrigatórios.<br><br>

**2. Validação de Dados de Entrada**
```
Como usuário interessado em cadastrar o curso, 
Eu quero que o sistema valide os dados inseridos no formulário,
Para que erros sejam evitados e o cadastro do curso seja feito corretamente.
```

Critérios de Aceitação:<br>
- O campo "Nome do curso" deve ser preenchido e deve conter ao menos 5 caracteres.
- O campo "Data de início" e "Data de fim" devem ser datas válida.
- O campo "Data de início" deve ser anterior à "Data de fim".
- O campo "Número de vagas" deve aceitar apenas números positivos.<br><br>

**3. Feedback de Erro**
```
Como usuário interessado em cadastrar o curso, 
Eu quero receber mensagens de erro claras 
Para que eu saiba o que precisa ser corrigido.
```
Critérios de Aceitação:<br>
- Caso o campo obrigatório não seja preenchido, uma mensagem de erro deve aparecer ao lado do campo.<br>
- Caso alguma regra de validação dos campos não esteja sendo cumprida, o sistema deve exibir uma mensagem de erro específica.<br><br>

**4. Confirmação de Cadastro**
```
Como usuário interessado em cadastrar o curso, 
Eu quero receber uma confirmação após o cadastro de um curso, 
Para que eu saiba que o curso foi cadastrado com sucesso.
```

Critérios de Aceitação:<br>
- Após preencher todos os campos corretamente e clicar no botão "CADASTRAR CURSO", uma mensagem de sucesso deve ser exibida.<br><br><br>

### Decisões Tomadas
- Decidiu-se que todos os campos seriam obrigatórios para garantir que todas as informações necessárias sejam coletadas.
- Validação de Dados: Implementação de validações básicas para assegurar a integridade dos dados.
- Experiência do Usuário: A inclusão de mensagens de erro e confirmação visa melhorar a clareza e o feedback durante o processo de cadastro.<br>

Essas user stories cobrem os principais aspectos do formulário de inscrição de cursos, desde o preenchimento dos dados até a confirmação de sucesso. Se necessário, podemos criar mais user stories para cobrir funcionalidades adicionais ou ajustes específicos na interface.