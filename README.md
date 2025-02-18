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

<img src="https://github.com/agodoi/m05-semana03/blob/main/imgs/diodo3.png" width="300">

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



## **4. Aplicações da Junção PN**
A junção PN tem aplicações em diversos dispositivos semicondutores:

1. **Diodo retificador:** Permite a conversão de corrente alternada em corrente contínua.
2. **Diodo Zener:** Opera em polarização reversa para regular tensões.
3. **LED (Diodo Emissor de Luz):** Converte energia elétrica em luz através da recombinação de elétrons e lacunas.
4. **Transistores (BJT e FET):** Utilizam múltiplas junções PN para amplificação e chaveamento de sinais.
5. **Fotodiodos:** Sensores ópticos que detectam luz e convertem em corrente elétrica.

---

## **Conclusão**
A **junção PN** é um dos conceitos mais importantes da eletrônica moderna, permitindo o desenvolvimento de componentes semicondutores essenciais para a tecnologia. Seu funcionamento baseia-se na **formação da camada de depleção** e no **controle do fluxo de corrente elétrica**, dependendo da polarização aplicada. A capacidade de manipular a condução elétrica com precisão fez dos semicondutores a base da computação, telecomunicações, sistemas embarcados e Internet das Coisas (IoT).

---

Esse texto está bem detalhado e técnico. Caso precise de ilustrações ou de uma formatação específica para uma apostila em PDF, posso estruturar isso para você! 🚀





### **2. Materiais Condutores e Semicondutores**
   - Definição de condutividade elétrica
   - Exemplos de materiais condutores (cobre, prata, alumínio)
   - Estrutura atômica dos semicondutores (Silício, Germânio)
   - Bandas de energia: Banda de Valência e Banda de Condução
   - Dopagem de semicondutores (tipo N e tipo P)
   - Junção PN e formação da barreira de potencial

### **3. Diodo Ideal**
   - Conceito teórico do diodo ideal
   - Características ideais (zero resistência direta, resistência infinita na polarização reversa)
   - Modelo gráfico da curva característica

### **4. Diodo Real**
   - Diferenças entre diodo ideal e real
   - Tensão de limiar (0,7V para silício e 0,3V para germânio)
   - Corrente de fuga em polarização reversa
   - Resistência dinâmica direta e zona de avalanche
   - Parâmetros elétricos: IF (corrente direta), VR (tensão reversa máxima), PIV (Peak Inverse Voltage)

### **5. Aplicações Práticas dos Diodos**
   - Retificação de corrente alternada (meia onda e onda completa)
   - Proteção contra inversão de polaridade
   - Circuitos de chaveamento rápido
   - Diodo Zener como regulador de tensão
   - Fotodiodo e diodo emissor de luz (LED)

### **6. Experimentos Práticos**
   - Medição de diodos com multímetro
   - Construção de um retificador de meia onda
   - Simulação de curva característica no software LTSpice ou Proteus

### **7. Conclusão**
   - Importância dos diodos na eletrônica moderna
   - Comparação entre diodo ideal e real na prática

### **8. Exercícios e Questões**
   - Questões teóricas sobre comportamento dos diodos
   - Cálculo de tensões e correntes em circuitos com diodos
   - Análise de gráficos de curva característica

Se precisar de mais detalhes ou quiser uma versão formatada em PDF, posso estruturar o material para você! 🚀
