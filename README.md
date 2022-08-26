# Hello Rails Back End

This is a demo project whose aim is to help me practice integrating my Rails application with a client side librart like React and use Redux for state management. 

The link to the front end PR can be found [here](https://github.com/isaka-lumato/rails-react-frontend/pull/1)


Enjoy!


# Built With
 - Ruby on Rails
 - React
 - Redux


# Additional Tools
  1. Rubocop
  2. Stylelint
  3. Ruby Gems

# Getting Started
To get local copy of the project and run

1. ``git clone git@github.com:isaka-lumato/hello-rails-back-end.git``
2. ``cd hello-rails-back-end``
3. ``gem install bundler``
4. ``bundle install``
5. ``rails s``

## Database Setup
Setup db

1. ``su - postgres``
2. ``psql``
3. ``create role isaka lumato createdb login password 'lumato'``
4. ``rails db:setup``
5. ``rails db:create``

# Tests

1. ``bundle exec rspec``
2. ``rubocop``

### Run your tests

1. ``rake``
2. ``rspec``

### To run rubocop we use:

1. `rubocop`

### To autocorrect offenses with rubocop we use:
1. `rubocop --auto-correct-all` or
2. `rubocop -A`

Have fun with TDD!

## Authors

👤 **isaka lumato**

- GitHub: [@isaka lumato](https://github.com/isaka-lumato)
- Twitter: [@isaka lumato](https://twitter.com/isaka_lumato)
- LinkedIn: [@isaka lumato](https://www.linkedin.com/in/isaka-lumato/)



## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/isaka-lumato/rails-react-api/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments
- My coding partners and Morning session partners.
- Microverse: [microverse community](https://github.com/microverseinc)

## 📝 License

This project is [MIT](./MIT.md) licensed.
