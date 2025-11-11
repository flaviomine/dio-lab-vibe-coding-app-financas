# 💸 FinanceIA - App de Finanças Pessoais 

Demonstrar os entregáveis do Desafio de Desenvolver um app de organização de finanças pessoais com IA conversacional com base no Desafio **CAIXA - Inteligência Artificial na Prática** da Plataforma **DIO**.

Link do desafio: https://web.dio.me/track/caixa-inteligencia-artificial-na-pratica


## 📑 Índice
- PRD Refinado
- Interações com a IA
- Funcionalidades do App
- Reflexões

### PRD Refinado no Copilot M365

```txt
# PRD – App de Finanças Pessoais com IA Conversacional (Vibe Coding)

## 1. Contexto
Criar um aplicativo de organização de finanças pessoais guiado por conversa, com automação máxima e fricção mínima, priorizando clareza visual, segurança e personalização. O app deve permitir que o usuário registre, acompanhe e planeje suas finanças como se estivesse conversando com um assistente inteligente.

## 2. Problema
Usuários desistem de controlar suas finanças por causa de:
- Excesso de lançamentos manuais
- Interfaces complexas e pouco intuitivas
- Falta de personalização e orientação prática

## 3. Público-Alvo
- Iniciantes em finanças pessoais
- Jovens adultos e profissionais que buscam praticidade
- Casais e famílias que desejam compartilhar o controle financeiro

## 4. Proposta de Valor
"Controle suas finanças conversando. O app entende, organiza, prevê e orienta — automaticamente."

## 5. Objetivos e Métricas
- Ativação D+7: ≥ 35%
- Retenção D+30: ≥ 25%
- Tempo médio de registro: ≤ 10s
- Acurácia de categorização: ≥ 85%
- NPS: ≥ 55

## 6. Princípios de UX, Design Universal e Acessibilidade

## Design Universal
1. Uso Equitativo
2. Flexibilidade no Uso
3. Uso Simples e Intuitivo
4. Informação Perceptível
5. Tolerância ao Erro
6. Baixo Esforço Físico
7. Dimensão e Espaço para Aproximação e Uso

## Acessibilidade (WCAG 2.2 AA)
- Contraste mínimo 4.5:1 (texto normal), 3:1 (texto grande)
- Alvos de toque ≥ 24x24 px
- Foco visível e navegação por teclado
- Suporte a leitores de tela

## 7. Funcionalidades-Chave (MVP)
- Chat em linguagem natural
- Entrada por voz
- OCR de recibos (fase 2)
- Classificação automática por IA
- Integração com Open Finance (opt-in)
- Importação via SMS/Push/OFX/CSV
- Metas financeiras e orçamentos dinâmicos
- Sugestão automática de orçamento
- Insights semanais e alertas inteligentes
- Previsão de saldo futuro
- Relatórios visuais simples
- Modo escuro
- Carteiras compartilhadas
- Educação financeira contextual
- Segurança: biometria, 2FA, criptografia
- Modo offline básico

## 8. Backlog da Fase 2
- OCR completo
- Pix/QR Code
- Gamificação leve
- Recomendações avançadas
- Visão de patrimônio e investimentos
- Versão Web

## 9. Fluxo Principal do Usuário
1. Onboarding com barra de progresso
2. Escolha entre estilo manual ou automático
3. Primeiro registro guiado por chat/voz
4. Sugestão de meta e orçamento automático
5. Tela resumo com CTA conversacional
6. Insights semanais e alertas

## 10. Telas Principais
- Chat/Registrar
- Resumo
- Metas e Orçamentos
- Relatórios
- Carteiras Compartilhadas
- Configurações

## 11. Arquitetura de IA e Integrações
- NLP/NLU para intenções
- Categorização supervisionada
- Motor de recomendações
- APIs de Open Finance
- Autenticação, push, analytics, armazenamento seguro

## 12. Segurança e Privacidade
- Biometria + 2FA
- Criptografia TLS e AES
- Consentimento granular
- Logs de auditoria
- Privacidade by design

## 13. Telemetria e Métricas
- Funis de onboarding
- Tempo para primeiro registro
- Uso de voz/OCR
- Acurácia de categorização
- Retenção D+7/D+30
- NPS/CSAT
- Sessões crash-free

## 14. Validação Rápida
- Testes de usabilidade semanais
- A/B de onboarding
- Diários de uso por 14 dias
- Avaliação do impacto do Open Finance

## 15. Critérios de Aceite
- Registro por texto e voz
- Categorização automática ≥ 85%
- Relatórios e gráficos por período
- Meta criada e orçamento sugerido
- Insights e alertas funcionais
- Carteira compartilhada funcional
- Login com biometria e 2FA
- Modo escuro e acessibilidade WCAG
- Evidência de aplicação dos 7 princípios do Design Universal

## 16. Roadmap
- MVP (0–12 semanas): funcionalidades principais, segurança, acessibilidade
- Fase 2 (13–24 semanas): funcionalidades avançadas, versão Web

## 17. Tom de Voz do Agente
- Calmo, prático e encorajador
- Frases curtas e orientadas à ação
- Explicações sob demanda
```

### 🤖 Interações com a IA

**Interações com o Copilot M365:**

> Aperfeiçoe o PRD criado

> Avaliae o PRD e veja se não tem nenhuma funcionalidade faltando ou a ser incrementada e incremente

> Inclua os princípios de Design Universal no PRD.

> Reescreva o PRD final incluindo todas essas melhorias e tendências para que ele seja o documento definitivo e pronto para virar prompt no Lovable.


**Interações com o Lovable:**

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document) {PRD}

> Não foi criado entrada com login e senha para controle e registros por usuário. Corrigir.

> A inclusão de novas metas não está funcionando. Corrigir.

> Relatórios não estão acumulando quando seleciona o periodo: ano, mês, etc. Corrigir.

Resultado Final no Lovable: https://vibe-finance-chat.lovable.app/

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/565b8012-80b8-4a88-9e46-ea156e232d73" />

<img width="1125" height="352" alt="image" src="https://github.com/user-attachments/assets/99f1ed5d-1428-417c-a29b-b33b1981d8e6" />

**Resumo básico das funcionalidades do App:**

---
## ✅ Funcionalidades do App

### Tela Inicial
- **Acesso rápido por cartões/atalhos**:
  - Gestão Comercial
  - Orçamentos Automatizados
  - Seguros Personalizados

### Saldo e Transações
- **Exibição do saldo disponível** em destaque
- **Lista de transações recentes**:
  - Nome/descrição da transação
  - Valor
  - Indicativo de entrada/saída
  - Organização cronológica

### Visão Financeira
- **Gráficos simples** para:
  - Receitas
  - Despesas
  - Resumo do fluxo financeiro

### Relatórios
- **Relatórios visuais** que apresentam o desempenho financeiro por período

### Metas
- **Acompanhamento de metas financeiras** (indicadores de progresso e comparação com objetivos definidos)

### Assistente Financeiro
- **Interação com assistente financeiro** para registro, consulta e orientação sobre finanças pessoais
---

### 🔍 Reflexões

  - O que funcionou bem?
    A construção e refinamento do PRD no Copilot M365 e a criação do app no Lovable.
    
  - O que não funcionou como o esperado?
    Algumas funcionalidades não funcionaram como tela de login, geração de relatórios atualizando os totalizadores e inserções de gastos. Como foi utilizado a versão free do Lovable, somente consegui construir funcionalidades dentro dos 5 créditos disponíveis.
    
  - O que aprendeu sobre conversar com IAs?
    As instruções devem ser bem claras, ricas de detalhamento e bem descritas para entregar o que se espera. Além disso, validações são necessárias a todo momento, alimentando a IA do que funciona bem e do que não entregou corretamente.


