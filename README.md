# Projeto: Streaming de Música (Etapa 4/5)

## Descrição

Esta é a quarta etapa do desenvolvimento de um serviço de streaming de música. Nesta fase, foi utilizado o json-server para simular uma API RESTful a partir de um arquivo JSON.

Essa abordagem é útil para testes e para o desenvolvimento do front-end enquanto o back-end ainda está sendo construído.

## Instalação

Antes de iniciar o projeto, certifique-se de ter o [**Node.js**](https://nodejs.org/pt) instalado na sua máquina.

1. **Desinstalar versões globais anteriores do json-server (caso necessário)**
```bash
npm uninstall -g json-server
```

2. **Instalar a versão correta do json-server globalmente**
```bash
npm i -g json-server@0.17
```
Esse comando instala a versão 0.17 do json-server globalmente, permitindo que ele seja executado de qualquer lugar no terminal.

3. **Iniciar o servidor JSON**
```bash
json-server --watch api-artists/artists.json --port 3000
```

### Esse comando:

- Monitora o arquivo artists.json dentro da pasta api-artists.
- Inicia o servidor na porta 3000.
- A API fake estará disponível em: http://localhost:3000/artists

## O que foi feito até aqui:
- Criar os cards da página inicial;
- Aprender a usar o **CSS Grid Layout**;
- Utilizar **media queries** para responsividade;
- **Instalar o Node.js**;
- Introduzir o **JavaScript** no projeto;
- Utilizar o conceito de **DOM**;
- Conhecer o método **Promises** do JavaScript.

## Tecnologias Utilizadas
- json-server
- HTML5
- CSS3 (Grid Layout, Media Queries)
- JavaScript (DOM, Promises)

## Como Contribuir

Para contribuir com o projeto, siga os passos abaixo:

1. Faça um **fork** do repositório.
   
2. Clone o repositório para sua máquina local:
```bash
git clone <URL_DO_REPOSITORIO>
```
   
3. Acesse o diretório do projeto:
```bash
cd nome-do-repositorio
```

4. Crie uma nova branch para suas alterações:
```bash
git checkout -b minha-feature
```
   
5. Faça suas alterações no código e realize um commit:
```bash
git commit -m "Minha nova feature"
```

6. Envie as alterações para o repositório remoto:
```bash
git push origin minha-feature
```
   
7. Acesse o repositório no GitHub e abra um Pull Request para revisão. 🚀
