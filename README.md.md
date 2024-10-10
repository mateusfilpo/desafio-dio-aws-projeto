# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS  
**Data:** 09/10/2024 
**Empresa:** Abstergo Industries 
**Responsável:** Mateus Filpo

## Introdução  
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, utilizando a infraestrutura da AWS, realizado por **Mateus Filpo**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto  
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:  
- **Amazon EC2 (Elastic Compute Cloud)**  
- **Foco da ferramenta:** Hospedagem do website da farmácia  
- **Descrição de caso de uso:** Utilizamos o Amazon EC2 para hospedar o site da farmácia, permitindo que os clientes façam pedidos online e visualizem informações sobre medicamentos. A plataforma foi configurada para escalar automaticamente durante picos de acesso, como em campanhas de marketing, garantindo estabilidade e performance sem desperdício de recursos em momentos de menor tráfego.

### Etapa 2:  
- **Amazon RDS (Relational Database Service)**  
- **Foco da ferramenta:** Gerenciamento de banco de dados para pedidos e clientes  
- **Descrição de caso de uso:** O Amazon RDS foi escolhido para gerenciar o banco de dados relacional que armazena informações sobre clientes, pedidos e estoque de medicamentos. Isso permitiu alta disponibilidade e backups automatizados, garantindo segurança e integridade dos dados.

### Etapa 3:  
- **AWS S3 (Simple Storage Service)**  
- **Foco da ferramenta:** Armazenamento de documentos e imagens dos produtos  
- **Descrição de caso de uso:** A farmácia utiliza o AWS S3 para armazenar imagens de produtos e documentos, como prescrições médicas digitalizadas enviadas pelos clientes. Com sua escalabilidade e política de arquivamento, o S3 permitiu reduzir custos, migrando documentos antigos para o S3 Glacier automaticamente.

## Conclusão  
A implementação de ferramentas na empresa Abstergo Industries tem como esperado benefícios claros, como **escalabilidade sob demanda**, **segurança aprimorada** para dados sensíveis, e **redução de custos operacionais** com o uso de políticas automatizadas de armazenamento. O que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos  
- Diagrama de arquitetura da solução AWS  
- Planilha de análise de custos do Amazon EC2 e RDS  
- Política de arquivamento do AWS S3

---

**Assinatura do Responsável pelo Projeto:**  
Mateus Filpo 
