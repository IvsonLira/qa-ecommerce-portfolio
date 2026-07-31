BUG-001

Título:
Produto não é adicionado ao carrinho após clicar em "Adicionar"

Ambiente:
Google Chrome 138 - Windows 11

Pré-condição:
Usuário está logado e existe um produto disponível.

Passos para reproduzir:
1. Acessar a página do produto.
2. Clicar em "Adicionar ao carrinho".
3. Acessar o carrinho.

Resultado esperado:
O sistema deve adicionar o produto ao carrinho.

Resultado atual:
O produto não aparece no carrinho.

Severidade:
Alta

Prioridade:
Alta


BUG-002

Título:
Sistema permite login com senha inválida

Ambiente:
Google Chrome
Windows 10

Pré-condição:
Usuário possui uma conta cadastrada e está na página de login.

Passos para reproduzir:
1. Acessar a página de login.
2. Informar um usuário válido.
3. Informar uma senha inválida.
4. Clicar no botão "Login".

Resultado esperado:
O sistema deve impedir o acesso, permanecer na página de login e exibir uma mensagem informando que as credenciais são inválidas.

Resultado atual:
O sistema permite o login mesmo utilizando uma senha inválida.

Severidade:
Alta

Prioridade:
Alta


BUG-003 

Título: sistema perimte acesso com email invalido 

Ambiente: google crhome windows 10 

Pré-condição: usuario possui cadstro e esta na pagina de login 

Passos: 
1. usuario esta na pagina de login 
2. informa email invalido 
3. informa senha valida 
4. clicar em "Login".

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem informando que o e-mail informado é inválido. 

Resultado atual: o sistema permite o acessio do ussuario com email invalido 

Severidade: Alta 

Prioridade: Alta


BUG-004

Título: Sistema não bloqueia o usuário após cinco tentativas consecutivas de login com senha inválida.

Ambiente: gloogle crhome windows 10

Pré-condição: usuario tem cadastro e tenta fazer login. 

Passos: 
1. usuario entra na tela de login
2. informa usuario
3. informa senha invalida pela 5 vez
4. clicar em "Login" 

Resultado esperado: o sistema deve bloquear o acesso por 15 minutos e exibir uma mensagem de texto infiormando que o cliente esta bloqueado temporariamenmte por 15 minutos.

Resultado atual: o sistema nao bloquea o cliente e opermite qaue ele e faça uma nova tentativa excedendo o limikte de 5. 

Severidade: Alta 

Prioridade: Alta
