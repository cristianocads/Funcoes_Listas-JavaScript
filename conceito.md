### Funções

### Definição

Funções são blocos de código projetados para executar uma tarefa específica. Elas ajudam a organizar e reutilizar código, tornando-o mais modular e legível.

### Sintaxe Básica

`function nomeDaFuncao(parametro1, parametro2) {
  // Corpo da função
  return resultado;
}`

### Exemplo:

`function saudacao(nome) {
  return `Olá, ${nome}!`;
}

console.log(saudacao("Maria")); // Output: Olá, Maria!`

### Funções Anônimas

`const saudacao = function(nome) {
  return `Olá, ${nome}!`;
};`

### Arrow Functions (ES6)

`const saudacao = (nome) => `Olá, ${nome}!`;`

### Constantes

### Definição e Uso

`const` é usado para declarar constantes, ou seja, valores que não podem ser alterados após a sua inicialização.

### Diferenças entre `var`, `let` e `const`

- `var`: tem escopo de função e pode ser reatribuído.
- `let`: tem escopo de bloco e pode ser reatribuído.
- `const`: tem escopo de bloco e não pode ser reatribuído.

### Exemplo:

`const PI = 3.14;
PI = 3.1415; // Isso causará um erro, pois PI é uma constante.`

### Listas (Arrays)

### Definição

Arrays são usados para armazenar múltiplos valores em uma única variável.

### Declaração e Inicialização

`let frutas = ["Maçã", "Banana", "Laranja"];`

### Métodos Úteis

- `push()`: adiciona um item no final do array.
- `pop()`: remove o último item do array.
- `shift()`: remove o primeiro item do array.
- `unshift()`: adiciona um item no início do array.

### Exemplo:

`let frutas = ["Maçã", "Banana", "Laranja"];
frutas.push("Uva"); // ["Maçã", "Banana", "Laranja", "Uva"]
frutas.pop(); // ["Maçã", "Banana", "Laranja"]`

### Condicionais

### Declaração `if-else`

Usada para executar código com base em uma condição.

### Exemplo:

`let idade = 18;
if (idade >= 18) {
  console.log("Você é maior de idade.");
} else {
  console.log("Você é menor de idade.");
}`

### Operadores de Comparação

- `==`: igual a
- `===`: estritamente igual a
- `!=`: diferente de
- `!==`: estritamente diferente de
- `>`: maior que
- `<`: menor que
- `>=`: maior ou igual a
- `<=`: menor ou igual a

### Estruturas `switch-case`

`let fruta = "Banana";
switch (fruta) {
  case "Maçã":
    console.log("Você escolheu Maçã.");
    break;
  case "Banana":
    console.log("Você escolheu Banana.");
    break;
  default:
    console.log("Fruta não encontrada.");
}`

### Operadores Lógicos

### Definição e Uso

Operadores lógicos são usados para combinar múltiplas condições.

### Operadores

- `&&`: E lógico (and)
- `||`: OU lógico (or)
- `!`: NÃO lógico (not)

### Exemplo:

`let a = true;
let b = false;
console.log(a && b); // false
console.log(a || b); // true
console.log(!a); // false`
