= Blog

This project rocks and uses MIT-LICENSE.


This is my first mountable engine.  It allows you to add posts to a blog

INSTALLATION

1.  ADD    gem 'blog', :git => 'git://github.com/johnybabylon/blog.git'   to your gemfile
2.  run Bundle Install
3.  in config/routes.rb put:  mount Blog::Engine, at: "/blog"
4.  run   rake blog:install:migrations
5.  run   rake db:migrate
6.  go to http://localhost:3000/blog/articles
7.  enjoy your blogging posts!!!!
