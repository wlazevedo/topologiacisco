# Configuração de Rede com Cisco Packet Tracer

## Cenário
Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

## Topologia
1. Crie uma nova topologia no Cisco Packet Tracer.
2. Arraste um switch para o centro da área de trabalho.
3. Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.

## Conexão dos Dispositivos
1. Conecte cada PC a uma porta diferente no switch usando cabos ethernet.
2. Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

## Configuração dos Endereços IP
1. Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP:
   - **PC-Membro-1**: FastEthernet0/1 - IP: 192.168.2.2
   - **PC-Membro-2**: FastEthernet1/1 - IP: 192.168.2.3
   - **PC-Membro-3**: FastEthernet2/1 - IP: 192.168.2.4
   - **PC-Membro-4**: FastEthernet3/1 - IP: 192.168.2.5
2. Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a sub-rede 192.168.2.0/24.

## Teste de Comunicação
1. Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe.
2. Abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.
3. O comando `ping` deve ser executado com sucesso, obtendo comunicação com os outros hosts.

## Conclusão
O laboratório foi configurado com 1 switch e 4 PCs, com os respectivos hostnames e endereços IP atribuídos. Todos os testes de comunicação foram bem-sucedidos, comprovando a configuração correta da rede.
