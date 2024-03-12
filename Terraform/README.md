# Terraform

Recursos de infraestrutura em nuvem devem sempre ser criados utilizando gerenciadores de configuração, tais como Cloudformation, Terraform ou Ansible, garantindo que todo recurso possa ser versionado e recriado de forma facilitada.

# Objetivo

- Criar uma instância Linux utilizando Terraform.
- A instância deve ter aberta somente às portas 80 e 443 para todos os endereços.
- A porta SSH (22) deve estar acessível somente para um range IP definido.
- Inputs: A execução do projeto deve aceitar dois parâmetros:
  - O IP ou range necessário para a liberação da porta SSH
  - A região da cloud em que será provisionada a instância

- Outputs: A execução deve imprimir o IP público da instância

# Notas

- Todos os recursos devem ser criados utilizando os créditos gratuitos da AWS.
- Não esquecer de destruir os recursos após criação e testes do desafio para não haver cobranças ou esgotamento dos créditos.
