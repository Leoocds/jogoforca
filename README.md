# Jogo da Forca
Este é um jogo da forca desenvolvido em Node.js com um backend utilizando Express.js e um banco de dados SQLite. O frontend é uma aplicação web simples que permite aos jogadores adivinharem palavras categorizadas.

## Pré-requisitos
Certifique-se de ter o Node.js instalado em sua máquina antes de executar o jogo.

## Instalação
Clone este repositório em sua máquina local: 

'git clone https://github.com/Leoocds/jogo-forca/'

Navegue até o diretório do projeto:

"cd jogo-da-forca"

Instale as dependências do projeto:

"npm install"

## Execução
Para iniciar o servidor e jogar o jogo da forca, siga os passos abaixo:

"npm start"

Em outra janela do terminal, inicie o ngrok para expor o servidor local:

"ngrok http 3000"

O ngrok fornecerá uma URL pública que você pode usar para acessar o jogo da forca no navegador.

## Estrutura do Projeto
public/ contém os arquivos estáticos (CSS, imagens e scripts).

jogodaforca.db é o banco de dados SQLite que armazena as categorias e palavras.

server.js é o arquivo principal do servidor Express.js.

O banco de dados SQLite (jogodaforca.db) contém tabelas para categorias e palavras. Certifique-se de adicionar suas palavras e categorias diretamente no banco de dados.
