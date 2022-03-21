Solução para implantação 3 máquinas virtuais Hyper V

Criando uma máquina virtual no Hyper-V

Primeiro será necessário habilitar o hyper-V no windows server 2008. Em seguinda, será necessário ir no menu Server Manager para iniciar
o gerenciamento. Podemos seguir o seguinte passo a passo: 

- Clicar em Start
- Administrative Tools
- Clicar em Server Manager
- Add Roles
- Adicionar a oção Hyper-V em roles
- selecionar uma placa de rede para a rede virtual
- Reiniciar o servidor

Após a máquina reiniciar vamos a criação da máquina virtual. Fazemos da seguinte forma.

- Acessar Server Manager

- Roles
- Hyper-V
- Hyper-V Manager
- Acessar o menu Action - New - Virtual Machine - Wizard
- Especificar o nome da VM
- Atribuir a quantidade de memória RAM
- Selecionar o adaptador de rede virtual
- Escolher usar um disco existente
- Realizar a configuração do sistema operacional
- Clicar em botão direito na VM
- Clicar em Settings
- Clicar em IDE Controller 1
- Selecionar a imagem do Sistema Operacional
- Clicar em Conectar a VM
- Ligar a VM
- Instalar o sistema operacional

Seguindo esse passo a passo, podemos ter o nosso sistema operacional em execulção.

Podemos ver que com a execução do hyper-v não é executada diretamente no Hardware. Em vez disso, ele é executado como um aplicativo em um S.O no 
nosso caso Windows 2008 Server. Esse é um tipo de Hypervisor tipo 2.

Configuração recomendada para um servidor suportar 3 máquinas virtuais:

- Servidor Dell PowerEdge T350 
- Memória 32Gb x DDR4
- Processador - Intel® Xeon® E-2324G (3.1 GHz, 8M Cache, 4 núcleos/4 threads, Turbo 65W, 3200 MT/s) 
- Unidade de Disco Rigido - SSD 1 TB
- Placa de Rede - Placa de Rede Placa de rede dual on-board, sem TOE 
- Serviço - 1 Ano de Suporte Básico
- Gerenciamento de Sistema Interno - IDRAC 9 Básico




