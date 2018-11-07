# vim-buildpack-heroku

## install
#### 1- manually
- go to [dashboard](https://dashboard.heroku.com/apps)
    * Personal 
- select `yourApp`
- Settings
- Add buildpack
- Enter Buildpack URL
  * type `https://github.com/Aissaoui-Ahmed/vim-buildpack-heroku`
  * Save changes

---
      Note:
       Your new buildpack configuration will be used when this app is next deployed.
---
#### 2- programmatically
```bash
$ heroku login
$ heroku https://github.com/Aissaoui-Ahmed/vim-buildpack-heroku -a `yourApp`  # you can "Vim" after Deploy
$ heroku run bash -a `yourApp`
  ~$ vim
```
