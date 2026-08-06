# IA Generativa para Data Science — Notas de Estudo

Repositório de estudos baseado no plano de 13 fases para LLMs e IA Generativa aplicada
a Data Science. O conteúdo é desenvolvido em **Jupyter notebooks** e consolidado em
**capítulos LaTeX** como referência técnica.

## Fases de estudo

| # | Fase | Conteúdo |
|---|------|----------|
| 1 | Fundamentos de Deep Learning | MLP, forward/backpropagation, otimização, regularização |
| 2 | NLP clássico e representação de texto | Tokenização, TF-IDF, embeddings, classificação |
| 3 | RNN, LSTM e GRU | Modelos sequenciais, vanishing gradient, limitações |
| 4 | Attention e Transformers | Self-attention, multi-head, positional encoding |
| 5 | Large Language Models | Hugging Face, fine-tuning, prompting |
| 6 | Embeddings, busca vetorial e RAG | Chunking, vector stores, retrieval, avaliação |
| 7 | LangChain, LangGraph e LlamaIndex | Chains, agentes, workflows documentais |
| 8 | Agentes de IA | Reasoning loop, tools, function calling |
| 9 | Model Context Protocol (MCP) | Servidores, clients, tools, resources |
| 10 | OpenAI API e Azure OpenAI | SDK, streaming, RAG corporativo |
| 11 | FastAPI | Endpoints, validação, segurança |
| 12 | Docker e deploy | Containers, Compose, orquestração |
| 13 | Observabilidade, avaliação e guardrails | Tracing, métricas, cache, fallback |

## Estrutura do repositório

```
.
├── contents/                # Jupyter notebooks por fase
│   ├── deep_learning/       # Fase 1
│   ├── nlp/                 # Fase 2
│   ├── rnn_lstm/            # Fase 3
│   ├── transformers/        # Fase 4
│   ├── llm/                 # Fase 5
│   ├── rag/                 # Fase 6
│   ├── langchain/           # Fase 7
│   ├── agents/              # Fase 8
│   ├── mcp/                 # Fase 9
│   ├── openai_api/          # Fase 10
│   ├── fastapi/             # Fase 11
│   ├── docker/              # Fase 12
│   └── observabilidade/     # Fase 13
├── scripts/                 # Scripts auxiliares e de plotagem
├── tex/                     # Consolidação em LaTeX
│   ├── main.tex
│   └── figures/
├── data/                    # Dados usados nos notebooks
│   ├── raw/
│   ├── interim/
│   ├── processed/
│   ├── reference/
│   └── manifests/
├── ai/                      # Políticas, skills e roles para agentes
├── docs/                    # Documentação complementar
├── refs/                    # Referências e papers
├── results/                 # Resultados de experimentos e treinamentos
└── figures/                 # Figuras gerais do projeto
```

## Como usar

1. Siga as fases em ordem — cada fase depende do conhecimento acumulado das anteriores.
2. Execute os notebooks em `contents/<fase>/`.
3. Ao final de cada fase, o conteúdo relevante é consolidado em `tex/main.tex`.
4. Scripts auxiliares e de plotagem ficam em `scripts/`.
5. Figuras geradas para o LaTeX são salvas em `tex/figures/`.

## Regras do projeto

- **Separação**: código de cálculo, dados e figuras são mantidos independentes.
- **Reprodutibilidade**: notebooks salvam resultados intermediários; scripts de figura leem apenas dados já salvos.
- **LaTeX**: capítulos integrados ao `main.tex`, sem fragmentação excessiva. Uma única pasta `figures/` dentro de `tex/`.
- **Idioma**: código e gráficos em inglês (padrão de publicação); notas e documentação em português.
- **Agentes**: decisões substantivas exigem consulta ao autor. Alterações permanentes são registradas em `TASK_LOG.md`.

## Trilha essencial (15 recursos)

1. Deep Learning Specialization — DeepLearning.AI
2. Natural Language Processing Specialization — DeepLearning.AI
3. Attention in Transformers: Concepts and Code in PyTorch
4. How Transformer LLMs Work
5. Hugging Face LLM Course — português
6. LangChain: Chat with Your Data
7. Building and Evaluating Advanced RAG Applications
8. LangChain Academy
9. Hugging Face AI Agents Course
10. Hugging Face MCP Course
11. OpenAI API — Developer Quickstart
12. FastAPI Tutorial
13. Docker Workshop
14. Safe and Reliable AI via Guardrails
15. LangSmith Evaluation

## Projetos de portfólio

| Projeto | Após a fase |
|---------|-------------|
| Classificador TF-IDF vs. embeddings | Fase 2 |
| Modelo de NLP com Transformer | Fase 5 |
| Chat com PDFs usando RAG | Fase 6 |
| Assistente de documentos corporativos | Fase 7 |
| Assistente SQL em linguagem natural | Fase 8 |
| Agente que consulta APIs externas | Fase 9 |
| Pipeline completo em produção | Fase 13 |

## Referência

Plano de Estudos de IA Generativa (2026) — 49 cursos, 7 projetos de portfólio,
15 recursos na trilha essencial.
