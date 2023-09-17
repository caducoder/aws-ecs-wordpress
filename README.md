# WordPress Stack - CloudFormation

Repositório com o template para criação de uma stack WordPress através da AWS CloudFormation. O template faz a criação dos seguintes recursos:

- Um cluster ECS para hospedar os containers do WordPress.
- Uma definição de tarefa que especifica como os containers do WordPress serão configurados.
- Um serviço ECS para garantir que a tarefa do WordPress seja sempre executada.
- Um balanceador de carga para distribuir o tráfego entre os containers.
- Configurações de dimensionamento automático para ajustar automaticamente o número de containers com base na carga.
- Um sistema de arquivos EFS para armazenar dados persistentes do WordPress.
- Banco de dados MySQL no RDS requerido pelo WordPress

