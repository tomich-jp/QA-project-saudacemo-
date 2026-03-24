# 02 - Test Plan  
## E-commerce - SauceDemo

---

## 1. Introdução

Este documento descreve o plano de testes para o e-commerce SauceDemo.  
O objetivo é validar os principais fluxos críticos da aplicação, desde a autenticação do usuário até a finalização da compra, garantindo que o sistema esteja funcional, estável e alinhado às expectativas do usuário.

---

## 2. Objetivo do Plano de Testes

Garantir que as funcionalidades críticas do sistema estejam operando corretamente, reduzindo o risco de falhas e garantindo estabilidade, confiabilidade e conformidade com os fluxos esperados do sistema..

Os testes serão estruturados para cobrir integralmente os fluxos principais do sistema:

- Login  
- Listagem de Produtos (Product Listing)  
- Carrinho de Compras (Cart)  
- Processo de Checkout  

---

## 3. Escopo

### 3.1 Dentro do Escopo

- Login  
- Listagem de Produtos  
- Carrinho de Compras  
- Processo de Checkout  

### 3.2 Fora do Escopo

- Página Home institucional  
- About Us  
- Blog  

---

## 4. Ambiente de Testes

- **URL da aplicação:** https://www.saucedemo.com/ 
- **Sistema Operacional:** Windows 11  
- **Navegador:** Google Chrome (versão estável mais recente)  
- **Dispositivo:** Desktop  
- **Ferramentas de apoio:**  
  - DevTools (Chrome)  
  - Cypress (para automação)

---

## 5. Estratégia de Execução

A execução dos testes seguirá a seguinte ordem:

1. Exploração do site e suas funcionalidades
2. Criação dos cenários de teste  
3. Elaboração dos casos de teste  
4. Execução de testes manuais  
5. Registro e reporte de bugs  
6. Automação dos cenários críticos com Cypress  
7. Execução da suíte de regressão automatizada  
8. Execução dos testes End-to-End 

Serão aplicadas as seguintes abordagens:

- Testes Funcionais  
- Testes Exploratórios  
- Testes de Interface (UI)  
- Testes de Regressão  
- Testes End to End

---

## 6. Critérios de Entrada

Os testes poderão ser iniciados quando:

- A funcionalidade estiver disponível para validação    
- O ambiente estiver acessível e estável  

---

## 7. Critérios de Saída

Os testes serão considerados concluídos quando:

- Todos os cenários planejados forem executados  
- Bugs críticos e de alta severidade forem formalmente documentados 
- Os fluxos principais estiverem validados  
- Evidências da execução estiverem documentadas  

---

## 8. Cronograma (Simulado)

- Dia 1 – Análise e planejamento
- Dia 2 – Criação de cenários e casos de teste
- Dia 3 – Execução manual e reporte de bugs
- Dia 4 – Automação e regressão

---

## 9. Riscos e Mitigações

| Risco | Mitigação |
|-------|------------|
| Requisitos não documentados | Realizar análise exploratória e registrar dúvidas |
| Instabilidade do ambiente | Validar ambiente antes da execução |
| Falta de massa de teste | Criar dados de teste controlados |
| Mudanças inesperadas na aplicação | Reexecutar cenários críticos |
| Dependência de dados inconsistentes | Validar e padronizar massa de teste |

---

## 10. Entregáveis

- Documento de Estratégia de Testes  
- Documento de Plano de Testes  
- Documento de Cenários de Teste  
- Casos de Teste detalhados  
- Relatório de Bugs  
- Evidências (prints e registros)  
- Scripts de automação  

---

## 11. Gestão de Defeitos

Os defeitos encontrados serão registrados no GitHub contendo:

- Título do bug
- Descrição
- Passos para reprodução
- Resultado esperado
- Resultado atual
- Evidências (prints)
- Severidade (Baixa, Média, Alta, Crítica)

---

