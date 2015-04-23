---
layout: default
title: Homework 1 (Part 1)
---

Posted: Feb. 10 2015  
Last Update: Feb. 12 2015  

## Part I: Intro to R 

For this part you will add to the simple analysis on Baltimore arrests
we did in class. I have included the R markdown
source file in [this github repository](https://github.com/hcorrada/IntroDataSciBaltimore). You will be submitting this part
of Homework 1 as a pull request (so we can all see each other's work). 

### The steps

1.  [Fork the github repository.](https://help.github.com/articles/fork-a-repo)  
2.  Think about what analysis you might want to do  
3.  [Update to latest version of course repository](https://help.github.com/articles/syncing-a-fork/)  
4.  Update the `baltimore.Rmd` file accordingly. [Here is more information on R markdown](http://www.rstudio.com/ide/docs/r_markdown)  
5.  "Knit" a new `baltimore.html`
    file. [Here is how to do so in Rstudio](http://www.rstudio.com/ide/docs/authoring/using_markdown).  
6.  Repeat step 3 to make sure you will update the most recent version  
7.  Push your updated version to github (using `git push`)  
8.  Submit your assignment by [making a pull request](https://help.github.com/articles/using-pull-requests)  

### The rules

1.  There is a specific template I'm asking you to follow (e.g., use your username as the chunk name to get sane figure names). Please do so.  
2.  You can work groups (at most 4 per group).  
3.  You can't repeat an analysis already submitted by another student/group. If you see that somebody else did what you wanted to do when
you updated (steps 3 or 6 above), you need to come up with something new.  
4.  Feel free to use more data from the [OpenBaltimore data set](https://data.baltimorecity.gov/) if you want.  

### Workflow

{% highlight bash %}
# fork your repository on github
git clone https://github.com/<yourusername>/IntroDataSciBaltimore.git

# modify baltimore.Rmd to do your analysis

# if you add new data
git add <path>

# commit your changes (as often as you want)
git commit -am "I've made some changes"

# add my repo as remote (only need to do once)
git remote add upstream https://github.com/hcorrada/IntroDataSciBaltimore.git

# update from my repository (you may need to resolve conflicts)
# you can do this step as many times as needed (most importantly before submitting your pull request)
git pull upstream

# push your changes to your github repository
git push origin master
{% endhighlight %}
