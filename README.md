## LifeStyle Articles

  <p class="align-center">
    This project is the Capstone of the Microverse curriculum at the end of the Ruby on Rails module!


## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Walkthrough Video and Deployment (Heroku)](#walkthrough-video-and-deployment-(heroku))
* [Usage](#usage)
* [Database Structure](#database-structure)
* [Contributors](#contributors)
* [Acknowledgements](#acknowledgements)
* [License](#license)

## About The Project
  This is rails capstone project where demonstrates my skills of RubyOnRails module. 
  In this app users can signup/login and use this app to message each other. I also tested the main features of this app.

### Built With
This project was built using these technologies.
* Ruby & Ruby on Rails
* Bootstrap
* HTML / CSS / SCSS
* SQLite
* Bcrypt
* Rubocop
* PG

## Live demo
* Live Demo Link --> App Deployed with Heroku: [LifeStyle-Articles](https://dry-savannah-74700.herokuapp.com/) :point_left:

### Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.7.2
Rails: 6.0.3.4

### Clone
* clone this repo:
  - Clone with SSH:
  ```
    git@github.com:hemant-soni-vst-au4/Lifestyle_articles.git
  ```
  - Clone with HTTPS
  ```
   https://github.com/hemant-soni-vst-au4/Lifestyle_articles.git

### Setup

Install gems with:

```
$ bundler install --without production
```

Setup database with:

```
$ rails db:migrate
```

To have some categories ready run

```
$ rails db:seed
```

Run yarn

```
$ yarn
```

### Usage

Start server with:

```
$ rails server
```

Open `http://localhost:3000/` in your browser and sing in
- for any technical problems running ```rails db:migrate:reset && rails db:seed``` should solve the problem

 ## Automated Test

* Run the command and see the output: 
```$ rails test```

## Database Structure
 * Database schema used for this project reflects the following structure:
 ![erd](app/assets/images/erd.png)

## Author

👤 **Gzim Asani**
- Github: [@GzimAsani](https://github.com/GzimAsani)
- Linkedin: [GzimAsani](https://www.linkedin.com/in/gzim-asani-83390a17a/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Credits
* Nelson Sakwa - [liFEstIye](https://www.behance.net/gallery/14554909/liFEsTlye-Mobile-version)
* [Microverse](https://www.microverse.org/)

## Copyright
This is a project developed by Microverse Student as the part of skill curriculum.
