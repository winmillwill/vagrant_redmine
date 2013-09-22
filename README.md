# Easy Redmine

This is a simple example of using chef and vagrant to play with redmine.

If you want to play with ec2, you will need to export your ```AWS_ACCESS_KEY_ID```
and your ```AWS_SECRET_ACCESS_KEY```.

##TODO:

* Add shell provisioner or wrapper cookbook to install xslt, xml, and
  imagemagick dev package deps for nokogiri and rmagick.
* Add ```bundle install``` invokation.
* Add ```rake``` invokation for ```generate_secret_key```.
* Explore using the application_ruby cookbook to describe the rails app.



