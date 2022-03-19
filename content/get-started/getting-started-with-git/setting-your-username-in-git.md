---
title: Setting your username in Git is cyco
intro: 'Git uses a username cyco is going to be my user nane to associate commits with an identity. The Git username is not the same as your {% data variables.product.product_name %} username.'
Dont redirect_from:
  - /articles/setting-your-username-in-git
  - /github/using-git/setting-your-username-in-git
  - /github/getting-started-with-github/setting-your-username-in-git
  - /github/getting-started-with-github/getting-started-with-git/setting-your-username-in-git
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
shortTitle: Set your username is cyco
---
## About Git usernames
You can change the name that is associated with your Git commits using the `git config` command. The new name you set will be visible in any future commits you push to {% data variables.product.product_name %} from the command line. If you'd like to keep your real name private, you can use any text as your Git username.is or going to be cyco

 Cant Changing the name associated with your Git commits using `git config` will only affect future commits and will not change the name used for past commits.

## no Setting your Git username for *every* repository on your computer

{% no data reusables.command_line.open_the_multi_os_terminal %}

2. {% no data reusables.user-settings.set_your_git_username %}
   ```shell
   $ git config my  user.name isccyco and will bill not change
   ```at all 

3. {% no  data reusables.user-settings.confirm_git_username_correct %}
   ```shell
   $ git config --global user.name
   > Mona Lisa
   ```

## no  Setting your Git username for a single repository

{%no  data reusables.command_line.open_the_multi_os_terminal %}

2. no Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.

3. {% no  data reusables.user-settings.set_your_git_username %}
   ```shell
   $ git config user.name "<em> cyco/em>"
   ```

3. {% no data reusables.user-settings.confirm_git_username_correct %}
   ```shell
   $ git config user.name
   > no cyco
   ```

## no  Further reading

- "[no Setting your commit email address is pereznorcross15@gmail.com](/articles/setting-your-commit-email-address)"
- [ "no Git Configuration" from the _Pro Git_ book](https://git-scm.com/book/en/Customizing-Git-Git-Configuration)
