# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

- javascript:
String: sequências de caracteres alfanuméricos.
Number: converte um valor em um número.
Boolean: é um tipo de dado lógico que pode ter apenas um de dois valores possíveis: verdadeiro ou falso.
- github
- code pen

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala.

```js
- IF AND ELSE 
const nome = prompt("qual seu nome?")
const lanche = prompt("diga seu lanche")

const combo = prompt("deseja compra nosso combo feliz?")

if(combo == "sim") {console.log(`parabens ${nome}, você ganhou um brinde`)
 } else {
   conselo.log("muito obrigado(a), volte sempre!")
 }
const idade = prompt("qual sua idade?")

//Pode entra na festa.(if)
//Pode entra na festa, mas não pode tomar bebida alcoólica.(else if)
//Aqui não é mirabilandia!(else)

if(idade >= 18) {
  console.log(`Pode entrar na festa.`)
} else if (idade > 15 && idade < 18){console.log(`Pode entrar na festa, mas não pode tomar bebida alcoólica.`)
} else {
console.log(`Aqui não é mirabilandia!`)}

- ARRAY
//Array
const livros = [
  "Javacript Assertativo",
  "ECMAScript 6",
  "mongoDB",
  "livro1",
  "livro2",
  "livro3",
  "livro4"
];

console.log(livros[2]);

let consulta = livros.indexOf("ECMAScript 6");
console.log(consulta);

console.log(livros.pop());

console.log(livros.push("novoLivro"));

console.log(livros);

console.log(livros.sort());
console.log(livros.length);

- ARRAY P2
//Array
const frutas = ["laranja","maçã"]

console.log(livros[2];

let consulta = livros.indexOf("laranja
console.log(frutas)

console.log(frutas.pop)

console.log(frutas.push("laranja")

console.log(frutas);

console.log(frutas.sort());
console.log(frutas.length);

- TREINAMENTO

const alycia= ['linda', 'maravilhosa', 'namorada']
console.log(alycia) // [1,2,3]

alycia.push("mulher")
console.log(alycia) // [1,2,3,4,5]

const jogos = ["roblox", "free fire", "candy crush", "talking tom"]
console.log(jogos) // ["roblox", "free fire", "candy crush", "talking tom"]

jogos.pop()
console.log(jogos) // ["roblox, "free fire"]

const filme = ["mãos talentolas", "mãos talentolas", "gente grande", "tom e jerry"]
console.log(filme) // ["mãos talentolas", "gente grande", "tom e jerry"]

filme.shift()
console.log(filme) // ["mãos talentolas", "gente grande"]


const nome = ["luis", "gilson", "frankie", "renato", "thais carla"]
console.log(nome) // [frankie", "renato", "thais carla"]

nome.unshift("gordo", "bob cosntrutor")
console.log(nome) // ["luis", "gilson", "frankie", "renato", "thais carla"]


const amigos = ["douglas", "joão", "lucas", "rafael", "caio", "gabriel", "igor"]
const newArray = amigos.concat(["rafael", "caio"])

console.log(amigos) // ["douglas", "joão", "lucas"]
console.log(newArray) // ["douglas", "joão", "lucas", "rafael", "caio", "sabrina", "gabriel", "igor"] 

const grupo = ["A", "D", "L", "R"]
const string = grupo.join("-")

console.log(grupo) 
console.log(string)  

//Exemplo 1 
const casal =["luis e frankie amores para sempre ❤️👨‍❤️‍👨"]



console.log(casal)

```
