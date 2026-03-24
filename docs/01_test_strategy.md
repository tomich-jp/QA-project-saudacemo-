# 01 - Test Strategy  
## E-commerce - SauceDemo

---

## 1. Objetivo do Projeto

Garantir a qualidade funcional do e-commerce SauceDemo através da validação dos principais fluxos críticos da aplicação, assegurando que as funcionalidades operem conforme o esperado e proporcionando uma experiência consistente ao usuário final.

---

## 2. Escopo de Teste

### 2.1 O que será testado

- Login  
- Listagem de Produtos (Product Listing)  
- Carrinho de Compras (Cart)  
- Processo de Checkout  

Essas funcionalidades foram definidas como fluxos críticos da aplicação por impactarem diretamente na jornada de compra do usuário.

---

### 2.2 O que não será testado

- Página Home institucional  
- About Us  
- Blog  

Essas áreas foram consideradas fora do escopo por não influenciarem diretamente no fluxo principal de compra.

---

## 3. Tipos de Teste Aplicados

Serão aplicadas as seguintes abordagens:

### 3.1 Testes Funcionais  
Validação do comportamento das funcionalidades do sistema.

### 3.2 Testes Exploratórios  
Exploração livre da aplicação com foco em identificar comportamentos inesperados e possíveis falhas.

### 3.3 Testes de Interface (UI Testing)  
Validação visual e estrutural dos elementos da interface do usuário.

### 3.4 Testes de Regressão
Reexecução de cenários críticos com automação após a execução dos testes manuais para garantir que alterações não impactaram funcionalidades já validadas.

### 3.5 Testes de Sistema (End-to-End)

Simular a jornada completa do usuário, validando a integração entre as funcionalidades do sistema.

---

## 4. Critérios de Entrada

Os testes serão iniciados quando:

- A aplicação estiver disponível e acessível  
- O ambiente estiver estável  

---

## 5. Critérios de Saída

Os testes serão considerados concluídos quando:

- Todos os cenários críticos executados com evidência
- Taxa de sucesso aceitável nos testes automatizados
- Bugs críticos resolvidos ou devidamente documentados

---

## 6. Riscos Identificados

- Requisitos e criterios de aceite não documentados  
- Instabilidade do ambiente  
- Falta de massa de teste adequada  
- Mudanças inesperadas na aplicação durante a execução 
- Dependência de dados mockados ou inconsistentes 

---