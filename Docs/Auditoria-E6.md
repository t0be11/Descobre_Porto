# Relatório de Auditoria E6 – Descobre o Porto

## 1. Objetivo

A auditoria teve como objetivo avaliar o desempenho, a acessibilidade e as boas práticas do website Descobre o Porto, identificando problemas e possíveis melhorias.

Foram analisadas três páginas:
- Página inicial (`index.html`)
- Locais a visitar (`locais.html`)
- Contactos (`contactos.html`)

Foram utilizadas duas ferramentas: Google Lighthouse e WAVE.

## 2. Resultados do Lighthouse

| Página | Performance | Acessibilidade | Best Practices | SEO |
|---|---:|---:|---:|---:|
| Início | 99 | 100 | 96 | 100 |
| Locais | 99 | 100 | 96 | 100 |
| Contactos | 99 | 100 | 96 | 100 |

Os resultados demonstram um bom desempenho nas condições dos testes realizados. As três páginas obtiveram a pontuação máxima nos testes automáticos de acessibilidade e SEO.

## 3. Resultados do WAVE

| Página | Erros | Erros de contraste | Avisos |
|---|---:|---:|---:|
| Início | 0 | 0 | 0 |
| Locais | 0 | 0 | 0 |
| Contactos | 0 | 0 | 0 |

O WAVE não identificou erros automáticos de acessibilidade, problemas de contraste ou avisos nas páginas analisadas.

Foram também reconhecidos elementos como textos alternativos nas imagens, etiquetas dos formulários, títulos estruturados e atributos ARIA.

Estes resultados não dispensam a verificação manual da acessibilidade.

## 4. Problemas identificados

### 4.1. Favicon inexistente

Nas três páginas, o Lighthouse identificou um erro 404 relacionado com o ficheiro `favicon.ico`.

Este problema foi apresentado na categoria Best Practices.

### 4.2. Recursos que bloqueiam a apresentação

O Lighthouse identificou recursos que podem atrasar a apresentação inicial das páginas.

As poupanças estimadas foram:
- Início: 1310 ms
- Locais: 990 ms
- Contactos: 1070 ms

### 4.3. CSS não utilizado

Nas três páginas foram identificadas oportunidades de redução de aproximadamente 22 KiB de CSS não utilizado durante o carregamento analisado.

### 4.4. CSS não minimizado

O Lighthouse identificou uma oportunidade de poupança estimada de 2 KiB através da minimização dos ficheiros CSS.

### 4.5. Otimização das imagens

Foram identificadas oportunidades de otimização das imagens nas páginas:

- Início: poupança estimada de 34 KiB.
- Locais: poupança estimada de 62 KiB.

### 4.6. Outros aspetos de desempenho

A ferramenta também apresentou recomendações relacionadas com dependências de rede, latência e descoberta do recurso LCP.

## 5. Plano de correção

| Problema | Correção proposta | Prioridade |
|---|---|---|
| Favicon inexistente | Criar um favicon e associá-lo às páginas | Alta |
| Recursos que bloqueiam a apresentação | Rever a ordem e o carregamento dos estilos | Média |
| CSS não utilizado | Identificar estilos redundantes sem prejudicar os componentes Bootstrap | Média |
| Imagens pouco otimizadas | Comprimir imagens e rever formatos e dimensões | Média |
| CSS não minimizado | Considerar ficheiros CSS comprimidos na publicação | Baixa |
| Dependências de rede | Analisar e otimizar os recursos externos necessários | Média |

## 6. Verificações manuais

Como complemento às ferramentas automáticas, deverão ser confirmados:

- Navegação por teclado.
- Visibilidade do foco nos elementos interativos.
- Funcionamento dos campos obrigatórios do formulário.
- Funcionamento das curiosidades expansíveis.
- Adequação dos textos alternativos das imagens.
- Apresentação do site em diferentes larguras de ecrã.

## 7. Conclusão

A auditoria inicial revelou resultados positivos nas três páginas analisadas.

O Lighthouse apresentou pontuações elevadas nas quatro categorias avaliadas e o WAVE não identificou erros automáticos de acessibilidade.

Apesar destes resultados, foram identificadas oportunidades de melhoria, principalmente relacionadas com o carregamento dos recursos CSS, a otimização de imagens e a ausência de favicon.

Foi definido um plano de correção para orientar as melhorias nas próximas fases do projeto.

A auditoria constitui uma avaliação inicial e não representa uma garantia de conformidade integral com as normas WCAG.