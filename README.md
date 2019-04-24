# Widesoftware - Frontend challenge
Você deverá desenvolver uma tela de login e cadastro de usuários, onde deve seguir as seguintes regras:
1) Campos necessários para cada ação:
- Campos de cadastro
  - Nome
    - Obrigatório mínimo 3 caracteres, máximo 30 caracteres
    - Não aceitar caracteres especiais ou numéricos
   - E-mail
     - Obrigatório, deve possuir o formato de e-mail válido
   - Senha
     - Obrigatório, mínimo 6 caracteres, máximo 20 caracteres
   - Confirmar Senha
     - Obrigatório, mínimo 6 caracteres, máximo 20 caracteres
     - Deve ser igual o campo senha
   - Data de nascimento
     - Opcional, validar formato de data: dia/mês/ano (24/02/2019)

- Campos de login
  - E-mail
    - Validar formato e se está preenchido antes de enviar
  - Senha
    - Validar se está preenchido antes de enviar

  ** Não se preocupe, os formulários não precisam ter nenhuma ação de postagem.

2) A aplicação deverá ser uma única página.

3) Ao carregar a página antes de aparecer os formulários deverá ser apresentado uma campanha publicitária para o usuário. Você deverá acessar o endpoint http://www.mocky.io/v2/5cc0a786310000580b036475 para baixar uma lista de campanhas publicitárias. A cada acesso deverá ser apresentada uma campanha diferente, de forma randômica.

4) A campanha deverá possuir um tempo regressivo dizendo ao usuário quando a campanha desaparecerá.

5) A campanha deverá possuir 2 botões um “Curti” e “Não Curti”, porém não se preocupe, os botões neste primeiro momento não terão nenhuma ação.

# Requisitos do projeto
- O projeto deverá ser enviado no Github público com instruções para execução do projeto.
- Tela deve ser responsiva.
- Deve ser desenvolvido em React.Js
- Pode ser utilizado bibliotecas de componentes como Material UI, Reactstrap, etc.

# O que avaliaremos?
- Conceitos de UI aplicados.
- Qualidade do código.

# Diferenciais
- Utilização de Redux.
- Criar formulários com Formik ou Redux Forms.
- Testes no código.
- Enviar o projeto em docker.

