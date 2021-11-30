# Stow n Rest Backend

## Table of Contents

- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## About Project

The aim of this project is to provide a RESTful API that will help manage data for service providers who offer limited time storage space solutions to their customers. The future prospects of this project are to provide a way for customers to request for luggage shipment at specified dates when they've deposited their luggage at any of the authorized Stow and Rest dealers.

<!-- ![screenshot](./screenshot.png) -->

## [API DOCUMENTION](#api-documentation)

- Coming Soon

## Built With

- Ruby 3.0.2
- Rails 6.1.4
- Postgresql

## Getting Started

- Clone this repo https://github.com/Lameck1/stow_n_rest_backend
  ```
  git clone https://github.com/Lameck1/stow_n_rest_backend.git
  ```
- Navigate to stow_n_rest_backend folder
  ```
  cd stow_n_rest_backend
  ```
- On the terminal, while in the 'stow_n_rest_backend' directory, run the following to install dependency:
  ```
  bundle install
  ```
- At this point, you still don't have the Postgress database. Run the following to get setup:

  - Ensure that postgresql service is up and runnning
    `sudo service postgresql start`
  - Create the database
    `rails db:create`

  - Migrate the database
    `rails db:migrate`

- To interact with the project, run:

  ```
  rails server
  ```

  OR

  ```
  rails s
  ```

- Go to the browser and enter
  `http://localhost:3000`

### Prerequisites

- Ensure you have these installed:

  - Git
  - Ruby 3.0.2
  - Ruby on rails `gem install rails`

- You also need to ensure your yarn is upto date
  ```
  yarn install --check-files
  ```

### API Documentation

- Coming soon

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Lameck1/stow_n_rest_backend/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/newFeature`)
3. Commit your Changes (`git commit -m 'Add some newFeature'`)
4. Push to the Branch (`git push -u origin feature/newFeature`)
5. Open a Pull Request

## Authors

👤 **Lameck Otieno**

- GitHub: [@githubhandle](https://github.com/Lameck1)
- Twitter: [@twitterhandle](https://twitter.com/lameck721)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/lameck-odhiambo-642b7077/)
- Portfolio: [Portfolio](https://lameck.me)

## Acknowledgements

Credits go to the following for providing guides on Ruby on Rails Association

- [**Rails Guides**](https://guides.rubyonrails.org/association_basics.html)

## Show your support

Give a ⭐️ if you like this project!
