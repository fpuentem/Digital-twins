# Titulo: Sistema de gerenciamento de uma casa inteligente com múltiplos usuários baseado em gêmeos digitais

## Capitulo 1: Introdução
### 1.1. Contexto
<!---
Coisa historica 2 paragrafos que cheve o problema
-->
O progresso do internet das coisas(IdC) tem permitido a implantação de uma inúmera quantidade de sensores e atuadores em diversas áreas da atividade humana que vão desde a indústria até as casas. No caso das casas inteligentes, a través do IdC conseguiu se obter uma enorme quantidade de dados com uma granularidade não vista antes. Tomando isso como base, os sistemas de gerenciamento para casas inteligentes permitem personalizar diferentes serviços para os moradores com uma maior sustentabilidade enérgetica mantendo o conforto deles.

Com a ajuda das redes inteligentes a otimização no uso da energia elétrica é possível ser feito no lado da demanda,(xxxx) em outras palavras no lado das casas, um exemplo de gerenciamento de lado da demanda é a tarifa branca residencial. Os medidores de energia inteligente permitem monitorar o consumo de energia dos aparelhos de uma casa em tempo real permitindo a os moradores ter conhecimento de seu gasto e consumo energetico.

### 1.2. Problema de Pesquisa
Os medidores inteligentes em uma casa disponibilizam os dados de consumo energético em tempo real por aparelho (especificar mejor, medidor general o individual?), ainda esses dados tem sido utilizados como simples números informativos do gasto de energia. Trabalhos mais atuais utilizam esses dados como entrada nos modelos de aprendizado de máquina para previsões do consumo energético de uma casa, mas isso não é de muita utilidade na otimização do consumo da energia elétrica. Geralmente, os modelos de aprendizado de máquina utilizam plataformas de nuvem, o que pode originar riscos na seguridade e privacidade dos moradores, por exemplo, a rutina dos moradores, o número de moradores de uma casa, os aparelhos que tem dentro de uma casa, etc. (conexión de ideas) Por outro lado, os gêmeos digitais permitem a adaptabilidade do perfil de consumo de uma casa, com isso um sistema de gerenciamento de energia domestica consegue a optimização do consumo de energia sem reduzir o conforto do morador. Não entanto, os modelos de gêmeos digitais de uma casa não consideram ao morador como um indivíduo e só tem em conta a casa como um tudo. Também os dados dos medidores inteligentes só fornecem informação com respeito o consumo de energia e não do estado interno dos aparelhos limitando desse modo a complexidade dos gêmeos digitais e a posibilidade de explorar su aplicabilidade em predição e previsão de falhas (revisao do ultimo paragrafo). 

### 1.3. Objetivos
#### 1.3.1. Objetivo Geral
Arquitetar e construir uma plataforma de gerenciamento de uma casa inteligente com múltiplos moradores basada em gêmeos digitais, assinatura electromagnética dos aparelhos é perfil de consumo de cada morador.
<!---
Para cada um dos objetivos o que outros artigos não consigureram
-->
#### 1.3.2. Objetivos Específicos
1.3.2.1. Selecionar uma arquitetura de referência para a plataforma de gerenciamento de uma casa inteligente que permita conciliar os perfiles de consumo energético de múltiplos moradores. 

1.3.2.2. Redesenhar a arquitetura para a plataforma de gerenciamento de uma casa inteligente a partir de novos componentes, funcionalidades e fluxos de operações, considerando a integração de gêmeos digitais e eficiencia energêtica.

1.3.2.3. Avaliar a detecção precoce de falhas dos aparelhos domésticos baseada em sua assinatura electromagnética. 

1.3.2.4. Definir um modelo de ameaça para a plataforma de gerenciamento de uma casa inteligente proposta.

### 1.4. Justificativa
<!---
Para cada um dos objetivos o que outros artigos não consigureram
-->
## Capitulo 2: Referencial Teorico
### 2.1. Casas Inteligentes
    1. Definição
    2. Arquiteturas de casa inteligente
        * Computação em nuvem
        * Computação de névoa
        * Computação de bordas
    3. Casas inteligentes e *Smart Grid*
        * Aparelhos inteligentes
        * Medidores inteligentes
        * Sistema de gerenciamento de energia doméstica inteligente
<!---
https://www.sciencedirect.com/science/article/pii/S2542660518300477?casa_token=JdHbFUPtmnYAAAAA:du5h4ALcj1bk00UR2lFKfiaEV-6MFI7YkVHDldRAx9V3Weva1su4JoqmvQcRmJXjgmIAZ4Gl14A
https://www.sciencedirect.com/science/article/pii/S1364032119308688?casa_token=1VZs_Rw5nPUAAAAA:O3u3pRq9gYLidEobwS4_0cd-PQrth8JV08EMaB9KBy8t2FBSNjFWFQI9ODZhebEj9K0QUh-QnGw
https://link.springer.com/article/10.1007/s11276-018-1712-5
https://www.sciencedirect.com/science/article/pii/S0040162517315676?casa_token=ocW3kppF8qwAAAAA:wnaJEe7kkW0JVJZN2O4nV6mmUsON2yINaMMz1-2bO7uXvI9NyfSPwH7QVJCt7SXU2886okNtUcw
-->
### 2.2. Gêmeos Digitais
    1. Origens e evolução
    2. Definição
    3. Características dos Gêmeos Digitais
        * Identificador único
        * Sensores e Atuadores
        * Inteligência Artificial
        * Comunicação
        * Representação
        * Confiança 
        * Privacidade e segurança
    4. Tecnologias habilitadoras
       1. Big Data
       2. Computação na nuvem e a borda
       3. Modelos baseados em dados 
    5. Estrutura de avaliação dos Gêmeos Digitais
       1. Métricas
           * Inteligência
           * Autonomia
           * Aprendizagem 
           * Fidelidade
       2. Níveis 
    6. Plataforma e Ecossistema de Gêmeos Digitais
    7. Gêmeos digitais aplicados as casas inteligentes
   
<!---
https://ieeexplore.ieee.org/abstract/document/8424832?casa_token=93KR-SmqTHIAAAAA:VsbR6l0GTtYuDf37ZhW0FCN6q6IVNwIMt944upkA_28MtFXxWsrgKzMIZPItnuN8vZX82AlB3CY
https://www.sciencedirect.com/science/article/pii/S2352484721000913#sec2
https://iopscience.iop.org/article/10.1088/1742-6596/1228/1/012031/pdf
https://ieeexplore.ieee.org/document/8807872
https://ieeexplore.ieee.org/abstract/document/8930829?casa_token=aWzL9Gy6AJ0AAAAA:9Bp_8y8j9uB6s6QdMVQiE9jqEphsqHhV0UAUXXi6gOjbpa2sxCjIVgKGhtdpY95TKkgVI0HHWqc
-->

### 2.3. Segurança e Privacidade de dados
    1. Pilares de ciber-segurança a considerar para gêmeos digitais
        * Segurança
        * Criptografia de dados
        * Identidade e Autenticação
        * Princípio do Mínimo Privilégio
        * Auditoria de Segurança
        * Monitoramento de Eventos ao Vivo e Resposta a Incidentes
        * Gerenciamento de dispositivos
    2. Modelos de ciber ameaças     
        * Casas inteligentes
        * Gêmeos digitais
        * Sistema de gerenciamento de energia doméstica inteligente
<!--
https://ieeexplore.ieee.org/abstract/document/9368968?casa_token=4GzCfNfrd-MAAAAA:OJnAEzQxlpcRGSTJGBPsdpweqLvs3SHn2YKVPbj7Mk77CRvZV9QvAzyPPmaftmYbRlii_geRIPU
-->

### 2.4. Detecção temprana de falhas
    1. Técnicas de detecção de falhas em aparelhos domésticos
    2. Detecção de falhas em aparelhos no contesto de casa inteligente 

## Capitulo 3: Apresentação da Proposta
### 3.1. Plataforma Proposta
### 3.2. Gerenciamiento de Energia
### 3.3. Gerenciamiento de Manutenção
### 3.4. Gerenciamiento de Segurança e Privacidade

## Capitulo 4: Materiais e Métodos

## Capitulo 5: Cronograma
<!---
Intervalo de 15 dias
-->