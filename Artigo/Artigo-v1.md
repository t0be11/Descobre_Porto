# Contributos da Inteligência Artificial para a Acessibilidade Web

## Resumo

A acessibilidade Web procura garantir que os websites podem ser utilizados por pessoas com diferentes capacidades e necessidades. A Inteligência Artificial (IA) pode contribuir para este objetivo, apoiando tarefas como a criação de descrições de imagens, a identificação de problemas de acessibilidade e a simplificação de conteúdos.

Este artigo analisa os possíveis contributos da IA, assim como as suas limitações. Como aplicação prática, será utilizado o projeto académico *Descobre o Porto*, um website turístico desenvolvido em HTML, CSS e JavaScript.

A análise pretende demonstrar que a IA pode ser uma ferramenta de apoio ao desenvolvimento Web, mas que os resultados produzidos devem ser avaliados e corrigidos por pessoas.

**Palavras-chave:** Inteligência Artificial, acessibilidade Web, WCAG, textos alternativos, HTML.

## 1. Introdução

Atualmente, os websites são utilizados para consultar informações, comunicar, estudar e aceder a diversos serviços. Por esse motivo, é importante garantir que todas as pessoas conseguem utilizar estes recursos, incluindo aquelas que apresentam limitações visuais, auditivas, motoras ou cognitivas.

A acessibilidade Web tem como objetivo reduzir as barreiras que dificultam a utilização das páginas e das suas funcionalidades. Um website acessível deve permitir, por exemplo, navegar através do teclado, compreender os conteúdos apresentados e utilizar tecnologias de apoio.

Ao mesmo tempo, a Inteligência Artificial tem evoluído e passou a ser utilizada em diferentes áreas, incluindo o desenvolvimento de websites. Estas ferramentas conseguem analisar conteúdos, gerar textos e sugerir alterações ao código.

No contexto da acessibilidade, a IA pode ajudar os programadores a identificar problemas e a produzir conteúdos mais adequados. Contudo, as respostas geradas nem sempre são corretas, pelo que não devem ser utilizadas sem verificação.

Este artigo procura responder à seguinte questão: **De que forma pode a Inteligência Artificial melhorar a acessibilidade de um website turístico e quais são as principais limitações da sua utilização?**

## 2. Acessibilidade Web e normas WCAG 2.2

A acessibilidade Web consiste em desenvolver páginas que possam ser utilizadas pelo maior número possível de pessoas, independentemente das suas capacidades ou das tecnologias que utilizam.

O World Wide Web Consortium (W3C) desenvolveu as Web Content Accessibility Guidelines (WCAG), um conjunto de recomendações internacionais para melhorar a acessibilidade dos conteúdos digitais.

As WCAG 2.2 organizam-se em quatro princípios fundamentais:

- **Percetível:** a informação deve ser apresentada de forma que os utilizadores a consigam percecionar.
- **Operável:** os componentes e a navegação devem poder ser utilizados através de diferentes formas de interação.
- **Compreensível:** a informação e o funcionamento da interface devem ser claros.
- **Robusto:** o conteúdo deve ser compatível com diferentes navegadores e tecnologias de apoio.

Uma das preocupações destas recomendações está relacionada com as imagens. Quando uma imagem transmite informação importante, deve existir uma alternativa textual que permita compreender o seu conteúdo.

No HTML, esta descrição é normalmente introduzida através do atributo `alt`, presente no elemento `img`.

Por exemplo, num website turístico, uma fotografia da Ribeira pode ter uma descrição que identifique os edifícios tradicionais junto ao rio Douro.

Esta informação pode ser transmitida através de leitores de ecrã, ajudando pessoas com deficiência visual a compreender o conteúdo da página.

## 3. Contributos da Inteligência Artificial

### 3.1. Geração de textos alternativos para imagens

Uma das aplicações da Inteligência Artificial na acessibilidade Web é a criação automática de descrições de imagens.

Os sistemas de IA com capacidade de análise visual podem identificar objetos, edifícios, paisagens e outros elementos presentes numa fotografia.

A partir dessa análise, conseguem gerar uma descrição textual que pode ser utilizada como ponto de partida para o atributo `alt`.

Num website turístico como o Descobre o Porto, esta funcionalidade pode ser útil para descrever fotografias de monumentos, locais históricos e pratos tradicionais.

Por exemplo, perante uma fotografia da Torre dos Clérigos, a IA pode identificar a torre e alguns elementos da paisagem urbana.

Contudo, não basta que a descrição esteja correta do ponto de vista visual. Também deve ser adequada ao contexto da página.

Se a fotografia for utilizada para apresentar um monumento turístico, a descrição deve privilegiar a informação que ajuda o visitante a compreender o local.

Por isso, a descrição gerada automaticamente deve ser analisada antes de ser integrada no website.

### 3.2. Identificação de problemas de acessibilidade

Outra aplicação possível da IA é o apoio à análise do código HTML e CSS.

Uma ferramenta pode ajudar a identificar imagens sem textos alternativos, campos de formulário pouco claros ou elementos cuja utilização através do teclado necessita de verificação.

Também pode sugerir melhorias na organização dos títulos, na identificação dos campos obrigatórios e na apresentação dos conteúdos.

No entanto, estas sugestões não substituem uma auditoria de acessibilidade.

A avaliação de um website deve combinar ferramentas automáticas com testes manuais, pois existem problemas que dependem da interpretação humana e do contexto em que os elementos são utilizados.

### 3.3. Simplificação de conteúdos

A Inteligência Artificial também pode apoiar a adaptação de textos, tornando-os mais simples e fáceis de compreender.

Num website turístico, esta possibilidade pode ser útil quando existem descrições históricas muito extensas ou expressões técnicas que dificultam a leitura.

Uma ferramenta de IA pode sugerir frases mais curtas, reorganizar parágrafos e explicar palavras complexas.

Contudo, a simplificação deve preservar o significado original da informação. Um texto mais curto não é necessariamente melhor se eliminar detalhes importantes ou apresentar informações incorretas.

## 4. Limitações e riscos da utilização da IA

Apesar das suas vantagens, a utilização da Inteligência Artificial apresenta limitações.

Um dos principais problemas é a possibilidade de produzir informações incorretas. Ao analisar uma imagem, a IA pode identificar erradamente um monumento ou acrescentar características que não estão presentes.

Outro problema é a falta de compreensão do contexto. Uma descrição pode apresentar muitos detalhes visuais, mas não destacar a informação mais importante para o utilizador.

Também existe o risco de aceitar automaticamente as respostas geradas, sem confirmar a sua qualidade.

Por exemplo, uma ferramenta pode criar uma descrição demasiado longa para uma imagem simples ou repetir informação que já aparece no texto da página.

Segundo as orientações do W3C, as alternativas textuais devem transmitir a informação relevante de acordo com a função e o contexto da imagem.

Assim, a utilização da IA deve ser acompanhada por revisão humana, garantindo que as descrições são claras, corretas e úteis.

## 5. Experiência prática prevista — Descobre o Porto

Para complementar a análise teórica, será realizada uma experiência prática utilizando cinco imagens do website Descobre o Porto.

Serão selecionadas imagens relacionadas com os locais turísticos e a gastronomia da cidade.

Para cada fotografia, será produzida uma descrição através de uma ferramenta de Inteligência Artificial e outra descrição escrita pelo grupo.

Posteriormente, as duas versões serão comparadas segundo três critérios: fidelidade à imagem, clareza e concisão, e adequação ao contexto do website.

Os resultados serão apresentados numa tabela, permitindo identificar as vantagens e limitações das descrições automáticas.

Esta experiência será desenvolvida na fase seguinte do trabalho. Por esse motivo, ainda não são apresentados resultados ou conclusões experimentais.

## 6. Conclusão preliminar

A Inteligência Artificial apresenta possibilidades interessantes para apoiar o desenvolvimento de websites acessíveis.

A geração de textos alternativos, a identificação de problemas no código e a simplificação de conteúdos são exemplos de tarefas em que estas ferramentas podem contribuir.

No entanto, a utilização da IA não garante automaticamente a acessibilidade de uma página.

É necessário avaliar as sugestões produzidas, realizar testes e garantir que os conteúdos respondem às necessidades reais dos utilizadores.

A experiência prática no Descobre o Porto permitirá aprofundar esta análise nas próximas fases do projeto.

## Referências iniciais

- W3C — Web Content Accessibility Guidelines (WCAG) 2.2. https://www.w3.org/TR/WCAG22/
- W3C WAI — WCAG 2 Overview. https://www.w3.org/WAI/standards-guidelines/wcag/
- W3C WAI — Images Tutorial. https://www.w3.org/WAI/tutorials/images/
- W3C WAI — An alt Decision Tree. https://www.w3.org/WAI/tutorials/images/decision-tree/
- W3C WAI — Evaluating Web Accessibility Overview. https://www.w3.org/WAI/test-evaluate/
- Diário da República — Decreto-Lei n.º 82/2022. https://diariodarepublica.pt/dr/detalhe/decreto-lei/82-2022-204379872

## Declaração de utilização de IA

Foi utilizada a ferramenta ChatGPT como apoio à estruturação e à redação preliminar do artigo. O conteúdo deverá ser revisto pelo grupo, que é responsável pela verificação das informações, consulta das referências e elaboração da análise final.