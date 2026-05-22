# Projeto Módulo 3 – Low Code/No Code/Vibecode

## 📌 Desafio Escolhido

**Gerenciador de Clientes - Empréstimo Consignado:** Plataforma moderna de gestão de clientes e oportunidades para empresas de empréstimo consignado. O sistema simplifica o cadastro, implementa controle granular de acesso (vendedores vs. gerentes), facilita a prospecção e fornece visibilidade gerencial através de dashboards em modo escuro.

---

## 🖥️ Protótipo

O protótipo funciona como um CRM customizado. Funcionários cadastram clientes, atualizam status operacionais (pendente, aprovado, pago) e gerenciam suas próprias oportunidades. Gerentes possuem visão macro, acompanham métricas da equipe, rastreiam responsáveis e monitoram os resultados gerais do negócio.

**Link para a aplicação criada:** [Acessar a Plataforma](https://consigno-flow-15.lovable.app/login)

---

## ⚙️ Plataforma Utilizada

**Lovable** (lovable.dev)

**Justificativa da escolha:** A ferramenta combina uma plataforma low-code baseada em React com IA generativa avançada. Ela foi selecionada por permitir o desenvolvimento ultra-rápido do frontend (redução de 70-80% no tempo de criação) e a iteração imediata da interface via engenharia de prompts.

---

## ✅ Vantagens Identificadas

1. **Protótipo rápido** – Iterações baseadas em feedback em tempo recorde

2. **Engenharia de prompts** – Geração de funcionalidades complexas via instruções em texto

3. **Interface moderna** – Design profissional com tema dark nativo e responsivo para mobile e desktop

---

## ⚠️ Limitações Encontradas

1. **Customização limitada** – Restrições em personalizações e lógicas muito avançadas da IA

2. **Dependência da plataforma** – O código e a execução ficam atrelados ao ecossistema do Lovable

3. **Backend limitado** – Ausência inicial de um banco de dados relacional robusto e autenticação complexa

---

## 📚 Reflexão Crítica

Contornei as limitações do backend simulando as regras de negócio de controle granular de acesso diretamente no fluxo de interface (roles de usuário). Para resolver as restrições de customização, apliquei engenharia de prompts avançada com contexto detalhado e instruções modulares para guiar a IA. O risco de dependência foi mitigado com o planejamento de um roadmap focado na exportação do frontend em React e futura integração com um banco de dados real (Versão 2.0).

---

## 👥 Colaboração

O grupo dividiu as tarefas com base em competências complementares:

| Área | Responsabilidade |
|------|------------------|
| **Requisitos & Modelagem** | Mapeamento de requisitos de negócio e modelagem dos dados capturados (CPF, Vínculo, Status) |
| **Design & Identidade Visual** | Definição da paleta de cores e estilo inspirado no Stripe e HubSpot |
| **Engenharia de Prompts** | Escrita, teste e refinamento das instruções na plataforma Lovable para geração dos componentes |

---

## 📝 Registro da Aula

**Data:** 11/05/2026

**Atividade:** Discussão crítica + mini-projeto de aplicação

**Local:** Laboratório de informática / Quadro branco

**Professor(a):** Kadidja Valéria

---

## 🚀 Próximos Passos

- Implementação de um sistema de autenticação robusto e seguro para login de usuários

- Integração com um banco de dados em nuvem real (PostgreSQL/Supabase) para persistência definitiva dos dados

- Evolução do painel gerencial no Projeto Final da Unidade 3, adicionando relatórios automatizados exportáveis e gráficos financeiros em tempo real
