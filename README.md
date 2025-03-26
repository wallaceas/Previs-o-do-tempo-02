Previsão do Tempo
Este é um aplicativo React que consulta a API do OpenWeatherMap para fornecer informações sobre o clima atual e a previsão para os próximos cinco dias de uma cidade especificada pelo usuário.

📌 Funcionalidades
Permite que o usuário insira o nome de uma cidade e obtenha a previsão do tempo.

Exibe informações meteorológicas atuais da cidade pesquisada.

Exibe a previsão do tempo para os próximos cinco dias.

🛠 Tecnologias Utilizadas
React.js

Axios (para requisições HTTP)

OpenWeatherMap API (para obtenção dos dados meteorológicos)

📂 Estrutura do Código
App.js: Componente principal que gerencia a busca e exibição dos dados.

WeatherInformations.jsx: Componente responsável por exibir as informações meteorológicas atuais.

WeatherInformations5Days.jsx: Componente responsável por exibir a previsão do tempo para os próximos cinco dias.

🚀 Como Executar
Clone o repositório

sh
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Instale as dependências

sh
Copiar
Editar
npm install
Execute o projeto

sh
Copiar
Editar
npm start
🔑 Configuração da API
O código usa uma chave de API do OpenWeatherMap. Para obter a sua própria chave:

Crie uma conta em OpenWeatherMap.

Gere uma API Key e substitua no código a variável key:

js
Copiar
Editar
const key = "SUA_CHAVE_AQUI";
📌 Observação
Certifique-se de que sua chave de API está válida.

Caso o número de requisições ultrapasse o limite gratuito da API, pode ser necessário aguardar ou contratar um plano pago.

![previsão-do-tempo-02](https://github.com/user-attachments/assets/1814a18c-5753-4358-88f0-1acee25cf4b1)
