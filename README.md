# Fira random tools

If the fira is comming you might need tools that help do this more quick. 

## Pre requirements 

- Install [Heroku Toolbelt](https://toolbelt.heroku.com/).
- Install sbt
- Install play  
- Install java


## Running Locally  

```sh
$ git clone https://github.com/Dsuarezj/scala-getting-started.git
$ cd fira-random-tools
$ sbt compile stage
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Play and Scala on Heroku, see these Dev Center articles:

- [Play and Scala on Heroku](https://devcenter.heroku.com/categories/language-support#scala-and-play)

