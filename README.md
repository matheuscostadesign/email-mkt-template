## E-mail Marketing Template

- Biblioteca para escrever HTML e CSS moderno e no final gerar HTML com tabelas para o correto funcionamento em plataformas de e-mail (Outlook)

## Dependências

- Node (**v.14 funcionou corretamente**);
- Foundation for E-mails (https://get.foundation/emails/docs/sass-guide.html)
- Gulp (https://gulpjs.com/docs/en/getting-started/quick-start)
- Sass (https://sass-lang.com/install)

## Como instalar

- Instalar Foundation globalmente:

  ```
  npm install --global foundation-cli
  ```

- Abrir terminal e navegar até a pasta que deseja criar o projeto:

  ```bash
  Ex: cd c:\dev-front
  ```

- Executar o comando abaixo p/ criar o template do Foundation:

  ```bash
  foundation new --framework emails
  ```

- Escolher um nome para o projeto:

  ```bash
  ex: email
  ```

- Navegue até a pasta criada:

  ```bash
  Ex: cd email
  ```

- Instale as dependências:

  ```bash
  npm install
  ```

- Execute o projeto:

  ```bash
  npm start
  ```

- Visualize o servidor local no browser:

  ```bash
  http://localhost:3000/
  ```

## Funcionamento

- Navegue até a pasta: `src\pages\index.html`
- Edite esse arquivo usando as tecnologias modernas de desenvolvimento web
- O Foundation irá gerar automaticamente na pasta: `dist\index.html` o arquivo HTML com tabelas
- Pegue este arquivo e utilize onde deseja criar o corpo do e-mail (MailChimp, MailerLite, PHPMailer, etc)
