# IDEA BOARD

This is a follow along project using Ruby on Rails API as backend and React as Frontend.

Ideaboard-client directory contains the React FrontEnd App

## Built With

- Ruby v2.6.5
- Ruby on Rails v6.0.3.2
- React

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.6.5
Rails: 6.0.3.2
Postgres: >=9.5
Nodejs

### Setup

~~~bash
$ git clone https://github.com/learnetto/ideaboard-api.git
$ cd ideaboard-api
~~~

Install gems with:

```
bundle install
```
Navigate to react-client app

```
cd ideaboard-client
npm install
```

Setup database with:

> make sure you have postgress sql installed and running on your system

```
   rails db:create
   rails db:migrate
   rails db:seed   # install sample list data
```

### Usage

Start server from the root folder with:

```
    rails s -p 3001
```

Start React client app

```
   npm start
```

# Authors

👤 **Uduak Essien**

- Github: [@acushlakoncept](https://github.com/acushlakoncept/)
- Twitter: [@acushlakoncept](https://twitter.com/acushlakoncept)
- Linkedin: [acushlakoncept](https://www.linkedin.com/in/acushlakoncept/)


## Acknowledgments
- [Sitepoint Article](https://www.sitepoint.com/react-rails-5-1/) on How to Build a React App that Works with a Rails 5.1 API
