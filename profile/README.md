# 🎓 Alunos de SI (IFRS - Campus Vacaria)
## Projeto Integrado de Recursos Humanos (RH)

Este repositório centraliza as diretrizes e a organização do projeto prático de **Gestão de RH**, desenvolvido de forma modular pelos alunos do curso de Bacharelado em Sistemas de Informação.

O projeto consiste em um ecossistema de microsserviços que se comunicam via APIs para automatizar processos de recrutamento, seleção e análise de dados.

---

### 🛠️ Stack Tecnológica Padronizada
Para garantir a interoperabilidade entre os módulos, todos os times utilizam:
* **Linguagem:** Python 3.10+
* **Framework Web:** [FastAPI](https://fastapi.tiangolo.com/)
* **Comunicação:** REST APIs (JSON)
* **Documentação:** Swagger/OpenAPI (disponível em cada módulo via `/docs`)

---

### 👥 Organização das Equipes e Escopo
O projeto foi dividido em 5 grupos funcionais. Cada grupo é responsável por uma parte vital do fluxo de RH:

| Grupo | Módulo / Escopo | Integrantes |
| :--- | :--- | :--- |
| **G1** | ✉️ **Mensageria** | Naiara, Maria Eduarda, Mauricio |
| **G2** | 📅 **Agendamentos de Entrevistas** | Giovane, Gabriel Pertile, Carlos |
| **G3** | 📋 **Cadastro (Empresas, Pessoas e Vagas)** | Josinei, Marcelo Boeira, João Pedro |
| **G4** | 🤝 **Match (Vagas x Pessoas)** | Vagner, Marcos, Giancarlo |
| **G5** | 📊 **Dashboards e Analytics** | Picheti, Gabriel Toledo, William |



---

### 📈 Integração com Gestão de Projetos
Este desenvolvimento não é apenas técnico, mas também uma aplicação prática da disciplina de **Gestão de Projetos**. 

Cada aluno desempenha um papel específico dentro do seu time (ex: *Project Manager, Tech Lead, Developer, QA*), e os repositórios individuais devem refletir:
1.  **Kanban/Project Board:** Acompanhamento de tarefas e prazos.
2.  **Documentação de API:** Contratos claros para que os outros grupos possam consumir os dados.
3.  **Versionamento:** Uso rigoroso de Commits Semânticos e Pull Requests.

---

### 🚀 Fluxo de Integração
1. O **G3** fornece a base de dados de candidatos e vagas.
2. O **G4** consome os dados do G3 para gerar as combinações (matches).
3. O **G2** utiliza os matches para agendar entrevistas.
4. O **G1** realiza a comunicação entre as partes interessadas.
5. O **G5** consome dados de todos os módulos acima para gerar insights e visualizações em tempo real.

---

### 📍 Localização
**Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Sul** **Campus Vacaria** Curso: Bacharelado em Sistemas de Informação  
Ano: 2026
