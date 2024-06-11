# Ollama

## Introdução

Bem-vindo ao repositório Ollama! Este é um projeto que utiliza inteligência
artificial (IA) para gerar respostas personalizadas. Neste readme, você
encontrará as instruções para clonar o repositório, instalar as dependências e
executar o aplicativo.

## Download Ollama

```
https://www.ollama.com/download
```

## Clonando o Repositório

Para começar, clone o repositório do Ollama utilizando o comando:
```
git clone https://github.com/HulkFront/ollama.git
```

## Instalando Dependências

Após clonar o repositório, navegue até a pasta do projeto e execute o comando:
```
npm install
```
Este comando instalará todas as dependências necessárias para executar o
aplicativo.

## Executando o Aplicativo

Para executar o aplicativo, execute o comando:
```
node index.js
```
Este comando iniciará o servidor do aplicativo. O aplicativo estará disponível
na porta 3000.

## Testes com Insomnia

Para testar as rotas do aplicativo, utilize a ferramenta Insomnia (ou qualquer
outro cliente HTTP). A rota POST para testes é:
```
http://localhost:3000/ia
```
Este endpoint permite que você teste as funcionalidades de IA do aplicativo.
Você pode enviar uma requisição POST com um payload JSON contendo os dados a
serem processados.

Exemplo de payload:
```json
{
  "text": "Seu texto aqui"
}
```
Substitua `Seu texto aqui` pelo seu próprio texto. A resposta do endpoint será
uma string com a resposta personalizada gerada pela IA.

## Conclusão

Espero que você tenha gostado deste repositório e que ele tenha sido útil para seus
projetos de IA. Se tiver alguma dúvida ou precisar de ajuda é só chamar!
