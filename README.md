# 🎯 Desafio Criativo DIO: Simplificando Tarefas e Ganhando Foco com IA

Repositório desenvolvido para o **Desafio Criativo** da [Digital Innovation One (DIO)](https://www.dio.me/). O objetivo desta atividade é aplicar técnicas de **Engenharia de Prompt** para transformar uma ideia genérica em um comando estruturado, claro e altamente eficaz para otimizar a produtividade e o foco nos estudos.

---

## 💡 O Problema (Antes da Engenharia de Prompt)

Em um processo de transição de carreira, conciliar a rotina de trabalho em tempo integral, compromissos familiares e os estudos em tecnologia exige alta eficiência. Pedidos vagos feitos à Inteligência Artificial geram respostas genéricas que não se adaptam à nossa realidade de tempo.

* ❌ **Prompt Vago:** *"Me ajude a organizar meus estudos de dados e programação para mudar de área."*
* **Resultado esperado:** Um plano genérico, longo demais para a rotina diária e desconectado da experiência prévia do estudante.

---

## 🧩 Construção Passo a Passo do Prompt

Para resolver esse problema, apliquei o framework **P-C-T-F** (Persona, Contexto, Tarefa e Formato):

### 1. Persona (Quem a IA deve ser?)
> *"Atue como um mentor de carreira em tecnologia e especialista em Análise de Dados, com foco em aprendizagem acelerada e gestão de tempo para profissionais em transição de carreira."*

### 2. Contexto (Qual é o cenário real?)
> *"Sou graduado em Análise e Desenvolvimento de Sistemas e atuo há mais de 10 anos na área administrativa e financeira. Estou em transição de carreira para a área de Dados e Desenvolvimento. Tenho disponibilidade estrita de **1 hora por dia** (de segunda a sexta) para estudar e preciso aproveitar minha bagagem analítica (Excel, Power BI e regras de negócio) para acelerar meu aprendizado em Python (Pandas) e automação, sem gerar fadiga mental após o expediente."*

### 3. Tarefa (O que deve ser feito?)
> *"Crie um plano de estudos semanal enxuto, prático e focado em resultados, dividindo minha 1 hora diária em blocos de foco (como a técnica Pomodoro) para evitar distrações e garantir evolução constante."*

### 4. Formato de Saída (Como entregar?)
> *"Entregue a resposta estruturada em uma tabela Markdown contendo: Dia da Semana, Tema Técnico, Divisão do Tempo (Teoria vs. Prática) e uma Micro-entrega diária. Ao final, adicione 3 regras práticas de bloqueio de distrações para aplicar antes de iniciar a sessão de estudos."*

---

## 🏆 Prompt Final Consolidado

Este é o comando final pronto para ser utilizado em qualquer LLM (ChatGPT, Gemini, Copilot):

```text
Atue como um mentor de carreira em tecnologia e especialista em Análise de Dados, com foco em aprendizagem acelerada e gestão de tempo para profissionais em transição de carreira.

Contexto: Sou formado em Análise e Desenvolvimento de Sistemas e possuo sólida experiência administrativa e financeira. Estou em transição de carreira para a área de Dados e Tecnologia. Tenho disponibilidade estrita de 1 hora líquida por dia (de segunda a sexta) para estudar e quero alavancar minha base em Excel e Power BI para dominar Python (Pandas), SQL e automação de processos, mantendo o foco total e evitando sobrecarga mental após o trabalho.

Tarefa: Crie um cronograma semanal de estudos altamente prático, dividindo minha 1 hora diária em blocos otimizados de atenção para maximizar a retenção e gerar entregas reais.

Formato: Apresente o plano em uma tabela com as colunas: Dia da Semana | Stack / Foco | Divisão de Tempo (Pomodoro) | Micro-entrega Prática. Abaixo da tabela, liste 3 ações rápidas de "ritual de início" para eliminar distrações e entrar em estado de foco imediato.

## 🚀 Resultado Gerado pela IA (Validação)

Ao executar o prompt acima, a IA gerou exatamente o planejamento estruturado abaixo:

| Dia da Semana | Stack / Foco | Divisão de Tempo (Pomodoro) | Micro-entrega Prática |
| :--- | :--- | :--- | :--- |
| **Segunda-feira** | **Python & Pandas** (Manipulação de Dados) | 15m revisão de sintaxe + 40m código + 5m anotações | Limpar e filtrar uma planilha de vendas/estoque via script Python. |
| **Terça-feira** | **SQL** (Consultas e Modelagem) | 20m conceitos + 35m prática + 5m revisão | Escrever 3 queries com `JOIN` e `GROUP BY` simulando indicadores financeiros. |
| **Quarta-feira** | **Power BI & DAX** (Visualização) | 15m estudo de métricas + 40m dashboard + 5m doc | Criar uma medida DAX calculando margem ou variação mensal (MoM). |
| **Quinta-feira** | **Automação / Scripting** | 10m planejamento + 45m desenvolvimento + 5m commit | Criar um pequeno script para automatizar uma tarefa repetitiva de rotina. |
| **Sexta-feira** | **Portfólio & GitHub** | 40m revisão de código + 20m documentação (`README`) | Subir o código/projeto da semana no GitHub documentando o problema resolvido. |

### 🛡️ Ritual de Início (Bloqueio de Distrações)
1. **Ambiente Fechado:** Fechar abas de e-mail, mensageiros e deixar o celular em modo "Não Perturbe" fora do alcance visual.
2. **Objetivo Único:** Abrir o VS Code ou editor de código já sabendo exatamente qual é a *Micro-entrega Prática* do dia (sem gastar tempo decidindo o que estudar).
3. **Timer Visível:** Iniciar um cronômetro de 50 minutos contínuos (ou dois ciclos de 25/5) para criar senso de urgência positiva.
