<img src="https://github.com/booscaaa/golang-2mb-treinamento-cgi/blob/master/readme-files/cgi.png" />

# Desafio imagem go < 2mb - Treinamento CGI Software

#### Realização do desafio junto com a empresa CGI Software de como gerar uma imagem com menos de 2 megas com Golang.

<br>
<br>

## Passos para a execução
<br>

### Build do Dockerfile
```bash
docker build -t booscaaa/golang-build-2mb .
```
### Verificando o tamanho da imagem
```bash
docker image ls
```
<img src="https://github.com/booscaaa/golang-2mb-treinamento-cgi/blob/master/readme-files/image-size.PNG" />

<br>
<br>

### Rodando a imagem criada
```bash
docker run --name golang-app --rm booscaaa/golang-build-2mb
```
### Output
```bash
CGI Software, Treinamento!
```
