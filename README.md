# AWS-CLOUDFORMATION-VPC-SUBNET-RT-IGW-EC2-SG
Redes, instância e permissão SSH criados juntamente.

Faça download deste template "ec2-sg-vpc.yaml"; 
Entre na console AWS; 
CloudFormation; 
Stacks; Create stack; 
emplate is ready; 
Upload a template file; 
Selecione o template que foi feito download; 
E configure com o nome que deseja para sua Stack;
O acesso SSH está com permissão padrão para 0.0.0.0/0; 
O tipo da instância esta por padrão a t2.miro, mas se quiser pode alterar no "InstanceType" do .yaml; 
No código yaml você consegue liberar o Security Group para mais outras porta (acrescente um "XLocation" e um "IpProtocol" no "InstanceSecurityGroup");
Defina a rede da sua VPC e subnets no código do yaml se desejar;
Única coisa que precisa realmente selecionar ao subir sua stack para o Cloudformation é o "KeyPair".
