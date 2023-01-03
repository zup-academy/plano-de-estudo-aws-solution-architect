# Plano de Estudo sobre a certificação aws solution architect

### Objetivo de aprendizagem

Adquirir o conhecimento necessário para obter a certificação aws solution architect

A preparação e a obtenção desta certificação demonstrarão:

* Conhecimento e habilidades em computação, rede, armazenamento e serviços de banco de dados da AWS, bem como serviços de implantação e gerenciamento da AWS

* Conhecimento e habilidades em implementação, gerenciamento e operação de workloads na AWS, bem como na implementação de controles de segurança e requisitos de conformidade

* Conhecimento e habilidades no uso do Console de Gerenciamento da AWS e da Interface da Linha de Comando (CLI) da AWS, 
compreensão do AWS Well-Architected Framework, da rede da AWS, dos serviços de segurança e da infraestrutura global da AWS

* Capacidade para identificar quais serviços da AWS atendem a um determinado requisito técnico e definir requisitos técnicos para uma aplicação baseada em AWS

### palavras chaves

- Design de arquiteturas seguras
- Design de arquiteturas resilientes
- Design de arquiteturas de alta performance
- Design de arquiteturas econômicas
- AWS Well Architected Framework
- Arquiteturas com fraco acoplamento
- AWS Faq's
- IAM & Billing
- KMS & Cloud HSM
- Simple Storage Service (S3)
- Elastic Cloud Compute (EC2)
- Elastic Block Storage (EBS)
- Elastic Load Balancers (ELB)
- Web Application Firewall (WAF)
- Virtual Private Cloud (VPC)
- CloudWatch Vs Cloud Trail
- CloudFront
- Databases
- Athena
- Macie
- Kinesis
- Data Transfer
- ENI, EN & EFA
- CloudFormation
- SQS, SWF & SNS
- EFS & FSx
- Lambda
- Active Directory
- High Performance Computing
- Route 53
- Auto Scaling
- ECS, Fargate, EKS & ECR

### Onde pesquisar

* Site oficial da aws
* Udemy
* Google
* Simulados

### Explorar o tema

A certificação solutions architect associate, atualmente em sua versão SAA C03:

- Duração: 130 minutos
- Custo: 150USD
- Formato: Aproximadamente 65 perguntas
- Pontuação: 100 a 1000, aprovação em 720

A prova é dividida em domínios, que são:

- Design de arquiteturas seguras

	- Modelo de responsabilidade compartilhada

		Tópicos chave:

			- IAM
				- Roles
				- Menor privilégio
				- Melhores práticas
				- Billing Account
				- Root account
				- Policies

			- AWS KMS
				- Gerenciada pela aws
				- Gerenciada pelo cliente
				- Importação de chaves
				- Rotação de chaves

			- AWS CloudHSM
				- Conceitos básicos

			- AWS VPC
				- vpc
				- subnets
				- NAT Gateway
			
			- AWS VPN
				- Conceitos básicos
		
			- AWS Direct Connect
				-	Conceitos básicos

			- AWS Snowball
				- Conceitos básicos

- Design de arquiteturas resilientes

		Tópicos chave:

			- Amazon Elastic Block Store
				- Custo
				- Iops
				- Persistência
				- Tipos de volume e casos de uso

			- Elastic File System 
				- Tipos de montagem
				- Sistemas operacionais suportados

			- Amazon Simple Storage Service (s3)
				- Classes de armazenamento
				- Formas de transferência de dados
				- Politicas de ciclo de vida
				- Versionamento
				- Locking

			- Arquiteturas com fraco acomplamento
				- sqs
				- sns
				- lambda
				- dynamodb
				- Kinesis

			- Elastic Load Balancer 
				- tipos de elb
				- casos de uso
				- acesso externo / interno
				- Auto scalling group
				- Placement groups

- Design de arquiteturas de alta performance

		Tópicos chave:

			- Amazon RDS
				- Tipos de banco de dados
				- Alta disponibilidade
				- Read Réplicas
				- Aurora Serveless
				- Backups

			- Dynamodb
				- Custo
				- Cache
				- throughput

			- Elasticache
				- Redis
				- Memcached

			- Cloudfront
				- Caching
				- Origins
				- Lambda Edge

			- Containers
				- eks
				- ecs
				- ecr
		
- Design de arquiteturas econômicas
	
	- Calculadora aws
	- Modelos de instâncias ec2 e custos (on demand, spot...)
	- Qual modelo de armazenamento utilizar e seus custos (ebs, rds, s3...)
  - Melhor solução X Custo beneficio

Cada domínio possui o seu peso, é possível visualizar cada item nesta [doc](https://d1.awsstatic.com/pt_BR/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf)

já aqui reside a doc oficial sobre a certificação, com todo material sobre, incluindo a opção de agendar o exame: https://aws.amazon.com/pt/certification/certified-solutions-architect-associate/

### Ao agendar o exame

Se cadastre com os dados iguais a de seu documento (RG, Habilitação, Passaporte, etc)

O exame é oferecido através da plataforma da pearsonvue, nela é possível executar um teste no pc que será utilizado para realizar a prova, em termos gerais não somente para a personvue mas qualquer teste online:

- Deixe o ambiente iluminado.
- Vá ao banheiro antes.
- Deixe a mesa limpa, se possível sem monitores, cabos, teclados, etc.
- Documento com identificação com fácil acesso.
- Se for utilizar a camera integrada do notebook e ele estiver conectado utilizando um cabo de rede, tome cuidado para não desconectar o cabo ou qualquer outro tipo de problema.
- Se o seu inglês ou espanhol não estiver na sua melhor versão, explique via chat e peça para o inspetor digitar as perguntas, geralmente ele pede para olhar os quatros cantos do cômodo que está fazendo a prova e embaixo da mesa.
- Atente-se ao fuso horário na hora de agendar a prova
- Existe a opção de agendar o exame com as questões em Português e durante o exame é possível "alternar" as questões para inglês, entretanto, se for possível, agende o exame em inglês, grande parte dos simulados estão em inglês e fará você ganhar tempo (cada minuto conta)
- Fique calmo que vai dar certo.

### Como se preparar para o exame

Aqui vai de como o estudante se sente em frente ao exame. Uma boa opção é se testar frente a um simulado e o resultado pode indicar a quantidade e ordem de material a ser estudado. 

Em todo caso, consumir o curso e o readness antes dos simulados pode ser uma boa.

#### Cursos

* Certificação Amazon AWS Solutions Architect Associate 2023, do Andre Iacono em português:

Curso com classificação de 4,8 de 5 (7.961 classificações) e 27.548 alunos

Link: https://www.udemy.com/course/certificacao-amazon-aws-2019-solutions-architect/

É um curso com bastante conceito, dicas e que cobre uns 90% do que cai na prova. Como é em português, assisti-lo em 2x fica bem fácil.

Durante as promoções na Udemy, é possível comprar esse curso por cerca de R$27,90.

* Ultimate AWS Certified Solutions Architect Associate SAA-C03, do Stephane Maarek em inglês:

Curso com classificação de 4,7 de 5 (161.021 classificações) e 699.643 alunos.

É um curso super completo e aborda praticamente todos os dominios cobrados no exame.

Link: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/

Durante as promoções na Udemy, é possível comprar esse curso por cerca de R$27,90.

* Exam readiness aws certified solutions architect associate

É um curso construido pela aws e tem como foco a preparação para o exame, o que esperar no exame, como ele é estruturado e como interpretar as perguntas.

É um curso rápido que ensina interpretar as perguntas e entender a mecânica de como a aws constroe seus exames.

Link: https://aws.amazon.com/pt/training/classroom/exam-readiness-aws-certified-solutions-architect-associate/

De grátis, zero 800, na faixa, no vasco.

#### Simulados

* Simulado Exame Amazon AWS Solutions Architect SAA C02 - 2022, do Andre Iacono em inglês

Classificação: 4,7 de 5 (612 classificações) e 4.184 alunos.

Link: https://www.udemy.com/course/simulado-certificacao-amazon-aws-solutions-architect-2019/

Simulados com um total de 273 perguntas, com opções de responder sem tempo e com o tempo (para se aproximar do exame).

O ponto chave aqui é se testar frente ao que a prova pede e aprender com as questões, no final é possível ver a explicação de cada pergunta e isso é muito bom.

Durante as promoções na Udemy, é possível comprar esse curso por cerca de R$27,90.

* Practice Exams | AWS Certified Solutions Architect Associate do Stephane Maarek em inglês:

Classificação: 4,7 de 5(10.116 classificações) e 113.936 alunos

Simulados com um total de 390 perguntas com o tempo (para se aproximar do exame).

O ponto chave aqui é se testar frente ao que a prova pede e aprender com as questões, no final é possível ver a explicação de cada pergunta e isso é muito bom.

Durante as promoções na Udemy, é possível comprar esse curso por cerca de R$27,90.

#### Acesso a console

Ter acesso a uma conta ajuda bastante, é possível verificar fluxos de criação de recursos, como por exemplo criação de uma instância ec2, vpc sem gerar custo e isso pode ajudar muito durante o exame.

A aws ainda conta com inúmeros recursos com camada de uso gratuito. Aproveite.

#### Documentação

* AWS Well-Architected

Os pilares que sustentam a base teórica e prática (melhores) na aws:

Link: https://aws.amazon.com/architecture/well-architected/

* Shared responsibility model

Documentação que esclarece os limites de responsabilidade compartilhada entre a AWS e o cliente.

https://aws.amazon.com/pt/compliance/shared-responsibility-model/

* AWS Faq's

É sempre bom recorrer a essa doc para pegar pontos chaves de serviços básicos e recorrentes durante o exame:

https://aws.amazon.com/pt/faqs/

### Como você pode recuperar ?
Escrever resumo sobre os tópicos abordados
Fazer um video rápido para youtube

## Valide seu conhecimento

Um bom score nos simulados pode dar uma boa pista de como está o entendimento sobre os domínios.

### Investigação de contexto

### Pessoas que são autoridade sobre o tema

- Arquitetos de soluções
- Devops/Sre's
- Pessoas já certificadas

### Fontes de consumo fácil

[Se você já conhece outro provedor (azure, gcp) esse comparativo de serviços pode ajudar a fazer um "de para"](https://www.techtarget.com/searchcloudcomputing/feature/A-cloud-services-cheat-sheet-for-AWS-Azure-and-Google-Cloud)

[Repositório no github com um compilado super completo do exame](https://github.com/keenanromain/AWS-SAA-C02-Study-Guide)
