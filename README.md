# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="./assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# PROJETO FASE 5: MACHINE LEARNING NA CABEÇA
 ![mlnacabeca](./assets/mlbacabeca.jpeg)

## Grupo 15

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/iolanda-helena-fabbrini-manzali-de-oliveira-14ab8ab0">Iolanda Helena Fabbrini Manzali de Oliveira</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Murilo Carone Nasser</a> 
- <a href="https://www.linkedin.com/in/pedro-eduardo-soares-de-sousa-439552309">Pedro Eduardo Soares de Sousa</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Yago Brendon Iama</a>
- <a href="https://www.linkedin.com/in/jonatasgomes">Jônatas Gomes Alves</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Andre Godoi Chaviato</a>

# ENTREGA 1

## 📜 Descrição
A Entrega 1 foca na análise de dados agrícolas usando ML supervionado e não supervisionado para precisao de produtividade agricola utilizando o dataset 'yeld_crop.csv'.

## 💻 Tecnologias utilizadas

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](#)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)](#)

## 📁 Estrutura de pastas

- **/docs/entrega_1** - Documentação do projeto
- **/src/entrega_1** - Código-fonte e scripts
- **/assets/entrega_1** - Base de dados

## 🔧 Como executar o Projeto
  1. Acessar o notebook do Google Colab atraves do link fornecido a seguir: [Link Entrega 1](https://colab.research.google.com/drive/1mGIY150CzsRO05xwk_pjD1t94CauImdd?usp=sharing)
  2. Selecione no  campo 'Ambiente de execução" o modo para executar o código.

     * Observação: link do notebook com acesso restrito a leitura do código

## 🎥 Demonstração

[Link para vídeo demonstrativo no Youtube](https://youtu.be/Q5CVTFYaELo)

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.

---
# ENTREGA 2 

## 📜 Descrição

A Entrega 2 consiste na utilização da calculadora da AWS para estimar os custos de implementação e hospedagem de um sistema baseado em nuvem, comparando São Paulo (Brasil) e Virgínia do Norte (EUA) e avaliando a opção mais vantajosa considerando tanto o custo financeiro quanto latência e Legislação vigente local. 

 ## 💻 Tecnologias utilizadas
[![Amazon_AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=flat&logo=amazon-web-services&logoColor=white)](#).

## 📁 Estrutura de pastas

- **/docs/entrega_2** - Documentação do projeto
- **/assets/entrega_2** - Relatórios de Preços Orçados

## 🔧 Como executar o Projeto
  1. Acessar  a AWS Pricing Cauculeto através do link [Link do site da AWS Calculator](https://calculator.aws/#/addService)
  2. Selecionar a opção “pesquisa por tipo de local”
  3. Selecionar local e a região, número de CPUs (WorksSpaces = 2), Sistema Operacional (Linux) e pacotes conforme citado avaixo 
  
                 *  2 CPUs
                 *  1 GiB de memória
                 *  Até 5 Gigabit de rede
                 *  50 GB de armazenamento (HD)
     
  4. salvar o registro da primeira pesquisa e repetir o processo utilizando a segunda localização.
  5. Selecionar os registros das duas regiões para análise dos resultados
  6. Comparar os custos mensais e anuais.
     
                 | Localidade        | Custo por Hora (USD) | Custo Armazenamento (50 GB) (USD) | Custo Mensal (USD) | Custo Anual (USD) |
                 |-------------------|---------------------:|----------------------------------:|-------------------:|------------------:|
                 | São Paulo         |              $0.0256 |                           $0.0058 |          $18,978   |       $227,736    |
                 | Virgínia do Norte |              $0.0188 |                           $0.0050 |          $13,974   |       $167,688    |

    

     ![graficocustos](https://github.com/Ioiofmanzali/FIAP-FASE5CAP1-FARMETCHBAERADACLOUDCOMPUTING/blob/main/assets/entrega2/graficocustos.png)(#)

  7. Realizar o teste de latencia da AWS

     [Link AWS Latency Test](https://awsspeedtest.com/latency)

     ![latency](https://github.com/Ioiofmanzali/FIAP-FASE5CAP1-FARMETCHBAERADACLOUDCOMPUTING/blob/main/assets/entrega2/latencia.PNG)
         
## Comentários finais

A escolha entre hospedar o sistema em Virgínia do Norte ou São Paulo requer uma análise cuidadosa. Se por um lado, a Virgínia do Norte se apresenta como a opção mais econômica, oferecendo custos operacionais mais baixos, São Paulo oferece a vantagem de uma baixa latência para usuários localizados no Brasil. Além disso, considerações regulatórias podem influenciar a escolha. Em alguns casos, pode haver restrições  locais legais que exigem tratamento e armazenamento rigoroso, principalmente no que tange aos dados sensíveis dos usuários.  
Considerando-se somente  o orçamento como a principal prioridade, Virginia do Norte pode ser a mais atraente. 
**Considerando os requisitos legais e de acesso rápido como sendo demandas essenciais ao Projeto,  a hospedagem em São Paulo é a opção mais adequada, mesmo que isso implique em custos mais elevados.** 

Obs: o relatório completo pode ser acessado prlo link a seguir: [Relatório](https://github.com/Ioiofmanzali/FIAP-FASE5CAP1-FARMETCHBAERADACLOUDCOMPUTING/blob/main/assets/entrega2/Entrega_2.pdf)

## 🎥 Demonstração

[Link para vídeo demonstrativo no Youtube](https://youtu.be/RSukZULjL6Q)

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.


---
# IR ALÉM 1 

## 📜 Descrição

O projeto "Sistema de Coleta e Comunicação de Dados Usando ESP32 Integrado ao Wi-Fi" tem como objetivo desenvolver uma solução utilizando um ESP32 para coleta de dados via sensores e comunicação Wi-Fi. Os dados coletados são enviados diretamento a um banco de dados Oracle hospedado na Oracle Cloud. A comunicação é feita via api REST.

## 💻 Tecnologias utilizadas

#### Hardware
![microesp](https://github.com/user-attachments/assets/815e3951-ddec-4284-af49-368e83202b44)
  - **ESP32:** Microcontrolador wi-fi e Bluetooth, ideal para aplicações de IoT.
  - **DHT22:** sensor de temperatura e umidade
  - **LDR:** sensor de luz (resistor-dependente de luz) para medir a intensidade da luz
  - **Jumpers** e protoboard para conexões

#### Software
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![MicroPython](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)
![Oracle Cloud Database 23ai](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
  - **WokWi:** Software online and gratuito para simulação de ESP32.
  - **MicroPython:** Linguagem de programação usada para escrever o código que fará as leituras dos dados dos sensores e mandará para o banco de dados.
  - **API REST:** Método de comunicação utilizado para enviar os dados para o banco Oracle.
  - **JSON:** Formato dos dados enviados ao banco Oracle.
  - **Oracle Cloud Database 23ai:** Banco de dados Oracle hospedado na nuvem.
  - **Oracle ORDS:** Ferramenta disponibilizada pela Oracle Cloud que permite criar e disponibiliar a **API REST**.
  - **Oracle SQL Developer** Ferramenta para acessar o banco de dados Oracle e visualizar/alterar os dados das tabelas.

## 📁 Estrutura de pastas

- **/docs/ir-alem-1** - Documentação do projeto
- **/src/ir-alem-1** - Código-fonte e scripts
- **/assets/ir-alem-1** - Imagens do circuito e diagrama de conexão

## 🔧 Como executar o Projeto
  1. Construir o projeto no WokWi, adicionando os componentes e carregando o código.
  2. Executar o código no WokWi e alterar os valores simulados dos sensores.
  3. Conectar a base de dados Oracle e verificar as linhas da tabela **SENSOR_LEITURAS**.
  4. Também é possível ler os dados gravados através da API REST.

## 🎥 Demonstração

[Link para vídeo demonstrativo no Youtube](https://youtu.be/gSLD32WOulg)

## 📋 Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.

---

<p align="center">
<strong>Projeto desenvolvido para o curso de Inteligência Artificial da FIAP.</strong>
</p>
