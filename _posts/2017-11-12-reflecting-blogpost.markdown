---
layout: post
title:  "Reflecting blogpost"
date:   2017-11-12 00:26:19 -0500
categories: jekyll update
---

### Examination 1

1. What do you think of pre-compiling your CSS?

   - Compare to regular CSS

      There are some perks that comes with using css preprocessors. The goal is to make the code more readable, less repetitative and easier to maintain. This can be done by using for example by using variables, nesting, partials/imports, mixins or inheritence(extend). Math operators can also be used to help us process to code.

   - Which techniques did you use?

      I started this projekt by copying the minima-theme that has all of the above mentioned features. Then I just modified the already existing code to match what I wanted for my site. At first it was difficult to grasp but after reading up on how to work with sass it became more apparent.

   - Pros and cons?

      The pros are that by using a css preprocessor is that you do not have to repeat yourself as much as if you were writing standard css. As you can store a great deal of code and reuse it with the help of for example variables and mixins. In addition to this the code is also easier to structure as you can use partials/imports for modularization and nesting to display your code in a cleaner manner.

      One con is that the code is harder to debug, as the code is changed from sass to css the line where to error occurs in the css does not match the sass code. A con that i initialy experienced when starting this project, is that I had to use more programs and a specific setup to use these tools. Which took a decent amount of troubleshooting and tuning before it worked properly.



3. What do you think of static site generators?

    I consider them to be great tools if the goal is to have a website that is rather simple, easy to maintain, stable and secure. For this project I used Jekyll that once it was up and running, was very efficient for me to use.

   - What type of projects are they suitable for?

       In my opinion when you want to publish articles or write blogs, ssg:s are a perfect tool. Basically,in any case that you just want to display information that does not take too much of user interaction.

4. What is robots.txt and how have you configure it for your site?

   It is basically instructions for search robots and crawlers, what parts of the website that they should have access to. It is standard that before robots start to scan your website the look for the robots.txt in the root of the site. This works well for robots that is programmed to have good intentions, but malware robots and email harvesters will most likely scan the website anyway. As I have nothing to gain on this site being scanned by robots, I simply disallowed all.

5. What is humans.txt and how have you configure it for your site?

   It is a textfile that states the creator of the site and give credidentials to other contributors as well. The purpose of the file is that one can claim authorship of material displayed on the site, without being intrusive with the code. In the humans.txt file for this site a merely stated my authorship and provided an email adress.

6. How did you implements comments to blog posts?

   I created an account with disqus because their services are compatible with my site. Then I added a disqus-section in my \_config.yml where I stated my disqus-shortname. Then I used the code provided in the disqus_comments.html from the \_includes-folder. Finally I added a code snippet at the bottom of my post.html to load comments.


7. What is Open Graph and how do you make use of it?
   
   Open graph is a protocol that explains how a site should looked when shared on a social graph like Facebook or Twitter. To use it you need to include some meta-tags in the head of your site. I used four basic tags, title, url, image and type.