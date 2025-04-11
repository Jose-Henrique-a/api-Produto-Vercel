# api-Produto-Vercel
Esta API em Node está hospedada no Vercel para ser consumida.

Link da API: https://api-produto-vercel.vercel.app/

# CRUD do Produto:
Este app está hospedado no Netlify. E está consumindo a API do Vercel.

link do CRUD: https://crud-produto-preco.netlify.app/

## Deploy do JSON Server na Vercel

Um template para fazer o deploy do [JSON Server](https://github.com/typicode/json-server) na [Vercel](https://vercel.com) permite que você rode uma API REST fake (mock API) online!

Demonstração deste repositório: 

1. [https://json-server-vercel-api.vercel.app/](https://json-server-vercel-api.vercel.app/)
2. [https://json-server-vercel-api.vercel.app/produtos](https://json-server-vercel-api.vercel.app/produtos)

### Como utilizar

1. Clique em "**Use this template**" ou clone este repositório.
2. Atualize o [`db.json`](./db.json) ou utilize o padrão no repositório.
3. Crie uma conta ou faça login na [Vercel](https://vercel.com).
4. A partir da dashboard da Vercel, clique "**+ New Project**" e então "**Import**" seu repositório.
5. Na tela "**Configure Project**", deixe tudo padrão e clique "**Deploy**".
6. Aguarde até que o deploy esteja terminado e o seu próprio JSON Server está pronto para uso!

## `db.json` padrão

```json
[
  {
    "id": 1,
    "descricao": "Sapato Social New York",
    "preco": "199.90",
    "imagem": "produto.webp"
  }
]
```

## Referências
1. Professor Anderson Fontes : https://github.com/andersonfontes
2. https://github.com/typicode/json-server
3. https://vercel.com
4. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
5. https://github.com/kitloong/json-server-vercel