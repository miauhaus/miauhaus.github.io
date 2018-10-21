open miauhaus
===
An opensource website for an opensource miauhaus

[miauhaus](https://miauhaus.github.io/) is an open research community

our mission is to enjoy sharing and creating knowledge

We are open to contributions that follow our conditions:

Responsibility – You take responsibility for your contributions (since we only host your content)

Civility – You support a civil environment and do not harass other users

Lawful Behavior – You do not violate copyright or other laws

No Harm – You do not harm our technology infrastructure, or other users

Terms of Use and Policies – You adhere to the below Terms of Use and to the applicable community policies when you visit our sites or participate in our communities

> All the data is public by design, no sensible data will be published, nor stored.

licensing
---
Each contributor owns it's contribution, and it's responsible of it

This is a publishing platform. Every contribution will published

The community keeps the right to decide weather or not to accept each contribution

Once accepted the content will published on the site, you can unplublish the content any time, by contacting us at `hey@miauhaus.org`

All content published is licensed with a [creative-commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/)

content
---
All content would be curated by the miauhaus community

We use [kramdown](https://kramdown.gettalong.org/quickref.html)

basics:
- `# first level header`
- `## second level header`
- `### third level header`
- `*italic text*`
- `**bold text**`
- `[link](http://www.miauhaus.org)`
- `![imagealt](http://www.miauhaus.org/assets/logo.png)`

Only links to elsewhere hosted media content (e.g. images, video...) are allowed

Images must be properly compressed

Content must have the following metadata:
  - *title*
  - *thumbnail*
  - *description*
  - *author*
  - *language*
  - *date*

colaboration
---
we embrace github [flow](https://guides.github.com/introduction/flow/)

we are open to contributions

quick guides
---
### first:
1. create a github account and login
2. go to [miauhaus github](https://github.com/miauhaus/miauhaus.github.io)

### add/edit research articles
1. go to `_research` folder
2. click on `create new file` or open an existing one and click the pencil for editing
3. Remember to name your file with the short title for your article, .md, use [kebab case](http://wiki.c2.com/?KebabCase)
4.add the following data at the beggining of the file:
```
---
layout: research
title: <<your title>>
description: <<your description>>
thumbnail: <<your thumnail url>> 300x425px
author: <<your name>>
language: << ISO 639-1 language code>>
date: << YYYY-MM-DD HH:MM >>
link: << optional >>
sections: [] << optional >>
---
```
5. add your content using markdown syntax
6. when you are happy with the result, `Propose file change` or `Propose new file`  and `create pull request`
> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/) and max-width for full width is 1280px

### add news
1. go to `_posts` folder
2. click on `create new file` or open an existing one and click the pencil for editing
3. Remember name your file following this format `yyyy-mm-dd-title` , .md, use [kebab case](http://wiki.c2.com/?KebabCase)
4. add the following data at the beggining of the file:
```
---
layout: post
title: <<your title>>
description: <<your description>>
thumbnail: <<your thumnail url 1280px x 128px>>
author: <<your name>>
language: << ISO 639-1 language code>>
date: << YYYY-MM-DD HH:MM >>
link: << optional >>
sections: [] << optional >>
---
```
5. add your content using markdown syntax
6. when you are happy with the result, `Propose file change` or `Propose new file`  and `create pull request`
> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/) and max-width for full width is 1280px

### add courses
1. go to `_courses` folder
2. click on `create new file` or open an existing one and click the pencil for editing
3. name your file with the title for your course, .md, use [kebab case](http://wiki.c2.com/?KebabCase)
4. add the following data at the beggining of the file:
```
---
layout: course
title: <<your title>>
description: <<your description>>
thumbnail: <<your thumnail url 260px height>>
author: <<your name>>
language: << ISO 639-1 language code>>
date: << YYYY-MM-DD HH:MM >>
link: << optional >>
sections: [] << optional >>
---
```
5. add your content using markdown syntax
6. when you are happy with the result, `Propose file change` or `Propose new file`  and `create pull request`
> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/) and max-width for full width is 1280px

### edit the home page
1. open `index.md`
2. when you are happy with the result, `Propose file change` or `Propose new file`  and `create pull request`

dev
---
The website it's super simple an flexible for evolution, uses [jekyll](jekyll.com) and [gh pages]() with almost no client side scripting, zero database. It embraces github as a collaboration platform

For localhosting, you can clone it and after installing ruby and jekyll you should be able to `jekyll serve` or `jekyll build`

builds will be saved at `_site`, all the styles will be located at `_sass`, there is no javascript yet and we are not usign any jekyll plugins.

open for contributions

keep it simple