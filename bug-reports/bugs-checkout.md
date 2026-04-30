# 🐞 Bug Reports – Checkout SauceDemo

---

## BUG 1 – Checkout sem produtos

**Severidade:** Alta  
**Prioridade:** Alta  

**Descrição:**  
O sistema permite finalizar o checkout mesmo sem produtos no carrinho.

**Passos para reproduzir:**
1.  Acessar o sistema Saucedemo
2. Realizar login com usuário válido
3. Acessar diretamente o checkout
4. Preencher dados
5. Finalizar

**Resultado esperado:**  
Sistema deve impedir finalização sem produtos.

**Resultado atual:**  
Checkout finaliza normalmente.

**Evidência:**  
(link)] (https://drive.google.com/file/d/1g1ZXWKhWdLigERaoUMFRjTjEkOC_xIKA/view?usp=sharing)

---

## BUG 2 – Botão não funcional

**Severidade:** Média  
**Prioridade:** Média  

**Descrição:**  
Na página de produtos existe um botão próximo ao filtro com ícone de seta para baixo que aparenta ser clicável, porém não executa nenhuma ação ao ser clicado.

**Passos para reproduzir:**
1. Acessar o sistema Saucedemo
2. Realizar login com usuário válido
3. Navegar até a página de produtos
4. Localizar o botão próximo ao filtro de ordenação
5. Clicar no botão

**Resultado esperado:** 
O botão deveria executar alguma ação ou abrir um menu de opções.

**Resultado atual:**  
Nenhuma ação ocorre ao clicar no botão.

**Evidência:**  
(link) https://drive.google.com/file/d/198jI7Y_IBLAsxNLCC9rAbGRRHH6wz4u_/view?usp=sharing

---

## BUG 3 Sistema aceita valores inválidos nos campos do formulário de checkout

**Severidade:** Alta 
**Prioridade:** Média  

**Descrição:**  
Durante o processo de checkout, o sistema aceita valores inconsistentes nos campos First Name, Last Name e Zip/Postal Code sem realizar validação.

**Passos para reproduzir:**
1. Acessar o sistema Saucedemo
2. Realizar login com usuário válido
3. Adicionar produto ao carrinho
4. Acessar checkout
5. Preencher os campos com valores incorretos ou trocados
6. Clicar em continuar

**Resultado esperado:** 
O sistema deveria validar os campos e impedir dados inconsistentes.

**Resultado atual:**  
O sistema permite continuar o processo normalmente.

**Evidência:**  
(link) https://drive.google.com/file/d/13YbxCN_mevLYbAsKiQ7sJ2HX0oFdOaD8/view?usp=sharing

