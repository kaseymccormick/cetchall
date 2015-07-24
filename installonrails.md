##How to Install Bootstrap on Rails Without sass:##
1. remove turbo links http://blog.steveklabnik.com/posts/2013-06-25-removing-turbolinks-from-rails-4
2. In Gemfile, “gem "twitter-bootstrap-rails"”(in terminal)
3. Then “bundle install” (in terminal)
4. After bundle install, run: rails generate bootstrap:install static  (in terminal)
5. create your layouts by typing “rails g bootstrap:layout variable”(in terminal)  (variable is the name/title you want your layout to have)
	* naming your layout the same as your controller will allow all of the views for that controller to adopt that layout








**Resources:**

* https://github.com/seyhunak/twitter-bootstrap-rails - this is where the steps are found also includes activated sass functionality steps 
* http://api.rubyonrails.org/classes/ActionView/Layouts.html
