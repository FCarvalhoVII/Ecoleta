<center>
    <img src="./web/src/assets/logo.svg">
    <img src="./web/src/assets/home-background.svg">
</center>

<h1 align="center">
    Projeto desenvolvido na Next Level Week #1 da Rocketseat
    <h6 align="center">Tecnologias usadas: TypeScript, NodeJS, React e React Native</h6>
</h1>

### Descrição

O projeto é uma plataforma integrada que busca ajudar os seus usuários a encontrar pontos de coleta que recolhem lixo considerado tóxico e que pode agredir o meio ambiente. Um estabelecimento pode se cadastrar pela plataforma web informando sua localidade no mapa e os tipos de lixo que ele recolhe, por meio do aplicativo móvel os usuários podem encontrar o estabelecimento pelo mapa e entrar em contato por meio de WhatsApp ou E-mail.

### Tecnologias

O projeto possui backend em **NodeJS**, frontend em **React** e o mobile em **React Native**, banco de dados SQL mais especificamente **SQLite** com o *QueryBuilder* **Knex**.

A api foi escrita com o *framework* **Express** junto com as *libs* **Multer** e **Celebrate** para fazer upload de imagens e validação respectivamente.

Para utilizar mapas na versão web da aplicação foi utilizado a biblioteca **Leaflet**, e outros recursos do React para ícone e dropzone.

Na versão mobile foi utilizado a biblioteca **React-Native-Maps** para a interação com mapas. Para escrever o aplicativo foi usado o *framework* Expo na aplicação mobile, para ter acesso às api's nativas do dispositivo sem ter a necessidade de alterar código nativo ou instalar dependência.

### Build

Para rodar a aplicação basta clonar este repositório em sua máquina.
#### Backend - Iniciando o servidor
Entre na pasta ```backend``` e rode o comando ```npm run dev``` o servidor estará rodando na porta ```3333``` de sua máquina.
#### Frontend
Para inicializar o frontend basta utilizar o comando ```npm start``` na pasta ```web```, a aplicação estará na porta padrão do ReactJS ```3000```.
#### Mobile
O aplicativo mobile será inicializado com o comando ```npm start``` na pasta ```mobile```, você poderá rodar o app em algum emulador Android ou iOS, no seu próprio celular baixando o aplicativo da Expo e usando o QR Code gerado ao iniciar a aplicação ou até mesmo em seu navegador em [Expo Snack](https://snack.expo.io/).