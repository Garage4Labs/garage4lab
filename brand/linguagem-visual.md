# Linguagem visual

Como a Garage4Lab se parece em site, redes, propostas e eventos. A base é a nossa marca (magenta, ink, a placa inclinada, o triângulo do A); a energia vem de referências de software houses AI-driven brasileiras: fundo escuro, cor em blocos inteiros, números enormes e elementos gráficos com personalidade. Inspiração, nunca cópia: tudo aqui é construído com os nossos tokens e a nossa geometria.

## Princípios

1. **Escuro primeiro, magenta em bloco.** Hero, capas e materiais de evento usam o tema Dark (`surface` = ink). Uma seção inteira em `magenta` por página, sangrando de borda a borda, marca a virada da narrativa (ex.: prova social, chamada para ação).
2. **Título é o herói.** Uma frase curta em `hero` (Sora 72px) ou `display`, no máximo duas linhas, sem nada competindo. Subtítulo em `body`, `ink-muted`, até duas linhas.
3. **Número grande, rótulo pequeno.** Resultados aparecem em `stat` (Sora 96px) com um rótulo curto em `body-sm` embaixo. Um número por bloco, nunca uma tabela de números.
4. **Lab à mostra.** Rótulos técnicos em `eyebrow` (mono, caixa alta): numeração de seção, tags de tecnologia, métricas de protótipo. É o lado laboratório da marca.
5. **Rápido no movimento, calmo na leitura.** Marquee e microinterações dão ritmo; o texto nunca se mexe enquanto é lido.

## Elementos gráficos

- **Selos (stickers).** Pequenos selos na forma da placa inclinada do logo, com contorno em `magenta-bright` ou preenchimento `magenta`, e uma palavra curta em `eyebrow`: AI FIRST, FAÇA RÁPIDO, APRENDA RÁPIDO, EM PRODUÇÃO, LAB. Use dois ou três por página, levemente rotacionados (−8° a 8°), soltos ao redor do título. Nunca em cima do texto.
- **Ícones de linha.** Traço de 2px em `magenta-bright` (sobre escuro) ou `ink` (sobre claro), cantos arredondados, sem preenchimento. Temas: circuito, agente, engrenagem, chave, frasco de laboratório, globo em grade.
- **Triângulo do A.** O recorte do A vira marcador de lista, separador e padrão de fundo em linhas de 6 a 12 triângulos.
- **Grade de pontos.** Textura de pontos em `line` (escuro) com espaçamento `space-4`, para fundos de mapa, dados e diagramas de arquitetura.
- **Marquee.** Faixa contínua com logos de clientes (com autorização) ou palavras-chave da marca separadas pelo triângulo: ARQUITETURA ▲ AGENTES ▲ MULTICLOUD ▲ SQUADS ▲ SRE ▲ IA GENERATIVA.
- **Numeração entre parênteses.** Seções e passos com `( 01 )`, `( 02 )` em `eyebrow`. O método da garagem vira `( 01 ) Diagnosticar`, `( 02 ) Prototipar`, `( 03 ) Provar`, `( 04 ) Escalar`. Indicação de rolagem: `( ROLE )`.

## Componentes de marca

- **Botão principal:** fundo `magenta`, texto `on-magenta`, `radius-pill`, `label` em caixa alta, padding `space-4` × `space-8`. Um por tela.
- **Botão secundário:** contorno de 1px em `ink`, texto `ink`, `radius-pill`.
- **Chip / tag:** `radius-pill`, fundo `magenta-soft`, texto `magenta-deep`, `eyebrow`. Para tecnologias e áreas: IA preditiva, LangGraph, AWS, Azure, GCP.
- **Card de produto ou oferta:** `surface-raised`, `radius-lg`, padding `space-6`, título `heading-2`, 2 a 4 chips e um link. Sem sombra.
- **Bloco de número:** fundo `night` ou `magenta`, `stat` em `on-magenta`, rótulo em `body-sm`.

## Estrutura de uma página (site ou landing)

1. **Hero** escuro: título `hero`, subtítulo, botão principal, dois ou três selos, `( ROLE )`.
2. **Marquee** de clientes ou palavras-chave, em seção `magenta` com rótulo em caixa alta.
3. **Manifesto curto** e **bloco de números**.
4. **O método da garagem** numerado `( 01 )` a `( 04 )`.
5. **Ofertas** em cards com chips.
6. **Prova:** depoimentos e cases, com nome e cargo reais e autorização.
7. **Chamada final:** "Vamos construir?" com botão principal.

## Fazer e evitar

| Fazer | Evitar |
| --- | --- |
| Um bloco magenta forte por página | Magenta espalhado em todo elemento |
| Selos com palavras da nossa mensagem | Selos com emoji, mascote ou ilustração figurativa |
| Números reais com rótulo claro | Números sem fonte ou arredondados para impressionar |
| Escuro com muito espaço em volta do título | Degradês azul-roxo, brilhos, sombras e efeitos 3D genéricos |
| Logo de cliente só com autorização | Usar logos de clientes ou de empregadores sem permissão |
