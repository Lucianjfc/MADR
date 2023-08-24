---
# These are optional elements. Feel free to remove any of them.
status: { accepted }
date: { 2023-08-24 }
deciders: { Lucian Julio }
---

# Framework para desenvolvimento de aplicação de BI na Web

## Context and Problem Statement

- Desenvolvimento de uma aplicação escalável que ofereça dashboards interativos.

<!-- This is an optional element. Feel free to remove. -->

## Decision Drivers

- Escalabilidade | Excelente desempenho | Ótima Experiência do Usuário

## Considered Options

- Utilização do framework Next.js para o desenvolvimento do projeto.
- Utilização da biblioteca React.js para o desenvolvimento do projeto, em conjunto com outras bibliotecas externas para lidar com questões de roteamento, requisições e gerenciamento de estado na aplicação.

## Decision Outcome

- Foi escolhido o Nextjs como ferramenta para desenvolvimento da aplicação

- A escolha do Next.js se deu devido à sua ampla utilização no mercado, excelente desempenho e ao fato de ser recomendado pela própria equipe do React. Além disso, o Next.js oferece soluções integradas para roteamento e carregamento rápido de imagens, eliminando a necessidade de depender de bibliotecas de terceiros para essas funcionalidades.

<!-- This is an optional element. Feel free to remove. -->

### Consequences

- Integrações de cache com a fetch API, contribuindo para a otimização.
- Suporte a SSR, resultando em uma renderização de página mais rápida.
- Pré-carregamento de páginas, antecipando redirecionamentos e proporcionando uma experiência de renderização quase instantânea.
- No entanto, é importante observar que a transição para o Next.js pode exigir treinamento da equipe para se familiarizar com o novo framework.

## More Information

- Em resumo, as decisões foram tomadas com base em uma análise criteriosa, incluindo avaliação de documentações e testes de desempenho por meio da PoC desenvolvida. O Next.js foi escolhido como uma solução adequada para atender às demandas de escalabilidade, desempenho e experiência do usuário.
