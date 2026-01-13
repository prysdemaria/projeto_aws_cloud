# RELATORIO DE IMPLEMENTACAO DE SERVICOS AWS

Data: 12/01/2026
Empresa: Abstergo Industries 
Responsavel: Pryscilla S. Maria

## Introducao
Este relatorio apresenta o processo de implementacao de ferramentas na empresa Abstergo Industries, realizado por Pryscilla S Maria. O objetivo do projeto foi elencar 3 servicos AWS, com a finalidade de realizar diminuicao de custos imediatos.

## Descricao do Projeto
O projeto de implementacao de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especi­ficos. A seguir, serao descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 - Simple Storage Service
- O foco principal do Amazon S3 é basicamente ser um serviço de armazenamento de objetos. Ele é  muito interessante porque consegue guardar e acessar qualquer volume de dados, com segurança, escalabilidade e durabilidade, garantindo assim que seus dados não se percam. 
- Na Abstergo Industries, o Amazon S3 será utilizado como repositório central de dados laboratoriais, laudos, exames e documentos regulatórios, garantindo alta durabilidade, baixo custo, escalabilidade e conformidade com requisitos de auditoria.

Etapa 2: 
- AWS Lambda
- O Lambda é uma ferramenta flexivel e economica. Seu foco principal é permitir a execução do código na nuvem, sem a necessidade da empresa gerenciar servidores próprios. Ou seja, é possivel escrever e carregar na nuvem o código utilizado pela farmaceutica e o AWS cuidará de toda a insfraestrutura: provisionamento, escalabilidade e manutenção. 
- Na Abstergo Industries, o AWS Lambda será ideal para automação de processos de controle de qualidade, validação de laudos, integração de sistemas e notificações, pois permite execução por evento, alta escala e redução significativa de custos operacionais.

Etapa 3: 
- EC2 - Elastic Compute Cloud - Spot Instances
- o foco principal dessa ferramenta é permitir que os usuários aproveitem a capacidade ociosa do AWS com um desconto de ate 90%, em comparação
com outros valores. Além de reduzir os custos que é o foco principal, essa ferramenta pode ser usada para várias aplicações sem estado, tolerantes a falhas e flexíveis como big data, cargas de trabalho conteinerizadas, CI/CD, servidores Web, computação de alta performance (HPC) e cargas de trabalho de teste e desenvolvimento. 
- Na Abstergo Industries, o uso do EC2 Spot Instances será ideal para criar simulações moleculares, análises químicas e processamento científico em lote, pois essas cargas são tolerantes a falhas e altamente computacionais.


## Conclusao
A implementacao de ferramentas na empresa Abstergo Industries tem como principal objetivo a reducao de custos operacionais aliada ao aumento de eficiencia. O Amazon S3 é utilizado como repositorio central para o armazenamento de relatorios, analises, imagens e demais arquivos gerados pela industria, garantindo alta durabilidade, segurança e baixo custo.

O AWS Lambda oferece uma excelente relação custo-beneficio para a execucao de aplicacoes e rotinas automatizadas necessarias a farmaceutica, permitindo a execucao de processos sob demanda sem a necessidade de manter servidores em funcionamento continuo.

Já o uso de EC2 Spot Instances proporciona uma solucao altamente economica e eficiente para a execucao de processos, analises e calculos de grande volume, possibilitando o processamento intensivo de dados com significativa reducao de custos, o que contribui diretamente para o aumento da eficiencia e produtividade da empresa. Recomenda-se a continuidade da utilizacao das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da Abtergo Industries.

## Anexos
Links consultados para esse projeto:

o que é o Spot instances
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/using-spot-instances.html
https://aws.amazon.com/pt/ec2/spot/

estudo de caso com Spot Instances em uma Farmaceutica
https://aws.amazon.com/startups/learn/tamarind-bio-is-driving-ai-assisted-drug-discovery-with-aws?lang=pt-BR

O que é o Lambda
https://docs.aws.amazon.com/pt_br/whitepapers/latest/security-overview-aws-lambda/benefits-of-lambda.html
https://aws.amazon.com/pt/lambda/
https://aws.amazon.com/pt/blogs/aws-brasil/lidando-com-bilhoes-de-invocacoes-melhores-praticas-do-aws-lambda/


O que é o S3
https://aws.amazon.com/pt/s3/
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html

anexo arquivo pdf com esquema de funcionamento das ferramentas

Assinatura do Responsavel pelo Projeto:

Pryscilla S Maria