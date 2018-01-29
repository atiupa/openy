In order to compile css here are the necessary steps:

- enter vagrant
- go to theme directory *cd ../../var/www/docroot/themes/custom/openy_lily/*
- *sudo apt-get install ruby-compass*
- *sudo apt-get install bundler*
- *sudo gem install autoprefixer-rails -v '6.4.1.1'*
- *bundle install*
- *sudo compass watch --poll*
- or if you need to compile css one time - *bundle exec compass compile*