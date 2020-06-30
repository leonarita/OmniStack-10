# Projeto "DevRadar"

## Projeto desenvolvido no evento OmniStack 10.0 fornecido pela empresa RocketSeat.

Nessa semana, foi desenvolvido uma aplicação full stack integrando backend (com NodeJS), frontend (com ReactJS) e mobile (com React-Native). 
<br>
A linguagem de programação utilizada foi o **`Javascript`**.

<br>
<br>
Esse projeto possibilita buscar desenvolvedores de uma determinada tecnologia em um raio de 10 km, podendo ser atualizada a aplicação mobile on real time.

<br>
<br>
<img src="/backend/uploads/foto3.png">
<br>

### 1. Backend

Para o backend, foram utilizadas ferramentas como `express`, `axios`, `mongoose`, `cors` e `socket.io`.
<br>
<br>
Foram feitas as seguintes funcionalidades:
  1. Models;
  2. Controllers;
  3. Conexão com banco de dados;
  4. Criação das rotas;
  5. Aplicação on real time.

<br>

### 2. Frontend

Para o frontend, foram utilizadas ferramentas como `axios`, `react-router-dom` e `socket.io-client`. 
<br>
<br>
Possui uma tela básica dividida em dois grids: um para cadastro de GitHub, e outro de listagem de dados cadastrados.

<br>
<img src="/backend/uploads/foto1.png">
<br>

### 3. Mobile

Foi utilizando o React-Native com o `Expo` para a criação da aplicação mobile.
<br>
Para o mobile, foram utilizadas ferramentas como `axios`, `react-navigation`, `react-native-maps` e `socket.io-client`.
<br>
<br>
Possui duas telas:
  1. Tela inicial (que possui o mapa para encontrar o usuário do GitHub filtrado por tecnologia e por localidade);
  2. Tela de exibição do perfil no GitHub.

<br>
<img src="/backend/uploads/foto2.png">
<br>

_Obs: Por limitação do meu emulador do android, eu não consegui usar o gps e, por isso, configurei para que o mapa seja direcionado para minha localidade (endereço)._

### 4. Funcionalidade On Real Time

Caso um desenvolvedor seja cadastrado, os desenvolvedores conseguem receber a atualização instantaneamente, sem a necessidade de atualizar a página.
<br>
Essa funcionalidade é devida ao `socket.io` e `socket.io-client`.
