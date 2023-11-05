# Social-Network-Project


This repository documents the development of a social media app using Django and Python, focusing on various stages of its creation.

## Stage 1: Initial Project Setup and Authentication

- Building a social media app similar to Twitter using Django and Python.
- Demonstrates project folder setup, Django installation, and additional package installation (django-allauth and django-crispy-forms).
- Creation of apps for guest pages and social network views.
- Database migration and creation of a superuser.
- Setting up project templates with Bootstrap 5.
- Updating URL patterns for authentication views, requiring email as a registration field.
- Configuring Django settings to redirect users to the landing page after logging in.
- Focus on initial project setup, template configuration, and basic authentication.

## Stage 2: Adding Post Model and Basic Social Feed

- Continuation of app development with the addition of a Post model and a basic social feed.
- Creation of the Post model in Django, with fields for post content, creation date, and author.
- Definition of a view to list all posts and setup of corresponding URLs.


## Stage 3: Enhancing Social Feed and Comments

- Focus on enhancing the social feed project with the introduction of a comment model.
- Updates to the redirect URL after login and enhancement of the navigation bar.
- Introduction of a "post detail" view to display individual posts and comments.


## Stage 4: Finalizing Post and Comment Functionality

- Finalizes post and comment functionality in the web application.
- Enables users to edit and delete posts using Django's generic views.
- Implementation of user-generated comments listed under posts, with the newest comments displayed first.
- Implementation of edit and delete buttons for posts, visible only to the post's author.
- Utilization of Django's generic views and mix-ins to restrict access based on user authorization.
- Successful implementation of create, read, update, and delete functionality for both posts and comments in the application.

## Stage 5: User Profiles Implementation

- Implement user profiles in a Django web application.
- Allows users to create and edit their profiles.
- Sets up the media directory for profile pictures and default images.
- Creation of URL patterns, views, and templates for displaying user profiles.
- Introduction of a profile edit view for users.

## Stage 6: Follow/Unfollow Feature

- Discussion of the addition of a follow/unfollow feature to the social platform.
- Modifications to the user profile model.
- Creation of views and templates, including follower status and action buttons.

## Stage 7: Implementing "Like" and "Dislike" Feature

- Implement a "like" and "dislike" feature in a Django-based social media platform.
- Creation of "add like" and "add dislike" views for post interaction.
- Updates to HTML templates for post lists, profiles, and post detail pages to display like and dislike counts.

These stages collectively cover the development of a social media app using Django, addressing various aspects from initial setup and authentication to post management, user profiles, social interactions, and more.

To run the project : python manage.py runserver




This repository documents the development of a social media app using Django and Python, focusing on various stages of its creation.

## Stage 1: Initial Project Setup and Authentication

- Building a social media app similar to Twitter using Django and Python.
- Demonstrates project folder setup, Django installation, and additional package installation (django-allauth and django-crispy-forms).
- Creation of apps for guest pages and social network views.
- Database migration and creation of a superuser.
- Setting up project templates with Bootstrap 5.
- Updating URL patterns for authentication views, requiring email as a registration field.
- Configuring Django settings to redirect users to the landing page after logging in.
- Focus on initial project setup, template configuration, and basic authentication.

## Stage 2: Adding Post Model and Basic Social Feed

- Continuation of app development with the addition of a Post model and a basic social feed.
- Creation of the Post model in Django, with fields for post content, creation date, and author.
- Definition of a view to list all posts and setup of corresponding URLs.


## Stage 3: Enhancing Social Feed and Comments

- Focus on enhancing the social feed project with the introduction of a comment model.
- Updates to the redirect URL after login and enhancement of the navigation bar.
- Introduction of a "post detail" view to display individual posts and comments.


## Stage 4: Finalizing Post and Comment Functionality

- Finalizes post and comment functionality in the web application.
- Enables users to edit and delete posts using Django's generic views.
- Implementation of user-generated comments listed under posts, with the newest comments displayed first.
- Implementation of edit and delete buttons for posts, visible only to the post's author.
- Utilization of Django's generic views and mix-ins to restrict access based on user authorization.
- Successful implementation of create, read, update, and delete functionality for both posts and comments in the application.

## Stage 5: User Profiles Implementation

- Implement user profiles in a Django web application.
- Allows users to create and edit their profiles.
- Sets up the media directory for profile pictures and default images.
- Creation of URL patterns, views, and templates for displaying user profiles.
- Introduction of a profile edit view for users.

## Stage 6: Follow/Unfollow Feature

- Discussion of the addition of a follow/unfollow feature to the social platform.
- Modifications to the user profile model.
- Creation of views and templates, including follower status and action buttons.

## Stage 7: Implementing "Like" and "Dislike" Feature

- Implement a "like" and "dislike" feature in a Django-based social media platform.
- Creation of "add like" and "add dislike" views for post interaction.
- Updates to HTML templates for post lists, profiles, and post detail pages to display like and dislike counts.

These stages collectively cover the development of a social media app using Django, addressing various aspects from initial setup and authentication to post management, user profiles, social interactions, and more.

To run the project : python manage.py runserver



