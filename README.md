# Rodadas de Negócios · SEBRAE

![Preview do projeto](assets/social-banner-whatsapp.png)

Uma página de apresentação para um SaaS de **rodadas de negócios**, pensado para apoiar o SEBRAE na operação de eventos de ponta a ponta: cadastro, matchmaking, agenda automática e relatório pós-rodada.

O projeto está em um único arquivo HTML, com CSS e JavaScript embutidos, pronto para abrir no navegador ou publicar como página estática.

## Visão Geral

A proposta transforma o processo manual de organização de rodadas em uma experiência digital clara e estruturada. A plataforma ajuda a cruzar demandas de compradores com ofertas de fornecedores, gerar agendas sem conflito e consolidar indicadores depois do evento.

## Funcionalidades Apresentadas

- **Cadastro pré-edital** de compradores, fornecedores, demandas, ofertas e documentos.
- **Matchmaking com curadoria** usando score de compatibilidade e aprovação humana.
- **Agenda automática** com slots, mesas, prioridades e envio individual aos participantes.
- **Relatório pós-rodada** com presença, resultado da reunião, NPS e expectativa de vendas.
- **Banner social Open Graph** otimizado para preview em WhatsApp e redes sociais.

## Entregas do Produto

| Entrega | Foco | Resultado |
| --- | --- | --- |
| 1 | Cadastros | Base de compradores, fornecedores, demandas e ofertas |
| 2 | Matchmaking | Sugestões ranqueadas e curadoria do SEBRAE |
| 3 | Agenda | Cronograma automático sem conflito |
| 4 | Pós-rodada | KPIs, formulários, dashboards e exportação |

## Estrutura

```text
.
├── analise-helka.html
└── assets/
    └── social-banner-whatsapp.png
```

## Como Abrir

Abra o arquivo diretamente no navegador:

```bash
open analise-helka.html
```

Ou sirva localmente:

```bash
python3 -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/analise-helka.html
```

## Preview em WhatsApp

O HTML já inclui metatags Open Graph e Twitter Card apontando para:

```text
assets/social-banner-whatsapp.png
```

O banner está no formato recomendado para preview social:

- `1200 x 630 px`
- PNG
- proporção `1.91:1`

Ao publicar o projeto, prefira trocar o caminho relativo do `og:image` por uma URL absoluta pública, por exemplo:

```html
<meta property="og:image" content="https://seu-dominio.com/assets/social-banner-whatsapp.png">
```

## Tecnologias

- HTML5
- CSS3
- JavaScript vanilla
- Google Fonts
- SVG inline para visualização de matchmaking

## Publicação

Por ser uma página estática, o projeto pode ser publicado facilmente em:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Para GitHub Pages, configure o repositório para servir a branch principal e acesse o arquivo `analise-helka.html`.
