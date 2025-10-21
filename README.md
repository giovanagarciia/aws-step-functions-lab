# AWS Step Functions Lab

## Introdução
Este repositório documenta minha prática com **AWS Step Functions**, aplicando os conceitos aprendidos nas aulas da DIO e construindo workflows automatizados na nuvem AWS.

## Objetivos do Laboratório
- Aplicar conceitos de **orquestração de serviços AWS** usando Step Functions.
- Criar workflows que automatizam tarefas entre diferentes serviços.
- Documentar processos técnicos de forma clara e estruturada.

## Conceitos Abordados
- **AWS Step Functions**: definição de estados, transições e execução de tarefas.
- **Tipos de estados**: `Task`, `Choice`, `Parallel`, `Wait`, `Fail`, `Succeed`.
- **Integração com outros serviços AWS**: Lambda, S3, SNS, SQS.
- **Tratamento de erros**: Retry policies e catchers.
- **Execução de workflows**: acionamento manual ou via eventos.

## Workflow Implementado
Descreva aqui seu workflow passo a passo, por exemplo:
1. **Estado inicial**: Recebe evento de um S3 ou Lambda.
2. **Task 1**: Processa dados usando função Lambda.
3. **Choice**: Decide caminho baseado em condições do evento.
4. **Task 2 / Parallel**: Executa múltiplas tarefas simultaneamente.
5. **Succeed / Fail**: Finaliza workflow com sucesso ou falha.

## Insights e Aprendizados
- Aprendi a definir Choice States para roteamento condicional de tarefas.
- O monitoramento no console facilita identificar falhas rapidamente.

## Conclusão
Este laboratório consolidou meu conhecimento em **workflows automatizados com AWS Step Functions**, documentação técnica e integração entre serviços AWS.
