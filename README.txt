Hello and welcome to my coding prototype on Ruby on Rails.

The following code following MVC conventions and the CRUD (Create Read Update Destroy) methodology for two related databases - journal entry titles and the entries themselves.

To intialize the code, first enter the ~/blog directory
Then, run "bin/rails db:migrate RAILS_ENV=development" to import the environment before running "bin/rails server". You can now type in localhost:3000 on your internet browser. To create, edit or destroy an entry, the username authentication is "admin" with password "intern".

A bonus feature includes Exception Handling Style that you will see if you attempt to enter a title less than 5 words long, or a blank title. Regrettably I was unable to merge my Devise and CanCanCan authentication syntax with this framework in the time constraints of finals and moving out week.

Thanks for your time!


A few sources that proved helpful were:
https://www.sitepoint.com/cancancan-rails-authorization-dance/
http://guides.rubyonrails.org/getting_started.html#listing-all-articles
https://www.nopio.com/blog/authentication-authorization-rails/
https://github.com/CanCanCommunity/cancancan
https://github.com/plataformatec/devise
https://www.ruby-lang.org/en/documentation/

