# WSP_Assignment_8_Node.js
This repository is the part of work in assignment 8 of WSP subject.

## Guest Section

For guest, at homepage use can see all of the topic in our database.
![homepage](./doc/guest/1home.png)

You can click to the topic and read the information of it. You can also see who the author is, but you can't edit or delete any topic.
![article](./doc/guest/2article.png)

In case of you want to try to force edit by put /edit in url, you will be redirected to login page and you will get "Please Login" message.
![try_to_edit](./doc/guest/3try_to_edit.png)

If you want to add your own article, you can register at register page.
![register](./doc/guest/4register.png)

## User Section

This is the homepage for users after they login
![homepage](./doc/user/1home.png)

In article page if this topic is your own, you can edit or delete it.
![article](./doc/user/2article.png)

You can change title and contents of your article.
![edit_article](./doc/user/3edit_article.png)

Or if you want to delete, you can delete it
![delete_article](./doc/user/4delete_article.png)

For user who want to add article you can click on "Add Article" at the top and you can create your own topic
![add_article](./doc/user/5add_article.png)

And when you click submit you will be redirect to homepage and get message "Article Added
![add_article_success](./doc/user/6add_article_success.png)

At login page, In case your user is correct but password isn't, you will get "Wrong password" message.
![wrong_password](./doc/user/7wrong_password.png)

But in case your username isn't match any user in database, you will get "No user found" message.
![no_user_found](./doc/user/8no_user_found.png)

## For account who doesn't own article

For other account who want to try to edit or delete the article that you don't own. you can't do it.
![other_user_edit](./doc/user/other_account/1other_user_edit.png)

Or in case you want to try to force edit by put /edit in url you will be redirected to homepage and get "Not Authorized" message"
![try_force_edit](./doc/user/other_account/2try_force_edit.png)

![force_edit_result](./doc/user/other_account/3force_edit_result.png)
