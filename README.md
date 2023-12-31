# Fonte-Retificadora-Ajustavel_Trabalho-USP
#### Disciplina de Eletrônica_2023

## Resumo do Projeto
Uma fonte retificadora ajustável de 3V a 12V que converte corrente alternada de 127V (com pico de cerca de 180V) em corrente contínua, permitindo selecionar a tensão de saída desejada. O projeto utiliza um circuito retificador, regulador de tensão e potenciômetro para fornecer energia flexível a dispositivos eletrônicos de baixa potência.

## Tabela de Preços
| Qtd. | Componentes         | Preço Unidade | Valor Total |
|-----:|:-------------------:| -------------:| -----------:|
| 2    | LED vermelho        | R$ 0,50       | R$ 1,00     |
| 1    | Diodo Zener (13v)   | R$ 0,65       | R$ 0,65     | 
| 1    | Potenciômetro 10k   | R$ 4,75       | R$ 4,75     |
| 10   | Diodo 1N4007        | R$ 0,20       | R$ 0,20     |
| 2    | Transistor BC337    | R$ 0,70       | R$ 1,40     |
| 10   | Resistor 2K2 Ω      | R$ 0,07       | R$ 0,70     |
| 10   | Resistor 1K Ω       | R$ 0,07       | R$ 0,70     |
| 10   | Resistor 100 Ω      | R$ 0,07       | R$ 0,70     |
| 10   | Resistor 4K7 Ω      | R$ 0,07       | R$ 0,70     |
| 1    | Resistor 120 Ω  1W  | R$ 0,00       | R$ 0,00     |
| -    | Valor total:        | -             | R$ 14,15    |

## Imagem do circuito
![Cirquito fonte](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/c41f07ee-a6f9-435e-9d52-1bffe82398d6)

## Link simulador no Falstad:
[Link simulador do circuito ](https://tinyurl.com/25djvyen)

## Funcionalidades
+ **Transformador:** O transformador é responsável pela primeira etapa da mudança de tensão, pois realiza a conversão da corrente alternada de 127V para uma tensão alternada de 12V. Por meio de princípios de indução eletromagnética, o transformador utiliza a relação de voltas nos enrolamentos primário e secundário para alcançar essa transformação. A variação do fluxo magnético no núcleo do transformador induz uma corrente elétrica proporcional no enrolamento secundário, resultando em uma tensão alternada de 12V. Dessa forma, o transformador mantém a corrente alternada, enquanto reduz a tensão de entrada para a saída desejada.

+ **Diodos cruzados, a Ponte de Diodos:** Próxima etapa para a mutação da corrente, é aproximá-la à corrente contínua (processo chamado de retificação) e, para isso, é indispensável o uso de uma ponte de diodos. Essa ponte, composta por quatro diodos, desempenha a função de bloquear o fluxo da corrente negativa em direção ao terra, forçando-a a seguir o mesmo caminho que a corrente positiva. Dessa forma, a corrente alternada é convertida em pulsos de corrente positiva constante.

+ **Capacitor:** Paralela à Ponte de Diodos, o capacitor realiza o processo de filtragem. O componente atua como um reservatório de carga temporária, carregando-se em pulsos de alta corrente e liberando carga durante o período de baixa corrente, suavisando os pulsos,  contribuindo para uma saída mais estável. 

+ **LED:** Indica se a fonte está ligada.

+ **Diodo Zener:** Esta peça "corta" qualquer aumento adicional na tensão quando atinge sua tensão Zener específica (no caso, 13V). Isso garante que a tensão de saída fique próxima ao valor desejado. No circuito em questão, onde a tensão máxima era de 12V, manter a tensão em torno de 13V é adequado. O diodo Zener é responsável por essa função de limitação, assegurando que a tensão não ultrapasse o valor desejado na saída.

+ **Potenciômetro:** Ele permite o controle do valor da tensão resultante entre 3V e 12V. Com o uso do potenciômetro, é possível ajustar a tensão de saída desejada dentro dessa faixa, proporcionando flexibilidade e controle preciso sobre a tensão fornecida pelo circuito. O potenciômetro atua como um dispositivo de ajuste, permitindo que o usuário defina a tensão desejada de acordo com as necessidades específicas do circuito ou dos dispositivos conectados

+ **Transistor:** A peça é utilizado para controlar a passagem da corrente de forma ajustável. Ao variar o sinal de entrada aplicado ao transistor, por meio do potenciômetro, é possível controlar a corrente que flui através dele e, consequentemente, a tensão de saída da fonte. 

+ **Carga - Resistor de 120 Ω:** Utilizada para comprovar e testar a fonte, isto é, não faz parte do circuito! Foi utilizado apenas para teste!

## Cálculos do capacitor:
![Calculo capacitor](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/706d73db-f02e-4e5a-b86e-ce2cc415eff1)

## Projeto do Esquemático e do PCB no EAGLE
### Imagem da impressão da placa
![Circuito da placa](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/361f6cd0-e0f1-41e7-8ebd-da1032864632)

### Imagem da impressão da placa com os componentes 
![Circuito na placa - Componentes](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/3d46e2ed-e801-4df5-9236-e6f3deb32221)

### Projeto do Esquemático
![Circuito Esquemático](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/97c5cdfa-10ec-4909-bbdf-4f3534e01178)

## Foto do projeto físico
![foto_circuito](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/ac912fa7-59f0-4263-bac3-51cfd4b172f0)

## Vídeo explicativo
(vídeo)

## Finalização
O projeto foi feito em 2023 no primeiro semestre do curso de BCC, da disciplina de Eletrônica,
na USP de São Carlos, lecionada pelo professor Eduardo do Valle Simoes. 




