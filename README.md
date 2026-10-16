# Projeto UiPath RPA

Projeto de automação desenvolvido no **UiPath Studio**, com arquivo principal `Main.xaml`.

## Visão geral

Este repositório contém um workflow de estudo de RPA. O arquivo `project.json` identifica o projeto como **"Teste Alura"** e descreve as dependências e configurações de execução.

> O objetivo detalhado e os resultados do fluxo ainda precisam ser documentados e validados. Esta descrição não pressupõe comportamento não verificado.

## Estrutura

```text
Uipath-RPA/
├── Main.xaml           # Fluxo principal
├── project.json        # Configurações e dependências
├── .objects/           # Recursos gerados pelo projeto
├── .project/           # Metadados do ambiente
├── .screenshots/       # Capturas/recursos de automação
├── .settings/          # Configurações locais
└── .tmh/               # Arquivos auxiliares do ambiente
```

## Ambiente identificado no projeto

- UiPath Studio: **22.4.1**
- Framework: **Legacy**
- Linguagem de expressões: **Visual Basic**
- Pacotes: UiPath.Excel.Activities 2.12.3; UiPath.Mail.Activities 1.15.1; UiPath.System.Activities 22.4.1; UiPath.UIAutomation.Activities 22.4.4
- Configuração: execução como workflow, com interação do usuário habilitada

## Como abrir

1. Instale uma versão compatível do **UiPath Studio**.
2. Clone ou baixe o repositório.
3. Abra o arquivo `project.json` no Studio.
4. Restaure as dependências e revise configurações, caminhos e atividades antes de executar.
5. Execute inicialmente em ambiente de testes, sem dados reais ou credenciais.

## Evoluções de documentação

- [ ] Descrever o processo de negócio automatizado.
- [ ] Incluir desenho AS-IS / TO-BE e entradas/saídas.
- [ ] Documentar exceções, logs e tratamento de falhas.
- [ ] Incluir evidências anonimizadas, testes e benefícios mensuráveis quando disponíveis.
- [ ] Avaliar quais arquivos gerados pelo Studio podem ser ignorados com segurança, sem afetar a reprodução do projeto.

**Atenção:** não publique credenciais, planilhas com dados pessoais nem informações internas de empresas.
