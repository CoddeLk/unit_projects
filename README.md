# Projeto UNIT - ServiceNow

## 📚 Descrição
O **Projeto UNIT** é uma aplicação acadêmica na plataforma ServiceNow, voltada para gerenciar alunos, professores, disciplinas e processos acadêmicos.  
O objetivo é criar um ambiente estruturado para automação de tarefas acadêmicas, controle de usuários e notificação de processos.

**Funcionalidades principais:**
- Tabelas personalizadas para alunos, professores e disciplinas
- Relacionamentos m2m (many-to-many)
- Record Producers e Flow Designer para automação de processos
- Notificações e aprovações automáticas
- Base de conhecimento "Secretaria Virtual"

---

## 👥 Equipe e Roles

| Usuário           | Nome completo              | Role Git/ServiceNow           |
| ----------------- | ------------------------- | ---------------------------- |
| unit_admin        | Lucas Gabriel             | Admin / UNIT_admin           |
| unit_dados        | Arthur Lucas              | Gestor de dados / UNIT_dados |
| unit_ui           | Gizelly Montes            | UX / UNIT_ui                 |
| unit_automacao    | Marcos Vinicius           | Flow Designer / UNIT_automacao    |
| unit_seguranca    | Clara Tavares             | Analista de seguranca / UNIT_seguranca     |
| unit_relatorios   | Elias Ferreira           |  Analista de relatorio / UNIT_relatorios     |

---

## ⚙️ Pré-requisitos
- Conta na plataforma Git (GitHub, GitLab ou Bitbucket)
- Git instalado localmente
- Acesso à instância de desenvolvimento ServiceNow compartilhada
- ServiceNow Studio habilitado para o escopo `x_unit`

---

## 📝 Estrutura de Branches
Adotamos o seguinte **workflow Git**:

- `main` → versão estável do projeto
- `develop` → branch de integração para desenvolvimento
- `feature/nome-da-feature` → novas funcionalidades
- `bugfix/nome-do-bug` → correções de bugs
- `hotfix/nome-do-hotfix` → correções urgentes em produção

---




