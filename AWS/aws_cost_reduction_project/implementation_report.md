# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 21/08/2025
**Empresa:** Abstergo Industries
**Responsável:** John Doe

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por John Doe. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização de Custos com Amazon S3 Intelligent-Tiering
*   **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
*   **Foco da ferramenta:** Armazenamento de objetos
*   **Descrição de caso de uso:** A Abstergo Industries armazena grandes volumes de dados de logs e backups, com padrões de acesso imprevisíveis. Ao utilizar o S3 Intelligent-Tiering, os dados serão movidos automaticamente para a camada de armazenamento mais econômica com base na frequência de acesso, sem impacto no desempenho ou sobrecarga operacional. Isso resultará em uma redução significativa nos custos de armazenamento, uma vez que os dados acessados com menos frequência serão movidos para camadas mais baratas (ex: S3 Infrequent Access).

### Etapa 2: Redução de Custos de Computação com AWS Savings Plans
*   **Nome da ferramenta:** AWS Savings Plans
*   **Foco da ferramenta:** Custo de computação (EC2, Fargate, Lambda)
*   **Descrição de caso de uso:** A empresa possui uma carga de trabalho de computação consistente e previsível para suas aplicações web e processamento de dados. Ao se comprometer com um AWS Savings Plan de 1 ou 3 anos, a Abstergo Industries pode obter um desconto de até 72% em suas instâncias EC2 e outros serviços de computação em troca de um compromisso de uso (medido em $/hora). Isso proporcionará uma economia imediata e substancial na fatura da AWS.

### Etapa 3: Gerenciamento de Custos com AWS Cost Explorer
*   **Nome da ferramenta:** AWS Cost Explorer
*   **Foco da ferramenta:** Análise e visualização de custos
*   **Descrição de caso de uso:** Para garantir um controle de custos contínuo, a Abstergo Industries utilizará o AWS Cost Explorer para visualizar, entender e gerenciar seus custos da AWS. A ferramenta permitirá a criação de relatórios personalizados para identificar tendências, rastrear os gastos por serviço ou tag, e prever os custos futuros. Com essas informações, a equipe de TI poderá tomar decisões mais informadas para otimizar os recursos e evitar gastos desnecessários.
