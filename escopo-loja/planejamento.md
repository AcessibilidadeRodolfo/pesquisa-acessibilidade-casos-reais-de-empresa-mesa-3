# 📄 Documento de Definições Iniciais (Planejamento do MVP)

## Visão Geral do Projeto

Este projeto tem como objetivo o desenvolvimento de uma **Loja de Action Figures online**, com foco em uma experiência acessível, intuitiva e moderna para os usuários.

O MVP (Produto Mínimo Viável) contemplará funcionalidades essenciais como:
- Listagem de produtos
- Visualização de detalhes
- Carrinho de compras básico
- Interface acessível (A11y)

---

## Escopo do MVP

O MVP da aplicação incluirá:

- Página inicial com produtos em destaque  
- Página de listagem de action figures  
- Página de detalhes do produto  
- Carrinho de compras simples  
- Estrutura base de backend e banco de dados  
- Aplicação de boas práticas de acessibilidade (A11y)

---

## Divisão de Responsabilidades

### 🎨 Prototipação UI/UX (Figma)
- **Responsável:** Rahquel  
- Criação de wireframes e protótipos navegáveis  
- Definição de layout e identidade visual  
- Aplicação de princípios de acessibilidade no design  

---

### 💻 Desenvolvimento Frontend
- **Erick:** HTML e CSS  
- **João:** JavaScript (JS Vanilla)

**Responsabilidades:**
- Implementação da interface  
- Aplicação de HTML semântico  
- Garantia de acessibilidade (A11y)  
- Integração com o backend  

---

### ⚙️ Backend e Banco de Dados
- **Vini:** Backend  
- **Mari:** Modelagem do Banco  

**Responsabilidades:**
- Estruturação das regras de negócio  
- Modelagem do banco de dados  
- Integração com frontend  

---

### 📝 Documentação Contínua
- **João & Mari**

**Responsabilidades:**
- Atualização do repositório  
- Registro de decisões técnicas  
- Documentação dos códigos  
- Garantia de clareza do projeto  

---

## ♿ Diretrizes de Acessibilidade (A11y)

A acessibilidade será aplicada desde o início do projeto, seguindo boas práticas e recomendações internacionais.

### ✔️ O que será aplicado:

### • Uso de HTML Semântico (HTML5)
Utilização de elementos como `<button>`, `<nav>`, `<main>` e `<article>` para garantir que tecnologias assistivas interpretem corretamente o conteúdo.

---

### • Contraste de cores adequado
Aplicação de cores seguindo as diretrizes da WCAG, garantindo boa legibilidade para usuários com baixa visão.

---

### • Alternativas textuais para imagens
Uso de atributos `alt` descritivos em todas as imagens relevantes.

---

### • Uso correto de labels em inputs
Associação entre `<label>` e campos de formulário para melhorar a usabilidade e acessibilidade.

---

### • Acessibilidade no ciclo de vida do projeto
A acessibilidade será responsabilidade compartilhada entre:
- UX
- Desenvolvimento
- QA

---

### • Navegação por teclado
Todas as funcionalidades serão acessíveis via teclado:
- Tab
- Enter
- Espaço

---

### • Uso de ARIA (quando necessário)
Aplicação de atributos ARIA para complementar o HTML semântico em casos específicos.

---

### • Estrutura clara e hierárquica
Organização adequada com:
- Títulos (`H1` a `H6`)
- Seções bem definidas
- Conteúdo estruturado

---

### • Testes de acessibilidade
Validação contínua com ferramentas como:
- Lighthouse  
- Skynet Technologies  

---