# Automação de formulário web com UiPath | Estudo prático de RPA

**UiPath Studio · Automação de interface · Navegador Chrome · Fluxo de cadastro**

## Visão geral

Este repositório contém um **workflow de estudo em UiPath**, identificado no arquivo `project.json` como **“Teste Alura”**. O fluxo principal (`Main.xaml`) utiliza automação de interface no **Google Chrome** sobre uma página da **Alura**, com cliques em **“Matricule-se”** e preenchimento de campos de formulário.

**Objetivo do exercício:** demonstrar o encadeamento de atividades de navegação, localização de elementos e preenchimento de dados em uma interface web.

> **Escopo comprovável:** há arquivos de configuração e um fluxo XAML. Este repositório não contém relatório de execução, taxa de sucesso, integração via API ou evidência de implantação em produção.

## O que existe no fluxo

A leitura de `Main.xaml` identifica a seguinte sequência de atividades:

1. Utilização de **navegador Chrome** em uma página da Alura.
2. Ações de **clique** em elementos associados a “Matricule-se”.
3. Preenchimento dos campos **Nome completo**, **Email**, **CPF** e **Telefone com DDD**.
4. Atividade **Message Box** para apresentação de mensagem.

O resultado final de uma inscrição ou submissão não deve ser presumido apenas pela presença dessas atividades no arquivo.

## Arquivos principais

| Arquivo ou pasta | Finalidade |
| --- | --- |
| [`Main.xaml`](./Main.xaml) | Fluxo visual de automação e suas atividades |
| [`project.json`](./project.json) | Configuração, dependências e referência ao workflow de entrada |
| [`.screenshots/`](./.screenshots) | Diretório de apoio presente no projeto UiPath |

**Configuração registrada:** UiPath Studio **22.4.1.0**, projeto **Legacy**, expressões **Visual Basic** e pacotes de Excel, Mail, System e UIAutomation. Esses dados descrevem os arquivos existentes, não requisitos mínimos universalmente válidos.

## Como analisar o exercício

1. Abrir a pasta no **UiPath Studio** compatível com o projeto.
2. Consultar `project.json` para identificar as dependências.
3. Inspecionar o workflow em `Main.xaml` e a ordem das atividades.
4. Validar seletores, elementos de interface e condições atuais da página antes de qualquer execução.

O formulário externo pode ter sido alterado desde a criação do exercício. **Não execute com dados pessoais reais nem submeta inscrições sem autorização.**

## Competências demonstradas pelo artefato

- Interpretação de uma jornada de cadastro e seus campos;
- Sequenciamento de tarefas em automação de interface;
- Utilização de atividades **Click**, **Type Into** e mensagem;
- Identificação de pré-condições, fragilidade de seletores e dependência de página externa.

## Melhorias que poderiam ser exploradas

Como evolução **proposta, não implementada**, seria possível documentar validações de entrada, tratamento de erros, uso de dados de teste, logs e critérios de sucesso do preenchimento.

**Observação:** o código da automação e os arquivos originais permanecem inalterados. Este README organiza o estudo sem atribuir resultados não demonstrados.
