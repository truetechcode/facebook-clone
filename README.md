# FACEBOOK CLONE

The challenge is to create a minimal working facebook clone with the the underlying database and controller structures, but not the realtime notifications (i.e. backend focused).  It's a learning exercise set by [The Odin Project](https://www.theodinproject.com/courses/ruby-on-rails/lessons/final-project?ref=lnav).

[Live Preview](https://mysterious-waters-41144.herokuapp.com)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

This project runs on [Ruby](https://www.ruby-lang.org/en/documentation/installation/), and [Rails](http://installrails.com/)

After installation, run `ruby -v` to make sure Ruby installed correctly. Example
```
$ ruby -v
ruby 2.3.0p0 (2015-12-25 revision 53290) [x86_64-darwin17]
```

Also make sure that Rails is installed, but running `rails -v`. 
Example
```
$ rails -v
Rails 5.1.6
```

### Installing

Run `bundle install` to install all project dependencies.

### Serve Project

Run the server with the following command:

```
rails s
```

Once its running, head over to your browser to [see Facebook clone](http://localhost:3000/).


### Running Tests

To run the project tests, run the following command:
```
rspec -f D
```

### Deploy on Heroku

You can deploy the project on [Heroku](https://www.heroku.com/) using the following steps:

1. Create a Heroku Account
2. On the terminal, run `heroku create` to create a new app
3. Run `heroku push` to start a deployment on Heroku.
4. Run `heroku migrate` to run migrations on your production database.
5. Visit your project URL as assigned by Heroku to see a live deployment of Facebook clone.

## Authors

* **Tever Aosu** [truetechcode](https://github.com/truetechcode)
* **Raphael Noriode** [Oghenebrume50](https://github.com/Oghenebrume50)

## License

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
