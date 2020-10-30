# Newsness - Hardware News

> A News Site by C.Hohn, R.Abdulbari, P.Auffermann, L.Haeussler
## Linux Runtime Installation
``` bash
# Dowload Ubuntu Windows Runtime here:
https://www.microsoft.com/de-de/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab

# For Further installation help use:
https://docs.microsoft.com/de-de/windows/wsl/install-win10

# After installation Navigate with cd ../../mnt zu den Windows Festplatten. 
Mit dem Befehl ls können alle verfügbaren speicherorte abgerufen werden.
```

yessir
## Build Setup (- Use on a webserver)

``` bash
#install npm
$ sudo apt update
$ sudo apt install npm

# install vue Framework
$ sudo npm install -g vue-cli

# Creating a Vue Project (Ab hier wir ein Projekt erstellt)
$ vue init webpack (beispielname)

# naviagte to the Project Folder
$ cd (beispielname)

# install dependencies
$ sudo npm install

# serve with hot reload at localhost:8080
$ npm run dev

You can now access the Baisc webpage on localhost:8080 in your Webrowser
```
## Installing Bootstrap 

```bash
# navigate to your Project folder ($ cd {beispielname})

# installing Bootstrap
$ sudo npm install vue bootstrap-vue bootstrap
```
#### Register the programm in your App.vue file
```css
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'

// Install BootstrapVue
Vue.use(BootstrapVue)
// Optionally install the BootstrapVue icon components plugin
Vue.use(IconsPlugin)
```
## Setting up Subpages
Check out the router page integration [here](https://stackoverflow.com/questions/54923395/set-up-router-for-subpages-in-vue-js) or in the originaly more detailed version [here](https://router.vuejs.org/guide/#javascript)!


For a detailed explanation on how things work, check out the [guide](https://medium.com/codingthesmartway-com-blog/vue-js-2-quickstart-tutorial-2017-246195cfbdd2).
For futher instuctions into Bootstrap use: https://bootstrap-vue.org/docs
