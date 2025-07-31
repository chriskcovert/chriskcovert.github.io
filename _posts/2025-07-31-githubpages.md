---
layout: post
title:An Adventure in GitHub Pages Website Publishing
date: 2025-07-31 12:00:00
description: Sharing a story of publishing to GitHub Pages
tags: social
categories: professional
---

<hr>
I have been working on my professional portfolio site which is can be used to compliment one’s LinkedIn profile and presence. As a project manager by profession and more broadly a technology enthusiast, I wanted to create an online presence beyond profiles on Social Media Sites like LinkedIn. A lot of job application sites that are SaaS for companies that have job openings now have more than just a place to add your LinkedIn profile address in the submission page. 

Many job application sites now give the option to include not just a LinkedIn URL: 


-   Your personal website (the intention being your professional website) 
-   Github account 
-   Twitter account 
-   Instagram account 

And so I began my 1 month journey to create my own presence on the internet for my professional portfolio. That 1 month can be described as frustrating, liberating, filled with failures and triumphs. 

***First***, I needed to decide on how to host my professional presence.  I could use a free web hosting service that normally is free trial and then requires payment after the trial period is over.  I did not want to pay for it if not necessary. 

I could spin up my own Virtual Private Server on a Cloud Infrastructure Service Provider and use it to host my portfolio site and various projects on the go: n8n automation, business website and file storage.

My software development projects need version source control and I had already decided on Github.com . Well, low and behold, they have Github Pages feature which allows a person to host websites. 

***The journey:***

I discovered Jekyll templates that are used by Github Pages to host static websites. 

I was incorrectly lead down the path of installing my on web server on my PC to develop my Jekyll based website. Development would occur locally and then using Git and Github Desktop be pushed up to GitHub.com. 

This involves a tech stack and development tools of the following: 

-    Windows Power-shell
-    NPM
-    Node.js 
-    Ruby on Rails (used for Ruby Gem files – needed to make the website work: whatever those are.... ) 
-    Git 
-    Github Desktop 
-    Jekyll Template – I chose the Al-Folio template extremely popular and found in many tutorial wepages and YouTube videos. 
-    A JSON Linter for JSON: [JSONLint.com](https://www.jsonlint.com)JSONlint.com 
-    A Mark Down linter for MD Files: markdownlint-cli 
-    A YAML Linter for YML/YAML Files: [Yamllint.com](https://www.yamllint.com)
-    Text editor for various file editing: Sublime Text 
-    Github.com for hosting the GitHub Pages 
-    GitHub Actions for deployment of the site 

This is not for the feint of heart to go down this path if for you the journey is not part of the adventure on the way to your destination. I tried for 2 weeks, and probably 20 hours of time to get this website up and running just locally let alone running on Github. Had I managed to get the website running locally on my PC, it certainly would not guarantee it would work on Github where the amount of fine grained control would be even less. 

***It never happened.***

I dove deep into tutorials and videos on how to use all of these tools on my PC to host a web server. I read and posted at the Github Al-Folio Discussion board.   I searched far and wide in Reddit and Stack Overflow. 

Like how vibe coding might feel to non-coders: every time I got through 1 error, another was revealed, always eluding me. 

Then, I found the Youtube video that saved me but not without its own adventure. Apparently, you didn’t need to host first locally to design and test the Jekyll based website and then push to Github. 

All you need to do is edit the website Al-Folio repo files directly on [Github](https://www.github.com)

The entire techstack was now 

-   GitHub Pages 
-   GitHub Actions 
-   I still used yamllint.com and JSONlint.com for validation 

2 major events happened before the site was up and running as it exists now: 

1.) I wasted 2 weeks working with a seller on Fiverr to fix my Al-Folio site as I could not get it up even with the reduced difficulty. It was a waste of $31 CAD, but I got my money back sort of: I have $31 CAD in credits at Fiverr. I don’t think I can get much development or help for that amount, but it is there. 

2.) Every commit to a file on the Jekyll Repo triggers a half dozen Github actions. I was doing hundreds of commits as I fumbled may way through how to properly edit the mark down files to customized the template and make it my own. I had recklessly  turned on an integration between Github and my Discord Server: [Project Management Achievers (North America)](https://discord.com/invite/QZ2aY8dG). One Sunday afternoon after finally “getting it” I updated 15 files in about 10 minutes which triggered a hundred or more Github Actions. 

***This got my Github account permanently suspended*** for suspicious activity, I could not log into my account and the website was down. 

***The reason:*** “In particular, any repositories that use GitHub Actions solely to interact with 3rd party websites, to engage in incentivized activities, or for general computing purposes may fall afoul of the GitHub Additional Product Terms:” 

I opened a ticket with Github and begged foregiveness explaining what had happened. I was denied. I would have to start over with another GitHub account, not a huge set back, but frustrating. 

I decided to reach out to someone who works at Github on LinkedIn as going through their customer service desk was a dead end. There were 5400 people working at Github according to LinkedIn. With my wife's help we chose 4 people from the list of 5400 people to reach out to on LinkedIn. 

***Mental Note:*** *This would be a great n8n Automation to build for finding who to connect with on LinkedIn if you have interest in a large company. Perhaps it already exists.*

I direct messaged all 4 of them with my plight. One person got back to me and said they would see what they could do. The next day I saw that my account was no longer suspended and my Github pages portfolio site was back up and running! 

***Triumph:*** [chriskcovert.github.io](https://chriskcovert.github.io) 

If you are a project manager or product manager and would like help getting a GitHub Pages website up and running for your portfolio please message me. You can choose to do the Al-Folio Jekyll template for your site, or we can be adventurous, and you can choose from one of thousands of other free or paid for Jekyll Templates. 

<hr>
### Human Intelligence Metrics 

-[x]   Research: 1 hour
-[x]   Writing & Editing: 1 hour
-[x]   Peer Review / Feedback Loop: 30 minutes 
-[x]   Total Work Time: 2.5 hours 
-[x]   First Ideation: July 15, 2025
-[x]   Publication Date: July 31, 2025
-[x]   Total Elapsed Time: 16 Days