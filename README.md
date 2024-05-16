


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project
<br>
</br>
<img src="https://live.staticflickr.com/65535/51119712284_5b9abba493_h.jpg" alt="homepage ss" />

## Overall Structure

### Back End

The app was built using Express and Sequelize on the back end with a PostgreSQL database. The backend structure is RESTful with AJAX requests that are fullfilled with JSON Objects. Model associations are used to minimize database queries to the backend, assuring speed and reliability.

### Front End

The front end is built with React and Javascript while utilizing Redux architecture, producing a lightning-fast user interface and calling upon dynamically rendered components.

### Built With

- [JavaScript](https://www.javascript.com/)
- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Express](https://expressjs.com/)
- [Node.js](https://nodejs.org/en/)
- [HTML](https://html.com/)
- [CSS](http://www.css3.info/)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Here is everything we need you to do to get started with SoundWave.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
 
2. Install NPM packages
   ```sh
   npm install
   ```
3. Add a '.env' with your environment variables to the root of your local directory

4. Create a postgreSQL user
   ```sh
   CREATE USERS <<your username>> WITH PASSWORD <<your password>> CREATEDB;
   ```
5. Create your database
   ```sh
   npx dotenv sequelize db:create
   ```
6. Migrate and seed your database
   ```sh
   npx dotenv sequelize db:migrate
   npx dotenv sequelize db:seed:all
   ```

<!-- USAGE EXAMPLES -->
<!-- ## Usage -->
<!-- ### An easy-to-use login with a pre-configured Demo User. -->
<!-- ![demo-login gif](imgs/demo-login.gif) -->
<!-- ### Search for Music Videos by title, artist, or genre. -->
<!-- ![search gif](imgs/search.gif) -->
<!-- ### Leave a rating and a comment on a Music Video. -->
<!-- ![rating gif](imgs/reviews.gif) -->
<!-- ### Add a Music Video to your list
![My List](site-images/my-list.gif) -->
<!-- ## Obstacles -->

<!-- ROADMAP -->


<!-- ACKNOWLEDGEMENTS -->
