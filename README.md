# README

## Ruby on Rails 2024- Airbnb clone -HTML, CSS, JavaScript, TailwindCSS, Ruby, Rails, PostgreSQL

## Configuración para levantar el proyecto:
versión de ruby:
```code
ruby 3.3.0
```
versión de rails 
```code 
rails 7.0.8.3
```
versión de Bundler
```code
Bundler version 2.5.9
```

## instalar todas las gemas
```bash
bundle install
```
## crear la base de datos
```bash
rails db:create
```
## migrar la base de datos
```bash
rails db:migrate
```
## migrar los assets 
```bash
rails assets:precompile
```

## correr el proyecto
```bash
rails s
```





# Para crear en pdf las tablas en diagrama de la base de datos
En gemfile
```gemifile 
gem 'rails-erd'
```
Para instalar 
```bash
bundle install
```
Para generar el pdf en diagrama con la base de datos
```bash
bundle exec erd
```
