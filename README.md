# EDGE COMPUTING & COMPUTER SYSTEMS
Integrantes <BR> 1- Gabriel Oliveira Rodrigues RM98565 / ZeusBiel <BR>
2- Gabriel Riqueto RM98685 / gabriel-riqueto<BR>
3- Lucas Vinicius de Almeida Brigida RM99094 / Fr3die<BR>
4- Leandro Ferreira De Morais RM99064 / Lmorais04<BR>
5- Gustavo Bianchi Velonisqui dos Santos RM98534 / gbianchi07
## PROJETO PROPOSTO PARA GLOBAL-SOLUTION
# Objetivo do Projeto: 
O sistema utiliza tecnologia avançada para proporcionar uma irrigação eficiente e sustentável, otimizando o uso da água e reduzindo desperdícios.<br><br> Além de controlar a irrigação, o sistema também inclui um sensor de temperatura que mede a temperatura ambiente do local de cultivo.<br><br> O sensor de temperatura é conectado ao Arduino por meio de um pino analógico e realiza leituras periódicas, convertendo o valor lido em uma escala de 0 a 1023.<br><br> O valor da temperatura é mapeado para uma escala de 0 a 50 graus Celsius, fornecendo uma leitura precisa do ambiente de cultivo.<br><br> As informações de temperatura e umidade do solo são exibidas em um display LCD, permitindo que os agricultores monitorem as condições ambientais em tempo real.<br>O monitoramento da temperatura é essencial, pois afeta o metabolismo, a transpiração e a absorção de nutrientes das plantas, permitindo aos agricultores tomar medidas adequadas para garantir o crescimento saudável das plantas.<br><br> Com o sistema de irrigação automatizado e o monitoramento da temperatura, os pequenos agricultores podem obter maior produtividade, eficiência e sustentabilidade em suas operações agrícolas.
# Instruções de uso do sistema de irrigação automatizado com sensor de temperatura<br><br>
Instalação:<br> 1-Posicione o sensor de temperatura em um local representativo da área de cultivo, evitando áreas de sombra ou influências externas.<br> 2-Conecte o sensor de temperatura ao Arduino utilizando um pino analógico.<br>3-Conecte o Arduino ao sistema de irrigação e certifique-se de que todas as conexões estão corretas.<br><br>
Configuração:<br><br>
1-No código do Arduino, verifique se o sensor de temperatura está corretamente configurado e calibrado. Certifique-se de que os valores de leitura analógica estão mapeados corretamente para a escala de temperatura desejada.<br>
2-Certifique-se de que o display LCD esteja configurado corretamente para exibir as leituras de temperatura e umidade do solo.<br>
## LIGANDO O MOTOR CC
3- Caso você esteja utilizando um motor CC no sistema de irrigação, certifique-se de que ele esteja corretamente conectado ao Arduino, utilizando os pinos adequados.<br>
4- No código do Arduino, implemente a lógica de controle do motor CC. Isso pode envolver o uso de um driver de motor, como um L298N, para controlar a direção e velocidade do motor.<br>
5- Defina os parâmetros de controle do motor CC de acordo com as necessidades do sistema de irrigação, como a velocidade de rotação e a direção do motor.<br>
6- Realize testes para verificar se o motor CC está respondendo corretamente aos comandos do Arduino. Verifique se o motor gira na direção correta e se a velocidade está de acordo com as configurações definidas.<br>
7- Faça ajustes no código, se necessário, para otimizar o desempenho do motor CC e garantir um controle preciso da irrigação.<br>
8-Valvula solenoide ligada juntamente.
  ### Configurando o MOTOR CC
1- No código do Arduino, defina os pinos de controle do motor CC como saídas.<br>
2- Implemente a lógica de controle do motor CC no código, utilizando funções como analogWrite() para controlar a velocidade e digitalWrite() para controlar a direção.<br>
3- Defina os parâmetros de controle desejados, como a velocidade de rotação e a direção do motor.<br>
4- Realize testes para verificar se o motor CC está respondendo corretamente aos comandos do Arduino. Verifique se o motor gira na direção correta e se a velocidade está de acordo com as configurações definidas.<br>
5- Faça ajustes no código, se necessário, para otimizar o desempenho e a precisão do controle do motor CC.<br>

## Adicionando uma valvula solenoide à fonte de água e à área de irrigação da plantação
1-Posicione a válvula solenoide em um local adequado, próximo à fonte de água e à área de irrigação da plantação.<br>
2-Verifique a tensão de alimentação necessária para a válvula solenoide e certifique-se de ter uma fonte de energia adequada.<br
3-Conecte os fios de alimentação da válvula solenoide aos terminais apropriados do sistema de energia ou do driver de válvula solenoide.<br>
4-Se estiver utilizando um driver de válvula solenoide, conecte os fios de controle do driver ao Arduino, utilizando os pinos corretos.<br>
5- Certifique-se de que todas as conexões estejam firmes e seguras.<br>
6- Verifique se a válvula solenoide está corretamente fixada na tubulação de água, garantindo que não haja vazamentos ou obstruções que possam prejudicar seu funcionamento.
### Configurando a valvula solenoide
1- No código do Arduino, defina o pino de controle da válvula solenoide como uma saída.<br>
2- Implemente a lógica de controle da válvula solenoide no código, utilizando a função digitalWrite() para ligar e desligar a válvula.<br>
3- Identifique o momento em que o motor CC deve ser acionado para puxar a água da fonte.<br>
4- Antes de acionar o motor CC, abra a válvula solenoide utilizando digitalWrite() para permitir o fluxo de água para o sistema de irrigação.<br>
5- Em seguida, acione o motor CC utilizando as funções apropriadas, como analogWrite() e digitalWrite(), para controlar a velocidade e a direção do motor.<br>
6- Após um período adequado de irrigação, desligue o motor CC e feche a válvula solenoide utilizando digitalWrite().<br>



### Instalação![Captura de tela 2023-05-31 215709](https://github.com/Lmorais04/EDGE-COMPUTING/assets/127115198/5b4ed574-badc-4648-a8f8-cb591f3ed8fa)
  
[CODE ARDUINO.TXT](https://github.com/Lmorais04/EDGE-COMPUTING/files/11619896/CODE.ARDUINO.TXT)


  
Operação:<br><br>
  1-Ligue o sistema de irrigação e deixe-o funcionar automaticamente, de acordo com as configurações pré-determinadas.<br>
  2-Monitore o display LCD para visualizar as leituras de temperatura e umidade do solo.<br>
  3-Observe as leituras de temperatura para identificar possíveis condições inadequadas para o cultivo. Caso a temperatura esteja muito alta ou muito baixa, considere tomar medidas corretivas, como ajustar a irrigação ou adotar práticas de proteção das plantas.<br>
  4-Use as leituras de umidade do solo como um indicador para determinar a frequência e duração da irrigação. Mantenha o solo adequadamente umedecido, evitando excesso ou falta de água para as plantas.<br><br>
Manutenção:<br><br>
1-Verifique regularmente as conexões do sistema para garantir que estejam firmes e funcionando corretamente.<br>
2-Limpe o sensor de temperatura e o display LCD, se necessário, para evitar acúmulo de sujeira ou obstruções.<br>
3-Monitore o desempenho do sistema ao longo do tempo e faça ajustes nas configurações, se necessário, para melhor atender às necessidades do seu cultivo.
 
# Requisitos do sistema de irrigação automatizado com sensor de temperatura
 1-Sensor de temperatura<br> 2-Arduino ou dispositivo de controle<br> 3-Display LCD<br> 4-Sistema de irrigação<br> 5-Conexões e cabos<br> 6-Fonte de energia<br> 7-Calibração e programação<br> 8-Motor cc 12V<br> 9-Valvula solenoide



# Dependências e outras informações relevantes do sistema de irrigação automatizado com sensor de temperatura
1- Conexão com a rede elétrica: Verifique se há disponibilidade de uma fonte de energia elétrica estável e próxima do local de instalação do sistema. Caso contrário, será necessário utilizar baterias ou painéis solares para alimentar o sistema.<br><br> 2-Internet ou conectividade: Se a plataforma de controle do sistema de irrigação automatizado requer acesso à internet para comunicação ou atualização de dados, verifique se há uma conexão estável e confiável disponível no local.<br><br> 3-Instalação adequada: Certifique-se de seguir as instruções de instalação do sistema de irrigação automatizado e posicionar corretamente o sensor de temperatura no local de cultivo para obter leituras precisas e representativas.<br><br> 4-Calibração do sensor: É importante realizar a calibração do sensor de temperatura de acordo com as instruções do fabricante ou do sistema utilizado. Isso garantirá que as leituras sejam precisas e confiáveis.<br> 5-Manutenção regular: Para garantir o funcionamento adequado do sistema, é recomendado realizar manutenções regulares, como limpeza dos componentes, verificação de cabos e conexões, substituição de baterias, se aplicável, e calibração periódica do sensor de temperatura.<br><br> 6-Treinamento e familiarização: É recomendado que os usuários do sistema recebam treinamento adequado sobre o funcionamento, configuração e uso do sistema de irrigação automatizado com sensor de temperatura. Isso garantirá um uso eficiente e correto do sistema.<br><br> 7-Compatibilidade com outras tecnologias: Se o sistema de irrigação automatizado com sensor de temperatura for integrado a outras tecnologias ou plataformas, verifique a compatibilidade entre os diferentes componentes e sistemas para garantir uma operação integrada e eficaz.

## Como incluir biblioteca no arduino?<br><br>

![passo1](https://github.com/Lmorais04/EDGE-COMPUTING/assets/127115198/ee6f867e-ad76-45ca-a618-e7851a0b26e4)
![passo2](https://github.com/Lmorais04/EDGE-COMPUTING/assets/127115198/0c5a2514-47cd-452f-9218-a7693b206f6f)
![passo3](https://github.com/Lmorais04/EDGE-COMPUTING/assets/127115198/a47d254a-8c24-40e3-a062-0770b6ab596d)
![passo4](https://github.com/Lmorais04/EDGE-COMPUTING/assets/127115198/4ab22ee8-ce6c-4208-8b4e-4002c8161fa5)


## Como baixar o IDE arduino?
https://docs.arduino.cc/software/ide-v1/tutorials/Windows
 
## contribuição<br>
https://github.com/ZeusBiel<br>
https://github.com/Fr3die<br>
https://github.com/gabriel-riqueto<br>
https://github.com/gbianchi07<br>
 
 ## licença<br> 
https://github.com/ZeusBiel<br>
https://github.com/Fr3die<br>
https://github.com/gabriel-riqueto<br>
https://github.com/gbianchi07<br>








