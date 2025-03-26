# Previsão do Tempo

Este é um aplicativo simples de previsão do tempo desenvolvido em React.js. Ele consome a API do OpenWeatherMap para obter informações meteorológicas atuais e previsões para os próximos 5 dias.

## Tecnologias Utilizadas

- React.js
- Axios
- OpenWeatherMap API

## Funcionalidades

- Busca previsão do tempo para uma cidade especificada pelo usuário.
- Exibe informações meteorológicas atuais.
- Exibe previsão do tempo para os próximos 5 dias.

## Instalação e Execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd seu-repositorio
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. Inicie o projeto:
   ```sh
   npm start
   ```

## Uso

1. Digite o nome de uma cidade no campo de entrada.
2. Clique no botão "Buscar".
3. Veja as informações meteorológicas atuais e a previsão para os próximos 5 dias.

## Configuração da API

Este projeto usa a API do OpenWeatherMap. Para utilizá-lo, você precisa de uma chave de API:

1. Crie uma conta no [OpenWeatherMap](https://openweathermap.org/).
2. Gere uma chave de API.
3. Substitua a chave dentro do arquivo `App.js` na constante `key`.

## Estrutura do Projeto

```
/
├── src/
│   ├── components/
│   │   ├── WeatherInformations/
│   │   ├── WeatherInformations5Days/
│   ├── App.js
│   ├── App.css
│   ├── index.js
├── package.json
└── README.md
```


## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Imagem Ilustrativa

![previsão-do-tempo-02](https://github.com/user-attachments/assets/8ce2b548-e181-4bf6-9887-b89b1a448958)



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

---

Desenvolvido por Wallace Araújo.
