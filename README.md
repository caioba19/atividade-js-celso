# 📘 Atividade Prática — Fundamentos de JavaScript

Exercícios introdutórios cobrindo os primeiros conceitos da linguagem JavaScript: variáveis, operadores aritméticos, estruturas condicionais e lógica básica de programação.

---

## 📋 Lista de Exercícios

| # | Título | Conceitos abordados |
|---|--------|---------------------|
| 01 | Olá, Mundo! | `console.log` |
| 02 | Variáveis de apresentação | `let`, template literals |
| 03 | Soma simples | Operador `+`, variáveis numéricas |
| 04 | As quatro operações | `+` `-` `*` `/` |
| 05 | Maior ou menor de idade | `if / else`, operador `>=` |
| 06 | Positivo, negativo ou zero | `if / else if / else` |
| 07 | Calculadora de IMC | Fórmula matemática, `toFixed()` |
| 08 | Maior entre três números | Comparação encadeada |
| 09 | Conversor Celsius → Fahrenheit | Fórmula de conversão |
| 10 | Par ou ímpar | Operador módulo `%` |
| 11 | Média e situação do aluno | Média aritmética, `toFixed()` |
| 12 | Antecessor e sucessor | Operadores `+` e `-` |

---

## 🧠 Conceitos Praticados

### Variáveis
```js
let nome = "João";
let idade = 20;
let cidade = "Salvador";
```

### Template Literals
```js
console.log(`Meu nome é ${nome}, tenho ${idade} anos e moro em ${cidade}.`);
```

### Operadores Aritméticos
| Operador | Operação       |
|----------|----------------|
| `+`      | Soma           |
| `-`      | Subtração      |
| `*`      | Multiplicação  |
| `/`      | Divisão        |
| `%`      | Módulo (resto) |

### Estruturas Condicionais
```js
if (condicao) {
  // bloco executado se verdadeiro
} else if (outraCondicao) {
  // bloco alternativo
} else {
  // bloco padrão
}
```

---

## 🗂️ Estrutura do Projeto

```
atividade-js/
├── ex01-ola-mundo.js
├── ex02-variaveis.js
├── ex03-soma.js
├── ex04-quatro-operacoes.js
├── ex05-maior-menor-idade.js
├── ex06-positivo-negativo-zero.js
├── ex07-imc.js
├── ex08-maior-numero.js
├── ex09-celsius-fahrenheit.js
├── ex10-par-impar.js
├── ex11-media-aluno.js
├── ex12-antecessor-sucessor.js
└── README.md
```

---

## ▶️ Como Executar

**No navegador:**
1. Abra o DevTools (`F12` ou `Ctrl + Shift + J`)
2. Acesse a aba **Console**
3. Cole o código e pressione `Enter`

**Com Node.js:**
```bash
node ex01-ola-mundo.js
```

---

## 📌 Referências Rápidas

- [`console.log()`](https://developer.mozilla.org/pt-BR/docs/Web/API/console/log) — exibe mensagens no console
- [`let`](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/let) — declara variável de escopo de bloco
- [Template literals](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Template_literals) — strings com interpolação usando crases
- [`toFixed()`](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed) — formata casas decimais
- [Operadores aritméticos](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators)

---

## 👨‍💻 Autor

**Caio Vinicius** — Estudante de Desenvolvimento Full Stack  
📍 Salvador, Bahia — Brasil  
🔗 [github.com/caioba19](https://github.com/caioba19)
