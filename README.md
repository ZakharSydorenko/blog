

#My first rails blog.

By [ZakharSydorenko](https://www.facebook.com/zakhar.sydorenko.br/).

This app is:

* Rack based;
* Complete MVC based on Rails engines;
* Has posts, comments and auth.

It has one module: [devise](https://github.com/plataformatec/devise). It’s a flexible authentication solution for Rails.

## Getting started

Blog is based on Rails 4.2.6. To install this blog you should run command:

```console
git clone https://github.com/ZakharSydorenko/blog.git
```
Previous command will download all project files to your computer.

After you  download project you need to run:

```ruby
rake db:migrate
```
This will migrate the database using the script in the db/migrate.

After all this you need to go to the blog folder:

```console
cd blog
```

And run the command:
```ruby
rails s
```
It will start your local server.

Now you can open your browser and type:
```console
http://localhost:3000
```

You can also have some problems with the version of rake or something else.
It can be easily solved by running:
```ruby
bundle update rake
```
Instead of rake you could write something you have problems with.

## Some tips, which can help you to understand how the app works.

* Unsigned users can create only comments.
* To register you need to click the button register.
* As soon as you registered you can create, delete, edit posts and delete comments.
* For exit click button log out.
