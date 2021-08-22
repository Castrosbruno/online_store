My first basic CRUD project in ruby on rails, done along the course of alura

Today the system is running on heroku at: https://onlinestorex.herokuapp.com/

I am not responsible for the products or departments created in this environment because anyone can access and create!

To install locally:

1- Download ruby 2.5.1:

https://www.ruby-lang.org/en/downloads/

Installation:

1- Clone the project repository:

git clone https://github.com/Castrosbruno/online_store.git

2- Enter the root of the cloned project and run the commands below step by step:

cd online_store

3- Install the gems:

bundle install or bundle

4- Run the migrations:

rake db: migrate

5- Start the application:

rails s
