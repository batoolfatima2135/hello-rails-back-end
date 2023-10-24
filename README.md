<a name="readme-top"></a>

<div align="center">

  <h1><b>hello-rails-backend</b></h1>

</div>

<!-- TABLE OF CONTENTS -->

## 📗 Table of Contents

- [📖 Fullstack - Rails with React ](#-hello-rails-backend-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
    - [Front-End](#Front-end)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Author ](#-author-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# 📖 hello-rails-backend <a name="about-project"></a>

**hello-rails-backend** is a  app that have 5 greetings
## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Server</summary>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
    <li><a href="https://rubyonrails.org/">Rails</a></li>
</details>
<details>
  <summary>Database</summary>
    <li><a href="https://www.postgresql.org/">Postgres</a></li>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Built using Ruby on Rails with React**

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## 🚀 Front-end link <a name="Front-end"></a>

- [Front end Link](https://github.com/batoolfatima2135/hello-react-front-end)

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

```
    ruby >= 3.2.0
    rails >= 7.0
    postgres >- 15.3
    node
```

### Setup

Clone this repository to your desired folder:

```bash
  git clone https://github.com/batoolfatima2135/hello-hello-rails-backend
```

You need to setup database for these project

```
  development = hello_rails_backend_dev
  test        = hello_rails_backend_test
  production  = hello_rails_backend_prod
```

or you can use your own database and change the ```config/database.yml```

```yml
  default: &default
    adapter: postgresql
    encoding: unicode
    pool: 5
    username: [your_username]
    password: [your_password]
    host: localhost

  development:
    <<: *default
    database: [your_database_for_development]

  test:
    <<: *default
    database: [your_database_for_test]

  production:
    <<: *default
    database: [your_database_for_production]
```

### Install

Install this project with:

```bash
  cd hello_rails_backend
  bundle install
  npm install
```

it will install the required gemfile for running the project

### Usage

to use this project:

```bash
   npm run build
   bin/rails server
```

it will run the the server on ```localhost:3000```

<!-- ### Test

to run test in these this project:

```ruby
   rspec
```

it will run the all the unit test of these project

 -->


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Author <a name="author"></a>

👤 **Batool Fatima**

- GitHub: [@githubhandle](https://github.com/batoolfatima2135)
- Twitter: [@twitterhandle](https://twitter.com/batool2135)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/batool-fatima-515531196/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- **Add UI System**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/ichsansandy/rails-one-app/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project you can share this project to your friend

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank microverse for this project

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>