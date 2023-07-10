# Fonte-Retificadora-Ajustavel_Trabalho-USP
#### Disciplina de Eletrônica_2023

## Resumo do Projeto
Uma fonte retificadora ajustável de 3V a 12V que converte corrente alternada de 127V (com pico de cerca de 180V) em corrente contínua, permitindo selecionar a tensão de saída desejada. O projeto utiliza um circuito retificador, regulador de tensão e potenciômetro para fornecer energia flexível a dispositivos eletrônicos de baixa potência.

## Tabela de Preços
| Qtd. | Componentes         | Preço Unidade | Valor Total |
|-----:|:-------------------:| -------------:| -----------:|
| 2    | LED vermelho        | R$ 0,50       | R$ 1,00     |
| 1    | Diodo Zener (13v)   | R$ 0,65       | R$ 0,65     | 
| 1    | Capacitor 470uF 25V | R$ 1,20       | R$ 1,20     |
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
![Circuito - Falstad](https://github.com/eduda-agc/FonteRetificadoraAjustavel-Trabalho-USP/assets/137100218/31f3f68e-4767-416d-ac14-bc1269d75910 "Circuito pelo Falstad")

## Funcionalidades
+ **Transformador:** O transformador é responsável pela primeira etapa da mudança de tensão, pois realiza a conversão da corrente alternada de 127V para uma tensão alternada de 12V. Por meio de princípios de indução eletromagnética, o transformador utiliza a relação de voltas nos enrolamentos primário e secundário para alcançar essa transformação. A variação do fluxo magnético no núcleo do transformador induz uma corrente elétrica proporcional no enrolamento secundário, resultando em uma tensão alternada de 12V. Dessa forma, o transformador mantém a corrente alternada, enquanto reduz a tensão de entrada para a saída desejada.

+ **Diodos cruzados, a Ponte de Diodos:** Próxima etapa para a mutação da corrente, é aproximá-la à corrente contínua (processo chamado de retificação) e, para isso, é indispensável o uso de uma ponte de diodos. Essa ponte, composta por quatro diodos, desempenha a função de bloquear o fluxo da corrente negativa em direção ao terra, forçando-a a seguir o mesmo caminho que a corrente positiva. Dessa forma, a corrente alternada é convertida em pulsos de corrente positiva constante.

+ **Capacitor:** Paralela à Ponte de Diodos, o capacitor realiza o processo de filtragem.

+ **LED:**

+ **Diodo Zener:**

+ **Potenciômetro:**

+ **Transistor:**

+ **Carga - Resistor de 120 Ω:**

##Cálculos do capacitor:
(Imagem dos cálculos)

##Link simulador no Falstad:
[Link simulador do circuito ](https://tinyurl.com/25djvyen)

## Projeto do Esquemático e do PCB no EAGLE
(imagem)

## Foto do projeto físico
(imagem pega do vídeo)

## Vídeo explicativo
(vídeo)






