---
layout: post
title:      " `**CLI Data Gem Portfolio Project**`"
date:       2020-02-16 14:27:05 -0500
permalink:  cli_data_gem_portfolio_project
---






 So this is the culmination of my first module for my time here at Flatiron School.  Everything I have learned pushed into a 2 week project.  I thought, man two weeks should be plenty of time to get this project completed and looking amazing.  There are many other things involved in getting this project off the ground aside from just getting code down.

 First and formost was just finding a program that I would use to get my code written in.  I decided quickly to not use the Learn.co IDE sandbox.  The thought was that once I am out in the world I will need to use something else and why not just start now.  My first 'original code' written in a separate program and without the pre written tests to help solve my coding puzzles.  

 Next of course is just deciding what I want my project to do.  During my one on one with my cohort lead we narrowed down my interests to my love of video games.  With that decided why not write a program that can bring me sales of video games.  I want this to tell me not just what games are on sale but also the sale price, the store where this game is on sale, and when this sale expires. 

 The first website I attempted to scrape was Gamestop.com.  Gamestop turned out to be a disaster for a first time coder to scrape information on.  I did not have the experience to recognize why I was having so much trouble narrowing down the information I wanted.  As it turned out this page was full of javascript, which makes it extremely difficult for a newbie to scrape anything.  It is not impossible, just beyond my skills at the time of this project.  So, on my search went for a suitable site to gather my information for my project.

 Once a site was found, on went my scraping.  This too turned out to be tougher than I had planned.  With determination and some help of my cohort lead the scraper was working and the information I wanted was at my finger tips.  Now, the real project could start, presenting my information to my user in a usable manner.  Building the Cli and actually have it use my scraping and be an interactive experience.

 I watched video after video of building a cli. I wrote a cli, I deleted a cli, I rewrote a cli.  On and on this went trial and error until I got my cli to say hello and ask for choices and say goodbye. 

 First I needed to have my cli display my data in a usable numbered list.  
		 
	 `Deal.all.each.with_index(1) do |deal, index|
		puts "#{index}.  #{deal.title}"
	end `


This allowed my cli to get the name of the game from my scraper and display in order with a number assined to it.

```
1.  Sonic Mania (Nintendo Switch Download)
2.  PlayStation Plus 12-Month Card
3.  Sid Meierâs Civilization VI Platinum Edition (PC Download)
4.  Samurai Shodown (PS4) - Pre-owned
5.  Samurai Shodown (Xbox One) - Pre-owned
6.  Assassin's Creed Odyssey - Gold Edition (PC Download)
7.  Monster Hunter World (PC Download)
8.  Overwatch Legendary Edition (PS4) + Genji Figurine
```

 Turns out this was to be the easiest part of this project. Next I needed to allow my user to select one of these games and get more information about it.  This attempt resulted in may empty lists being displayed, and once I had a full list there was alot of information being displayed for games that were not selected.  

 With some help from my cohorts fellow students we were able to get my project and theirs put together and working to the best of our current abilities.  I am really looking forward to see what else this coding journey is going to bring me.  This project truly was a test of not just my ability with what I had learned, but also with my emotions and how I handle stress when being put to the test with a deadline.
 
