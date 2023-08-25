# Less Is More
_________________

A simple clean responsive hugo theme using bootstrap 5


## Main features 

- dynamic menu
- display with pagination
- tags
- categories
- archive page
- about page 
- responsive display
- google analytics


## How to get this theme


### Download this theme directly 


Download this theme and put it in your themes fold



### Using submodule Mode 

```
git submodule add --depth=1 https://github.com/m03315/lessIsMore.git themes/lessIsMore
git submodule update --init --recursive
```


## How to config

add below in your site config file :

```
theme ='lessIsMore'
googleAnalytics = ''

[author]
  name = "m03315"
  homepage = "https://m03315.github.io/"

[menu]
[[menu.main]]
  name = 'Home'
  pageRef = '/'
  weight = 10
[[menu.main]]
  name = 'Category'
  pageRef = '/categories'
  weight = 20
[[menu.main]]
  name = 'Archive'
  pageRef = '/archive'
  weight = 30
[[menu.main]]
  name = 'About'
  pageRef = '/about'
  weight = 40

[params]
  avatar_URL = '/img/avatar.png'
  bio = 'this is my bio example'
  peusedo = 'm03315'

[params.social]  
  twitter = 'https://twitter.com/m03315_'
  github = ''
  linkedin = ''
  google = '' 
  
```





