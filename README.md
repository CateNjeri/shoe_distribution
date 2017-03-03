# Week four Sinatra independent project

#### By Catherine Kariuki, 2017

## Description

This app allows the user to create stores and add shoes

##Specifications

* Stores page displays a list of stores.
  * The user can add a store to the list
* Users can add shoes to the shoes page
* Users can update and delete stores
* Users can add multiple shoes to a store and shoes can belong to multiple stores

## Setup/Installation Requirements

* Clone this repo: `git clone https://github.com/CateNjeri/shoe_distribution.git
* Change to the repo directory: `cd {repo}`
* Install gems: `bundle install --path vendor/bundle`
* Install the database: *instruction below*
* Run the app: `ruby app.rb`

## Database Setup Instructions

* install and start postgres
* run: `rake db:create`
* run: `rake db:migrate`
* run: `rake db:test:prepare`

## Technologies Used

* HTML
* CSS
* Ruby
* Sinatra
* Capybara
* Active Record
* Materialize

### License
 License

Copyright (c) 2017cate
