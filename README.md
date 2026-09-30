# Tito Fretes e Socorro - site institucional

Site one-page da **Tito Fretes e Socorro**: fretes, pequenas mudanças, guincho, resgate de motos e transporte de veículos.

## Estrutura

```
index.html   # página única (hero, sobre, serviços, depoimentos, mapa, FAQ)
styles.css   # estilos (tema claro/escuro automático, vermelho da marca)
script.js    # link do WhatsApp, menu mobile, header, animações, carrossel, FAQ
assets/      # favicon e fotos
```

Sem build: HTML, CSS e JS puros. Publique a pasta em GitHub Pages, Netlify, Vercel ou hospedagem comum.

## Antes de publicar

- **WhatsApp**: troque `WHATSAPP` no topo do `script.js` pelo número real (só dígitos, com 55 + DDD). Todos os botões usam essa constante.
- **Mapa**: em `index.html`, troque `SUA+CIDADE` no `src` do iframe pelo endereço ou cidade de atendimento.
- **Endereço**: se houver endereço fixo, substitua o texto do item "Endereço" na seção Localização.
- **Depoimentos** são exemplos. Substitua por avaliações reais de clientes.
- **Logo**: o cabeçalho usa um logotipo em texto. Se quiser usar o logo oficial, salve em `assets/` e troque o bloco `.brand`.

Dados já usados (perfil do WhatsApp Business): atendimento somente com hora marcada, empresa de carga e frete desde julho de 2026, Instagram [@titofreteseresgate](https://www.instagram.com/titofreteseresgate/).

## Créditos das imagens

Fotos via [Unsplash](https://unsplash.com) (licença Unsplash).
