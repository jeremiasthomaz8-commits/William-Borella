# William Borella — portfólio audiovisual

Site estático, sem dependências de instalação. Execute `npm run dev` e acesse http://127.0.0.1:4173. Verificação de sintaxe: `npm run check`. A pasta publicável é `dist/`.

## Conteúdo e edição

- `dist/app.js`: traduções PT/EN, projetos, serviços e galeria. Casos e resultados foram transcritos/adaptados do PDF fornecido. As capas e galerias dos clientes usam as mídias fornecidas no ZIP. Amadeus mantém sua apresentação tipográfica, pois não há arquivos desse cliente no ZIP.
- `dist/style.css`: identidade visual e responsividade. Paleta: #000000, #C13E00, #F1EBD5.
- `dist/assets/`: fotografias fornecidas otimizadas em WebP, logotipos SVG originais sem alteração, fontes Barlow Condensed e DM Sans hospedadas localmente.
- `dist/index.html`: estrutura semântica, metadados e formulário.

## Pendências de conteúdo

Foram integrados os 22 arquivos do ZIP: Gross (5 fotos e 5 vídeos), O Rocco (2 vídeos), Affinità (2 vídeos), Bons Ares (3 imagens), Quero Férias (3 imagens) e Clicar e Viajar (2 imagens). Imagens em WebP e vídeos H.264/AAC com faststart, proporções preservadas e carregamento sob demanda. Nenhum original foi sobrescrito. `dist/case-media.json` registra o vínculo entre arquivos originais e versões web; `dist/case-media.js` fornece os mesmos dados ao navegador.

Continuam pendentes as mídias de Amadeus e um canal real de contato. Os retratos são apresentados como retratos de William, sem atribuir autoria fotográfica.

O formulário valida os campos e baixa um briefing local; **não envia nem armazena dados em servidor**. A interface informa isso explicitamente. Conectar um canal de contato confirmado antes de lançar para captação de leads. O fluxo de Sites mantém esta prévia privada por padrão.

## Recursos

Navegação por âncoras, menu mobile, catálogo filtrável, rolagem horizontal com botões e toque, detalhes em dialog nativo, lightbox com setas e teclado, Escape para fechar, retorno de foco nativo, PT/EN persistido localmente, movimentos reduzidos respeitados, lazy loading e fontes locais.
