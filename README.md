<img width="1920" height="720" alt="Banner do Projeto" src="" />

# 🧠 Ra Vision – Gerenciamento Inteligente de Regras de Negócio

## 🔍 Visão Geral
Desenvolvido por nós, alunos do 6º semestre de ADS da Fatec São José dos Campos – Jessen Vidal, o **Ra Vision** é uma aplicação web para gerenciamento inteligente de regras de negócio com suporte de **IA Generativa**.

O sistema permite cadastrar, versionar, simular e explicar regras empresariais, promovendo maior rastreabilidade, transparência e redução de inconsistências operacionais.

Parceiro Acadêmico: **Dom Rock**

---

## 🎯 Desafio do Semestre
Empresas trabalham com regras de negócio dinâmicas que sofrem alterações constantes devido a campanhas, mudanças estratégicas e acordos comerciais.  

Muitas dessas regras:
- Não estão formalmente documentadas  
- Geram conflitos operacionais  
- Não possuem rastreabilidade  
- São de conhecimento tácito  

Nosso objetivo é desenvolver uma aplicação que organize essas regras e utilize **IA Generativa** para explicar decisões e apoiar a tomada de decisão empresarial.

---

## 🚀 Solução Proposta
A aplicação oferecerá:

- Cadastro e versionamento de regras de negócio  
- Simulação de aplicação de regras  
- Explicação automática de decisões via LLM  
- Identificação de possíveis conflitos  
- Histórico e rastreabilidade das decisões  
- Geração de relatórios explicativos  

---

## 🧩 MVP (Produto Mínimo Viável)

O MVP contempla:

- Cadastro de regras
- Listagem de regras
- Simulação de aplicação
- Explicação automática da decisão
- Histórico de execução

---

## 👥 Personas do Sistema

- **Administrador de Regras** – Responsável por cadastrar e manter regras.
- **Analista de Operações** – Aplica regras e precisa entender decisões.
- **Gestor Comercial** – Avalia impacto financeiro das regras.
- **Auditor Interno** – Necessita rastreabilidade e justificativas formais.

---

#### 📃 Backlog do Produto
| Rank | Prioridade | User Story | Estimativa | Sprint | Status |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1 | Alta | Como Administrador de Regras, quero utilizar linguagem natural para criar novas diretrizes, para tornar a atualização de comissões mais rápida e intuitiva. | 13 | 1 | ⏳ |
| 2 | Alta | Como Administrador de Regras, quero enviar arquivos de regulamentos antigos para o sistema, para que a ferramenta aprenda as normas automaticamente sem eu precisar digitar tudo do zero. | 8 | 1 | ⏳ |
| 3 | Alta | Como Administrador de Regras, quero visualizar um painel com todas as diretrizes ativas no momento, para ter um panorama claro das comissões que estão valendo. | 8 | 1 | ⏳ |
| 4 | Alta | Como Analista de Operações, quero simular o cálculo de uma venda específica no sistema, para confirmar se os descontos estão corretos antes de aprovar os pagamentos. | 13 | 1 | ⏳ |
| 5 | Alta | Como Analista de Operações, quero visualizar o desfecho das regras de maneira clara, para ter certeza de que a ferramenta interpretou a campanha corretamente. | 8 | 2 | ⏳ |
| 6 | Alta | Como Analista de Operações, quero que o assistente explique em texto o motivo do resultado gerado, para conseguir justificar os valores para os vendedores que tiverem dúvidas. | 8 | 2 | ⏳ |
| 7 | Média | Como Administrador de Regras, quero poder reativar e alternar para diretrizes antigas, para agilizar o trabalho durante períodos de mudanças de vendas. | 8 | 2 | ⏳ |
| 8 | Média | Como Auditor Interno, quero inspecionar a linha do tempo de mudanças feitas nas normas, para compreender e rastrear todo o fluxo de alterações realizadas. | 5 | 2 | ⏳ |
| 9 | Média | Como Administrador de Regras, quero receber um alerta caso eu crie uma diretriz que seja contraditória com outra, para evitar pagamentos duplicados ou prejuízos. | 8 | 3 | ⏳ |
| 10 | Baixa | Como Gestor Comercial, quero ter acesso a representações visuais referentes aos resultados gerados, para tornar a explicação da ferramenta mais clara para a diretoria. | 13 | 3 | ⏳ |
| 11 | Baixa | Como CTO da Dom Rock, quero monitorar indicadores e métricas de uso da plataforma (observabilidade), para atestar o desempenho e a estabilidade do sistema ao longo do tempo. | 8 | 3 | ⏳ |
| 12 | Alta | Como Analista de Operações, quero acessar um guia prático de uso no portal, para aprender a manusear as funcionalidades sem depender do time de suporte. | 3 | 3 | ⏳ |

---

# ✅ Critérios de Aceitação Detalhados

 ### <a href="./Relatório/Sprint1.md">1️⃣ Critérios referentes à 1ª Sprint </a> 
 
---

#### 🚦 Definition of Ready (DoR)
O DoR representa o nosso acordo de equipe indicando quando uma *User Story* está preparada para ter seu desenvolvimento iniciado em uma Sprint. Uma tarefa só será puxada para desenvolvimento se cumprir os seguintes critérios de checklist:

**Sobre a User Story:**
- [ ] Possui título claro, descrição bem definida e objetivo compreendido por todos.
- [ ] Os Critérios de Aceitação estão detalhados e documentados.
- [ ] As regras de negócio da tarefa estão claras.
- [ ] A história foi estimada pela equipe (em *Story Points*).
- [ ] A tarefa não possui dependências bloqueadoras que impeçam seu início.
- [ ] A compreensão da entrega foi validada com todo o time.

**Sobre os Artefatos Correlatos:**
- [ ] Design/documentação visual (Wireframes/Mockups) estão disponíveis (para tarefas de Front-end).
- [ ] O Modelo de Dados está definido e disponível (para tarefas de Back-end).
- [ ] A estratégia de testes foi definida.

---

#### 🏁 Definition of Done (DoD)
O DoD é o checklist de compromisso da nossa equipe que garante que a *User Story* foi totalmente concluída e atinge os critérios de qualidade necessários para ser entregue à Dom Rock.

**Critérios de Conclusão:**
- [ ] O código foi devidamente versionado no Git.
- [ ] O desenvolvimento ocorreu em uma branch específica (`feature/` ou `bugfix/`).
- [ ] Foi aberto um *Pull Request* (PR) antes da liberação para *Code Review*.
- [ ] Fragmentos de código comentados ou lixo de desenvolvimento foram removidos.
- [ ] Todos os Critérios de Aceitação da *User Story* foram plenamente satisfeitos e testados.
- [ ] Testes de unidade foram implementados com cobertura de código mínima de 70%.
- [ ] A funcionalidade roda localmente na máquina sem falhas e sem quebrar o que já existia.

---

## 📈 Requisitos Funcionais

- CRUD completo de regras de negócio  
- Versionamento de regras  
- Simulação de aplicação  
- Explicação automatizada via LLM  
- Registro de histórico de execuções  
- Geração de relatórios  

---

## 📊 Requisitos Não Funcionais

- **SpringBoot** para Backend  
- **Vue.js (SPA)** para Frontend  
- Integração com **Modelos LLM via API pública**  
- Utilização de framework como **LangChain / LangGraph / LlamaIndex**  
- Manual de Instalação  
- Manual do Usuário  
- Vídeo tutorial demonstrativo  
- Segurança e controle de acesso  

---

## 🛠️ Tecnologias

### Backend
- SpringBoot  
- Java  
- PostgreSQL  

### Frontend
- Vue.js (SPA)  
- TypeScript   

### IA Generativa
- Integração com API LLM (OpenAI / Gemini / Hugging Face)  
- Framework de orquestração (LangChain ou similar)  

### DevOps
- Docker  
- GitHub   

---

## 🌿 Estratégia de Branch

Utilizaremos o modelo **GitHub Flow**:

- `main` → versão estável  
- `feature/nome-da-feature`  
- `bugfix/nome-do-bug`  

Todo desenvolvimento ocorre em branch separada com abertura obrigatória de **Pull Request** antes do merge.

---

## 📝 Padrão de Commits

Seguiremos o padrão simplificado de Conventional Commits:
