<!-- PROJECT LOGO -->
<h1 align="center">Cinema</h1>
<div align="center">
  <a href="https://github.com/DeminDmitrii/vuetify_cinema">
    <img src="public/cinema_logo.jpg" alt="Logo" width="80px" height="80px">
  </a>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

![product-screenshot]
The Cinema web application uses data from the TMDB API (https://developer.themoviedb.org).
<br/>
Implemented SPA about popular movies, movie search, detailed information on the movie and adding/removing a movie from Favorites.

### Built With

![Vue][Vue.js]
![Vite][Vite]
![Vuetify][Vuetify]
![Node.js][Node.js]

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://developer.themoviedb.org/reference/intro/authentication#api-key-quick-start](https://developer.themoviedb.org/reference/intro/authentication#api-key-quick-start)
2. Clone the repo
   ```sh
   git clone https://github.com/DeminDmitrii/vuetify_cinema.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `CinemaService.js`
   ```js
   this.apiKey = 'ENTER YOUR API KEY';
   ```
5. Maybe needs to use VPN.

## Contacts
[![Telegram][Telegram]][Telegram-url]
[![Gmail][Gmail]][Gmail-url]

[Telegram]: https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white
[Telegram-url]: https://t.me/demin_dmitrii_s/

[Gmail]: https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white
[Gmail-url]: mailto://d.s.demin@gmail.com

[product-screenshot]: readme_scan.png
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vite]: https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white
[Vuetify]: https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF
[Node.js]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
