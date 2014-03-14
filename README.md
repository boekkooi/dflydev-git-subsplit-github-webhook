Git Subsplit GitHub WebHook for Openshift
===========================

This is a example repository for using https://github.com/dflydev/dflydev-git-subsplit-github-webhook on openshift.

Openshift setup
-----------------
To setup this repo on openshift you can do the following:
- Create a new PHP 5.4 Application
- Add the redis catridge (using the following url:  http://cartreflect-claytondev.rhcloud.com/reflect?github=smarterclayton/openshift-redis-cart)
- Restart the application (`rhc app restart -a <app_name>`)
- Clone this repo
- Add your application repo as a remote
- Add your config.json
- Do a git push to the application (`git push -f upstream`)
- Done!