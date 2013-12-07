coderwall-facebook-auth-example
===============================

Walkthrough of tutorial @ https://coderwall.com/p/bsfitw


Basic rails steps:

* git clone https://github.com/trh/coderwall-facebook-auth-example
* bundle install
* bundle exec rake db:migrate
* Add your facebook app id and secret as environment variables, e.g.
    export FACEBOOK_APP_IP=yourspecialappid
    export FACEBOOK_APP_SECRET=yourspecialsecretsssh
* Add the app id to the facebook.js.coffee
* you'll also need to go into your facebook app and edit the callback url
