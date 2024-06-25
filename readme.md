deploy with heroku before adding ci-cd:


1) install heroku CLI
2) Add procfile
3) run `heroku login`
4) run `heroku create`
5) run `git push heroku main`
6) run `heroku ps:scale web=1`
7) Go to Heroku config vars and set your DB connection string

