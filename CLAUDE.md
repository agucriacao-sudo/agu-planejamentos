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

- `modelo-planejamento.md` — estrutura para um planejamento de conteúdo.
- `modelo-roteiro.md` — estrutura para roteiro (Reels/vídeo).
- `modelo-carrossel.md` — estrutura para carrossel.
- `modelo-stories.md` — estrutura para sequência de stories.

### `planejamentos/`

Planejamentos de conteúdo já elaborados, organizados por cliente e/ou período.

### `referencias/`

Materiais de apoio: benchmarks, relatórios de performance, exemplos de referência, inspirações.

## Diretrizes para trabalhar neste repositório

- **Não inventar informações sobre clientes.** Toda informação de posicionamento, regras ou histórico deve vir de fontes reais fornecidas pela agência ou pelo cliente. Na ausência de informação, deixar o campo em aberto ou sinalizar a lacuna — nunca preencher com suposições.
- Ao criar a pasta de um novo cliente, sempre incluir os quatro arquivos-base (`posicionamento.md`, `informacoes.md`, `regras-de-conteudo.md`, `historico.md`), mesmo que inicialmente vazios/em branco.
- Ao criar planejamentos ou peças de conteúdo para um cliente específico, sempre consultar antes `clientes/<cliente>/posicionamento.md` e `clientes/<cliente>/regras-de-conteudo.md`.
- Manter os arquivos de `modelos/` genéricos e reutilizáveis — sem referências a clientes específicos.
- Preferir Markdown simples e objetivo, com seções claras, para que os arquivos sejam fáceis de ler e editar tanto por humanos quanto por IA.
