## Resumo

Belo Horizonte tem fama de ser a capital com mais bares do Brasil, de fato, ela parece ter bares em todas esquinas.
Esse projeto se dedica a investigar o quão singular é essa propriedade da capital mineira.

## Metodologia

- Coleta de dados
- Pré-processamento
- Criação do Indíce de Bares por Cidade (IBC)
- Análise exploratória
- visualização

## Estrutura do repositório

~~~
bh-botecos/
│
├── data/
│ ├── processed/
│ └── raw/
│
├── notebooks/
│
├── src/
│
├── README.md
└── requirements.txt
~~~

## Referencial Teórico
A distribuição espacial de atividades econômicas e sociais nas cidades é um tema recorrente na geografia e na economia urbana. A Teoria do Lugar Central, formulada por Walter Christaller em 1933, propõe que bens e serviços se organizam em uma hierarquia de centros urbanos, definidos pela acessibilidade, pelo fluxo de pessoas e pelo alcance de mercado. Em síntese, cada cidade ou bairro exerce uma função central, concentrando atividades de acordo com sua capacidade de atrair consumidores. Essa estrutura explica por que determinadas regiões urbanas apresentam uma concentração desproporcional de estabelecimentos — fenômeno que, no caso de Belo Horizonte, pode ser observado na densidade de bares e restaurantes ao longo dos eixos de maior circulação.

A partir dessa base conceitual, estudos recentes em teoria de escalonamento urbano (Bettencourt, 2022) demonstram que as variáveis socioeconômicas não crescem de forma linear com o tamanho das cidades. A densidade populacional, o número de interações sociais e a oferta de comércio tendem a seguir um comportamento superlinear, no qual grandes centros apresentam muito mais atividades do que o esperado proporcionalmente. Sob essa perspectiva, a concentração de bares em Belo Horizonte pode ser interpretada como uma manifestação superlinear da vida social urbana, onde o aumento da população e da conectividade estimula o crescimento acelerado de espaços de sociabilidade.

A forma urbana da capital mineira reforça essa interpretação. Como analisa o estudo A investigação da forma urbana em Minas Gerais, Brasil (Scielo, 2019), Belo Horizonte foi concebida a partir de um plano geométrico modernizador, inspirado em modelos europeus, mas acabou expandindo-se de maneira fragmentada e irregular. Esse processo resultou em uma cidade de contrastes — com um núcleo planejado de alta densidade e uma periferia orgânica, marcada por centralidades locais. Essa morfologia híbrida favoreceu a proliferação de polos de lazer e comércio de bairro, especialmente bares, que funcionam como pontos de encontro e identidade comunitária.

Por fim, as teorias de redes urbanas complementam essa análise ao enfatizar que o espaço urbano é sustentado por fluxos de mobilidade e interação, e não apenas por proximidade física. O artigo Estudos sobre a rede urbana: os precursores da teoria das localidades centrais (UEPG, 2015) destaca que a dinâmica das cidades depende da interconexão entre seus diversos núcleos funcionais. Nesse contexto, a localização de bares pode ser entendida como um indicador empírico da intensidade das relações sociais e da conectividade intraurbana — um reflexo direto da vitalidade da rede urbana belo-horizontina.

Assim, a partir da integração entre as teorias de centralidade, escalonamento e rede urbana, é possível compreender a alta concentração de bares em Belo Horizonte não como mera coincidência cultural, mas como um fenômeno espacial e socioeconômico consistente, emergente das próprias propriedades estruturais da cidade.

## Referências

BETTENCOURT, Luís M. A. Global City Densities: Re-examining Urban Scaling Theory. 2022. Disponível em: https://arxiv.org/abs/2210.08067

CHRISTALLER, Walter. A Teoria do Lugar Central. Tradução de material didático (1966). Disponível em: https://economiadoterritorio.wordpress.com/wp-content/uploads/2014/10/aula-3-teoria-do-lugar-central-christaller.pdf

COSTA, Luiz A.; ANDRADE, M. M. A investigação da forma urbana em Minas Gerais, Brasil. urbe – Revista Brasileira de Gestão Urbana, v. 11, 2019. Disponível em: https://www.scielo.br/j/urbe/a/PYKWxr4kskJ5HjMCnhCrmrC/?format=pdf&lang=pt

SILVA, Rodrigo P. Estudos sobre a rede urbana: os precursores da teoria das localidades centrais. Observatório da Geografia – UEPG, 2015. Disponível em: https://observatoriodageografia.uepg.br/files/original/08ea3137d5c8abd995478e650bd312488ac57543.pdf