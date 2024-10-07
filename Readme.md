# Introdução
  Esse é o projeto de um sistema de localização em tempo real baseado na utilização do RSSI (Received Signal Strength Indication), em português indicador de intensidade de sinal recebido, para determinar a posição de um ESP32 dentro de uma matriz de roteadores preestabelecida.

  ### Contextualização e objetivo:
  Esse projeto surgiu a partir de um desafio proposto pela FIAP, em parceria com a John Deere, uma das principais e mais inovadoras empresas na área de fabricação de equipamentos agrícolas, para os discentes do curso de engenharia da computação. Nesse contexto, tem-se como objetivo principal buscar uma solução para a dificuldade de otimização do reabastecimento de peças nos carros-kit dentro das fábricas. Assim, por meio da criação de um RTLS (real time location system) busca-se coletar dados para otimizar o percusso e movimentação de insumos dentro da área fabril. Para superar essa dificuldade, busca-se elaborar um sistema para localizar o carro-kit dentro da área da fábrica, por meio do uso de ESP32 em conjunto com uma rede de roteadores Wi-Fi para realizar "triangulação", a partir da coleta de dados como o RSSI recolhido pelo ESP32. Desse modo, esses dados poderá ser enviado a um servidor local estabelecido por meio do XAMPP, possibitando a consulta por intermédio do banco de dados MySQL ou pela aplicação web que demonstra a localização do carro-kit em um mapa. Além disso, destaca-se a utilização de um script Python para tratamento desses dados, também como a otimização de percussos com auxilio de um algoritmo A* (A estrela), também criado na linguagem Python.

# Desenvolvimento
  A priori, para o entendimento desse trabalho é importante salientar as ferramentas e tecnologia escolhidas para a elaboração desse projeto.

  ### Tecnologias:
  - ESP32 - é um microcontrolador poderoso e versátil de hardware aberto. Possui Wi-Fi e Bluetooth integrados, o que elimina a necessidade de comprar módulos separados;
  - PHP - é uma linguagem de programação, voltada para o desenvolvimento de aplicações web, atuante principalmente ao lado do servidor, fornecendo a conexão entre o servidor e a interface de usuário;
  - Python - é uma linguagem de programação de alto nível, ou seja, possui uma sintax mais simplificada e próxima a linguagem humana, tem diversas aplicações como na área da ciência de dados, web, servidores, etc. O Python oferece diversos recursos, como a orientação a objetos, diversas bibliotecas e frameworks;
  - C++ - também uma linguagem de progrmação de alto nível, relevante por sua eficiência e desempenho, além de permitir o controle direto sobre o hardware. O C++ também permite a criação de classes e objetos para estruturar o código de forma modular e reutilizável;
  - MySQL - é um sistema de gerenciamento de banco de dados, que o utiliza a linguagem SQL (Structured Query Language) como interface. O SQL é uma linguagem de programação que permite trabalhar com dados relacionais em bancos de dados;
  - XAMPP - é um pacote com os principais servidores de código aberto, que inclui um banco de dados MySQL e Apache com suporte para PHP.

  ### Funcionamento
  
  
  #### Diagramas

  ![Diagrama de funcionamento](https://github.com/user-attachments/assets/0c6873f5-8866-4634-8d59-2b1cb24f4c58)

  ### Demonstração

# Resultados