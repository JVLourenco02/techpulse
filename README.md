# TechPulse — Portal de Notícias de Tecnologia

Página inicial desenvolvida em HTML5 e CSS3 externo para a entrega prática do projeto TechPulse, com foco em organização semântica, separação entre estrutura e estilo e adaptação para telas menores.

## Estrutura de arquivos

- **index.html** : estrutura da página com cabeçalho, navegação, três seções principais (article) e rodapé.
- **style.css**: estilos externos, regras do Box Model e ajuste responsivo para telas de até 600px.
- **imagens/**: imagens utilizadas nas seções de notícias, inovações e tutoriais.

## Especificações técnicas e justificativas

### Cores
- **Cabeçalho e rodapé (#0f172a)**: tom escuro para criar contraste nítido com o texto branco e separar visualmente o início e o fim da página.
- **Fundo da página (#f4f6f9) e cartões (#ffffff)**: fundo cinza claro para reduzir o brilho direto em relação ao branco puro, mantendo os blocos de conteúdo destacados com borda discreta (`#cbd5e1`).
- **Texto principal (#1e293b)**: cinza bem escuro, mais suave para leitura contínua do que preto puro.
- **Botão (#1d4ed8, com #1e40af no hover)**: azul para diferenciar a ação de retorno ao início sem competir com o restante do texto.

### Tipografia
- **Fonte**: Arial, escolhida por ser simples, legível e disponível sem depender de fontes externas.
- **Tamanho e alinhamento**: corpo com 16px e line-height: 1.5 alinhado à esquerda para facilitar a leitura de parágrafos e listas.

### Espaços criados e layout
- O conteúdo principal fica dentro de **main** limitado a 800px de largura e centralizado com margin: 24px auto.
- Cada **article** recebeu padding interno e margin-bottom para separar os blocos, e as imagens usam width: 100% com max-width: 600px e height: auto para não estourar a tela.
- Abaixo de 600px (@media), os espaçamentos internos e das margens dos links de navegação são reduzidos para caber melhor no celular.

### Tecnologias e serviços utilizados
- **HTML5 e CSS3**: marcação semântica e estilização externa.
- **VS Code / Git / GitHub**: edição do código, versionamento e publicação do repositório.

## Sitemap Visual

Hierarquia organizada a partir da página inicial (**index.html**), agrupando os conteúdos por tema (taxonomia) e nível de profundidade (hierarquia):

```text
TechPulse (Página Inicial)
├── Notícias (#noticias)
│   ├── Inteligência Artificial
│   └── Computação em Nuvem
├── Inovações (#inovacoes)
│   ├── Robótica avançada
│   └── Realidade Virtual
└── Tutoriais (#tutoriais)
    ├── Introdução à programação
    └── Desenvolvimento Web