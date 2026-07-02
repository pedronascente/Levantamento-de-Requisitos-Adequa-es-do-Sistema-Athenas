# Levantamento de Requisitos - Adequacoes do Sistema Athenas

Este repositório reúne um levantamento de requisitos funcionais para adequações no Sistema Athenas, com foco em integrações, cadastro de associados, importação de dados e autenticação.

O material foi organizado para documentar necessidades de negócio, regras funcionais, estruturas de dados esperadas e evidências visuais do sistema atual, servindo como base para análise técnica, modelagem da solução e alinhamento com a equipe responsável pelo Athenas.

## Objetivo do projeto

O objetivo do levantamento é registrar, de forma estruturada, as alterações necessárias no ecossistema Athenas para atender processos relacionados ao cadastro e gestão de associados médicos.

Entre os pontos analisados estão:

- envio de observações pela API de cadastro de pessoas;
- classificação de endereços para cobrança;
- importação de convênios e dependentes do sistema atual;
- ajuste da tela de cadastro de associado;
- autenticação de associado por CPF e senha.

## Conteudo do levantamento

O documento principal do projeto é:

- `Levantamento de Requisitos – Adequações do Sistema Athenas..docx`

Ele contém os requisitos funcionais identificados, separados por códigos de referência:

| Requisito | Tema | Resumo |
| --- | --- | --- |
| RF-001 | Observações na API de cadastro | Adequar o endpoint de cadastro de pessoas para receber múltiplas observações com tipo, descrição, data e responsável. |
| RF-002 | Tipo de endereço | Permitir classificar endereços, incluindo o novo tipo `Cobrança`, usado para correspondências financeiras. |
| RF-003 | Convênios e dependentes | Importar dados de convênios como Unimed, Uniodonto e Uniair, incluindo seus dependentes. |
| RF-004 | Tela de dados gerais | Ajustar a tela de cadastro de associado para manter apenas os campos necessários. |
| RF-005 | Autenticação por CPF | Permitir login do associado usando CPF e senha, respeitando pré-condições como cadastro ativo e CRM válido. |

## Evidencias visuais

A pasta `prints/athenas.omline/` contém capturas de tela usadas como apoio ao levantamento:

- `dados gerais.png`
- `historicos.png`
- `cadastro de endereço.png`
- `Captura de tela 2026-07-01 113157.png`

Essas imagens ajudam a contextualizar o funcionamento atual das telas e servem como referência para as alterações propostas.

## Principais competencias demonstradas

Este projeto evidencia habilidades importantes para atuação em análise de sistemas, requisitos e integração entre áreas técnicas e de negócio:

- levantamento e documentação de requisitos funcionais;
- escrita de regras de negócio claras e rastreáveis;
- especificação de payloads e estruturas esperadas para APIs;
- análise de telas e processos existentes;
- organização de evidências para apoiar decisões técnicas;
- comunicação entre negócio, desenvolvimento e equipe responsável pelo sistema.

## Status dos requisitos

No checklist do documento, os requisitos RF-001 e RF-002 aparecem como concluídos. Os requisitos RF-003, RF-004 e RF-005 constam como pendentes ou ainda em análise.

## Observacao importante

Os dados descritos no levantamento servem como referência com base no sistema atual. A definição final sobre armazenamento, adaptação, descarte de campos ou forma de disponibilização deve ser validada pela equipe responsável pelo Athenas durante a análise técnica e a modelagem da aplicação.

## Como um recrutador pode avaliar este projeto

Este não é um projeto de código-fonte, mas sim um artefato de análise e documentação funcional. Ele demonstra a capacidade de entender um sistema existente, transformar necessidades operacionais em requisitos objetivos e preparar insumos para que uma equipe técnica consiga estimar, desenvolver e validar as alterações solicitadas.
