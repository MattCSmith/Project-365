# Project-365

I started a very ambitious project... 365 Days of Code Challenge! Similar in nature to the [100 Days of Code Challenge](https://www.100daysofcode.com/), I will be spending a minimum of 1 hour each day of 2021 working on a personal project hopefully learning a thing or two and improving my coding abilities. I intend to work on a couple of projects, each containing elements that should push me out of my comfort zone and allow me to expand my knowledge and skill set. You can check out my plans in the video below:

[![365 Days Of Code](https://cdn.discordapp.com/attachments/743608750635483297/794663588211720192/365_Days-small.png)](https://youtu.be/e2tShvgFYaI)

It would make my day if this encourages even one person to sign up to the 100 Days Challenge. You can find out more about the challenge here: https://www.100daysofcode.com/. Reach out if you are starting a coding challenge project of your own, I'd love to check it out.

## Useful Links

- Follow me on [**Twitter**](https://twitter.com/MattCSmith_) for daily updates.
- Subscribe on [**Youtube**](https://www.youtube.com/channel/UCQnCh_U9PeXh_7FaxUB7Lsg) for periodic update videos.
- [Other Links can be found here](https://linktr.ee/mattcsmith)

## Day 1
Spent a good couple of hours setting up and configuring Gatsby, Contentful and Netlify as the foundation to the first project.
Worked a little on bringing the exisiting navbar and landing page to the newsite with Styled-Components.


## Day 2 
Today was really a project architecture day. Starting out with project mapping, followed by creating some Contentful content types and finished up with a little component. 

## Day 3
Spent an hour today building out the footer component, making consideration on how I want to integrate this to Contentful in the near future. Also spent a little time considering a couple of features I want to implement down the road. 

## Day 4
Built out a Contentful content type for the footer and integrated it into the footer. Worked on the community section of the homepage, bringing the homepage to an almost complete state. A few tweaks and mobile quires should be enough to finish this page off. 

## Day 5
Set up Gatsby to dynamically create pages for each game server, based on the data it gets from the Contentful model. Experienced a weird issue where netlify does not appear to have the style sheet for the new page. Will investigate more tomorrow. 

## Day 6 
Investigated the bug that plagues the server page, unfortunately it remains unsolved for now. Its appear not to be utilising styled components on these generated pages. 

## Day 7
With a little help finally solved the issue with the server page today. I plan to spend the time reading the articles I was provided below to fully understand the issue at hand. But essentially, local was using a webpack file to directly build from the dependancies with a webpack server, where production was building out the static Gatsby files.  
- [Understanding the Gatsby lifecycle](https://www.narative.co/articles/understanding-the-gatsby-lifecycle)
- [Gatsby bootstrap lifecycle](https://gist.github.com/sw-yx/09306ec03df7b4cd8e7469bb74c078fb)
- [The Perils of Rehydration](https://www.joshwcomeau.com/react/the-perils-of-rehydration/)

## Day 8
Added infinite scroll to the member cards and implmeneted drop down menus to the navigation bar. 

## Day 9
Made some decent progress on the server page template. Still a few things I want to add, but that might come in a future iteration. 

## Day 10 
Fixed a deployment tooltip issue and implemented a file download section. Aside from some styling and minor tweaks this completes the server page. 

## Day 11
Spent some time today cleaning up the code to make it more efficient. Also restyled the member cards a little bit to match the styling on the server page. 
I'm not pushing the latest changes this evening since I broke/removed alot to make the chances to the homepage. I'll push up tomorrow when I have it in a much better state. 

## Day 12
Today was one of those days where motivation and cognitive ability was rather on the low side, due to a busy and overwhelming personal day. As a planned method to deal with days like these, I switched up the routine a little bit, working on content, laying it out and making small optimisations to the code and styling and other non demanding tasks I had otherwise been putting off. Overall I am feeling rather happy with the progression of the project in just 12 days. 

## Day 13
Spent time refactoring the pages today. Hardcoded content on the index page is now fetched from Contenful. All of the original title bars have been replaced with the new Floating title bar component. 
Hoping tomorrow, I can look into creating an application form that is powered by Netlify forms and integrates with PlanBs Discord bot via Netlify's serverless functions. 

## Day 14
Form time! Started laying out the form and making considerations on how I want this to intereact with both Netlify forms and the Discord bot. The current system has the form hits the bots endpoint directly. Which is great but this was a great opportunity to experiemtn with Netlify forms and deal with a flaw in the current system. If the Discord bot was down or errored out, the applicants data would be lost. With Netlify forms we have a failsafe. 

## Day 15 
Bug Hunting! Today was unforuntatly no very productive due to the realisation that forms are not discoved by as Netlify forms if they are state dependant. Because I want to conditionally render the form, I will need to figure out another method. 

## Day 16
Switched things up today and worked on a small Node project. Half way through this micro project, will reveal more once complete. 

## Day 17
Worked on the frontend for the secret micro project today. Was a nice change going back to plain react. Its been that long I forgot how things like React Router worked. Was a good little refresher project all round. Also remembered why I hate CORs

## Day 18
Refactoring the backend and looked into ways to improve the project. Also Identified a couple of bugs that need fixing. 

## Day 19
The twitter bot I have been working on picks up a lot of irrelevant content and spam. Spent some time looking into the Sentiment npm package, which is pretty cool. But it wasn't really build to solve the problem I was facing, so I build a basic version of Sentiment that fit my needs. 

## Day 20 
Worked on a couple of methods to reduce the spam collected by the twitter bot. Unfortunately nothing seems to be perfect. 

## Day 21 
Worked on the Twitter bots logging system, logging sample Tweets ready for analysis to help improve the filtering process. 

## Day 22 
Today I worked on a dummy implementation of One Time Password authentication. Authentication is often something that comes up in projects I get involved with, so I thought it would be worth investing sometime figuring different auth types. 

## Day 23
Finalised the filtering system on the Twitter bot and heavily refactored the code base. I am now confident the project is in great shape for maintenance and future development. Just a few things left to tidy up and a couple of features to implement.  

## Day 24
- ✅ Refactor complete
- ✅ Improved API
- ✅ Implemented #jsdoc, will be using this in all my future projects!

Note: [JSDoc](https://jsdoc.app/about-getting-started.html) is such simple yet underated functionality to annotate functions. Great in multi-contributor projects but also in solo projects. I have lost count the amount of times I have to go look up what params my functions take. 

## Day 25
- ✅ Added caching to the API endpoints
- ✅ Found and fixed an evasive bug
- ✅ API improvements

Caching endpoints was something I have often overlooked when working on APIs and something I have never worked with before. So it was great to learn something new, but it should also prove super useful in reducing the APIs response time. Which on some endpoints can be a little longer that I would have liked, I might have to consider breaking up the data served on some of these endpoints or even consider pagination of some sort. 

## Day 26
- ✅ Further API enhancements

Scope creep can be a real problem in project. I think today I realised just how far this project has crept. The API is looking much better for it, but I may need to consider drawing a line for V1 release. 

## Day 27
- ✅ Completed the API, pending some minor tweaks required by testing
- ✅ Cleaned up the code
- ✅ Deployed

I consider v1 of the backend portion of this project complete. I will be closely monitoring it running over the next couple of days and making minor tweaks as required. 

## Day 28
- ✅ Mapped out a rough plan for v1 of the front end
- ✅ Made some adjustments to the front end and fixed leaderboard
- ✅ Spent some time looking over the backend logs and database, identified some bugs

## Day 29
- ✅ Fixed API bugs identified yesterday
- ✅ Leader card style and feature enhancements

## Day 30
- ✅ Enhanced the leader card styling
- ✅ Implmented placeholder animations

Love the cool effect packages such as `react-content-loader` can add to the loading state of an application. 

## Day 31
- ✅ Implemented Google Analytics and Tag Manager
- ✅ Finished styling and functionality of all components and pages. 

- ✅ Project is almost complete.

## Day 32
- ✅ Discovered 3 bugs
- ✅ Fixed one & added some console.logs to capture more data for another
- ✅ Spent some time considering workarounds for a pretty critical issue with not being able to fetch the users timezone from the twitter API. Without the users timezone I can't accurately check dates for continuity. 

## Day 33
I spent today working on a fix for the critical issue with timezones. I have fixed some of the timezone issues, but there are still some edge cases this will not work. 
Still considering a couple of ideas, but the solution might be to rank the leaderboard by a different metric. 

## Day 34
- ✅ Trialed a couple of alternative methods to rank the leaderboard
- ✅ Settled on ranking the leader board by attempting to extract the user delared day number. 
- ✅ Set up logging to test the concept overnight

## Day 35
- ✅ Validated the alternative method for ranking the leader board works
- ✅ Made some minor tweaks to account for the variations in input. 
- ✅ Started adapting the database to store and utilise this new ranking method. 

## Day 36
After stagnating in the current project for the last couple of days, I decided to switch things up a little today. Knowing I'll likely be needing working on a couple of Discord bots this year, I started working on a boilerplate bot, combinging some of the handy functions and features from previous bots. 

## Day 37
- ✅ Finished puttig together the [basic boiler plate Discord bot](https://github.com/MattCSmith/BoilerBot-Basic)

## Day 38
Wasn't really sure what I wanted to work on next. Do I go back to the very first project, or maybe even the twitterbot project. 
In the end I decided to take it easy and implemented more Discord events to the boilerbot, since these would be useful in the future. 

## Day 39
Again, today I wasn't 100% sure what to work on next. So I spent a little time brainstorming a couple of ideas, along side adding some more events to the discord boilerbot. 

## Day 40
On a mission today to finish added every event to the Discord boilerbot. I fell a little short. Every event file has now been created, just need to create the boilercode, comment and log for the last half. 

## Day 41
#### **Project:** Leaderboard

Done Today:

- ✅ Finished the new leading ranking logic
- ✅ Wrote a script to update existing users records
- ✅ Tweaked the leadercard

Todo Tommorow:

- 📅 Tidy up and finish the leadercard 
- 📅 Add the new logic to new users being added to the database
- 📅 Add basic filtering. 


## Day 42
#### **Project:** Leaderboard

Done Today:

- ✅ Tidied up and completed the Learcard update
- ✅ New leaders are now stored with thier day number

Todo Tommorow:

- 📅 Add basic leaderboard sorting and filtering


## Day 43
#### **Project:** Leaderboard

Done Today:

- ✅ Add basic leaderboard sorting and filtering
- ✅ Bot now likes Tweets

## Day 44
#### **Project:** Leaderboard

Done Today:

- ✅ Improved the UI for filter and sorting functionality

## Day 45
#### **Project:** Leaderboard

Done Today:

- ✅ Started working on milestones
- ✅ Implemented some more statistics

## Day 46
#### **Project:** Leaderboard

Done Today:

- ✅ Further worked on milestones
- ✅ Fixed some minor bugs

## Day 47
#### **Project:** Leaderboard

Done Today:

- ✅ Finished up milestones
- ✅ Implemented some logs and tests to ensure milestones work, before releasing the feature. 

## Day 48
#### **Project:** Leaderboard

Done Today:

The milestones feature contained a handful of bugs. Worked through a couple of them and refactored some code. 
Will again see how the tests go overnight with live data


## Day 49
#### **Project:** Leaderboard

Done Today:

The milestones feature now appears to be working correctly after a few more tweaks. Tomorrow will improve this feature and hopefully push it live. 
