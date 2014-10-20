Spring Music
============

[Click here for original README](https://github.com/cloudfoundry-samples/spring-music/blob/master/README.md) (source repo).

## Deploy to CF (rapidly) ##

* Clone this repo (https://github.com/gfoligna/spring-music.git) 
  *  _cd spring-music_ and then compile it with (_./gladlew assemble_ as stated in the source README)
* Create a databse service in CF using the CF CLI. In this case the service we are expecting to use is MySQLso I suggest to name it “mysql-server” (or so) at the time you create it
* You are ready to push!
