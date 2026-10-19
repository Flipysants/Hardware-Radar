# Hardware Radar — versão 0.1

Comparador mobile-first de ofertas de hardware para PC.

## O que já funciona
- Busca por nome/modelo e detalhes.
- Filtro por categoria.
- Filtro por loja.
- Preço máximo.
- Ordenação automática pelo menor preço.
- Interface responsiva para Android e desktop.
- Manifesto PWA e cache offline básico.

## Importante
Todos os produtos, lojas e preços da versão inicial são fictícios. Não use estes valores para decisões de compra. Não há ainda integração com lojas reais, frete, estoque, histórico ou alertas.

## Testar no computador
Abra `index.html` no navegador. A busca e os filtros funcionam localmente.

## Publicar grátis e instalar no Android
Uma opção é usar GitHub Pages:
1. Crie uma conta no GitHub, se ainda não tiver.
2. Crie um repositório público chamado `hardware-radar`.
3. Envie `index.html`, `manifest.webmanifest` e `sw.js` para a raiz do repositório.
4. Em Settings → Pages, habilite a publicação pela branch principal (`main`) e pasta raiz (`/root`).
5. Aguarde o endereço HTTPS do site.
6. Abra o endereço no Chrome do Android e use o menu ⋮ → “Adicionar à tela inicial” ou “Instalar app”, conforme aparecer.

O caminho de projeto do GitHub Pages costuma ser `https://SEU-USUARIO.github.io/hardware-radar/`. O navegador precisa de HTTPS para ativar o service worker em produção.

## Próxima etapa: dados reais
Precisamos escolher fontes de dados permitidas (API, feed de afiliados ou integração autorizada). Não é seguro depender de scraping frágil nem afirmar que uma oferta está ativa sem validar preço, estoque e data da consulta.
