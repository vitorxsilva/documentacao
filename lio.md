# Documentação Cielo LIO

Nessa documentação você tem acesso a todas as informações sobre a plataforma Cielo LIO e boas práticas para o desenvolvimento e modelos de integração disponíveis para complementar o negócio de seu cliente.

O objetivo dessa documentação é facilitar o processo de desenvolvimento fornecendo os materiais necessários para realizar a integração com a Cielo LIO e todos os conceitos sobre a Cielo Store, a loja de aplicativos da Cielo disponível na Cielo LIO.

# Visão Geral da Plataforma

## Modelos disponíveis da Cielo LIO

Atualmente a Cielo LIO está disponível em 2 modelos: LIO V2 e LIO +

![Comparação - LIO V1 e LIO V2](https://desenvolvedores.cielo.com.br/api-portal/sites/default/files/lio_v1_v2.png)
![BLUE](https://desenvolvedores.cielo.com.br/api-portal/sites/default/files/blue_lio.png)

### Cielo LIO V2

A Cielo LIO V2 é o modelo da LIO que dispoe do recurso de impressão, o cliente poderá ter a 1ª e 2ª via impressa após o pagamento realizado. Além disso, as aplicações parceiras poderão utilizar os métodos disponíveis da impressora para imprimir dados importantes ou necessários para o negócio do cliente.

**Especificação da Bobina:**
Papel Azul 48 gramas, Comprimento: 12 metros, Diâmetro máximo: 30 milímetros, Largura: 57 milímetros.

**NFC**: Tecnologia presente permitindo o pagamento utilizando cartões com tecnologia contactless.

### Cielo LIO+

 Solução 2 em 1,  a primeira do segmento a oferecer smartphone e maquininha de cartão em um único aparelho, com o objetivo de digitalizar o pequeno negócio. 

A Cielo LIO+ oferece mobilidade e praticidade ao vendedor. Isso porque ela é 2 em 1: o mesmo equipamento opera como um smartphone, com todas as suas funções de voz e aplicativos, e uma maquininha de cartão que se conecta de maneira rápida e intuitiva ao celular com um simples snap (encaixe magnético que oferece uma conexão imediata entre o celular e o módulo de pagamento), diferente das soluções que exigem o pareamento via bluetooth, por exemplo.

Ambas contam com a Cielo Store, loja de aplicativos B2B disponível em todos as LIO´s, dando escala e distribuição para qualquer aplicativo integrado a ela.

# Arquitetura

## Modelos de integração com a plataforma Cielo LIO

Existem 2 modelos de Integração com a Cielo LIO:

#### Integração Local | Cielo LIO Order Manager SDK

A Cielo disponibiliza um SDK com base na Cielo LIO Order Manager API que permite ao desenvolvedor e parceiro Cielo LIO integrar em sua aplicação as funcionalidades da Cielo LIO.

[![Vídeo Demo](https://img.youtube.com/vi/d7y-x6p36YU/0.jpg)](https://www.youtube.com/watch?v=d7y-x6p36YU)
 
 Clique na imagem acima, para acessar o vídeo
 
 #### Integração Remota | Cielo LIO Order Manager

Conjunto de APIs que permitem que o cliente continue utilizando sua solução de PDV / Automação Comercial com todas as funcionalidades. No momento de realizar o pagamento, ocorre a integração com o gerenciador de pedidos (Order Manager) da Cielo LIO, de forma rápida, simples e segura.

[![Vídeo Demo](https://img.youtube.com/vi/d7y-x6p36YU/0.jpg)](https://www.youtube.com/watch?v=QxfTkJEN1Qs)

Clique na imagem acima, para acessar o vídeo

## Especificações técnicas do hardware da Cielo LIO

A plataforma Cielo LIO teve seu sistema operacional próprio baseado em Android.
Confira abaixo a tabela com as especificações técnicas da Cielo LIO:

| | ![LIO V1](https://desenvolvedores.cielo.com.br/api-portal/sites/default/files/lio_v1_small.png) | ![LIO V2](https://desenvolvedores.cielo.com.br/api-portal/sites/default/files/lio_v2_small.png) | ![LIO V2](https://desenvolvedores.cielo.com.br/api-portal/sites/default/files/lio_small.png) |
|----------------------|---------------------------------------------|---------------------------------------------|------------------|
| Versão               | **LIO V1**                                  | **LIO V2**                                  | **LIO +**        |
| Sistema operacional  | Android OS Cielo 5.1.1                      | Android OS Cielo 6.0 (Marshmallow)          | Android 8.1 Oreo |
| Memória              | 2GB LPDDR3                                  | 1GB LPDDR3                                  | 2GB              |
| Armazenamento        | -                                           | -                                           | 16GB expansível (80GB micro SD)        |
| Dual Chip            | Dual SIM Stand-by                           | -                                           | Dual Chip        |
| Frequência           | 2.4 GHz                                     | 2.4 GHz                                     | 2.4 GHz          |
| Tipo do SIM Card     | micro SIM (3FF)                             | micro SIM (3FF)                             | micro SIM e/ou Nano SIM               |
| Frequência GSM Mhz   | Quad-Band 850/900/1800/1900                 | Quad-Band 850/900/1800/1900                 | Quad-Band 850/900/1800/1900      |
| Tamanho em polegadas | 5"                                          | 5.5"                                        | 6"               |
| Tipo de tela         | AMOLED                                      | AMOLED                                      | AMOLED           |
| Resolução da tela    | 720 x 1280 pixels                           | 720 x 1280 pixels                           | LCD 6" HD+ 1440x720 pixels        |                       
| Densidade de pixels  | 293 ppi                                     | 267 ppi                                     | 268 ppi          |
| Câmera               | 12.8 Mega Pixels                            | 13 Mega Pixels                              | 12 Mega Pixels   |
| Resolução da câmera  | 4128 x 3096 pixels                          | 4160 x 3120 pixels                          | 12MP LED flash Zoom digital x4 08MPLED flash Zoom digital x4                        |
| Flash                | Flash LED                                   | Flash LED                                   | Flash LED        |
| USB                  | USB 2.0 Micro-B (Micro-USB) Somente Energia | USB 2.0 Micro-B (Micro-USB) Somente Energia | Micro USB 2.0    |
| Bluetooth            | Versão 4.0 com A2DP                         | Versão 4.0 com A2DP/LE                      | Versão 4.1 suporta LE                     |
| WiFi                 | 802.11 a/b/g/n (2.4GHz)                     | 802.11 b/g/n (2.4GHz)                       | 802.11b/g/n (2.4GHz)      |
| GPS                  | A-GPS. GeoTagging                           | A-GPS                                       | A-GPS            |
| Sensores             | Acelerômetro, Proximidade e Luminosidade    | Acelerômetro, Proximidade e Luminosidade    | Leitor de digitais, acelerômetro, luminosidade e proximidade                   |
| Saída de áudio       | Audio Jack 3.5mm                            | Audio Jack 3.5mm                            | Audio Jack 3.5mm |
| Peso                 | 363 g                                       | 507 g                                       | 156 g            |
| Altura               | 34mm                                        | 46mm                                        | 9mm              |
| Largura              | 84mm                                        | 81mm                                        | 75mm             |
| Comprimento          | 168mm                                       | 228mm                                       | 158mm            |

### Serviços periféricos

A Cielo LIO também se integra com os seguintes periféricos de hardware:

**Impressoras Bluetooth**

É possível conectar a Cielo LIO com impressoras bluetooth para realizar a impressão de recibos e outras informações importantes.

Já existem parceiros que estão utilizando impressoras Bluetooth das marcas Zebra, Datex, Leopardo integradas com a Cielo LIO.

Todos os protocolos de comunicação e pareamento ficam sob responsabilidade do aplicativo do parceiro.

### Rotação de tela na Cielo LIO

As rotações na tela de exibição possuem comportamento diferente entre as versões da Cielo LIO.

Na LIO V1 a orientação da tela é travada.

Na LIO V2 é possível controlar a orientação da tela. Por padrão, a orientação da tela exibida é livre e definida de acordo com o acelerômetro do equipamento.

Caso o desenvolvedor deseje controlar e usar de forma personalizada a orientação de tela da Cielo LIO, este deverá utilizar de acordo com a documentação do Android.

[Documentação Oficial do Android](https://developer.android.com/guide/topics/manifest/activity-element.html)

Acesse o item: android:screenOrientation para obter maiores informações.

### Dados Móveis na Cielo LIO

A Cielo LIO já vem configurada com um SIM Card. A operadora do SIM Card é definida de acordo com o endereço de cadastro do estabelecimento comercial.

A Cielo envia o SIM Card da melhor operadora de acordo com o endereço de cadastro da LIO solicitada.

Esse SIM Card permite a conexão com a tecnologia 3G da Cielo LIO e possui um pacote de dados ilimitado.
