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
  * Can specify url of their blog page
  * User Profile should also include the following information
    * Description about what the user will blog about
    * A header image for their blog

* Blog Posts
  * Logged-in users should be able to do the following in regards to blog posts
    * Create Function
    * Edit Function
    * Delete Function
  * One post can only have one user / One user can have many blog posts

* Blog Post List
  * Show a list of summaries of existing Blog Posts
  * Can search by post title or username
  * Blog Post Links should follow the url specified by the user in their own profile

* User Blog Post List
  * Similar to Blog Post list only it shows the blog posts of a specific user
  * Also shows some information about the user such as their name, email, blog description

* Like Function
  * Allow logged-in users to like Blog Posts of other users

* Comment Function
  * Allow logged-in users to comment on Blog Posts

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

* Blog Post List
  * Show list of summaries of existing Blog Posts
  * Can search by Blog Post title or username

* Edit Post Function
  * Allow admin to edit any Blog Posts

* Delete Post Function
  * Allow admin to delete any Blog Posts

* Comment List
  * Show lists of all comments made by users
  * Can specify to show only comments of one post

* Delete Comment Function
  * Allow admin to delete any comments