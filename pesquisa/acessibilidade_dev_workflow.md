# O que muda no trabalho do desenvolvedor quando a empresa tem política de acessibilidade?

Quando uma empresa adota uma política de acessibilidade, o trabalho do desenvolvedor deixa de ser focado apenas em funcionalidade e estética para incluir a garantia de que o produto digital possa ser utilizado por **todas as pessoas**, independentemente de suas habilidades físicas ou cognitivas.

## Principais mudanças

### 1. Adoção de Padrões Semânticos (HTML5)

O uso de HTML estrutural e semântico — como `<button>`, `<nav>`, `<main>`, `<article>` — torna-se obrigatório para que tecnologias assistivas, como leitores de tela, interpretem corretamente o conteúdo.

### 2. Foco na Navegação por Teclado

O desenvolvedor deve garantir que todas as funcionalidades sejam acessíveis sem o uso de mouse, incluindo:

- Ordem de foco lógica (`tabindex`)
- Visibilidade do indicador de foco
- Gerenciamento de foco em elementos dinâmicos (como modais)

### 3. Aplicação das Diretrizes WCAG

A conformidade com a **Web Content Accessibility Guidelines (WCAG)** passa a ser uma meta. Isso envolve:

- Garantir contraste de cor adequado
- Fornecer alternativas textuais para imagens (`alt text`)
- Criar descrições para elementos não textuais

É necessário também um **checklist de requisitos ampliado** para toda nova feature, verificando se ela contempla os critérios de acessibilidade.

### 4. Inclusão da Acessibilidade no Ciclo de Vida (*Shift Left*)

A acessibilidade é incorporada desde o design e o planejamento — não deixada para o final, pois a adaptação de um design finalizado é mais cara e complexa.

### 5. Responsabilidade Compartilhada

A acessibilidade passa a ser uma preocupação de **toda a equipe** (UX, QA, Dev), e não apenas do front-end. O feedback de usuários com deficiência torna-se parte do processo de melhoria contínua.

---

## Referência: WCAG

A **Web Content Accessibility Guidelines**, criada pelo [World Wide Web Consortium (W3C)](https://www.w3.org/TR/WCAG21/), é a principal referência de acessibilidade na web e valida essas práticas ao transformá-las em padrões internacionais.

Seus princípios justificam e embasam diretamente os pontos descritos acima:

- Navegação por teclado
- Uso de HTML semântico
- Contraste de cores
- `alt text` e uso de ARIA
- Testes com tecnologias assistivas
- Aplicação da acessibilidade desde o início e por toda a equipe