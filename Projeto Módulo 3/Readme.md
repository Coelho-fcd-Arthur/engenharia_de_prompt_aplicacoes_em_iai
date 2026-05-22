# Gerenciador de Clientes - Empréstimo Consignado

> Plataforma moderna de gestão de clientes e oportunidades para empresas de empréstimo consignado, desenvolvida com low-code/no-code.

🔗 **[Acessar a Plataforma](https://consigno-flow-15.lovable.app/dashboard)**

---

## 📋 Sobre o Projeto

O **Gerenciador de Clientes** é uma solução integrada que permite que vendedores e gerentes realizem o gerenciamento completo de clientes e oportunidades de forma moderna, intuitiva e segura.

A plataforma foi desenvolvida como projeto aplicado da disciplina de "Engenharia de Prompt e Aplicações em IA", demonstrando como ferramentas low-code combinadas com engenharia de prompts podem criar soluções profissionais em tempo recorde.

### 🎯 Objetivos

- Simplificar o cadastro e gerenciamento de clientes
- Implementar controle granular de acesso por tipo de usuário
- Facilitar prospecção e acompanhamento de oportunidades
- Fornecer visibilidade gerencial através de dashboards
- Reduzir tempo de desenvolvimento com low-code

---

## ✨ Funcionalidades

### 👤 Para Funcionários

- ✅ Cadastro intuitivo de clientes
- ✅ Visualização exclusiva de seus próprios clientes
- ✅ Edição de informações de clientes
- ✅ Criação de listas de oportunidades
- ✅ Atualização de status operacionais
- ✅ Organização de observações e retornos
- ✅ Pesquisa e filtros avançados

### 👨‍💼 Para Gerentes

- ✅ Visualização de todos os clientes
- ✅ Rastreamento de responsáveis por cadastro
- ✅ Acompanhamento de métricas da equipe
- ✅ Dashboards gerais e relatórios
- ✅ Gerenciamento centralizado de oportunidades
- ✅ Monitoramento de operações (aprovadas, pagas)
- ✅ Controle total de acessos

---

## 📊 Dados Capturados

O sistema realiza o cadastro estruturado de:

| Campo | Tipo | Descrição |
|-------|------|-----------|
| Nome do Cliente | Texto | Identificação do cliente |
| CPF | Máscara | Validação de pessoa física |
| Email | Email | Contato e comunicação |
| Telefone | Telefone | Comunicação direta |
| Vínculo | Categoria | Tipo de relação com empresa |
| Tipo de Operação | Categoria | Produto/serviço solicitado |
| Status da Operação | Status | Estado atual (pendente, aprovado, pago) |
| Observações | Texto Longo | Notas e contexto |
| Responsável | Usuário | Funcionário responsável |

---

## 🛠️ Stack Tecnológico

### Plataforma

- **[Lovable](https://lovable.dev)** - Plataforma low-code baseada em IA
- **IA Generativa** - Integração com modelos de linguagem para geração de código
- **Frontend** - React com componentes modernos

### Design

- **Tema:** Dark Mode
- **Paleta:** Preto + Azul com Glow elegante
- **Inspiração:** HubSpot, Pipedrive, Notion, Stripe, Monday

---

## 🚀 Por que Lovable?

### ✅ Vantagens Implementadas

| Vantagem | Impacto |
|----------|--------|
| **Desenvolvimento Ultra-Rápido** | Redução de 70-80% no time-to-market |
| **Engenharia de Prompts** | Geração de funcionalidades via instruções precisas |
| **Interface Moderna** | Design profissional sem designer dedicado |
| **Responsividade** | Funcionamento perfeito em desktop e mobile |
| **Escalabilidade** | Estrutura preparada para integrações futuras |
| **Prototipagem Ágil** | Iterações rápidas baseadas em feedback |

### ⚠️ Limitações Identificadas

| Limitação | Mitigação |
|-----------|-----------|
| **Dependência da Plataforma** | Documentação completa de arquitetura |
| **Backend Limitado** | Roadmap para integração com BD real |
| **Personalizações Avançadas** | Uso estratégico de engenharia de prompts |
| **Autenticação Robusta** | Planejado para versão 2.0 |

---

## 🎓 Aprendizados Técnicos

### 1. Engenharia de Prompts
- Estruturação de prompts detalhados para gerar código preciso
- Iteração e refinamento de instruções para resultados esperados
- Uso de contexto e exemplos para melhor compreensão da IA

### 2. Arquitetura Low-Code
- Design modular de funcionalidades
- Separação clara entre níveis de acesso
- Reutilização de componentes

### 3. Experiência do Usuário
- Importância de identidade visual consistente
- Simplificação de fluxos operacionais
- Feedback contínuo na iteração

### 4. Gestão de Requisitos
- Levantamento preciso com stakeholders
- Priorização de funcionalidades
- Validação com usuários finais

---

## 📈 Desafios Enfrentados

### Desafio 1: Estrutura Relacional Complexa
**Problema:** Conectar múltiplas tabelas em um único comando
**Solução:** Estruturação manual do banco de dados relacional com prompts guiados

### Desafio 2: Controle Granular de Acesso
**Problema:** Implementar permissões por tipo de usuário
**Solução:** Separação clara de interfaces e fluxos por role

### Desafio 3: Interface Moderna Mantendo Simplicidade
**Problema:** Criar design profissional sem complexidade excessiva
**Solução:** Uso de dark theme elegante e componentes minimalistas

### Desafio 4: Validação de Dados
**Problema:** Garantir qualidade de cadastros (CPF, Email)
**Solução:** Máscaras de entrada e validações em tempo real

---
