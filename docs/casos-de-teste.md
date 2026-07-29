CT-001 → Login com senha inválida
CT-002 → Pagamento com cartão sem saldo
CT-003 → Adicionar produto duas vezes
CT-004 → Reteste do login
CT-005 → Regressão do cadastro


ID: CT-001

Título:
Adicionar o mesmo produto duas vezes ao carrinho

Tipo:
Positivo

Pré-condição:
Usuário está na página de produtos e existe
um produto disponível para compra.

Passos:
1. Acessar a página de produtos.
2. Selecionar um produto.
3. Clicar em "Adicionar ao carrinho".
4. Voltar para a página do produto.
5. Clicar novamente em "Adicionar ao carrinho".
6. Acessar o carrinho.

Resultado esperado:
O carrinho deve apresentar duas unidades
do mesmo produto.

ID: CT-002

Título:
Login com usuário e senha válidos

Tipo:
Positivo

Pré-condição:
Usuário possui uma conta cadastrada
e está na página de login.

Passos:
1. Informar um e-mail válido.
2. Informar uma senha válida.
3. Clicar em "Entrar".

Resultado esperado:
O sistema deve autenticar o usuário e permitir
o acesso à área logada.

ID: CT-003

Título:
Cadastro utilizando e-mail já cadastrado

Tipo:
Negativo

Pré-condição:
Usuário está na página de cadastro e existe
uma conta cadastrada com o e-mail utilizado.

Passos:
1. Acessar a página de cadastro.
2. Informar um e-mail já cadastrado.
3. Informar uma senha válida.
4. Clicar no botão "Cadastrar".

Resultado esperado:
O sistema deve impedir o cadastro e apresentar
uma mensagem informando que o e-mail já está cadastrado.

ID: CT-004

Título:
Reteste do login com senha inválida após correção

Tipo:
Negativo / Reteste

Pré-condição:
Usuário possui uma conta cadastrada e está
na página de login.

Passos:
1. Informar um e-mail válido.
2. Informar uma senha inválida.
3. Clicar em "Entrar".

Resultado esperado:
O sistema deve impedir o acesso e apresentar
uma mensagem informando que as credenciais
são inválidas.

ID: CT-005

Título:
Validar cadastro após alteração na funcionalidade de login

Tipo:
Regressão / Positivo

Pré-condição:
Foi realizada uma alteração na funcionalidade de login.
O e-mail utilizado ainda não possui cadastro.

Passos:
1. Acessar a página de cadastro.
2. Informar um e-mail válido e não cadastrado.
3. Informar uma senha válida.
4. Clicar em "Cadastrar".

Resultado esperado:
O sistema deve criar o novo usuário e permitir
a conclusão do cadastro normalmente.
