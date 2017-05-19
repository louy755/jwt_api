# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
add  a new user >>
 User.create(email:'a@a.com', password:'changeme', password_confirmation:'changeme')

#from new terminal
curl http://localhost:3000/home<!DOCTYPE html>
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
curl -X POST -d email="a@a.com" -d password="changeme" http://localhost:3000/auth_user



