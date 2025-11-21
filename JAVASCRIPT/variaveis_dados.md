# JavaScript: Dominando Variáveis e Tipos de Dados

Este `README.md` documenta o conteúdo da aula sobre **Variáveis e Tipos de Dados** em JavaScript, parte do curso da DevClub.

O vídeo original pode ser acessado aqui: [JavaScript Course: Mastering Variables and Data Types](https://www.youtube.com/watch?v=4Y87KSByqOY)

---

## 💡 O que são Variáveis?

Variáveis são como "caixas" nomeadas na memória do computador que usamos para armazenar e identificar informações (dados). Elas são essenciais para manipular dados em qualquer programa.

## 🔑 Declaração de Variáveis em JavaScript

Em JavaScript, existem três palavras-chave principais para declarar variáveis:

| Palavra-chave | Uso | Descrição |
| :--- | :--- | :--- |
| `const` | **Constante** | O valor **não pode** ser alterado após a atribuição inicial. **Recomendado** por padrão. |
| `let` | **Mutável** | O valor **pode** ser alterado (reatribuído) posteriormente. |
| `var` | **Antiga** | Forma antiga e **não recomendada** para novos projetos. |

**Exemplo:**

```javascript
const nome = "Manus"; // Valor constante
let idade = 25; // Valor que pode mudar
idade = 26; // Reatribuição permitida com 'let'
```

## 📊 Tipos de Dados Fundamentais

O JavaScript possui diversos tipos de dados para representar diferentes tipos de informação:

### 1. String (Texto)

Usado para dados textuais. Pode ser delimitado por aspas duplas (`"`), aspas simples (`'`) ou crases (`` ` ``).

*   **Template Literals (Crases):** Permitem incorporar variáveis diretamente e criar textos com múltiplas linhas.

```javascript
const saudacao = `Olá, ${nome}!`;
```

### 2. Number (Número)

Usado para valores numéricos, incluindo inteiros e decimais.

```javascript
const numeroInteiro = 10;
const numeroDecimal = 3.14;
const resultado = numeroInteiro + numeroDecimal;
```

### 3. Boolean (Booleano)

Representa um valor lógico, que pode ser apenas **verdadeiro** ou **falso**.

| Valor | Significado |
| :--- | :--- |
| `true` | Verdadeiro |
| `false` | Falso |

```javascript
const estaLogado = true;
const temPermissao = false;
```

### 4. Object (Objeto)

Uma estrutura que agrupa múltiplas informações relacionadas em pares de **chave: valor**.

```javascript
const pessoa = {
    nome: "Alice",
    idade: 30,
    profissao: "Desenvolvedora"
};
```

### 5. Array (Matriz/Lista)

Uma lista ordenada que permite armazenar múltiplos valores (de qualquer tipo) em uma única variável. Os itens são acessados por seu **índice**, que começa em `0`.

```javascript
const listaDeFrutas = ["Maçã", "Banana", "Laranja"];
console.log(listaDeFrutas[0]); // Saída: "Maçã"
```

### 6. Null e Undefined

| Tipo | Significado |
| :--- | :--- |
| `null` | Ausência **intencional** de valor. O programador define que a variável está vazia. |
| `undefined` | A variável foi declarada, mas **nenhum valor** foi atribuído a ela. |

```javascript
let valorNulo = null;
let valorIndefinido; // É undefined por padrão
```
