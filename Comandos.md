## Comandos para você explorar todas as funcionalidades dos binários do Zabbix Agent + Recursos demonstrados na apresentação

## Como rastrear os contadores de performance do Windows

Basta executar o comando:

  ### typeperf -qx
  
E terás listado todos os contadores disponíveis para aquele host Windows. Melhor que isto, pode combinar um parâmetro para estas informações em console irem para um arquivo do tipo texto:

  ### typeperf -qx -q -o NOMEDOARQUIVO.txt:
  
Como auxiliar, se tens acesso ao host, pode utilizar o próprio Monitor de Desempenho para auxiliar no processo e entendimento inclusive de formas de retorno do valor e o path.
Basta ativar o gerenciador indo ao Executar do Windows (ou Win+R) e digitar "mmc" e depois Enter.

Feito isto, vá até Arquivo > Adicionar/Remover Snap-in

Em Snap-ins disponíveis, selecione "Monitor de Desempenho" e clique em "Adicionar". Depois clique em "OK".

Terás adicionado o console para poder utilizar. Então de Raíz do Console, vá até "Desempenho (Local)" > Ferramentas de Monitoramento > Desempenho do Sistema.

E voilá! Agora está disponível um belo recurso para te ajudar a trabalhar/mapear contadores de performance do Windows e viabilizar a criação de monitoramentos personalizados no Zabbix conforme sua necessidade.

  
