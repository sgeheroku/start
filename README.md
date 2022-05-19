# start
start: learning experimenting consuming

```
$ heroku login

$ heroku create --> creates new app on heroku
	»   Warning: heroku update available from 7.53.0 to 7.60.2.
		Creating app... done, ⬢ salty-ridge-99999
		https://salty-ridge-99999.herokuapp.com/ | https://git.heroku.com/salty-ridge-99999.git

goto heroku.com --> select an app newly created --> go to deploy --> copy command for git push
	$ cd expressCourse/
	$ git init
			Initialized empty Git repository in C:/****/Softwares/Projects/expressCourse/.git/
			
	$ heroku git:remote -a salty-ridge-99999
			set git remote heroku to https://git.heroku.com/salty-ridge-99999.git
	
	$ git add .
	$ git commit -am "make it better"
	$ git push heroku master

```
