# Desafio_DIO
Depositório Dio - Vendas com IA
# Caderno Temático NotebookLM — Claude Design

## 1. Contexto e Objetivos

Este repositório foi criado como entrega do desafio prático da DIO sobre uso de Inteligência Artificial como ferramenta de aprendizagem ativa, com foco na criação de um **Caderno Temático no NotebookLM**.

O tema escolhido foi **Claude Design**, recurso da Anthropic Labs voltado à criação de designs, protótipos, apresentações, one-pagers, materiais visuais e fluxos interativos por meio de conversa com Claude.

A escolha do tema se justifica porque Claude Design representa uma mudança relevante no fluxo de trabalho entre ideia, design, prototipagem, apresentação e possível entrega para desenvolvimento. Em vez de depender apenas de ferramentas visuais tradicionais, o usuário pode descrever objetivos, público, layout, conteúdo e referências, recebendo uma primeira versão visual no canvas e refinando o resultado por chat, comentários inline e ajustes progressivos.

### Objetivos de estudo

Os objetivos deste caderno temático são:

1. Compreender o que é Claude Design e em quais situações ele pode ser usado.
2. Identificar o fluxo básico de trabalho: criação de projeto, inserção de contexto, geração, iteração, exportação e compartilhamento.
3. Entender o papel do design system dentro do Claude Design.
4. Documentar prompts estratégicos para estudar o tema no NotebookLM.
5. Registrar dificuldades encontradas na extração de respostas da IA e formas de melhorar os prompts.
6. Criar um miniguia final com resumos, glossário e prompts reutilizáveis.

---

## 2. Curadoria de Fontes

Foram selecionadas fontes abertas, priorizando documentação oficial da Anthropic/Claude e materiais complementares sobre uso, design system, aprendizagem e Skills.

### Fontes principais usadas no NotebookLM

| Nº | Fonte                                                           | Tipo                    | Link                                                                                       | Justificativa de uso                                                                                                      |
| -- | --------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| 1  | Get started with Claude Design — Claude Help Center             | Documentação oficial    | https://support.claude.com/en/articles/14604416-get-started-with-claude-design             | Explica o funcionamento básico do Claude Design, fluxo de projeto, prompts, iteração, exportação e limitações conhecidas. |
| 2  | Set up your design system in Claude Design — Claude Help Center | Documentação oficial    | https://support.claude.com/en/articles/14604397-set-up-your-design-system-in-claude-design | Explica como configurar design system, ativos de marca, componentes, cores, tipografia e padrões reutilizáveis.           |
| 3  | Introducing Claude Design by Anthropic Labs — Anthropic         | Anúncio oficial         | https://www.anthropic.com/news/claude-design-anthropic-labs                                | Apresenta o produto, casos de uso, colaboração, exportação e handoff para Claude Code.                                    |
| 4  | The Complete Guide to Building Skills for Claude — Anthropic    | PDF técnico             | https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf  | Complementa o estudo ao explicar como Skills estruturam instruções reutilizáveis para fluxos repetíveis no Claude.        |
| 5  | Create custom course materials — Claude Resources               | Caso de uso educacional | https://claude.com/resources/use-cases/create-custom-course-materials                      | Relaciona IA, criação de materiais educacionais e aprendizagem ativa, conectando o tema ao objetivo do desafio.           |

### Fontes complementares

| Fonte                                      | Link                                                                          | Observação                                                                         |
| ------------------------------------------ | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Claude Tutorials                           | https://claude.com/resources/tutorials                                        | Portal de tutoriais oficiais para ampliar o estudo.                                |
| Claude Design Guide — Sartech Labs         | https://www.sartechlabs.com/blog/claude-design-guide                          | Material complementar com exemplos práticos de prompts e fluxo de uso.             |
| Claude Design — A MasterClass              | https://maven.com/p/a8ae73/claude-design-a-master-class                       | Fonte complementar de mercado. Pode exigir acesso específico.                      |
| Claude Beginner Guide — Belmont University | https://www.belmont.edu/data/_files/claude-a-step-by-step-beginners-guide.pdf | Guia introdutório sobre Claude, útil para contextualização de usuários iniciantes. |

### Fontes audiovisuais a validar

Os vídeos abaixo foram listados como fontes complementares. Para uso rigoroso no NotebookLM, recomenda-se obter transcrição, legenda ou resumo verificável antes de citá-los como base factual.

* https://www.youtube.com/watch?v=t_LBECIQQqs
* https://www.youtube.com/watch?v=cl5Oudk3Hjo
* https://www.youtube.com/watch?v=kAs6gvOCsi0
* https://www.youtube.com/watch?v=Z90zSsooYEw
* https://www.youtube.com/watch?v=e7ngdzwzRZ0
* https://www.youtube.com/watch?v=OGdD4YtRPJs

---

## 3. Perguntas Norteadoras do Caderno Temático

As perguntas abaixo orientaram a investigação no NotebookLM:

1. O que é Claude Design e qual problema ele resolve?
2. Como funciona o fluxo de criação dentro do Claude Design?
3. Qual é a importância do design system para gerar resultados consistentes?
4. Quais tipos de materiais podem ser criados com Claude Design?
5. Como escrever bons prompts para Claude Design?
6. Quando usar chat e quando usar comentários inline?
7. Quais são as opções de exportação e compartilhamento?
8. Quais são as limitações conhecidas da ferramenta?
9. Como Claude Design se conecta a Claude Code, Skills e fluxos de trabalho profissionais?
10. Como transformar o estudo sobre Claude Design em um material de revisão reutilizável?

---

## 4. Engenharia de Prompts e “Cicatrizes”

Esta seção registra prompts estratégicos, variações testáveis e dificuldades esperadas ao usar IA para estudar Claude Design.

> Observação: os campos de “resultado esperado” devem ser conferidos e ajustados após a execução real dos prompts no NotebookLM, usando as respostas efetivamente obtidas no seu caderno.

### 4.1 Prompt inicial — amplo demais

**Prompt usado:**

```text
Explique o que é Claude Design.
```

**Problema identificado:**

O prompt é genérico. Ele tende a gerar uma resposta superficial, com pouca separação entre definição, fluxo de uso, casos práticos, limitações e fontes.

**Melhoria aplicada:**

Especificar formato, profundidade, fontes e comparação entre conceitos.

---

### 4.2 Prompt melhorado — resumo estruturado

**Prompt usado:**

```text
Com base exclusivamente nas fontes carregadas, explique o que é Claude Design em português, organizando a resposta em:
1. definição;
2. problema que resolve;
3. principais recursos;
4. fluxo de uso;
5. casos de uso;
6. limitações;
7. relação com Claude Code e design systems.
Inclua referência à fonte usada em cada seção.
```

**Resultado esperado:**

Uma resposta mais organizada, com melhor rastreabilidade das fontes e separação entre definição, uso prático e limitações.

**Cicatriz registrada:**

Quando a IA não é instruída a usar somente as fontes carregadas, ela pode misturar conhecimento externo ou inferências. A correção foi exigir explicitamente: “com base exclusivamente nas fontes carregadas”.

---

### 4.3 Prompt para comparação de fontes

**Prompt usado:**

```text
Compare as fontes carregadas sobre Claude Design. Indique:
1. quais fontes são oficiais;
2. quais são complementares;
3. quais informações aparecem em mais de uma fonte;
4. quais informações aparecem em apenas uma fonte;
5. quais pontos ainda precisam de validação.
Organize em tabela.
```

**Resultado esperado:**

Uma visão crítica da curadoria, separando fontes oficiais de fontes secundárias.

**Cicatriz registrada:**

Algumas fontes podem ter tom promocional ou de opinião. A solução foi pedir classificação por autoridade da fonte: oficial, educacional, mercado, comunidade ou vídeo.

---

### 4.4 Prompt para extrair fluxo de trabalho

**Prompt usado:**

```text
Extraia das fontes um passo a passo prático para usar Claude Design desde a criação do projeto até a exportação final. Para cada etapa, indique:
- objetivo da etapa;
- ação recomendada;
- tipo de prompt que funciona melhor;
- erro comum;
- como corrigir o erro.
```

**Resultado esperado:**

Um checklist prático de uso do Claude Design.

**Cicatriz registrada:**

A IA pode listar etapas sem explicar o motivo de cada uma. A correção foi exigir “objetivo da etapa” e “erro comum”.

---

### 4.5 Prompt para glossário

**Prompt usado:**

```text
Crie um glossário em português com os principais termos das fontes sobre Claude Design. Para cada termo, apresente:
- definição simples;
- importância prática;
- exemplo de uso;
- fonte de referência.
```

**Resultado esperado:**

Glossário didático para revisão rápida.

**Cicatriz registrada:**

A primeira resposta pode trazer termos demais ou termos genéricos. A melhoria é limitar a 15 ou 20 termos centrais.

---

### 4.6 Prompt para limitações e troubleshooting

**Prompt usado:**

```text
Com base nas fontes carregadas, liste as limitações conhecidas do Claude Design e proponha soluções práticas ou alternativas de contorno. Separe em:
1. problemas de comentários inline;
2. problemas de salvamento;
3. grandes codebases;
4. erros de chat;
5. excesso de generalidade visual;
6. boas práticas para reduzir retrabalho.
```

**Resultado esperado:**

Uma seção de troubleshooting útil e realista.

**Cicatriz registrada:**

A IA pode transformar limitações em críticas exageradas. A correção foi pedir apenas limitações documentadas nas fontes e separar fatos de recomendações.

---

### 4.7 Prompt para gerar material de estudo

**Prompt usado:**

```text
Transforme as fontes carregadas em um miniguia de estudo para iniciantes sobre Claude Design. O material deve conter:
1. resumo executivo;
2. mapa mental textual;
3. passo a passo de uso;
4. glossário;
5. checklist de boas práticas;
6. prompts reutilizáveis;
7. perguntas de revisão.
Use linguagem simples, mas tecnicamente correta.
```

**Resultado esperado:**

Um miniguia completo para revisão e portfólio.

**Cicatriz registrada:**

Quando o prompt pede muitos entregáveis ao mesmo tempo, a resposta pode ficar longa e menos precisa. A solução é pedir primeiro a estrutura e depois gerar cada parte separadamente.

---

## 5. Miniguia de Estudo — Claude Design

### 5.1 Resumo executivo

Claude Design é uma ferramenta da Anthropic Labs que permite criar trabalhos visuais por meio de conversa com Claude. O usuário descreve o que deseja construir, adiciona contexto relevante, revisa o resultado em um canvas visual e refina a entrega por chat, comentários inline ou ajustes diretos.

A ferramenta pode ser usada para gerar protótipos, wireframes, mockups, apresentações, landing pages, materiais de marketing, one-pagers e fluxos visuais. Seu valor está na redução da distância entre ideia, visualização, iteração e entrega.

Um ponto central é o uso de design systems. Quando um design system é configurado, Claude Design pode aplicar cores, tipografia, componentes e padrões visuais da organização de forma consistente nos projetos.

Claude Design não deve ser tratado como uma ferramenta mágica que acerta tudo no primeiro prompt. O melhor uso acontece por iteração: começar simples, fornecer contexto, pedir variações, revisar criticamente, corrigir pontos específicos e exportar no formato adequado.

---

### 5.2 Fluxo prático de uso

#### Etapa 1 — Definir o objetivo

Antes de abrir a ferramenta, defina claramente:

* O que será criado?
* Para quem será criado?
* Qual problema o material deve resolver?
* O resultado será uma apresentação, protótipo, landing page, dashboard ou material educacional?

Exemplo:

```text
Quero criar uma landing page para um curso introdutório sobre IA aplicada a negócios, voltada para empreendedores iniciantes, com foco em clareza, credibilidade e conversão.
```

---

#### Etapa 2 — Adicionar contexto

Claude Design funciona melhor quando recebe contexto. Esse contexto pode incluir:

* prints de telas existentes;
* documentos de marca;
* apresentações;
* referências visuais;
* arquivos DOCX, PPTX, XLSX ou PDF;
* código ou componentes existentes;
* exemplos de concorrentes ou inspirações.

Quanto mais específico for o contexto, menor tende a ser o retrabalho.

---

#### Etapa 3 — Criar ou aplicar design system

O design system serve para padronizar identidade visual e componentes. Ele pode conter:

* paleta de cores;
* tipografia;
* tamanhos e espaçamentos;
* botões;
* cards;
* inputs;
* navegação;
* padrões de layout;
* diretrizes de uso da marca.

Prompt sugerido:

```text
Crie um design system para a marca abaixo. Inclua paleta de cores, tipografia, grid, espaçamentos, componentes principais, botões, cards, inputs, badges, estados visuais e regras de uso.

Marca: [nome]
Setor: [setor]
Público-alvo: [público]
Personalidade da marca: [ex.: sofisticada, acessível, moderna, institucional]
Cores existentes: [se houver]
Restrições: [se houver]
```

---

#### Etapa 4 — Gerar a primeira versão

A primeira versão deve priorizar estrutura, hierarquia e conteúdo principal. Evite pedir todos os detalhes de uma vez.

Prompt sugerido:

```text
Crie a primeira versão de uma página [tipo da página] para [objetivo]. 
Público-alvo: [público].
Priorize:
1. clareza da proposta de valor;
2. hierarquia visual;
3. chamada para ação;
4. organização em seções;
5. versão desktop e mobile.
Use meu design system.
```

---

#### Etapa 5 — Iterar com chat

Use o chat para mudanças amplas:

* alterar estrutura da página;
* pedir versões alternativas;
* mudar estilo visual;
* reorganizar seções;
* adicionar novos blocos;
* revisar acessibilidade;
* avaliar hierarquia visual.

Exemplo:

```text
Mostre três alternativas para a seção hero:
1. uma mais institucional;
2. uma mais comercial;
3. uma mais ousada e visual.
Explique a diferença estratégica entre elas.
```

---

#### Etapa 6 — Iterar com comentários inline

Use comentários inline para ajustes pontuais:

* aumentar espaçamento;
* mudar botão;
* ajustar card específico;
* trocar dropdown por radio button;
* corrigir contraste;
* alterar componente local.

Exemplo:

```text
Aumente o espaçamento interno deste card para melhorar a leitura.
```

---

#### Etapa 7 — Revisar criticamente

Antes de exportar, solicite uma auditoria:

```text
Revise este design como um designer sênior. Avalie:
1. clareza da mensagem;
2. hierarquia visual;
3. contraste;
4. acessibilidade;
5. consistência com o design system;
6. responsividade;
7. possíveis pontos de confusão para o usuário.
Sugira melhorias objetivas.
```

---

#### Etapa 8 — Exportar ou compartilhar

Após a revisão, o projeto pode ser exportado ou compartilhado. Os formatos podem incluir:

* PDF;
* PPTX;
* HTML standalone;
* Canva;
* arquivo ZIP;
* handoff para Claude Code;
* link compartilhável dentro da organização.

A escolha depende do objetivo:

| Objetivo                     | Melhor saída                |
| ---------------------------- | --------------------------- |
| Apresentar para stakeholders | PDF ou PPTX                 |
| Editar visualmente em equipe | Canva                       |
| Testar protótipo             | HTML ou link compartilhável |
| Desenvolver produto          | Handoff para Claude Code    |
| Arquivar entrega             | PDF ou ZIP                  |

---

## 6. Glossário

| Termo              | Definição simples                                                                   | Importância prática                                                |
| ------------------ | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| Claude Design      | Ferramenta da Anthropic Labs para criar trabalhos visuais conversando com Claude.   | Permite transformar ideias em designs, protótipos e apresentações. |
| Canvas             | Área visual onde o design gerado aparece e pode ser revisado.                       | Permite visualizar e iterar sobre o resultado.                     |
| Chat               | Interface de conversa usada para pedir criações e mudanças.                         | Serve para direcionar a IA em mudanças amplas.                     |
| Comentário inline  | Comentário feito diretamente sobre uma parte específica do design.                  | Ajuda a corrigir elementos pontuais com mais precisão.             |
| Design system      | Conjunto de regras visuais, componentes, cores e tipografia.                        | Garante consistência visual entre projetos.                        |
| UI kit             | Conjunto de componentes visuais reutilizáveis.                                      | Facilita a criação de interfaces padronizadas.                     |
| Protótipo          | Versão visual ou interativa de uma ideia.                                           | Ajuda a testar conceitos antes do desenvolvimento.                 |
| Wireframe          | Estrutura inicial de uma tela ou página.                                            | Ajuda a organizar conteúdo e fluxo antes do refinamento visual.    |
| Mockup             | Representação visual mais acabada de uma interface.                                 | Ajuda a apresentar aparência e hierarquia visual.                  |
| Handoff            | Processo de entrega do design para implementação.                                   | Conecta design e desenvolvimento.                                  |
| Claude Code        | Ferramenta da Anthropic voltada a desenvolvimento com Claude.                       | Pode receber handoff de projetos vindos do Claude Design.          |
| Exportação         | Ação de salvar ou enviar o projeto em outro formato.                                | Permite transformar o design em PDF, PPTX, HTML, Canva ou ZIP.     |
| Responsividade     | Capacidade do design funcionar em diferentes tamanhos de tela.                      | Essencial para desktop, tablet e mobile.                           |
| Acessibilidade     | Qualidade de um design ser utilizável por pessoas com diferentes necessidades.      | Envolve contraste, leitura, navegação e clareza.                   |
| Prompt             | Instrução dada à IA.                                                                | Define a qualidade, direção e precisão da resposta.                |
| Iteração           | Processo de melhorar uma versão por ciclos de feedback.                             | É o principal método para obter resultados melhores com IA.        |
| Skills             | Pastas de instruções que ensinam Claude a executar fluxos específicos.              | Podem padronizar processos repetíveis.                             |
| MCP                | Model Context Protocol, usado para conectar modelos a ferramentas e dados externos. | Pode ampliar fluxos de trabalho com integrações.                   |
| Fonte oficial      | Documento publicado pela própria empresa ou instituição responsável.                | Tem maior autoridade para validar informações sobre o produto.     |
| Fonte complementar | Conteúdo externo usado para exemplos ou perspectivas adicionais.                    | Ajuda a enriquecer o estudo, mas deve ser validado.                |

---

## 7. Checklist de Boas Práticas para Claude Design

Antes de começar:

* [ ] Definir objetivo do projeto.
* [ ] Definir público-alvo.
* [ ] Definir formato final esperado.
* [ ] Separar referências visuais.
* [ ] Separar materiais de marca.
* [ ] Definir se será usado design system.
* [ ] Informar restrições de layout, tom e conteúdo.

Durante a criação:

* [ ] Começar com uma estrutura simples.
* [ ] Pedir primeira versão antes de detalhar demais.
* [ ] Solicitar variações quando houver dúvida.
* [ ] Usar chat para mudanças amplas.
* [ ] Usar comentários inline para ajustes específicos.
* [ ] Pedir revisão de acessibilidade.
* [ ] Pedir revisão de hierarquia visual.
* [ ] Validar responsividade.

Antes da entrega:

* [ ] Conferir textos.
* [ ] Conferir contraste.
* [ ] Conferir consistência visual.
* [ ] Conferir se o design atende ao objetivo.
* [ ] Exportar no formato correto.
* [ ] Registrar aprendizados e ajustes feitos.

---

## 8. Prompts Reutilizáveis

### 8.1 Prompt para estudar uma fonte no NotebookLM

```text
Com base exclusivamente nesta fonte, faça um resumo estruturado em português com:
1. ideia central;
2. conceitos principais;
3. recursos mencionados;
4. limitações;
5. exemplos práticos;
6. perguntas que ainda ficam em aberto.
Não use conhecimento externo.
```

---

### 8.2 Prompt para comparar fontes

```text
Compare as fontes carregadas sobre Claude Design e organize a resposta em tabela com:
1. fonte;
2. tipo de fonte;
3. principais contribuições;
4. pontos confirmados por outras fontes;
5. pontos não confirmados;
6. nível de confiabilidade.
```

---

### 8.3 Prompt para criar guia de estudo

```text
Transforme as fontes carregadas em um guia de estudo para iniciantes sobre Claude Design. O guia deve conter:
1. resumo executivo;
2. explicação passo a passo;
3. glossário;
4. erros comuns;
5. boas práticas;
6. perguntas de revisão;
7. prompts reutilizáveis.
Use linguagem clara e objetiva.
```

---

### 8.4 Prompt para gerar perguntas de revisão

```text
Crie 20 perguntas de revisão sobre Claude Design com base nas fontes carregadas. Divida em:
1. perguntas fáceis;
2. perguntas intermediárias;
3. perguntas avançadas;
4. perguntas práticas.
Inclua gabarito comentado.
```

---

### 8.5 Prompt para transformar estudo em portfólio

```text
Com base no conteúdo estudado, transforme este caderno em uma documentação de portfólio para GitHub. A estrutura deve conter:
1. contexto;
2. objetivo;
3. fontes usadas;
4. metodologia;
5. prompts testados;
6. principais aprendizados;
7. miniguia final;
8. próximos passos.
```

---

### 8.6 Prompt para revisar criticamente uma resposta

```text
Revise a resposta anterior e verifique:
1. quais afirmações estão apoiadas nas fontes;
2. quais afirmações parecem inferência;
3. quais pontos precisam de citação;
4. quais trechos estão vagos;
5. como melhorar a precisão.
Reescreva a resposta final com mais rigor.
```

---

### 8.7 Prompt para Claude Design — landing page

```text
Crie uma landing page para [produto/serviço].
Objetivo principal: [gerar leads / vender / apresentar / educar].
Público-alvo: [descrição].
Tom visual: [moderno / premium / educacional / institucional].
Estrutura desejada:
1. hero section com proposta de valor clara;
2. benefícios principais;
3. como funciona;
4. prova social;
5. chamada para ação;
6. FAQ;
7. rodapé.
Crie versões desktop e mobile.
Use hierarquia visual forte, bom contraste e CTAs claros.
```

---

### 8.8 Prompt para Claude Design — apresentação

```text
Crie uma apresentação visual sobre [tema] para [público].
Duração estimada: [x minutos].
Objetivo: [ensinar / convencer / vender / apresentar estratégia].
Estrutura:
1. capa;
2. contexto;
3. problema;
4. solução;
5. exemplos;
6. passo a passo;
7. conclusão;
8. próximos passos.
Use visual limpo, títulos fortes, pouco texto por slide e elementos gráficos coerentes.
Exporte em formato adequado para apresentação.
```

---

### 8.9 Prompt para Claude Design — auditoria

```text
Revise este design como um designer sênior e avalie:
1. clareza da mensagem;
2. hierarquia visual;
3. contraste;
4. acessibilidade;
5. consistência com a marca;
6. responsividade;
7. qualidade dos CTAs;
8. pontos de fricção para o usuário.
Dê recomendações práticas e priorizadas.
```

---

## 9. Principais Aprendizados

1. Claude Design funciona melhor quando recebe contexto claro.
2. O design system é essencial para manter consistência visual.
3. A primeira geração deve ser tratada como ponto de partida, não como entrega final.
4. O processo ideal é iterativo: gerar, revisar, comentar, ajustar e exportar.
5. Chat é mais adequado para mudanças amplas.
6. Comentários inline são mais adequados para ajustes pontuais.
7. A exportação deve ser escolhida conforme o uso final.
8. Fontes oficiais devem ter prioridade sobre fontes promocionais ou opinativas.
9. Vídeos devem ser usados com transcrição ou validação antes de serem citados.
10. Bons prompts reduzem retrabalho e tornam o estudo mais confiável.

---

## 10. Troubleshooting

| Problema                                           | Causa provável                     | Solução                                                   |
| -------------------------------------------------- | ---------------------------------- | --------------------------------------------------------- |
| Resposta genérica do NotebookLM                    | Prompt amplo demais                | Pedir estrutura, fonte e nível de detalhe.                |
| Resposta sem referências                           | Falta de instrução explícita       | Solicitar referência por seção.                           |
| Confusão entre Claude, Claude Design e Claude Code | Conceitos próximos                 | Pedir tabela comparativa.                                 |
| Material com tom promocional                       | Fonte secundária ou marketing      | Priorizar fontes oficiais.                                |
| Design genérico                                    | Falta de design system ou contexto | Adicionar marca, público, referências e restrições.       |
| Ajustes pequenos gerando retrabalho                | Uso de chat para tudo              | Usar comentários inline para elementos específicos.       |
| Resultado visual inconsistente                     | Prompt com pouca direção           | Especificar layout, objetivo, estilo, público e formato.  |
| Dificuldade com vídeos                             | Ausência de transcrição            | Usar apenas como fonte complementar até validar conteúdo. |

---

## 11. Estrutura Recomendada do Repositório

```text
caderno-tematico-claude-design/
│
├── README.md
├── fontes/
│   └── lista-de-fontes.md
├── prompts/
│   └── prompts-testados.md
├── miniguia/
│   └── miniguia-claude-design.md
└── imagens/
    └── capturas-notebooklm/
```

Caso o projeto seja entregue apenas pelo `README.md`, todo o conteúdo pode ficar centralizado neste arquivo.

---

## 12. Descrição para Entrega na DIO

Este projeto apresenta um Caderno Temático criado para estudar **Claude Design**, ferramenta da Anthropic Labs voltada à criação de designs, protótipos, apresentações e materiais visuais por meio de IA conversacional.

O repositório documenta a curadoria de fontes, os objetivos de estudo, os prompts usados no NotebookLM, as dificuldades encontradas no processo de extração de respostas e um miniguia final com resumo estruturado, glossário e prompts reutilizáveis.

O objetivo foi demonstrar aprendizagem ativa com IA, pensamento crítico, curadoria de fontes e organização do conhecimento em formato de portfólio técnico.

---

## 13. Próximos Passos

* Executar os prompts no NotebookLM com as fontes carregadas.
* Substituir os campos de “resultado esperado” pelas respostas reais obtidas.
* Adicionar prints do NotebookLM na pasta `imagens/`.
* Criar um arquivo separado com prompts testados.
* Criar uma versão em PDF do miniguia.
* Adicionar exemplos práticos de projetos criados no Claude Design.
* Atualizar o repositório conforme novas versões da ferramenta forem lançadas.

---

## 14. Conclusão

O estudo de Claude Design mostra como ferramentas de IA podem apoiar processos criativos, educacionais e profissionais. O principal aprendizado é que a qualidade do resultado não depende apenas da ferramenta, mas da combinação entre boas fontes, prompts bem estruturados, contexto adequado, revisão crítica e iteração.

Este repositório registra não apenas o resultado final, mas também o raciocínio usado para chegar até ele, incluindo perguntas, ajustes, limitações e aprendizados.
