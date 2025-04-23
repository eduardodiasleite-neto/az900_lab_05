# az900_lab_05
 Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

1. Criando uma Máquina Virtual (VM) no Azure
Passo a Passo Básico:

1) Acessar o Portal do Azure:
Acesse o portal em portal.azure.com e clique em "Criar um recurso" > "Máquina Virtual".

2) Informações Básicas:
  Assinatura: Escolha a assinatura Azure que você usará.
  Grupo de Recursos: Escolha um grupo de recursos existente ou crie um novo para organizar os recursos.
  Nome da VM: Defina um nome único para a sua máquina virtual.
  Região: Escolha a região onde a VM será hospedada, levando em conta latência e compliance.

3) Escolha da Imagem do SO:
Você pode escolher imagens de sistemas operacionais como Windows Server, Ubuntu, Red Hat, etc.

4) Configuração de Autenticação:
Senha ou Chave SSH: Escolha o tipo de autenticação, seja uma senha para Windows ou uma chave SSH para Linux.

5) Tamanho da VM (Dimensionamento):
O Azure oferece uma grande variedade de tamanhos de máquinas virtuais, variando em termos de CPU, memória RAM e armazenamento. Você pode escolher entre tipos de VM como B-Series (custo-benefício), D-Series (uso geral), F-Series (mais foco em CPU), entre outros.

6) Configurações de Rede:
O Azure cria uma Virtual Network (VNet) por padrão, permitindo que sua VM se comunique com outros recursos dentro da mesma rede virtual.

7) Armazenamento:
Escolha o tipo de disco, como SSD Padrão ou SSD Premium, dependendo das necessidades de desempenho de sua aplicação.
Defina a quantidade de armazenamento necessário.

8) Configurações de Segurança:
Configure um Security Group (grupo de segurança) para controlar o tráfego de rede para a VM.
Se necessário, configure o acesso por IP público ou apenas por IP privado.

9) Revisão e Criação:
Após configurar todos os parâmetros, revise suas escolhas e clique em "Criar" para provisionar a VM.
