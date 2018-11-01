# README

Things you may want to cover:

* Ruby version - '2.4.4'

* System dependencies - 
 - System should have ruby and rails installed.
 - It requires 'Postgres, Nginx, Docker' to be installed in the system.

* How to run the test suite
-  bundle exec rspec spec/controllers/currencies_controller_spec.rb


* Testing instructions - 
- To login with facebook use test user credentials -:
  - email - test_gbzaxmy_global@tfbnw.net
  - password - currencies123
- For testing I have kept AppKey and Secret key both open in devise.rb, whereas keeping them in secret file is the right way of doing it.