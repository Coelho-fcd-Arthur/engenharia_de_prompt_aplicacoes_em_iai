# Projeto Módulo 3 – Low Code/No Code/Vibecode

## 📌 Desafio Escolhido

**Gerenciador de Clientes - Empréstimo Consignado:** Plataforma moderna de gestão de clientes e oportunidades para empresas de empréstimo consignado. O sistema simplifica o cadastro, implementa controle granular de acesso (roles) e gerencia oportunidades de forma intuitiva.

---

## 🖥️ Protótipo

O protótipo funciona como um CRM customizado. Funcionários cadastram clientes, atualizam status operacionais (pendente, aprovado, pago) e gerenciam suas próprias oportunidades. Gerentes possuem visibilidade completa sobre todas as operações, com painéis de controle e relatórios consolidados.

**Link para a aplicação criada:** [Acessar a Plataforma](https://consigno-flow-15.lovable.app/login)

---

## ⚙️ Plataforma Utilizada

**Lovable** (lovable.dev)

**Justificativa da escolha:** A ferramenta combina uma plataforma low-code baseada em React com IA generativa avançada. Foi selecionada por permitir o desenvolvimento ultra-rápido do frontend (reduzindo semanas para dias), facilitar iterações ágeis baseadas em feedback e eliminar a necessidade de boilerplate repetitivo em HTML/CSS/JavaScript.

---

## ✅ Vantagens Identificadas

1. **Protótipo rápido** – Iterações baseadas em feedback em tempo recorde, permitindo validação de conceitos em horas

2. **Engenharia de prompts** – Geração de funcionalidades complexas via instruções em texto, sem necessidade de codificação manual tradicional

3. **Interface moderna** – Design profissional com tema dark nativo e responsivo para mobile e desktop

4. **Autonomia total** – Desenvolvimento independente de todos os aspectos do projeto (requisitos, design, engenharia de prompts)

---

## ⚠️ Limitações Encontradas

1. **Customização limitada** – Restrições em personalizações e lógicas muito avançadas da IA; algumas validações complexas precisam ser simuladas

2. **Dependência da plataforma** – O código e a execução ficam atrelados ao ecossistema do Lovable; portabilidade limitada

3. **Backend limitado** – Ausência inicial de um banco de dados relacional robusto e autenticação complexa; dados armazenados em localStorage

---

## 📚 Reflexão Crítica

Contornei as limitações do backend simulando as regras de negócio de controle granular de acesso diretamente no fluxo de interface (roles de usuário). Para resolver as restrições de customização, utilizei técnicas avançadas de engenharia de prompts, decompondoo problemas complexos em instruções incrementais e refinadas iterativamente.

A experiência reforçou que plataformas low-code/no-code são ideais para MVPs e prototipagem rápida, mas aplicações production-grade ainda requerem backend robusto e customização profunda que essas ferramentas não oferecem nativamente.

---

## 👤 Desenvolvimento Individual

Este projeto foi desenvolvido **completamente por uma única pessoa**, abrangendo:

- **Requisitos & Modelagem:** Mapeamento de requisitos de negócio e modelagem dos dados capturados (CPF, Vínculo, Status)
- **Design & Identidade Visual:** Definição da paleta de cores e estilo inspirado no Stripe e HubSpot
- **Engenharia de Prompts:** Escrita, teste e refinamento das instruções na plataforma Lovable para geração dos componentes
- **Validação & Testes:** Verificação de fluxos de usuário e edgecases
- **Documentação:** Registro de decisões e aprendizados ao longo do desenvolvimento

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
