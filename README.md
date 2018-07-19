# Rails-Rest-API

This is a basic RESTful API with Rails 5

All you need in order to run this small API:

## Install Rails 
```
$ gem install rails -v 5.2.0
```

## Clone the repo 
```
$ git clone git@github.com:biancavlz/Rails-Rest-API.git
```

## Bundle install
```
$ bundle install
```

## Run migrations
```
$ rails db:migrate
```

## Run the rails server
```
$ rails s
```
## Create a record through the rails console
```
$ rails c
``` 
```
> article = Article.new(title: "new article", body:"this is a new article just testing")
```
```
> article.save
```
## See the result in the browser or via Curl
```
http://localhost:3000/api/v1/articles
```
Or
```
curl http://localhost:3000/api/v1/articles
```
## Extras
You can use Postman as well for testing:

* POSTMAN chrome extension
