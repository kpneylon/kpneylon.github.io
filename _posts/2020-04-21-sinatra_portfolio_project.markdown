---
layout: post
title:      "**Sinatra Portfolio Project**"
date:       2020-04-22 02:51:08 +0000
permalink:  sinatra_portfolio_project
---


 Well this project was the one to almost take me out.  Let me tell you though I am way more comfortable with routes than I was at the beginning of this module.  I had decided to make a web application that would allow a user to create an account and make themselve a list of video games they own and which system each game was on.  

To begin I learned how to set session in the application controller, this allows users to create a unique view of things that other users are unable to see.  All I required was a username and a password, this would allow the user to login and be shown their homepage.

	 `get '/login' do
		if !logged_in?
		erb :'/users/login'
		else
			redirect "/users/#{current_user.slug}"
		end
	end`
		
Slug is a nifty tool I found I could use that would take any user input and remove any whitespace, making into dashes, and make any letters lowercase.  It also removes any special characters. This is to create a friendlier looking url for the user with all any special characters in it.

Once the user is logged into their unique session they can began adding games, Upon adding a game they will be returned to their show page where their list of games will be shown.

From there they can choose to edit a particular game, either changing the name the system or both.  On the edit screen they may also delete a game from their list and be brought back to the show page or their home screen.

On the top of the each page is a nav bar that shows the users username and a link with which to logout.

This project really challenged me, in the way that I think about code and where and how far I will go to look for answers.  I struggled quite a bit with my edit method and the form that uses it.  I learned how to route paths across controllers and get everything to function together.  I am looking forward the learning in the rails module and see how far I can go with coding as my new career.


