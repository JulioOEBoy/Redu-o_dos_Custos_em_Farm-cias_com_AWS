# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/01/2026
Empresa: Abstergo Industries
Responsável: Júlio César Ferreira Pedrini

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Júlio César Ferreira Pedrini**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, alinhando a infraestrutura de nuvem com as melhores práticas de otimização de custos (FinOps).

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma focada em um serviço AWS que oferece um impacto rápido na redução de custos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: AWS Cost Explorer

- **Nome da ferramenta:** AWS Cost Explorer
- **Foco da ferramenta:** Visibilidade e Análise de Custos
- **Descrição de caso de uso:** A ferramenta foi implementada para fornecer uma visão detalhada dos gastos com a AWS. O caso de uso imediato é a **identificação de picos de custo e serviços mais caros** (como EC2, RDS e S3), permitindo que a equipe de FinOps crie relatórios personalizados e filtros por tags para alocar custos e identificar rapidamente anomalias. Isso permite uma ação corretiva imediata, como a desativação de recursos esquecidos ou mal configurados.

### Etapa 2: AWS Trusted Advisor

- **Nome da ferramenta:** AWS Trusted Advisor
- **Foco da ferramenta:** Otimização de Custos e Melhores Práticas
- **Descrição de caso de uso:** O Trusted Advisor foi configurado para realizar **verificações automáticas de otimização de custos**. O caso de uso principal é a **identificação de recursos ociosos ou subutilizados**, como instâncias EC2 com baixo uso de CPU, volumes EBS não anexados ou balanceadores de carga inativos. As recomendações geradas permitem que a equipe realize o *right-sizing* (dimensionamento correto) ou a exclusão desses recursos, resultando em economia imediata.

### Etapa 3: Amazon EC2 Spot Instances

- **Nome da ferramenta:** Amazon EC2 Spot Instances
- **Foco da ferramenta:** Redução de Custos de Computação
- **Descrição de caso de uso:** O uso de Instâncias Spot foi implementado para **cargas de trabalho flexíveis e tolerantes a falhas**, como processamento de dados em lote (batch jobs), testes de integração contínua e ambientes de desenvolvimento/staging. O caso de uso consiste em migrar essas cargas de trabalho de instâncias On-Demand para Spot, aproveitando a capacidade excedente da AWS com descontos de até 90%, gerando uma redução de custo imediata e significativa no consumo de computação.

## Conclusão

A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **a redução imediata dos custos operacionais, o aumento da visibilidade financeira e a melhoria da eficiência no uso dos recursos de nuvem**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa, como a adoção de Savings Plans e a automação de desligamento de ambientes fora do horário comercial.

## Anexos

[Não há anexos neste momento. O relatório serve como a entrega principal do projeto.]

Assinatura do Responsável pelo Projeto:

Júlio César Ferreira Pedrini
