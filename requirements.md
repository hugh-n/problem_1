# TEST BLOG PROJECT
## SUMMARY
Create a blog-like system that allows users to register an account; through that account, users can create their own blog posts which will show up on the front page.

## LANGUAGE
* PHP
* MySQL

## DEVELOPMENT FLOW
* At the start, the assigned developers must create a Detailed Requirements and Designs of the system based on the System details listed below.
* Detailed Requirements must cover the following:
  * Functions List
  * System Flow
  * ERD
* Upload made documents to Qiita
  * Functions List
  * Diagrams
    * System Flow
    * ERD

## USER SIDE FUNCTIONS
* User Signup
  * Allow guests to register their own account

* Login Function
  * Allow guests to login through the account they registered

* Logout Function
  * Allow logged-in users to logout

* User Profile
  * Logged-in users should be able to do the following in regards to their profile
	  * Edit Function
  * User Profile should contain the user's registered information
  * User Profile may also include information about the user's posts such as 
    description of what the user will post / blog about

* Posts
  * Logged-in users should be able to do the following in regards to posts
    * Create Function
    * Edit Function
    * Delete Function
  * One post can only have one user / One user can have many posts

* Post List
  * Show a list of all created posts
  * Can search by post title or username

* User Post List (Blog)
  * Similar to post list only it shows the posts of a specific user
  * Also shows some information about the user such as their name, email, blog description

* Like Function
  * Allow logged-in users to like posts of other users

* Comment Function
  * Allow logged-in users to comment on posts of other users

## ADMIN SIDE FUNCTIONS
* Login Function
  * Allow admin to login

* User List
  * Shows list of all registered users
  * Can search by user name or e-mail address

* Disable User Function
  * Allow the admin to disable user accout

* Re-enable User Function
  * Allow the admin to re-enable disabled user accounts

* Logout Function
  * Allow admin to logout

* Post List
  * Show list of all created user posts
  * Can search by post title or username

* Edit Post Function
  * Allow admin to edit any posts

* Delete Post Function
  * Allow admin to delete any posts

* Comment List
  * Show lists of all comments made by users
  * Can specify to show only comments of one post

* Delete Comment Function
  * Allow admin to delete any comments