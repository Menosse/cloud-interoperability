# cloud-interoperability
# Desafio - Cloud Platform Infraestructure
O arquivo desafio.yaml cria o ambiente solicitado no desafio da aula de mba Cloud & DevOps - Cloud Platform Infraestructure.
![Alt text](https://raw.githubusercontent.com/Menosse/cloud-interoperability/main/Screen%20Shot%202021-08-23%20at%2011.06.59.png)
1. Logar no ambiente Sandbox do AWS academy
2. Apagar Instancias e VPCs criadas por padrão
3. Acessar o serviço CloudFormation
4. Utilizar o arquivo desafio.yaml para provisionar os recursos

## Recursos provisionados
- 1 VPC
- 1 Internet Gateway (associada a VPC criada)
- 3 Public Subnets
- 3 Private Subnets
- 3 Nat Gateways
- 3 ElasticIp (allocados aos Nat Gateways)
- 1 Route table publica
- 3 Route table privada
- 2 security groups
- 1 Load balancer classico
- 1 Launch Config
- 1 Auto Scaling Group (para o launch config)
