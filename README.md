# 🏋️ Assistente de Personal Trainer com IA

Projeto desenvolvido durante uma aula da **DIO (Digital Innovation One)** sobre **Inteligência Artificial e Engenharia de Prompts**.

O objetivo do projeto é aplicar técnicas de **Prompt Engineering** para criar um assistente virtual capaz de gerar **planos de treinamento personalizados** a partir das características, objetivos, disponibilidade e preferências do usuário.

---

## 📌 Sobre o projeto

A proposta consiste em desenvolver um **prompt estruturado**, capaz de orientar um modelo de linguagem a atuar como um **Personal Trainer Sênior**, analisando as informações fornecidas pelo usuário antes de gerar um plano de treinamento.

O prompt foi desenvolvido utilizando boas práticas de Engenharia de Prompts, como:

* Clareza
* Especificidade
* Contextualização
* Estruturação da resposta
* Definição de regras
* Restrições
* Critérios de qualidade
* Personalização
* Iteração e melhoria

A ideia é demonstrar como um prompt bem estruturado pode transformar uma solicitação genérica em uma resposta mais organizada, contextualizada e personalizada.

---

## 🎯 Objetivo

Criar um assistente de IA capaz de gerar um plano de treinamento considerando informações como:

* Objetivo principal
* Objetivo secundário
* Idade
* Altura
* Peso
* Biotipo corporal
* Nível de experiência
* Tempo de treino
* Dias disponíveis por semana
* Tempo disponível por sessão
* Preferência de exercícios
* Local de treinamento
* Equipamentos disponíveis
* Exercícios preferidos
* Exercícios que o usuário não gosta
* Limitações físicas
* Restrições
* Outras observações relevantes

---

## 🧠 Conceitos de Engenharia de Prompts utilizados

### 1. Clareza

As instruções são apresentadas de maneira direta e organizada, reduzindo ambiguidades para o modelo de linguagem.

### 2. Especificidade

O prompt define exatamente quais informações devem ser consideradas e quais elementos devem aparecer no resultado final.

### 3. Contextualização

O modelo recebe informações sobre o perfil do usuário, seus objetivos, preferências e limitações antes de gerar o treinamento.

### 4. Estrutura de saída

A resposta possui uma estrutura previamente definida, facilitando a interpretação e utilização do treino.

### 5. Regras e restrições

São estabelecidas regras para evitar respostas genéricas ou incompatíveis com as informações fornecidas.

### 6. Critérios de qualidade

Antes de apresentar o resultado, o modelo deve verificar se o treino é compatível com disponibilidade, objetivo, experiência, equipamentos e recuperação.

---

## 🏋️ Tipos de treinamento considerados

O prompt considera diferentes possibilidades de treinamento:

* **Funcional**
* **Maquinário**
* **Peso Livre**
* **Cardio**
* **HIIT**

A escolha deve considerar o objetivo e as preferências informadas pelo usuário.

---

## 📅 Divisão semanal

Como referência, o projeto utiliza:

| Dias por semana | Sugestão  |
| --------------- | --------- |
| 1 dia           | Full Body |
| 3 dias          | ABC       |
| 5 dias          | ABCDE     |

A estrutura não é rígida. O assistente deve adaptar a divisão caso o usuário informe uma quantidade diferente de dias.

---

## 📊 Estrutura do treino gerado

O resultado proposto pelo prompt apresenta:

* Análise do perfil
* Estratégia de treinamento
* Divisão semanal
* Exercícios
* Grupos musculares
* Séries
* Repetições
* Tempo de descanso
* RPE/RIR
* Orientações técnicas
* Aquecimento
* Cardio
* Estratégia de progressão
* Recuperação
* Cuidados
* Resumo semanal

---

## 📈 Progressão

O assistente também deve apresentar uma estratégia de **sobrecarga progressiva**, explicando como o usuário pode evoluir gradualmente por meio de:

* Aumento de carga
* Aumento de repetições
* Ajuste de volume
* Aumento de intensidade
* Progressão da dificuldade

---

## ⚠️ Segurança

O projeto possui uma regra importante: o assistente não deve substituir profissionais de saúde.

Quando o usuário informar lesões, dores ou restrições, o modelo deve considerar essas informações e, quando necessário, recomendar avaliação de um profissional qualificado.

O objetivo do projeto é demonstrar o uso de IA e Engenharia de Prompts para **organização e personalização de informações**, e não realizar diagnóstico ou tratamento médico.

---

## 🔄 Fluxo do projeto

```text
Usuário
   ↓
Fornece informações pessoais e objetivos
   ↓
IA analisa o perfil
   ↓
Define estratégia de treinamento
   ↓
Define divisão semanal
   ↓
Seleciona exercícios
   ↓
Define séries, repetições e descanso
   ↓
Cria estratégia de progressão
   ↓
Realiza validação das regras
   ↓
Plano de treinamento personalizado
```

---

## 📂 Estrutura do projeto

```text
assistente-personal-trainer-ia/
│
├── README.md
│
└── prompt/
    └── personal-trainer-prompt.md
```

---

## 🚀 Como utilizar

1. Copie o prompt disponível neste repositório.
2. Abra uma ferramenta de IA generativa de sua preferência.
3. Cole o prompt.
4. Preencha os campos solicitados com as informações do usuário.
5. Envie o prompt.
6. Analise o plano de treinamento gerado pela IA.

---

## 💡 Exemplo de utilização

O usuário pode fornecer informações como:

```text
Objetivo principal: __________________
Biotipo: __________________
Dias disponíveis: __________________
Tempo por treino: __________________
Nível de experiência: __________________
Tipo de exercício preferido: __________________
Equipamentos disponíveis: __________________
```

A IA utilizará essas informações para construir uma sugestão de treinamento personalizada.

---

## 🎓 Sobre o aprendizado

Este projeto foi desenvolvido como parte dos estudos de **Inteligência Artificial e Engenharia de Prompts na DIO**.

Durante o desenvolvimento, foram aplicados conceitos como:

* Prompt Engineering
* Zero-Shot Prompting
* Few-Shot Prompting
* Clareza nas instruções
* Contextualização
* Especificidade
* Definição de formato de saída
* Definição de regras
* Personalização de respostas
* Validação e melhoria de prompts

---

## 🛠️ Tecnologias e ferramentas

O projeto utiliza principalmente:

* **Inteligência Artificial Generativa**
* **Large Language Models (LLMs)**
* **Prompt Engineering**
* **Markdown**
* **Git**
* **GitHub**

Não é necessário desenvolver uma aplicação ou backend para utilizar o projeto. O principal componente é o **prompt estruturado**.

---

## 📚 Aprendizados

Este projeto ajudou a compreender que a qualidade da resposta de um modelo de linguagem não depende apenas do modelo utilizado, mas também da qualidade das instruções fornecidas.

Um prompt bem estruturado pode:

> Transformar uma solicitação genérica em uma tarefa contextualizada, organizada e orientada a um resultado específico.

---

## ⚠️ Disclaimer

Este projeto possui finalidade **educacional** e demonstra conceitos de Inteligência Artificial e Engenharia de Prompts.

O plano gerado por uma IA não substitui a avaliação de um **profissional de Educação Física, médico ou outro profissional de saúde qualificado**.

Antes de iniciar qualquer programa de exercícios, especialmente em caso de dores, lesões, condições de saúde ou limitações físicas, procure orientação profissional.

---

## 👨‍💻 Autor

**Higor Lima**

Projeto desenvolvido durante os estudos de **Inteligência Artificial e Engenharia de Prompts na DIO**.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
