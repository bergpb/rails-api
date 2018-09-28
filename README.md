# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* rails new name_app
* rails generate scaffold user name username password
* rails generate scaffold link title link tags visualized user:belongs_to

* Make a migrate: rails db:migrate
* Undo a migrate: rails db:rollback

* Create a new user:
User.create(:name => "berg", :username => "bergpb", :password => "123456")

* Create a new link:
Link.create(:title => "First", :link => "http", :visualized => true, :user_id => 1)