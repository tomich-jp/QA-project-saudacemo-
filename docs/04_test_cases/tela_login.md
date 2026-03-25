# Casos de Teste - Funcionalidade: Tela de Login

**Sistema:** SauceDemo  
**Responsável:** João Pedro Tomich  

---

## CT-LOGIN-01 - Login válido

**Prioridade:** Alta  
**Severidade:** Crítica  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir o usuário válido "standard_user"
2. Inserir a senha válida "secret_sauce"
3. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve redirecionar o usuário para a página de inventário de produtos.

---

## CT-LOGIN-02 - Login com usuário e senha inválidos

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir o usuário inválido "standard_user123"
2. Inserir a senha inválida "secret_sauce01"
3. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve exibir a mensagem de erro:  
"Epic sadface: Username and password do not match any user in this service"

---

## CT-LOGIN-03 - Login com campos "username" e "password" vazios

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Clicar no botão "Login" sem preencher os campos

### Resultado Esperado:
O sistema deve exibir a mensagem de erro:  
"Epic sadface: Username is required"

---

## CT-LOGIN-04 - Login com campo "username" vazio

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir a senha válida "secret_sauce"
2. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve exibir a mensagem de erro:  
"Epic sadface: Username is required"

---

## CT-LOGIN-05 - Login com campo "password" vazio

**Prioridade:** Alta  
**Severidade:** Alta  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir o usuário válido "standard_user"
2. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve exibir a mensagem de erro:  
"Epic sadface: Password is required"

---

## CT-LOGIN-06 - Login com usuário bloqueado

**Prioridade:** Alta  
**Severidade:** Crítica  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir o usuário "locked_out_user"
2. Inserir a senha válida "secret_sauce"
3. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve exibir a mensagem de erro informando que o usuário está bloqueado.

---

## CT-LOGIN-07 - Login com usuário com comportamento inesperado

**Prioridade:** Média  
**Severidade:** Média  
**Tipo:** Funcional  

### Pré-condição:
Usuário acessa a tela de login: https://www.saucedemo.com/

### Passos:
1. Inserir o usuário "problem_user"
2. Inserir a senha válida "secret_sauce"
3. Clicar no botão "Login"

### Resultado Esperado:
O sistema deve permitir o login, porém o comportamento da aplicação deve ser validado quanto a possíveis inconsistências.