#  Jungle 

A mini e-commerce application built with Rails 4.2 for purposes of teaching Rails by example. This project was built by yours truly using Ruby on Rails, PostgreSQL, Rspec, Stripe and ActiveRecord.

Jungle looks like:

<b>Login</b>

!["Login"](https://github.com/Don-Stevenson/Jungle-Rails/blob/master/docs/Login%202020-02-12%2013-40-41.png)

<b>App Mainpage</b>

!["App Mainpage"](https://github.com/Don-Stevenson/Jungle-Rails/blob/master/docs/Login%202020-02-12%2013-40-41.png)

<b>Adding to cart</b>

!["Adding to cart"](https://github.com/Don-Stevenson/Jungle-Rails/blob/master/docs/Add%20to%20cart%202020-02-12%2013-42-28.png)

<b>My Cart</b>

!["My Cart"](https://github.com/Don-Stevenson/Jungle-Rails/blob/master/docs/MyCart%202020-02-12%2013-43-14.png)

<b>Paying</b>

!["Pay"](https://github.com/Don-Stevenson/Jungle-Rails/blob/master/docs/Pay%202020-02-12%2013-45-13.png)

##  Setup 

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

##  Stripe Testing 

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

##  Dependencies 

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe