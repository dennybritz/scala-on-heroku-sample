This is a sample project that shows how to deploy a Scala application on Heroku. The application was built based on the tutorial at [https://devcenter.heroku.com/articles/scala](https://devcenter.heroku.com/articles/scala).

## Components

- `src/main/scala/Web.scala` - The application code. Starts a Jetty server that responds with "Hello World"
- `project/build.sbt` - Adds the [sbt-start-script plugin](https://github.com/sbt/sbt-start-script). The plugin is needed for the `stage` task that Heroku uses to build the application.
- `project/build.properties` - Defined sbt version.
- `build.sbt` -  Project settings and dependencies. Also includes the the tasks and settings from the [sbt-start-script plugin](https://github.com/sbt/sbt-start-script)].

## Deploying to Heroku

Make sure you have the [Herkoku Toolbelt](https://toolbelt.heroku.com/) installed.

```shell
# Create a new heroku application
heroku create 
# Push the repo to heroku
git push heroku master
```