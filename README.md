<p align="center">
  <img src="https://www.guairaca.com.br/wp-content/themes/guairaca-mobile/images/uniguairaca.png" width="260" />
</p>

> Projeto construído como exemplo para a palestra do projeto integrador do curso de Análise e Desenvolvimento de Sistemas, da [UniGuairaca](https://www.guairaca.com.br), no dia 02 de julho de 2020.

![Light](github/home_light.jpg)

![Dark](github/home.png)

### 💡 Você vai precisar

- O editor de código [Visual Studio Code](https://code.visualstudio.com/Download), da Microsoft. Além de ter vários recursos interessantes, é o mesmo utilizado na aula gravada da palestra.
- A extensão [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass), que você pode instalar diretamente do seu VSCode, na aba **Extensões**;
  - Ela pode ser visualizada com o atalho `Ctrl + Shift + X` (ou `⌘ + Shift + X` no Mac);
- A extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), que pode ser encontrada da mesma forma.

### 📝 Como usar?

```bash
# Clone o repositório
$ git clone https://github.com/MattZ6/palestra-projeto-integrador-tads-2020.git viagenzinhas

# Entre na pasta do projeto
$ cd viagenzinhas

# Abra o VSCode na pasta do projeto
$ code .
```

Com o editor de código aberto na pasta do projeto, você irá notar dois botões no canto inferior direito do mesmo: **Go Live** & **Watch Sass**.

Ao clicar no botão **Go Live**, a extensão irá "servir" localmente a página na porta `5500` - basicamente abrir seu navegador com a aplicação no endereço `http://localhost:5500`. Isso irá servir de hot reload em tempo de desenvolvimento, ou seja, todas as alterações feitas dentro dos arquivos do projeto irão refletir na atualização da página (assim não precisamos ficar apertando `F5` o tempo todo 😉);

O segundo botão habilitado pelas extensões instaladas é o **Watch Sass**. Quando habilitado, irá fazer com que todo o código escrito utilizando SASS seja transformado em CSS puro, assim tornando nossa página super estilosa. 💅🏻
