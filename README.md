# FechaJogo — página de divulgação

Página única de marketing do app. Todos os botões levam para
`https://fechajogo-app.vercel.app/login`.

## Como abrir

Dá dois cliques no `index.html`. É só isso — o arquivo é **autocontido**:
CSS, fontes do sistema e as três imagens estão todos dentro dele, em
`data:` URI. Não depende de internet, de CDN nem de servidor. Funciona
aberto do disco, mandado por e-mail ou hospedado em qualquer lugar.

## Como publicar

Como é um arquivo só, qualquer hospedagem estática serve:

- **Vercel** — `vercel deploy` nesta pasta, ou arrastar a pasta no dashboard.
- **GitHub Pages / Netlify / Cloudflare Pages** — mesma ideia.
- Um subdomínio apontando pra cá, se um dia o FechaJogo tiver domínio próprio.

Nada precisa ser buildado.

## Sobre as imagens

Os três prints saíram do tarball dos guias em PDF
(`../guias/fonte-dos-guias.tar.gz`), que usa o **elenco fictício** — Bruna
Lima, Caio Ferreira, etc. — e telefones inventados.

⚠️ **Não troque por prints de `../prints/`.** Aqueles têm nome e telefone de
gente real, e esta página é feita pra ser pública.

As imagens foram recortadas para 780×1688, redimensionadas para 640×1385 e
convertidas para WebP (qualidade 80), o que deixa o arquivo final em ~162 KB.

## O que precisa de atenção quando o app mudar

O texto afirma coisas concretas sobre o produto. Se alguma mudar, a página
mente:

- é gratuito (existe só a tela de apoio via Pix, opcional);
- avulso entra sem criar conta, só com o telefone;
- login por Google **ou** código de 6 dígitos no e-mail;
- esportes: vôlei, futebol, futsal, beach tênis e peteca;
- dá pra excluir a conta pelo próprio app.

Os prints também envelhecem — a tela do organizador e a de sorteio mudam com
alguma frequência.

## Fontes

Para regerar do zero, o material está em:

- `../guias/fonte-dos-guias.tar.gz` → `img/guia-11-jogo-organizador.png`,
  `img/guia-13-sorteio-resultado.png`, `img/guia-18-avulso-inicial.png`
- `../definicoes.md` → especificação do produto, de onde saíram as afirmações
