# Plano de Estudo sobre a certificação aws solution architect

### Objetivo de aprendizagem

Adquirir o conhecimento necessário para obter a certificação aws solution architect

A preparação e a obtenção desta certificação demonstrarão:

* Conhecimento e habilidades em computação, rede, armazenamento e serviços de banco de dados da AWS, bem como serviços de implantação e gerenciamento da AWS

* Conhecimento e habilidades em implementação, gerenciamento e operação de workloads na AWS, bem como na implementação de controles de segurança e requisitos de conformidade

* Conhecimento e habilidades no uso do Console de Gerenciamento da AWS e da Interface da Linha de Comando (CLI) da AWS, 
compreensão do AWS Well-Architected Framework, da rede da AWS, dos serviços de segurança e da infraestrutura global da AWS

* Capacidade para identificar quais serviços da AWS atendem a um determinado requisito técnico e definir requisitos técnicos para uma aplicação baseada em AWS

### Por quê obter a certificação AWS Certified Solutions Architect - Associate (motivação do plano de estudo)

Existem várias razões pelas quais alguém poderia optar por obter a certificação AWS Certified Solutions Architect - Associate:

- Validação de habilidades: a certificação demonstra que o indivíduo tem conhecimento e experiência em projetar soluções na nuvem usando o Amazon Web Services.

- Destaque no mercado de trabalho: a certificação AWS é amplamente reconhecida e procurada por empregadores em todo o mundo. Ter a certificação pode ajudar a se destacar entre outros candidatos.

- Aumento de salário: os profissionais certificados geralmente têm salários mais elevados do que aqueles sem certificação.

- Oportunidades de crescimento profissional: a certificação pode abrir novas oportunidades de carreira para aqueles que buscam crescimento profissional na área de nuvem.

- Atualização de habilidades: obter a certificação exige que o indivíduo mantenha-se atualizado com as últimas tendências e tecnologias na nuvem.

### Pré requisitos

Não há pré-requisitos oficiais exigidos pela Amazon para obter a certificação AWS Certified Solutions Architect - Associate, mas é recomendável ter alguma experiência prévia em projetar e implementar soluções na nuvem. Algumas dicas incluem:

- Conhecimento prévio de infraestrutura de nuvem: ter familiaridade com conceitos de nuvem, como alta disponibilidade, escalabilidade, segurança, entre outros.

- Conhecimento básico de serviços AWS: entender os serviços AWS mais comuns, como EC2, S3, VPC, entre outros.

- Experiência prática: praticar projetando e implementando soluções na nuvem usando o AWS pode ser útil antes de realizar a prova de certificação.

Em geral, a Amazon sugere que os candidatos tenham alguma experiência em projetar soluções em nuvem antes de se prepararem para a certificação. Além disso, existem muitos cursos e recursos de treinamento disponíveis online que podem ajudar a se preparar para a prova.

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

		- Tópicos chave:

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
				- Conceitos básicos

			- AWS Snowball
				- Conceitos básicos

Esse domínio habilita competências em (habilidades ganhas com o tópico apresentado):

- Aplicar as práticas recomendadas de segurança da AWS a usuários do IAM e usuários-raiz (por exemplo, autenticação com multifator [MFA]).

- Projetar um modelo de autorização flexível que inclua usuários, grupos, funções e políticas do IAM.

- Projetar uma estratégia de controle de acesso baseada em função (por exemplo, AWS Security Token Service [AWS STS], mudança de função, acesso entre contas).

- Projetar uma estratégia de segurança para várias contas da AWS (por exemplo, AWS Control Tower, políticas de controle de serviço [SCPs]).

- Determinar o uso apropriado de políticas de recursos para os serviços da AWS.

- Determinar quando federar um serviço de diretório com funções do IAM.

- Projetar arquiteturas de VPC com componentes de segurança (por exemplo, security groups, tabelas de rotas, ACLs de rede, gateways NAT).

- Determinar estratégias de segmentação de rede (por exemplo, usando sub-redes públicas e privadas).

- Integrar serviços da AWS para proteger aplicativos (por exemplo, AWS Shield, AWS WAF, AWS SSO, AWS Secrets Manager).

- Proteger conexões de rede externas de e para a nuvem AWS (por exemplo, VPN, AWS Direct Connect).

- Alinhar as tecnologias da AWS para atender aos requisitos de conformidade.

- Criptografia de dados em repouso (por exemplo, AWS Key Management Service [AWS KMS]).

- Criptografia de dados em trânsito (por exemplo, AWS Certificate Manager [ACM] usando TLS).

- Implementar políticas de acesso para chaves de criptografia.

- Implementar backups e replicações de dados.

- Implementar políticas para acesso, ciclo de vida e proteção de dados.

- Alternar chaves de criptografia e renovar certificados.

- Design de arquiteturas resilientes

	- Tópicos chave:

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

Esse domínio habilita competências em (habilidades ganhas com o tópico):

- Projetar arquiteturas orientadas por eventos, microsserviços e/ou multicamadas com base em
requisitos.

- Determinar estratégias de scaling para componentes usados em um projeto de arquitetura.

- Determinar os serviços da AWS necessários para obter um acomplamento fraco com base em
requisitos.

- Determinar quando usar contêineres.

- Determinar quando usar tecnologias e padrões sem servidor.

- Recomendar tecnologias apropriadas de computação, armazenamento, redes e banco de dados com base em requisitos.

- Usar serviços da AWS com propósito específico para cargas de trabalho.

- Determinar estratégias de automação para garantir a integridade da infraestrutura.

- Determinar os serviços da AWS necessários para fornecer uma arquitetura altamente disponível e/ou tolerante a falhas nas Zonas de Disponibilidade ou Regiões AWS.

- Identificar métricas com base nos requisitos empresariais para oferecer uma solução altamente
disponível.

- Implementar designs para mitigar pontos únicos de falha.

- Implementar estratégias para garantir a durabilidade e a disponibilidade dos dados (por
exemplo, backups).

- Selecionar uma estratégia de DR apropriada para atender aos requisitos empresariais.

- Usar serviços da AWS que melhoram a confiabilidade de aplicativos legados e aplicativos que não foram criados para a nuvem (por exemplo, quando não é possível fazer alterações nos
aplicativos).

- Usar serviços da AWS com propósito específico para cargas de trabalho.

- Design de arquiteturas de alta performance

	- Tópicos chave
		- Amazon RDS
			- Tipos de banco de dados
			- Alta disponibilidade
			- Read Réplicas
			- Aurora Serveless
			- Backup

		- Dynamodb
			- Custo
			- Cache
			- throughput

		- Elasticache
			- Redis
			- Memcache

		- Cloudfront
			- Caching
			- Origins
			- Lambda Edg
			
		- Containers
			- eks
			- ecs
			- ecr

Esse domínio habilita competências em (habilidades ganhas com o tópico):	

- Determinar quais serviços e configurações de armazenamento atendem às demandas de desempenho.

- Determinar quais serviços de armazenamento que podem ser dimensionados para atender às necessidades futuras.

- Desacoplar cargas de trabalho para que os componentes possam ser dimensionados de forma independente.

- Identificar métricas e condições para realizar ações de scaling.

- Selecionar as opções e os recursos de computação apropriados (por exemplo, tipos de instância do EC2) para atender aos requisitos empresariais.

- Selecionar o tipo e o tamanho de recurso apropriados (por exemplo, a quantidade de memória do Lambda) para atender aos requisitos empresariais.

- Configurar réplicas de leitura para atender aos requisitos empresariais.

- Projetar arquiteturas de banco de dados.

- Determinar um mecanismo de banco de dados apropriado (por exemplo, MySQL em comparação com o PostgreSQL).

- Determinar um tipo de banco de dados apropriado (por exemplo, Amazon Aurora, Amazon DynamoDB).

- Integrar o armazenamento em cache para atender aos requisitos empresariais.

- Criar uma topologia de rede para várias arquiteturas (por exemplo, global, híbrida, multicamadas).

- Determinar quais configurações de rede podem ser dimensionadas para acomodar necessidades futuras.

- Determinar o posicionamento adequado dos recursos para atender aos requisitos empresariais.

- Selecionar a estratégia de balanceamento de carga apropriada.

- Criar e proteger data lakes.

- Projetar arquiteturas de streaming de dados.

- Projetar soluções de transferência de dados.

- Implementar estratégias de visualização.

- Selecionar opções de computação apropriadas para processamento de dados (por exemplo, Amazon EMR).

- Selecionar configurações apropriadas para ingestão.

- Transformar dados entre formatos (por exemplo, .csv para .parquet).

- Design de arquiteturas econômicas
  	
	- Calculadora aws
	- Modelos de instâncias ec2 e custos (on demand, spot...)
	- Qual modelo de armazenamento utilizar e seus custos (ebs, rds, s3...)
    - Melhor solução X Custo beneficio

Esse domínio habilita competências em (habilidades ganhas com o tópico):	

- Projetar estratégias de armazenamento apropriadas (por exemplo, fazer upload em lote para o Amazon S3 em comparação com upload individual).

- Determinar o tamanho de armazenamento correto para uma carga de trabalho.

- Determinar o método de menor custo de transferência de dados de uma carga de trabalho para o armazenamento da AWS.

- Determinar quando o auto scaling de armazenamento é necessário.

- Gerenciar ciclos de vida de objetos do S3.

- Selecionar a solução apropriada de backup e/ou arquivamento.

- Selecionar o serviço apropriado para a migração de dados aos serviços de armazenamento.

- Selecionar o nível de armazenamento apropriado.

- Selecionar o ciclo de vida de dados correto para armazenamento.

- Selecionar o serviço de armazenamento mais econômico para uma carga de trabalho.

- Determinar uma estratégia de balanceamento de carga apropriada (por exemplo, Application Load Balancer [camada 7] em comparação com o Network Load Balancer [camada 4] em comparação com o Gateway Load Balancer).

- Determinar métodos e estratégias de scaling apropriados para cargas de trabalho elásticas (por exemplo, horizontal em comparação com vertical, hibernação do EC2).

- Determinar serviços de computação da AWS econômicos com casos de uso apropriados (por exemplo, Lambda, Amazon EC2, Fargate)

- Determinar a disponibilidade necessária para diferentes classes de cargas de trabalho (por exemplo, cargas de trabalho de produção e de não produção)

- Escolher a família de instâncias apropriada para uma carga de trabalho.

- Escolher o tamanho de instância apropriado para uma carga de trabalho.

- Projetar políticas de backup e retenção apropriadas (por exemplo, frequência de snapshots).

- Determinar um mecanismo de banco de dados apropriado (por exemplo, MySQL em comparação com o PostgreSQL).

- Determinar serviços de banco de dados da AWS econômicos com casos de uso apropriados (por exemplo, DynamoDB em comparação com o Amazon RDS, sem servidor).

- Determinar tipos de banco de dados da AWS econômicos (por exemplo, formato de série
temporal, formato colunar).

- Migrar esquemas e dados de banco de dados para diferentes locais e/ou diferentes mecanismos de banco de dados.

- Configurar tipos de gateway NAT apropriados para uma rede (por exemplo, um único gateway NAT compartilhado em comparação com gateways NAT para cada Zona de Disponibilidade).

- Configurar conexões de rede apropriadas (por exemplo, Direct Connect em comparação com a VPN e com a Internet).

- Configurar rotas de rede apropriadas para minimizar os custos de transferência de rede (por exemplo, região para região, Zona de Disponibilidade para Zona de Disponibilidade, privado para público, Global Accelerator, endpoints de VPC).

- Determinar necessidades estratégicas para redes de entrega de conteúdo (CDNs) e cache de borda.

- Analisar as cargas de trabalho para otimizações de rede.

- Selecionar uma estratégia de limitação de largura de banda apropriada.

- Selecionar a alocação de largura de banda apropriada para um dispositivo de rede (por exemplo, uma única VPN em comparação com várias VPNs, velocidade do Direct Connect).

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

AWS Well-Architected

- [Os pilares que sustentam a base teórica e prática (melhores) na aws](https://aws.amazon.com/architecture/well-architected/)

Shared responsibility model

- [Documentação que esclarece os limites de responsabilidade compartilhada entre a AWS e o cliente](https://aws.amazon.com/pt/compliance/shared-responsibility-model/)

AWS Faq's

- [Perguntas frequentes de todos os serviços da aws](https://aws.amazon.com/pt/faqs/)

Design de arquiteturas seguras

- [Principios de design](https://wa.aws.amazon.com/wat.pillar.security.pt_BR.html)

- [Fundamentos de segurança](https://aws.amazon.com/pt/faqs/)

Design de arquiteturas resilientes

- [Excelência operacional](https://wa.aws.amazon.com/wat.pillar.operationalExcellence.pt_BR.html)

- [Abordagem da Amazon Web Services à resiliência operacional no setor financeiro e além](https://d1.awsstatic.com/whitepapers/pt_BR/compliance/AWS_Operational_Resilience.pdf)

- [Arquiteturas Resilientes na Nuvem](https://thedevconf.s3-sa-east-1.amazonaws.com/presentations/TDC2021ED1/arquitetura/WVZ-4948_2021-03-25T035900_TDC+-+Arquiteturas+resilientes+na+nuvem+v3.pdf)

Design de arquiteturas de alta performance

- [Eficiência de performance](https://wa.aws.amazon.com/wat.pillar.performance.pt_BR.html)

Design de arquiteturas econômicas

- [Otimização de custos](https://wa.aws.amazon.com/wat.pillar.costOptimization.pt_BR.html)

- [Recursos econômicos](https://docs.aws.amazon.com/pt_br/wellarchitected/latest/framework/a-cost-effective-resources.html)

### Como você pode recuperar ?

Escrever resumo sobre os tópicos chave e ou serviços abordados e compara-los com demais cloud providers

Fazer um video rápido para youtube sobre tópicos chaves e ou serviços abordados

## Valide seu conhecimento

Um bom score nos simulados pode dar uma boa pista de como está o entendimento sobre os domínios.

### Investigação de contexto

### Pessoas que são autoridade sobre o tema

Deivid Bitti Padilha  (CEO / CTO Flexa Cloud) 

Linkedin: https://www.linkedin.com/in/deividbitti/

Twitter: https://twitter.com/bittix

Leonardo Silva dos Santos (Especialista Devops) 

Linkedin: https://www.linkedin.com/in/rmnobarra/
Twitter: https://twitter.com/rmnobarra

### Fontes de consumo fácil

[Se você já conhece outro provedor (azure, gcp) esse comparativo de serviços pode ajudar a fazer um "de para"](https://www.techtarget.com/searchcloudcomputing/feature/A-cloud-services-cheat-sheet-for-AWS-Azure-and-Google-Cloud)

[Repositório no github com um compilado super completo do exame](https://github.com/keenanromain/AWS-SAA-C02-Study-Guide)
