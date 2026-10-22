# Atividade 2 — Minha Página Consome uma API

Projeto de consulta de CEP usando HTML, CSS, JavaScript, `fetch()`, JSON e `try/catch`, conforme a atividade de Desenvolvimento de Websites.

## Como testar no computador

1. Extraia os arquivos da pasta compactada.
2. Abra `index.html` no navegador. Se possível, use a extensão Live Server do Visual Studio Code.
3. Digite `13010-111` e clique em **Buscar**. Deve aparecer o endereço retornado pela API.
4. Teste `00000-000` para conferir a mensagem de CEP não encontrado.
5. Teste uma entrada incompleta, como `123`, para conferir a validação do formulário.

A consulta depende de conexão com a internet, pois usa a API pública ViaCEP.

## Publicar no GitHub

1. Entre em https://github.com e faça login.
2. Clique no botão **+** e escolha **New repository**.
3. Dê um nome ao repositório, por exemplo `atividade-fetch-viacep`.
4. Escolha **Public** (a menos que seu professor peça outra configuração) e clique em **Create repository**.
5. Na página do repositório, clique em **Add file > Upload files**.
6. Envie os três arquivos do site (`index.html`, `style.css` e `script.js`) e também este `README.md`.
7. Clique em **Commit changes** para salvar os arquivos no repositório.

## Publicar o site pelo GitHub Pages

1. No repositório, abra **Settings**.
2. No menu lateral, escolha **Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Em **Branch**, selecione `main` e a pasta `/ (root)`.
5. Clique em **Save**.
6. Aguarde alguns minutos e atualize a página. O GitHub Pages mostrará o endereço publicado, normalmente neste formato:
   `https://SEU-USUARIO.github.io/atividade-fetch-viacep/`

Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub. Use o link exato que aparecer em Settings > Pages.

## O que enviar ao professor

Envie os dois links:
- Repositório do GitHub: `https://github.com/SEU-USUARIO/atividade-fetch-viacep`
- Site publicado: `https://SEU-USUARIO.github.io/atividade-fetch-viacep/`

Antes de enviar, abra o link do site em uma janela anônima para confirmar que está público e funcionando.
