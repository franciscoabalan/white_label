# WhiteLabel
This repo constains Ruby on Rails 6 code from training WhiteLabel project.
Following this documentation you will be able to clone, setup the project and leave ready to start coding.

## General Info
You must consider we are working with the next technologies:
* Ruby: `2.6.2`
* Rails: `6.0.3`
* Postgres: `>= 10.3`

## Cloning Project
* Clone the repository by running `git clone https://github.com/franciscoabalan/white_label.git`
* Enter in the project directory `cd white_label`
* Execute `bundle install`

## Enviroment Variables
* create a new file `/config/master.key`
* get the master key code with your lead backend

## Database Config
if you don't have installed postgresql please follow that [instructions](https://www.robinwieruch.de/postgres-sql-macos-setup)

* create postgres user `pj-whitelabel`
```bash 
        psql postgres
        CREATE ROLE "pj-whitelabel" LOGIN SUPERUSER PASSWORD 'pj-whitelabel';
```
* create db `rails db:create`
* migrate db `rails db:migrate`

## Run the app
* execute `rails s``

You are ready for coding :D