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

# API

GET     /api/users								- api/users#index
POST    /api/users(.:format)                  	- api/users#create
GET     /api/users/:id(.:format)     		    - api/users#show
PATCH   /api/users/:id(.:format)              	- api/users#update
PUT     /api/users/:id(.:format)              	- api/users#update
DELETE  /api/users/:id(.:format)              	- api/users#destroy
GET     /api/users/typeahead/:input(.:format) 	- api/users#typeahead

* ...
