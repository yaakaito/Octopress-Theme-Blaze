# Octopress Theme Blaze
"Blaze", a my blog template.
e.g. http://yaakaito.gituhb.com/

## feature
- import Angular.js
 - Archives filter
- Plugings
 - Language marked Github
 - Coderwall Badges

## Install
```
cd octopress/.theme
git clone http://github.com/yaakaito/octopress-theme-blaze.git
rake install\["blaze"\]
```
- setup _config.yaml
 - `default_asides`
  - `[asides/recent_posts.html, asides/github.html, asides/coderwall.html]`
  - This template not supported `twitter`, `delicous` , etc . because blaze using Angular.js. if you want support asides, use Angular.
 - coderwall badges
  - add `coderwall_user: {user_name}`

