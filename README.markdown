# Octopress Theme Blaze
"Blaze", a [my blog](http://yaakaito.gituhb.com/) template.

## Warning
This version is  prototype. Has no supported diverse default functions.
I'll support functions, if needs it.
if you want a function, please Pull Reuqest.

## feature
* Angular.js
  * Archives filter
  * Rewirited github, coderwall and recent_archives
 
## Install
```
cd octopress/.theme
git clone http://github.com/yaakaito/octopress-theme-blaze.git
rake install\["blaze"\]
```
- Setup _config.yaml
 - `default_asides`
  - `[asides/recent_posts.html, asides/github.html, asides/coderwall.html]`
  - This template not supported `twitter`, `delicous` , etc . because blaze using Angular.js. if you want support asides, use Angular.
 - Coderwall badges
  - add `coderwall_user: {user_name}`
 - Posts in the index page
  - add `index_posts`: {posts}` 
