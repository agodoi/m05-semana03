# Atendimento do Professor

## Terças e quintas. Professor de horário parcial. Nesses 2 dias, podem contar comigo!

# Semama 03 - Semicondutores e Diodos

## Impactos no seu Projeto

* Proteção dos seus circuitos
* Construção de fontes retificadoras

# 1. Introdução

A eletrônica moderna é construída com base em componentes semicondutores, sendo os **diodos** um dos dispositivos fundamentais em diversos circuitos.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/atlas1.png" width="300">

Eles desempenham um papel essencial no controle do fluxo de corrente elétrica, permitindo sua passagem em apenas uma direção e bloqueando-a na outra.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo2.png" width="300">

## Comportamento do Diodo

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo1.gif" width="300">

* Quando o positivo da bateria está conectado no positivo do diodo, dizemos que o diodo está polarizado diretamente e por isso, ele está conduzindo a corrente.

* Quando o positivo da bateria está conectado no negativo do diodo, ele está polarizado reversamente e por isso, ele está conduzindo praticamente nada.


## Do que é feito o Diodo?

**O diodo é feito de semicondutor**.


- **Condutores:** são materiais que permitem a livre movimentação dos elétrons, facilitando a condução elétrica. Exemplos comuns incluem **cobre, prata e alumínio**, amplamente utilizados em fios e trilhas de circuitos eletrônicos. Resumindo: condutor é que possui elétrons livres na sua camada de valência.

- **Isolantes:** são materiais que **não permitem** a passagem de corrente elétrica facilmente, pois possuem poucos elétrons livres. Exemplos incluem **borracha, vidro e plástico**, usados como revestimentos protetores. Resumindo: isolante mal possui elétrons livres na sua camada de valência.

- **Semicondutores:** possuem uma condutividade intermediária entre condutores e isolantes. O **silício** e o **germânio** são os semicondutores mais utilizados na eletrônica, pois podem ser manipulados para conduzir eletricidade de maneira controlada. Resumindo: semicondutor possui mais ou menos elétrons livres na sua camada.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/atomos.png" width="400">


A principal característica dos semicondutores é a capacidade de serem **dopados** no momento da fabricação.

**Dopagem** é um processo no qual pequenas quantidades de impurezas são adicionadas para modificar suas propriedades elétricas. 

Esse processo possibilita a criação da **junção PN**, que é a base para o funcionamento dos diodos.

## **1.2 Importância dos Diodos na Eletrônica**

Os diodos são componentes semicondutores que possuem **dois terminais: anodo e catodo**. Seu principal comportamento é permitir a passagem de corrente elétrica quando polarizados diretamente e bloqueá-la quando polarizados reversamente. Essa propriedade os torna essenciais em várias aplicações, como:

- **Retificação de corrente alternada:** transformação de corrente alternada (CA) em corrente contínua (CC), essencial para fontes de alimentação.
- **Proteção de circuitos:** evitam danos causados por inversão de polaridade ou surtos de tensão.
- **Chaveamento eletrônico:** utilizados para controlar sinais em alta velocidade.
- **Diodos emissores de luz (LEDs):** dispositivos que convertem energia elétrica em luz visível.

## **1.3 Aplicações Práticas**

A eletrônica digital e analógica faz amplo uso dos diodos, como:

- **Fontes de alimentação** para dispositivos eletrônicos.
- **Carregadores de bateria** que impedem a corrente reversa.
- **Sensores ópticos e fotodiodos** usados em câmeras e sistemas de automação.

## Junção PN

A **junção PN** é a base para o funcionamento dos semicondutores, sendo o princípio de operação de dispositivos eletrônicos como **diodos, transistores e circuitos integrados**. 

Ela é formada pela combinação de dois tipos diferentes de semicondutores: **tipo P** (positivo) e **tipo N** (negativo). 

Essa estrutura cria uma região de transição onde ocorrem fenômenos físicos importantes para o controle do fluxo de corrente elétrica.

### 1. Formação da Junção PN

Como já visto, a junção PN é criada quando um material semicondutor (geralmente **silício** ou **germânio**) passa por um processo chamado **dopagem**, no qual átomos de impurezas são adicionados intencionalmente para modificar suas propriedades elétricas.

### 1.1 Semicondutor Tipo N

No semicondutor **tipo N**, o silício puro (Si) ou germânio (Ge) é dopado com um material do **grupo V da Tabela Periódica**, como **fósforo (P), arsênio (As) ou antimônio (Sb)**. Esses átomos possuem **cinco elétrons de valência**, um a mais do que o necessário para formar ligações covalentes com o silício. Esse **elétron extra** fica fracamente ligado ao átomo dopante e pode se mover livremente pela estrutura do material, tornando-se um **portador de carga negativa (elétron livre)**.

### 1.2 Semicondutor Tipo P

No semicondutor **tipo P**, o silício ou germânio é dopado com elementos do **grupo III da Tabela Periódica**, como **boro (B), alumínio (Al) ou gálio (Ga)**. Esses átomos possuem **apenas três elétrons de valência**, o que resulta em uma **falta de um elétron** nas ligações covalentes, criando um **espaço vazio** ou **lacuna**. Essa lacuna pode ser preenchida por elétrons de átomos vizinhos, permitindo o deslocamento da carga positiva através do material.


## 2. Formação da Camada de Depleção

Quando um semicondutor tipo P é colocado em contato com um semicondutor tipo N, os portadores de carga começam a se mover espontaneamente devido à **diferença na concentração de elétrons e lacunas** entre os dois materiais.

### **2.1 Difusão de Cargas**
- Elétrons livres da **região N** começam a se difundir para a **região P**, preenchendo as lacunas.
- Da mesma forma, lacunas da **região P** migram para a **região N**, sendo preenchidas por elétrons disponíveis.

### **2.2 Formação da Barreira de Potencial**
À medida que os elétrons e lacunas se recombinam na interface entre as duas regiões, forma-se uma **zona empobrecida de portadores de carga** chamada de **camada de depleção**. Essa camada atua como uma **barreira de potencial**, impedindo a passagem livre de cargas adicionais.

- Como resultado da migração inicial de cargas, a região próxima à interface na **região N** fica **carregada positivamente** (pois perdeu elétrons), e a região próxima na **região P** fica **carregada negativamente** (pois perdeu lacunas, ou seja, ganhou elétrons).
- Essa separação de cargas gera um **campo elétrico interno** que impede a difusão contínua de elétrons e lacunas.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/camada_deplecao.jpg" width="400">

A diferença de potencial criada entre as regiões P e N é conhecida como **tensão de barreira**, que é aproximadamente:
- **0,7V para semicondutores de silício (Si)**
- **0,3V para semicondutores de germânio (Ge)**

Essa barreira impede o fluxo espontâneo de corrente elétrica quando não há uma fonte externa de energia aplicada.


## 3. Polarização da Junção PN

A junção PN pode ser polarizada de duas formas distintas: **polarização direta** e **polarização reversa**.

### 3.1 Polarização Direta
Quando aplicamos uma **tensão externa positiva** no terminal P e **negativa** no terminal N, a barreira de potencial é reduzida, permitindo o fluxo de corrente elétrica.

- O potencial positivo empurra as lacunas da **região P** em direção à junção.
- O potencial negativo empurra os elétrons da **região N** em direção à junção.
- Quando a tensão aplicada supera a barreira de potencial (~0,7V para Si e ~0,3V para Ge), os portadores atravessam a junção e a corrente flui livremente.

**Consequências:**
- O diodo conduz corrente elétrica.
- A resistência da junção PN diminui significativamente.

### 3.2 Polarização Reversa
Quando aplicamos uma **tensão externa negativa** no terminal P e **positiva** no terminal N, a barreira de potencial **aumenta**, dificultando a passagem da corrente elétrica.

- O potencial positivo na **região N** atrai mais elétrons para longe da junção.
- O potencial negativo na **região P** atrai mais lacunas para longe da junção.
- A camada de depleção **se expande**, aumentando a resistência do diodo.

**Consequências:**
- A corrente praticamente **não flui** (apenas uma pequena corrente de fuga devido a elétrons minoritários).
- O diodo atua como um **interruptor aberto**.

Se a tensão reversa for aumentada além do limite máximo do componente, ocorre a **avalanche** ou **ruptura** do diodo, levando à condução reversa intensa e, em alguns casos, à destruição do componente.

## Sabe a resposta?

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/test_your_luck.jpg" width="400">

### Qual lâmpada do circuito abaixo vai acender?

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo3.png" width="400">


## Curva Característica do Diodo Real vs Real

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo4.png" width="600">





## Prática (1) - Dominando o Oscilocópio

O Oscila server para você analisar sinais no domínio do tempo. Sua tela é organizada em X e Y, sendo X o eixo dos tempos, em Y o eixo de Volts.

Os botões mais usados:

* **AUTO** serve para ajustar o sinal automaticamente no centro da tela
* **CH1** serve para habilitar/desabilitar o canal 1. Você pode ligar/desligar o canal 1 pressionando esse botão por 1 ou 2s
* **CH2** serve para habilitar/desabilitar o canal 2.
* **F1** serve para habilitar/desabilitar o tipo de acomplamento do sinal. DC serve para ler sinais contínuos, AC serve para ler sinais contínuos e alternados, GND serve para aterrar o sinal de entrada. Você faz isso calibrar o sinal no meio da tela manualmente
* **SET TO ZERO** serve para centrar os sinais no meio da tela de forma automática
* **SCALE VOLTS** serve para configurar quanto vale 1 quadradinho da tela no eixo vertical
* **SCALE SEC** serve para configurar quanto vale 1 quadradinho da tela no eixo horizontal

Siga as orientações do professor para fazer a sua primeira medição no oscilas.


## Prática (2) - Dominando o Gerador de Sinais

Esse equipamento serve para você gerar sinais senoidais, onda quadrada e onda triangular, com diversas frequências e amplitudes.

Os botões mais usados são todos :)

* **RANGE (Hz)/GATE** server para você escolher a frequência do sinal de saída. Exemplo: selecionando **X2k** você vai ter frequência de **0 até 2kHz**. Se pressionar **X20k**, você terá de **0 até 20k Hz**
* **FUNCTION**, você escolhe o tipo de sinal. Os possíveis são: senoidal, quadrado e triangular.
* **ATT**, você aplica uma redução do sinal de saíde de 20dB ou 40dB
* **FREQUENCY**, você ajusta a frequência do sinal
* **AMPL**, você ajusta a amplitude do sinal. Esse gerador libera de 0 até 10.9Vp ou 21,8Vpp



## Prática (3) - Teste de Condutividade do Diodo

## Nessa aula prática, vamos montar um relatório organizado e registrar os valores medidos e calculados

### 1) Configuração do Multímetro:

* Ajustar o multímetro para o modo "Teste de Diodo" ou medição de tensão DC. Quando você está na escala de Diodo, o resultado na tela é sempre Volts.
* Medição do Diodo:
*    Conectar as pontas de prova do multímetro nos terminais do diodo:
*    Vermelho no ânodo e preto no cátodo (polarização direta).
*    Preto no ânodo e vermelho no cátodo (polarização reversa).

### Responda:

* (a) O que aconteceu com o valor da tensão na polarização direta?
* (b) O que aconteceu com o valor da tensão na polarização reserva?
* (c) O que aconteceu com o sinal sonoro na polarização direta?
* (d) O que aconteceu com o sinal sonoro na polarização reserva?

## Prática (4) - Teste de Retificação do Diodo


Monte o circuito abaixo usando 1 diodo **(D)** 1N4007, resistor **(R)** de 1k ohms e um protoboard pequeno.

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/oscilas-01.png" width="600">

No desenho há 2 telas de osciloscópio, mas na sua bancada, você vai usar 2 canais **CH1** e **CH2** no mesmo osciloscópio.

[Simulação disponível aqui](https://www.tinkercad.com/things/9RGCbPlLCHo-swanky-uusam/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=vf-AVNbVSZOR9WH4_qO6Z_5lJVH93FmJYmTr0_vttfM)

### Responda:


(a) Usando o multímetro de bancada, coloque na escala 20V~ (tensão alternada em 20 volts) e confira se você tem 10V~ na saída do gerador de sinais. Ajuste o knob **AMPL** para **MIN** ou **MAX** até encontrar os 10V~.

(b) Usando o multímetro de bancada na mesma escala 20V~, meça a tensão sobre o **R**. Quanto você encontrou?

(c) Usando o multímetro de bancada, mas agora na escala 2V~, meça a tensão sobre o **D**. Quanto você encontrou?

(d) Agora, comprove matematicamente os valores que você mediu.

(e) Diminua o valor de **AMPL** do gerador de sinais para abaixo de 0,7V~ (use o multímetro de bancada para conferir o valor).

(f) Repita as medições de (c) e (d). O que você conclui?

(g) Volte o valor de AMPL para o máximo, e vamos analisar o comportamento de retificação do D. Compare na sua tela do oscilas, o sinal senoidal original e o retificado, tentando colocar os dois sinais um sobre o outro na sua tela, mexendo no botão **POSITION VERTICAL**. Consegue verificar que metade da onda não está presente no **R**?

# PRÁTICA (5) - RETIFICADOR DE ONDA COMPLETA

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/retificador-onda-completa.jpg" width="600">

