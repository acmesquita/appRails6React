# App Example Rails 6 and React

## Pré-condições
```
  rvm use ruby-2.6.3
  rvm install rails@6.0.0
```

## Iniciando um projeto

```
  rails new PROJECT_NAME -BT --webpack=react
  cd PROJECT_NAME/
  bundle add react-rails
  rails webpacker:install
  rails g react:install
```

## Adicionando um recurso

```
  rails g resource User f_name:string l_name:string
  rails db:prepare // Cria um banco se ele não existir e roda as migrações
  rails db:seed
```