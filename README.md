# 🔐 Gerador de Senhas Aleatórias  
### HTML • CSS • JavaScript

Um **Gerador de Senhas Aleatórias personalizável**, desenvolvido com **HTML, CSS e JavaScript puro**, focado em **segurança**, **usabilidade** e **design moderno**.

O usuário pode definir o **tamanho da senha** e escolher **quais tipos de caracteres** deseja incluir, gerando **senhas fortes** de forma rápida e intuitiva. 

---

## ✨ Funcionalidades

🔢 Definição da quantidade de caracteres da senha  
&nbsp;&nbsp;&nbsp;&nbsp;• Mínimo: **4**  
&nbsp;&nbsp;&nbsp;&nbsp;• Máximo: **40**

🔠 Opções de caracteres:
- Letras **maiúsculas**
- Letras **minúsculas**
- **Números**
- **Caracteres especiais**

⚙️ Geração dinâmica da senha com JavaScript  
🚨 Validação automática (impede gerar senha sem critérios)  
🖥 Interface simples, moderna e responsiva  
🎨 Design clean com paleta **roxa e magenta**

---

## 🎨 Interface e Estilo

🎨 Fundo em tom **lavanda** com container **roxo escuro**  
💎 Bordas arredondadas e sombra suave  
🖱 Botão com efeito **hover** e transições suaves  
📐 Layout centralizado usando **Flexbox**  
✨ Visual focado em clareza e experiência do usuário  

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica da aplicação  
- **CSS3** — Estilização, layout flexível e efeitos visuais  
- **JavaScript (ES6+)** — Lógica de geração da senha e manipulação do DOM  

---

## 🧠 Funcionamento do JavaScript

O JavaScript é responsável por **toda a lógica de geração da senha**, desde a escolha dos caracteres até a exibição do resultado na interface.

### 🔹 Conjuntos de caracteres

O código define quatro grupos principais de caracteres:

- **Letras maiúsculas** (`A–Z`)
- **Letras minúsculas** (`a–z`)
- **Números** (`0–9`)
- **Caracteres especiais** (`!@#$%&/*-+`)

---

### 🔹 Montagem dinâmica do conjunto

Com base nas opções selecionadas pelo usuário, o script monta dinamicamente um conjunto de caracteres permitido, chamado de **`charPool`**, que será utilizado na geração da senha.

---

### 🔹 Validação

Caso nenhuma opção seja marcada, o sistema exibe um **alerta automático**, impedindo a geração da senha.  

---

### 🔹 Geração aleatória

A senha é criada utilizando o método **`Math.random()`**, que seleciona caracteres aleatórios do conjunto permitido até atingir o tamanho definido pelo usuário.

---

### 🔹 Interação com o DOM

Ao clicar no botão **“Gerar Senha”**, o JavaScript atualiza o conteúdo da tela dinamicamente, exibindo a senha gerada **sem recarregar a página**.

---

## 💡 Possíveis Melhorias Futuras

- 📋 Botão para copiar a senha
- 🔐 Indicador visual de força da senha
- 🌙 Modo escuro / claro
- 📱 Melhor adaptação para telas menores
- 🔄 Garantir ao menos um caractere de cada tipo selecionado

---

## 📄 Licença

Projeto desenvolvido para **fins educacionais**, prática de **JavaScript** e composição de **portfólio**, ideal para estudos de lógica e desenvolvimento front-end.




