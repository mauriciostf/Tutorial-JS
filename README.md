[ExemploVariavelJS.txt](https://github.com/mauriciostf/Tutorial-JS/files/15069417/ExemploVariavelJS.txt)[exemploSintaxeBasica.txt](https://github.com/mauriciostf/Tutorial-JS/files/15069403/exemploSintaxeBasica.txt)# Tutorial-JS
Este guia oferece um tutorial básico de introdução ao JavaScript.

# O que nós iremos aprender nesse tutorial?  

  Nós teremos um arquivo com um total de 8 tópicos, com o intuito de dar um panorama e introdução ao JavaScript.

• O que é JavaScript?
• Configuração de ambiente
• Sintaxe básica
• Variáveis
• Tipos de dados
• Funções
• Estruturas de controle
• Eventos e manipulação do DOM

# Afinal, o que é JavaScript?

   JavaScript é uma linguagem de programação de alto nível, interpretada e orientada a objetos. Ela é amplamente utilizada para criar interatividade em páginas web, como validação de formulários, animações, efeitos visuais dinâmicos, entre outros. Além disso, com o Node.js, JavaScript também pode ser utilizado para desenvolvimento do lado do servidor.
   
# Configuração de Ambiente:
  
  Para começar a programar em JavaScript, você só precisa de um navegador web e um editor de texto simples, como o Visual Studio Code, Sublime Text ou Atom. Basta criar um novo arquivo com extensão ".js" e começar a escrever seu código.
  
# Sintaxe Básica

  JavaScript é uma linguagem case-sensitive, ou seja, diferencia maiúsculas de minúsculas. Sua sintaxe é semelhante a outras linguagens de programação, como Java e C, porém mais flexível e menos verbosa.

  # Exemplo Síntaxe Básica no JS:

  ```
// Exemplo de um comentário em JavaScript

// Declaração de variáveis
let nome = "João";
const idade = 30;

// Estrutura de controle (if-else)
if (idade >= 18) {
    console.log(nome + " é maior de idade.");
} else {
    console.log(nome + " é menor de idade.");
}
```

#  Variável

  Em JavaScript, você pode declarar variáveis utilizando as palavras-chave var, let ou const. Recomenda-se o uso de let e const, pois var tem escopo de função, enquanto let e const têm escopo de bloco.

   # Exemplo Variáveis
```
let nome = "Maria"; // Variável mutável
const PI = 3.14; // Constante, não pode ser alterada
```
# Tipos de Dados

  JavaScript é uma linguagem dinamicamente tipada, o que significa que você não precisa declarar o tipo de uma variável explicitamente. Alguns tipos de dados em JavaScript incluem:

Números (inteiros e decimais);
Strings (texto);
Booleanos (true ou false);
Arrays (listas de elementos);
Objetos (coleções de pares chave-valor)
# Exemplo Tipos de dados
```
let numero = 42;
let texto = "Olá, mundo!";
let estaChovendo = true;
let lista = [1, 2, 3, 4, 5];
let pessoa = { nome: "Ana", idade: 25 };
```
# Funções no JavaScript

Uma função em JavaScript é um bloco de código reutilizável que executa uma tarefa específica. Ela pode receber parâmetros (também chamados de argumentos) e pode retornar um valor. As funções são fundamentais para organizar e modularizar o código.

# Exemplo Declaração de Função no JS:
```
function nomeDaFuncao(parametro1, parametro2) {
    // bloco de código
}
```
 • 'nomeDaFuncao': É o nome que você escolhe para sua função.
 • 'parametro1', 'parametro2': São os parâmetros que a função pode receber. Você pode ter zero ou mais parâmetros.
 # Exemplo Função JS:
 ```
function soma(a, b) {
    return a + b;
}

let resultado = soma(2, 3); // resultado é 5

```
# Estruturas de Controle No JavaScript:

JavaScript oferece diversas estruturas de controle para tomada de decisões e repetição de código, incluindo if, else, switch, while, do-while, for e for-in.
# Exemplo de if, else, for:
```
let numero = 10;

if (numero > 0) {
    console.log("Número positivo");
} else if (numero < 0) {
    console.log("Número negativo");
} else {
    console.log("Zero");
}

for (let i = 0; i < 5; i++) {
    console.log(i);
}
```
# Exemplo de While JS:

```
let lista = ["Maçã", "Banana", "Laranja", "Pera"];
let i = 0;

while (i < lista.length) {
    console.log(lista[i]);
    i++;
}
```

# Exemplo de Switch Case no JS:

```
let diaDaSemana = "Segunda-feira";
let mensagem;

switch (diaDaSemana) {
    case "Segunda-feira":
        mensagem = "Hoje é segunda-feira. Bom trabalho!";
        break;
    case "Terça-feira":
        mensagem = "Hoje é terça-feira. Vamos lá!";
        break;
    case "Quarta-feira":
        mensagem = "Hoje é quarta-feira. Metade da semana!";
        break;
    case "Quinta-feira":
        mensagem = "Hoje é quinta-feira. Quase lá!";
        break;
    case "Sexta-feira":
        mensagem = "Hoje é sexta-feira. Finalmente!";
        break;
    default:
        mensagem = "Bom fim de semana!";
}

console.log(mensagem);
```
# Eventos e Manipulação do DOM:

Eventos são ações que ocorrem em elementos HTML, como clique do mouse, pressionamento de tecla, entre outros. JavaScript permite que você manipule esses eventos e interaja dinamicamente com o Document Object Model (DOM), que representa a estrutura da página web.

# Exemplo Manipulção do DOM no JS:

```
// Selecionando um elemento pelo ID
let botao = document.getElementById("meuBotao");

// Adicionando um ouvinte de evento de clique
botao.addEventListener("click", function() {
    console.log("Botão clicado!");
});
```











  
