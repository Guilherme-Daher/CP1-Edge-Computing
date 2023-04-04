# Integrantes

Nomes:
Bruno Silva Bastos
Gabriel Freitas
Guilherme Daher
Matheus Lucas

Turma: ESPW1
Ano: 2023

# Objetivo
Vocês foram contratados pela Vinheria Agnello para desenvolver um sistema de monitoramento a ser instalado no ambiente em que os vinhos são armazenados. O dono a Vinheria informou que a qualidade do vinho é influenciada diretamente pelas condições de temperatura, umidade e luminosidade do ambiente. Neste primeiro momento, você propôs ao dono da Vinheria um projeto em etapas, de modo que seu 1° desafio é:

Elaborar um sistema usando Arduino que faça a captura das informações de luminosidade do ambiente. Para isso pesquise sobre o LDR. Verifique como eles funcionam e como poderiam ser usados no projeto.

De posse dos dados coletados, implemente um sistema de alarme, utilizando LEDs, para sinalizar quando o a ambiente estiver OK, ou quando alguma grandeza estiver fora dos limites estipulados. Use um LED verde para indicar que está OK, um LED amarelo para indica que está em níveis de alerta e um LED Vermelho para indicar que tem algum problema.

Quando a luminosidade estiver em nível de alerta, deve soar uma buzina (buzzer) por 3 segundos. A buzina volta a soar caso a luminosidade permaneça em nível de alerta.

# Descrição do desafio
  Foi proposto que desenvolvêssemos um projeto em arduíno que pudesse monitorar os níveis de luminosidade de uma vinheria e assim retornar
diferentes alertas sobre o status do vinho em descanso.

# Desenvolvimento do projeto
  Visto isso desenvolvemos um projeto que atendesse a esses requisitos, com 3 tipos de alertas sendo eles o estável(quando está tudo ok com a luminosidade), o alerta (quando o nível de luminosidade está subindo e se continuar pode prejudicar o projeto) e por último o nível de problema (quando o projeto está com luminosidade o suficiente para prejudicar as garrafas de vinho)

# Como foi desenvolvido o projeto?
  O projeto foi desenvolvido em conjunto usando o tinkercad, utilizamos 3 leds (verde, amarelo e vermelho) para indicar o status de luminosidade e um buzzer pra tocar
de um jeito em cada um dos casos, assim ao ligar o projeto ele indicará se a luminosidade está no status estável(luz verde, sem tocar o buzzer), se está no nível de alerta(luz amarela, tocando o buzzer por 2 segundos a cada 3 segundos) e por último o status de problema(luz vermelha, com o buzzer apitando até que seja arrumada a luminosidade).
  
# Como executar o projeto
  https://www.tinkercad.com/things/fv3xi54HsJ2-brilliant-stantia-gaaris/editel
  
# Quais são os passos a serem realizados para executar o projeto?
  entrando neste link a cima vc terá acesso ao projeto, iniciando simulação você terá o projeto no status estável, clique no sensor LDR e vá aumentando a quantidade de luz recebida pelo simulador para que o projeto ative os outros modos
  
# Pré-requisitos
  É preciso ter uma conta no Autodesk Tinkercad para simular o projeto
No projeto foram usados:
1 Arduíno Uno R3 e 1 protoboard
4 resistores, 3 de 220Ω e 1 de 10kΩ
1 Sensor LDR
1 Piezo
3 LEDs 1 vermelho, 1 verde e 1 amarelo 
  
# Video Explicativo
  
  
