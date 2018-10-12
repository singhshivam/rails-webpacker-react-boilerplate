# Rails Webpacker React Boilerplate

This is a pure [Ruby on Rails](http://rubyonrails.org/) / [React](https://facebook.github.io/react/) / [Webpack 4](https://webpack.js.org/) boilerplate app.

## Getting started

    git clone git@github.com:singhshivam/rails-webpacker-react-boilerplate.git
    bundle install
    npm install
    rake db:create
    npm run webpack
    rails s


## To build the boilerplate from scratch

```ruby
    # create new rails app with webpack
    rails new rails-webpacker-boilerplate --webpack

    bundle install
     
    # generating dummy model
    rails generate model Article title:string content:text

    rake db:migrate
    
    # generating dummy controller
    rails generate controller Articles list

    # define root route to articles#list in routes.rb

    # install react
    npm install --save react react-dom
    bundle exec rails webpacker:install:react
```
