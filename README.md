open miauhaus
===
An opensource website for an opensource miauhaus

[miauhaus]() is an open research community

licensing
---
Each contributor owns it's contribution, and it's responsible of it

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

we [chat]()

quick guides
---
### fork the repository
1. create a github account
2. go to [miauhaus github](https://github.com/miauhaus)
3. Press `fork!`
![](https://i.postimg.cc/nFCPKTwm/Screen-Shot-2018-10-15-at-02-01-55.png)

### add a research article

1. On your fork, click on `branch` and create a new branch with the name of your research article
![](https://i.postimg.cc/L54qthBB/Screen-Shot-2018-10-15-at-02-11-24.png)

2. with the branch selected, click on the `_research` folder
![](https://i.postimg.cc/1tXhDQVV/Screen-Shot-2018-10-15-at-02-13-37.png)

3. click on `create new file`
![](https://i.postimg.cc/MTLkDF1P/Screen-Shot-2018-10-15-at-02-14-21.png)

4. name your file with the short title for your article, .md, use [kebab case](http://wiki.c2.com/?KebabCase)

>add the following data at the beggining of the file:
```
---
layout: research
title: <<your title>>
description: <<your description>>
thumbnail: <<your thumnail url>>
author: <<your name>>
language: << ISO 639-1 language code>>
date: << YYYY-MM-DD HH:MM >>
link: << optional >>
---
```

5. add your content using markdown syntax and commit your changes. this will save a version of your file, you can come back to edit later
![](https://i.postimg.cc/D0Q9TytD/Screen-Shot-2018-10-15-at-02-20-43.png)

6. when you are happy with the result, make a pull request, as explained below.

> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/)

### add news
1. On your fork, click on `branch` and create a new branch with the name of your research article

2. with the branch selected, click on the `_posts` folder

3. click on `create new file`

4. name your file following this format `yyyy-mm-dd-title` , .md, use [kebab case](http://wiki.c2.com/?KebabCase)

>add the following data at the beggining of the file:
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
---
```
5. add your content using markdown syntax and commit your changes. this will save a version of your file, you can come back to edit later

6. when you are happy with the result, make a pull request, as explained below.

> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/)

### add courses

. On your fork, click on `branch` and create a new branch with the name of your research article

2. with the branch selected, click on the `_courses` folder

3. click on `create new file`

4. name your file with the title for your course, .md, use [kebab case](http://wiki.c2.com/?KebabCase)

>add the following data at the beggining of the file:
```
---
layout: course
title: <<your title>>
description: <<your description>>
thumbnail: <<your thumnail url 1280px x 128px>>
author: <<your name>>
language: << ISO 639-1 language code>>
date: << YYYY-MM-DD HH:MM >>
link: << optional >>
---
```
5. add your content using markdown syntax and commit your changes. this will save a version of your file, you can come back to edit later

6. when you are happy with the result, make a pull request, as explained below.

> Remember that all the images must be hosted at external services such as [postimg.cc](https://postimg.cc) or [flikr](https://www.flickr.com/)


### make a pull request

1. go to your github fork, and select `compare & pull request` from the main page, for the branch you want to merge.
![](https://i.postimg.cc/MGxj6sMF/Screen-Shot-2018-10-15-at-02-27-08.png)

2. review the data and click on create pull request
![](https://i.postimg.cc/zB2Lk8ds/Screen-Shot-2018-10-15-at-02-29-52.png)

3. wait for miauhaus feedback

contributors
---

