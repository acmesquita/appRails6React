# App Example Rails 6 and React

##Pré-condições
```
  rvm use ruby-2.6.3
  rvm install rails@6.0.0
```

##Iniciando um projeto

```
  rails new PROJECT_NAME -BT --webpack=react
  cd PROJECT_NAME/
  bundle add react-rails
  rails webpacker:install
  rails g react:install
```

