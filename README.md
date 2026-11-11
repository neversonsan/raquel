# ATELIER PROTECT — V1 em Astro

Protótipo migrado do HTML original para Astro, pronto para publicar na Vercel.

## Como executar

```bash
npm install
npm run dev
```

Abra o endereço indicado (geralmente http://localhost:4321).

## Publicar na Vercel

1. Envie esta pasta para um repositório no GitHub.
2. Na Vercel, escolha **Add New > Project** e importe o repositório.
3. Preset: **Astro**; Build Command: `npm run build`; Output Directory: `dist`.
4. Clique em Deploy.

## Limitações desta V1

- Dados do painel armazenados somente no `localStorage` do navegador; não sincronizam entre computadores.
- A área do cliente é uma simulação e **não possui login/autenticação real**.
- A impressão do certificado é feita pelo navegador e não constitui garantia oficial.
- Não há envio automático de e-mails nem banco de dados no servidor.
- Não insira dados reais de clientes nesta versão pública.
- A identidade ATELIER PROTECT é provisória.

Para produção, será necessário integrar autenticação, persistência em banco de dados, permissões e envio seguro de e-mails via backend (WordPress/plugin ou API separada).
