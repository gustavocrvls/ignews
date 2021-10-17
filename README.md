<h1 align="center">
  ig.news
</h1>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Ignite | Rocketseat" src="https://img.shields.io/badge/made%20in-Ignite%20|%20Rocketseat-5965e0">
  </a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-5965e0">
</p>

## 💡 Sobre o Projeto

O projeto foi desenvolvido a trilha de React do Ignite, programa realizado pela [Rocketseat](https://rocketseat.com.br/) 🚀💜

O ignews é uma plataforma de assinatura de artigos relacionados ao framework React.

Você pode dar uma olhada no protótipo do projeto em: <a href="https://www.figma.com/file/GQTFNpji8OBdhvnzccMgsx/Ignite---ig.news" target="_blank">ig.news</a>

## 🛠 Tecnologias Usadas
- Typescript
- React
- Next
- NextAuth
- Prisma
- FaunaDB
- Stripe

## 🧙‍♂️ Como Iniciar o Projeto

Primeiro faça a clonagem do projeto em algum diretorio do seu computador:
```bash
> cd "algum/diretorio/qualquer"
> git clone https://github.com/gustavocrvls/ignews.git
```

Depois disso instale as dependências:
```bash
> yarn
```

Após isso crie um arquivo _.env_ na raiz do projeto com os seguintes campos:

```env
STRIPE_API_KEY=
STRIPE_SUCCESS_URL=
STRIPE_CANCEL_URL=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

FAUNADB_KEY=

PRISMIC_ENDPOINT=
PRISMIC_ACCESS_TOKEN=
```

E então é só iniciar o projeto:
```bash
> yarn dev
```

O projeto vai iniciar em http://localhost:3000. 

Isso é tudo, pessoal!😉
