# agu-planejamentos

Este repositório centraliza o contexto, posicionamento, regras de conteúdo, histórico e planejamentos de conteúdo dos clientes da **Agência Agú**.

## Objetivo

Servir como fonte única de verdade para tudo que envolve a produção de conteúdo dos clientes: quem são, como falam, o que pode e o que não pode ser dito, o que já foi feito, e o que está planejado.

## Estrutura do repositório

```
clientes/           # Uma pasta por cliente, com contexto e regras
modelos/            # Templates reutilizáveis para planejamento e peças de conteúdo
planejamentos/       # Planejamentos de conteúdo (calendários, pautas, etc.)
referencias/         # Materiais de referência (benchmarks, exemplos, inspirações)
```

### `clientes/`

Cada cliente tem sua própria subpasta (`clientes/<nome-do-cliente>/`) contendo:

- `posicionamento.md` — posicionamento de marca, propósito, valores, diferenciais.
- `informacoes.md` — dados gerais do cliente (segmento, produtos/serviços, público, contatos, canais).
- `regras-de-conteudo.md` — o que pode e o que não pode ser feito em termos de conteúdo, tom de voz, restrições, aprovações necessárias.
- `historico.md` — registro histórico de conteúdos publicados, decisões tomadas e aprendizados.

Novas pastas de cliente devem seguir sempre esse padrão de quatro arquivos.

### `modelos/`

Templates-base para criação de conteúdo, sem informações específicas de clientes:

- `modelo-planejamento.md` — **estrutura oficial** do planejamento mensal de conteúdo da Agência Agú (ver seção abaixo).
- `modelo-roteiro.md` — estrutura para roteiro (Reels/vídeo).
- `modelo-carrossel.md` — estrutura para carrossel.
- `modelo-stories.md` — estrutura para sequência de stories.

#### Padrão oficial de planejamento mensal

`modelos/modelo-planejamento.md` é o formato **obrigatório** para todo planejamento mensal de conteúdo da Agência Agú. Nenhum outro formato de calendário de conteúdo (genérico, improvisado ou de terceiros) deve substituir essa estrutura. Todo planejamento mensal deve conter, nesta ordem:

1. **Identificação** — cliente e período.
2. **Branding do período** — mensagem central do mês (não pode ser uma frase publicitária genérica; deve sintetizar o momento real da marca no período) e explicação de como ela se distribui entre os pilares estratégicos do cliente.
3. **Diretrizes para o calendário de conteúdo** — quantidade de posts semanais, distribuição por pilares e datas estratégicas do período (datas comerciais, eventos, lançamentos, campanhas, gravações e demais acontecimentos do cliente).
4. **Calendário mensal** — cada conteúdo com `DATA`, `FORMATO`, `TEMA`, `PILAR`, `IDEIA DO POST` e `STATUS`.

Regras que se aplicam a todo planejamento gerado a partir deste modelo:

- Coerência com a mensagem central do mês — os conteúdos não podem parecer ideias isoladas.
- Distribuição estratégica dos pilares, sem repetir assuntos apenas para preencher o calendário.
- `TEMA` (assunto/ângulo específico) é diferente de `IDEIA DO POST` (o que se quer comunicar, provocar ou demonstrar).
- O formato de cada conteúdo é escolhido pela melhor forma de comunicar a ideia, não para variar formatos.
- Consultar sempre o histórico do cliente (`historico.md`) para evitar repetição de pautas e abordagens.
- Antes de criar um planejamento, consultar todos os arquivos de `clientes/[nome-do-cliente]/`.
- Esta etapa não produz copies completas, roteiros ou textos de carrossel — apenas estratégia, pauta, formato e direção.
- `STATUS` reflete somente informação fornecida; na ausência de informação sobre produção/captação, usar "A produzir".

### `planejamentos/`

Planejamentos de conteúdo já elaborados, organizados por cliente e/ou período.

### `referencias/`

Materiais de apoio: benchmarks, relatórios de performance, exemplos de referência, inspirações.

## Diretrizes para trabalhar neste repositório

- **Não inventar informações sobre clientes.** Toda informação de posicionamento, regras, histórico, datas, eventos, produtos, serviços ou resultados deve vir de fontes reais fornecidas pela agência ou pelo cliente. Na ausência de informação, sinalizar `[INFORMAÇÃO NECESSÁRIA]` — nunca preencher com suposições.
- Ao criar a pasta de um novo cliente, sempre incluir os quatro arquivos-base (`posicionamento.md`, `informacoes.md`, `regras-de-conteudo.md`, `historico.md`), mesmo que inicialmente vazios/em branco.
- Ao criar planejamentos ou peças de conteúdo para um cliente específico, sempre consultar antes `clientes/<cliente>/posicionamento.md` e `clientes/<cliente>/regras-de-conteudo.md`.
- Manter os arquivos de `modelos/` genéricos e reutilizáveis — sem referências a clientes específicos.
- Preferir Markdown simples e objetivo, com seções claras, para que os arquivos sejam fáceis de ler e editar tanto por humanos quanto por IA.
