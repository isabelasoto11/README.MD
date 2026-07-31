# README.MD
# ----------------Introdução de Back-end-----------------------------
## O que é ? 
 O Back-ende é o código que está por trás da interfarce de um site,o qual os usuários não vemm ele também é responsável pelo o processamento,a lógica de negócio e a comunicação,garantindo que tudo funcione corretamente.

 ## O que é Front-end?
 Front-end é a parte de um site ou aplicativo que o usuário vê e com a qual interage diretamente na tela, incluindo botões, menus, textos e cores.

 ## O que é a API?
 API (Interface de Programação de Aplicações) é um conjunto de regras que permite que diferentes sistemas de software conversem entre si de forma segura. Ela funciona como uma ponte ou um garçom, que pega o pedido de um aplicativo, leva para outro sistema processar e traz a resposta de volta.

## Pacotes
Pacotes são bibliotecas de código pré-pronto que instalamos no projeto usando o gerenciador NPM para facilitar o desenvolvimento e não precisar recriar funcionalidades do zero.

## Comandos
 1- *npm init -y* --> Cria rapidamente o package.json base sem fazer perguntas.*NPM= gerenciador de pacote no node *

 2. *npm i <nome arquivo>* /*npm install<nome arquivo>*

 3.*npm i nodemon* serve para instalar o Nodemon, uma ferramenta que reinicia o seu servidor Node.js de forma automática assim que você altera e salva qualquer arquivo no código.

 4.*npm install chalk* Muda a cor da fonte. como usar:
  import chalk from 'chalk';

console.log(chalk.blue('Hello world!'));

5.*npm install figlet*
import figlet from "figlet";

async function doStuff() {
  const text = await figlet.text("Hello World!!");
  console.log(text);
}

doStuff();
