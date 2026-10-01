# Processo de Software 🚀

Bem-vindo ao repositório acadêmico da disciplina de **Processo de Software**, ministrada na **Universidade de Rio Verde (UniRV)** no semestre letivo **2026/2**.

Este repositório serve como central de armazenamento, consulta e versionamento dos materiais didáticos, apresentações de aula em LaTeX (Beamer), listas de exercícios, gabaritos de exames e documentações institucionais pertinentes à disciplina.

---

## 📌 Visão Geral da Disciplina

A disciplina de **Processo de Software** aborda os conceitos, modelos, métodos e ferramentas essenciais para a estruturação, gestão e melhoria do ciclo de vida de desenvolvimento de software. Durante o curso, são explorados desde os fundamentos da Engenharia de Software clássica até as abordagens ágeis modernas e práticas avançadas de cultura DevOps e Google SRE.

### 🎯 Objetivos de Aprendizagem
- Compreender os fundamentos e terminologias clássicas da Engenharia de Software.
- Analisar aspectos legais, registros e propriedade intelectual de software no Brasil.
- Dominar a estrutura dos processos de software genéricos e adaptativos.
- Entender o Processo Unificado (RUP), suas fases e disciplinas integradas.
- Aplicar frameworks e metodologias ágeis (Scrum, XP, Kanban).
- Introduzir conceitos modernos de automação, CI/CD, DevOps e Engenharia de Confiabilidade de Sites (Google SRE).

---

## 📂 Estrutura do Repositório

```text
.
├── aulas/                  # Apresentações de slides e listas de exercícios por tópico
│   ├── 2.Introdução aos tópicos de base.../
│   ├── 3. Processos de Registro de Software e Propriedade Intelectual/
│   ├── 4. Processo Genérico/
│   ├── 5. Processo Unificado/
│   ├── 6. Agile/
│   ├── 7. XP e Kanbam/
│   └── 8. Devops e Google SRE/
├── inicio/                 # Documentos de planejamento acadêmico (Plano de Ensino e Cronograma)
├── provas/                 # Provas, listas de revisão e resoluções detalhadas em LaTeX
│   └── n1/                 # Material completo de avaliação referente à N1
├── notas/                  # [Ignorado no Git] Planilhas com notas e frequências dos alunos
├── .gitignore              # Configuração para ignorar arquivos temporários e dados sensíveis
└── README.md               # Documentação principal do repositório
```

---

## 📚 Módulos e Conteúdo Programático (`aulas/`)

O repositório está organizado em módulos sequenciais, acompanhados por fontes `.tex` (LaTeX Beamer) e imagens ilustrativas:

### 1. Introdução aos Tópicos de Base e Terminologias Essenciais
- Conceitos fundamentais de Engenharia de Software segundo Roger Pressman (*Engenharia de Software: Uma Abordagem Profissional*) e Ian Sommerville.
- A natureza do software, mitos do desenvolvimento e evolução dos sistemas.

### 2. Processos de Registro de Software e Propriedade Intelectual
- Legislação brasileira de software (Lei nº 9.609/1998 e Lei de Direitos Autorais nº 9.610/1998).
- Processo de registro no INPI (Instituto Nacional da Propriedade Industrial).
- Proteção de código-fonte, licenças de software (Open Source vs. Proprietário) e patentes.

### 3. Processo Genérico
- Atividades de Arcabouço (*Framework Activities*): Comunicação, Planejamento, Modelagem, Construção e Implantação.
- Ações e tarefas de apoio (Gestão de Riscos, Garantia da Qualidade, Gestão de Configuração).
- Modelos de fluxo de processo: linear, iterativo, evolutivo e paralelo.

### 4. Processo Unificado (RUP - Rational Unified Process)
- Filosofia do Processo Unificado: Guiado por Casos de Uso, Centrado na Arquitetura, Iterativo e Incremental.
- **Fases do RUP**: Concepção (*Inception*), Elaboração (*Elaboration*), Construção (*Construction*) e Transição (*Transition*).
- Disciplinas do RUP e marcos de cada fase (*Milestones*).

### 5. Metodologias Ágeis (Agile)
- O Manifesto Ágil (2001): 4 Valores e 12 Princípios do desenvolvimento ágil.
- Framework **Scrum**: Papéis (Product Owner, Scrum Master, Developers), Artefatos (Product Backlog, Sprint Backlog, Incremento) e Eventos (Sprint Planning, Daily, Review, Retrospective).

### 6. XP (Extreme Programming) e Kanban
- **Extreme Programming (XP)**: Valores (Comunicação, Simplicidade, Feedback, Coragem, Respeito) e Práticas de Engenharia (TDD, Programação em Par, Integração Contínua, Refatoração, Propriedade Coletiva).
- **Kanban**: Gestão visual do fluxo de trabalho, limitação de Trabalho em Progresso (*WIP - Work in Progress*), medição de Lead Time e Cycle Time.

### 7. DevOps e Google SRE (Site Reliability Engineering)
- Cultura **DevOps**: Integração entre Desenvolvimento e Operações, autogestão e automação (CI/CD).
- **Google SRE**: Engenharia aplicada a operações de infraestrutura e sistemas distribuídos em grande escala.
- Indicadores chaves: SLA, SLO, SLI e gestão do Orçamento de Erros (*Error Budget*).

---

## 📄 Documentação Acadêmica (`inicio/`)

Esta pasta armazena as diretrizes oficiais da disciplina:
- **`PLANO DE ENSINO - Modelo.docx`**: Ementa, competências, bibliografia básica e complementar, e critérios de avaliação.
- **`CRONOGRAMA DE AULAS - Modelo.docx`**: Calendário de aulas com datas pré-definidas de tópicos e provas.

---

## 📝 Avaliações e Exercícios (`provas/`)

Contém as provas aplicadas, simulados e listas preparatórias com resoluções detalhadas:
- **`provas/n1/`**:
  - `main.tex` / `main.pdf`: Avaliação N1 aplicativa.
  - `prova_resolvida_n1.tex` / `prova_resolvida_n1.pdf`: Gabarito comentado com explicações passo a passo.
  - `lista_exercicios.tex` / `lista_exercicios.pdf`: Lista de exercícios preparatórios para fixação de conteúdo.

---

## 🛡️ Segurança e Versionamento (`.gitignore`)

Por questões de privacidade de dados (LGPD) e boas práticas de controle de versão:
- A pasta **`notas/`** (onde ficam salvas as planilhas `*.xlsx` contendo registros de notas e frequências) está **estritamente ignorada** e **não é enviada para o repositório Git**.
- Arquivos de compilação do LaTeX (`*.aux`, `*.log`, `*.synctex.gz`, `*.fls`, `*.fdb_latexmk`, etc.) e temporários do sistema operacionais são descartados automaticamente.

---

## 🛠️ Como Compilar os Documentos em LaTeX

Caso deseje editar ou recompilar os slides Beamer ou provas em formato `.tex`:

### Pré-requisitos
- Distribuição LaTeX instalada: **TeX Live** (Linux) ou **MikTeX** (Windows).
- Editor LaTeX recomendado: **VS Code** (com a extensão *LaTeX Workshop*), **Texmaker** ou **Overleaf**.

### Comando para Compilação via Terminal
```bash
# Para compilar uma prova ou apresentação
pdflatex -synctex=1 -interaction=nonstopmode main.tex

# Ou utilizando latexmk (automação completa)
latexmk -pdf main.tex
```

---

## 👨‍🏫 Informações Gerais
- **Instituição:** Universidade de Rio Verde (UniRV)
- **Curso:** Engenharia de Software / Ciência da Computação
- **Disciplina:** Processo de Software
- **Semestre:** 2026/2

---
*README gerado e atualizado para estruturação e documentação do repositório.*
