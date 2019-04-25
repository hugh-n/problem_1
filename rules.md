# 開発ルール

# プロジェクト開始
## 1. GitHub
### Collaborator
* Add this accounts as collaborator
  * hugh-n
  * andybit-okutama
### Projects & Issues
* Create two projects for admin and user
* Separate cards in projects into four groups
  * To do
  * In progress
  * Under Review
    * Pull request has been made
    * Review has been requested
  * Approved
    * Pull request has been approved
  * Done
    * Pull request has been merged
* Create issues using the cards
  * One issue = One Function
    * Ex. Migrations, Seed Data, Login Function
  * When creating an issue, create and assign a milestone to the issue
    * Milestone name will be for each week since the project development started 
      * Ex. Week 1 or 1st Week
### Branch
* Set [Require pull request reviews before merging] in repo settings
* Create one branch for one issue
  * Branch should be created from develop branch
  * Name of the branch should be: feature/#{issue_no}_{function_name}
### GitHub Commit
* Commit message must always start with the issue no.
  * Ex. #1: Created backend of login function
### Pull Request
* When an issue is finished, create a pull request using the issue branch
* You can name the pull request after the branch name or function
  * Ex. feature/#1_login
  * Ex. Login Function
* Assign [hugh-n] and [andybit-okutama] as reviewers
  * If there is no problem, the pull request will be approved and merged to develop
  * In case of an issue, a comment regarding the issues found will be made
  * Once the issues are fixed, please request a review again to both [hugh-n] and [andybit-okutama]

## 2. Coding

### Common
* Properly indent all lines
* Add comments to describe more complex parts of your code

### DB
* When you need to change a part of your database, you must create a new migration file. Do not modify previous files

### HTML / Blade
* Do not use the same [id] twice in one HTML file
* Keep [class] names consistent for all HTML files
* As much as possible, do not use inline CSS or Javascript
* Use [route('{route_name}')] for links if possible

### CSS
* Prioritize PC design first
* For mobile design, use:
  * @media screen and (max-width: 768px)
  * Anything else above will be considered as PC
* Order all lines from A to Z
  * For selectors, order them as follows: #id -> .class -> tag