# Introdução (NX + ANGULAR + TAILWIND CSS)

Este é um guia básico sobre como usar o **Tailwind** em projetos **Angular** e **Angular Libs** com o **Nx**. Ele fornece instruções iniciais passo a passo sobre como iniciar e configurar novos aplicativos e bibliotecas para usar o tailwind.

### Criando um projeto Angular
* Para criar um novo projeto usando o Nx, você pode executar o seguinte comando:
  * Este comando criará um novo projeto Angular chamado "my-app" em seu projeto Nx.
```shell
npm install @nrwl/angular
npx -p @nrwl/nx nx g @nrwl/angular:application my-app
```

* Para configurar o **Tailwind** em seu projeto Angular, você pode executar o seguinte comando:
  * Este comando irá realizar a configuração automática do Tailwind em seu projeto, adicionando os arquivos e dependências necessários.
```shell
npx -p @nrwl/nx nx g @nrwl/angular:setup-tailwind my-app
```

### Criando uma biblioteca Angular
* Se você deseja criar uma nova biblioteca Angular em seu projeto Nx, pode executar o seguinte comando:
  * Este comando criará uma nova biblioteca Angular chamada "my-lib" em seu projeto Nx, com suporte para construção e configuração do Tailwind CSS.
```shell
npx -p @nrwl/nx nx g @nx/angular:library my-lib --buildable --add-tailwind
```

### Algumas referencias:
* O Tailwind CSS é uma estrutura CSS utilitária altamente personalizável que permite criar estilos rapidamente, aplicando classes diretamente no HTML. Aqui estão alguns recursos úteis sobre o uso do Tailwind CSS com o Angular:

#### Como usar o Tailwind CSS em modo "Just-in-Time" no Angular
https://www.amadousall.com/how-to-use-tailwind-just-in-time-mode-in-angular/

#### Uso do Tailwind CSS com projetos Angular
https://v2.tailwindcss.com/docs/just-in-time-mode#enabling-jit-mode

#### Documentação oficial do Tailwind CSS sobre o modo "Just-in-Time"
https://nx.dev/recipes/other/using-tailwind-css-with-angular-projects
