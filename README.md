# Project-365

I started a very ambitious project... 365 Days of Code Challenge! Similar in nature to the [100 Days of Code Challenge](https://www.100daysofcode.com/), I will be spending a minimum of 1 hour each day of 2021 working on a personal project hopefully learning a thing or two and improving my coding abilities. I intend to work on a couple of projects, each containing elements that should push me out of my comfort zone and allow me to expand my knowledge and skill set. You can check out my plans in the video below:

[![365 Days Of Code](https://cdn.discordapp.com/attachments/743608750635483297/794663588211720192/365_Days-small.png)](https://youtu.be/e2tShvgFYaI)

It would make my day if this encourages even one person to sign up to the 100 Days Challenge. You can find out more about the challenge here: https://www.100daysofcode.com/. Reach out if you are starting a coding challenge project of your own, I'd love to check it out.

## Useful Links

- Follow me on [**Twitter**](https://twitter.com/MattCSmith_) for daily updates.
- Subscribe on [**Youtube**](https://www.youtube.com/channel/UCQnCh_U9PeXh_7FaxUB7Lsg) for periodic update videos.
- [Other Links can be found here](https://linktr.ee/mattcsmith)

## Shameless Plug
[![](https://images.ctfassets.net/aq13lwl6616q/2fU4z36oCseTDi1KHAbZbv/6db2a17b155ec8303a57933f63360b44/Hero-WithText-2.jpeg)](https://bit.ly/tech-paths)
Over at Zero To Mastery we just launched [Career Paths](https://bit.ly/tech-paths) to help our students find their personalised career path based on their previous experiences and ambitions. If you are looking for a personal roadmap into your chosen career or aren't sure which area of tech you want to pursue, go take the 3 minute quiz

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

## Day 50
#### **Project:** Leaderboard

Done Today:
Made improvements to the milestone feature, but not quite ready to push it live today. 

## Day 51
#### **Project:** Leaderboard

Continued working on the milestone feature and refactored some code and removed alot of the old leaderboard ranking logic. 

## Day 52
#### **Project:** Leaderboard

Identified a bug resulting in some day counts not being updated in the databased. Tracked down the issue and pushed a fix.

## Day 53
#### **Project:** Leaderboard

Fixed a couple of minor bug created from the refactoring a couple days ago and finally implemented the next round of tests for the milestone functionality. 
If all goes to plan over the next couple of days, I can start having the bot respond to tweets upon the tweeter reaching a 100DaysOfCode milestone. I'm being super cautious with this rollout as I want to reduce the chance the bot goes on a spamming spree. 

## Day 54
#### **Project:** Leaderboard

Spent some time today reading up on the twitter API after having issues in getting the bot to reply to tweets. Instead it was just tweeting. Hopeful I have found the solution to this. Also wrote some milestone stats tracking, hoping this data will help me make a more informed decision on how to interact with the community regarding milestones. For example, I probably don't want to have the bot retweet every early milestone as this could get super spammy. 

## Day 55
#### **Project:** Leaderboard

After finally cracking the reply to tweet functionality last night, I spent today refactoring in the working implementation for replies. ALso spend some time working on the language files for the bot to use when reply to the milestone tweets. 

## Day 56
#### **Project:** Leaderboard

Spent some more time today working on the language files for the bot to use when sending milestone replies. Also started to pencil out the batching together of milestones for potential retweeting. 

## Day 57
#### **Project:** Leaderboard

Continued working on the batching together of milestones, feeling confident about this feature. 

## Day 58
#### **Project:** Leaderboard
Re-wrote and finished the language files for milestone replies. Checked over the milestone replies implementation and launched it 🎉

## Day 59
#### **Project:** Leaderboard
Today I implemented a lastUpdated feature. I had noticed the leader board always looked pretty stale and most of the profiles on the leaderboard had not posted for several days or more. This feature now ensures that each profile was updated within the last three days at least. 

## Day 60
#### **Project:** Leaderboard

Over the last couple of days I have started to notice issues with the database, which resulted from the change of direction early on in the way in which the leaderboard is ranked alongside other minor changes along the way. Today I started to map out a new structure for the databse, making considerations for both the current and future features. 
I think I have come up with a decent plan and have made a start on the implmentation.  


## Day 61
#### **Project:** Leaderboard

Didn't have much spare time today to make a bunch of progress, so I spent a little time working on the new database optimisations. 

## Day 62
#### **Project:** Leaderboard

Today I finished of the new database optimisations. Will need to test them out tomorrow and perhaps tweak them a little. 


## Day 63 
#### **Project:** Leaderboard

🔹 Made a bunch of minor tweaks to the bot
🔹 Implemented a last touch query param, so the frontend can filter how many days a leader can be inactive for, before they are hidden from the leaderboard. 
🔹 Added a new challenge


## Day 64
#### **Project:** Leaderboard

Today I made a start on refactoring the database helper functions to make them work efficiently with the new database structure.

## Day 65
#### **Project:** Leaderboard

Continued to work on the database helper functions. Although not entirely a personal project, I also worked a little on the Zero To Mastery Discord bot, updating some of the remaining features to the v12 update of Discord.Js. This updated really highlighted to me, why as devs we should aim to avoid making breaking changes to APIs and wrappers. Especially when they are used by thousands of people. 

## Day 66
#### **Project:** Leaderboard

Again I worked on updating the database helper functions to the new database stucture. These have been a massive time sink and I will be glad to get them done, but the new structure will make maintenace and new features alot easier and also the API will be slightly more powerful an optimised. 


## Day 67
#### **Project:** Leaderboard

In fear of sounding like a broken record, I spent an hour today updating the database helper functions to the new database stucture.

## Day 68
#### **Project:** Leaderboard

Plugged away at some more of the database helper functions. 

## Day 69
#### **Project:** Leaderboard

Spent a couple more hours today working on the helper functions again. 


## Day 70
#### **Project:** Leaderboard

Made a real push today to get the majority of these helper functions sorted and have got really close. Just a couple more left to do and I can proceed to testing before final implementation. 

## Day 71
#### **Project:** Leaderboard

Spent an hour working on the final few helper functions. Hope to finish them off tomorrow ready to complete the implimentation and run some tests.

## Day 72
#### **Project:** Leaderboard

Super close to finishing these helper functions now. Finished off another one and made a decent started to the second one. One and a half left to do. 

## Day 73
#### **Project:** Leaderboard

Finished up the helper functions today 🎉. Next up is to implement and test the helper function. Fingers cross I can do all of that by midweek 

## Day 74
#### **Project:** Leaderboard

Made a start on implementing the functions throughout the codebase of the Twitter bot. On target to wrap this up by midweek. 

## Day 75
#### **Project:** Leaderboard

Made some great progress today. Have implemented the new helper functions throughout the codebase. Although ahead of shedule, I am going to take the spare day to double check everything again, just to ensure I haven't missed anything, since it is a pretty big change. 

## Day 76
#### **Project:** Leaderboard

Spent today double checking the optimised helper functions had been implemented correctly, before launching them. Smoothed over a few bugs from things I had missed. But the newly optimised helper functions are now live. Tommorrow I can make use of the new DB structure to implement some new features. 


## Day 77
#### **Project:** Leaderboard

Fixed up a couple of bugs and implemented the daily milestone logger, hopefully providing the ability to tweet shout out's to a couple of milestone achievers each day. I also started to work on a roadmap for Challenged.Dev

## Day 78
#### **Project:** Leaderboard
Identified and fixed a bug, where milestones where being pushed twice to the array in the milestone document. 

As mentioned in yesterdays log, I created a roadmap/list of features I would like to add to Challenged.Dev. Which will likely require a bit of an overhall to the Frontend.
I realised that recently I am no longer pushing my self to learn anything new, and if I am going to commit to overhauling the frontend I should at least look at utilising different tools/frameworks and services. Otherwise I would just be building yet another React application in much the same way I have done multiple time before. 

After looking at different options and solutions, I spend some time today evaluating Next JS and vercel as a potential solution. Tomorrow I will experiement some more and decide. 

## Day 79
#### **Project:** Challenged.Dev - Next.js FrontEnd

So today I spent a bunch of time setting up Next.js with Contentful & Netlify. Still have a bit of experiementing to do, but its looking like a great option for the front end. 


## Day 80
#### **Project:** Challenged.Dev - Next.js FrontEnd

Today I did some more experiementing with Next.js and for the most part I have been really enjoying it. Figured out how to integrate it with Contentful headless CMS in the way I want to use it. Now that I have explored Next, I think tomorrow I can actually start working on rebuilding the Front End. 

## Day 81
#### **Project:** Challenged.Dev - Next.js FrontEnd

Today I spent some time working on the initial layout and strucutre for the front end. Unforuntately there is not much visible progress to look back on, but I am more than happy with the progress

## Day 82
#### **Project:** Challenged.Dev - Next.js FrontEnd

After deciding to roll with a sidebar layout for this design, I spent some time today starting to build out the first itteration of it. 

## Day 83
#### **Project:** Challenged.Dev - Next.js FrontEnd

Spent time today bringing the sidebar near completion. It now has collapsible functionality, submenus, icons and badges. 

## Day 84
#### **Project:** Challenged.Dev - Next.js FrontEnd

Today I added some more polish to the collapisble sidebar for the frontend. Really pleased with how its turning out. I reckon another days work and the sidebar will be mostly complete, subject to the itterative updates. 


## Day 85
#### **Project:** Challenged.Dev - Next.js FrontEnd

Today I spent some time finishing off the sidebar. Unfortunately I had to undo some of the work yesterday and change plans for the sidebar menu, as it doesn't seem possible right now to use `getStaticProps` in the `_app.js` file. 


## Day 86
#### **Project:** Challenged.Dev - Next.js FrontEnd
Today I made a quick start on the index page of the new front end. 


## Day 87
#### **Project:** Challenged.Dev - Next.js FrontEnd
Spend some more time today working on the index page. Created a couple of section to crate feature highlights. Ran into a couple of issues with the sidebar causing some overflow. Hopefully I have more time tomorrow to address the issues. 

## Day 88
#### **Project:** Challenged.Dev - Next.js FrontEnd
After noticing some issues yesterday with the layout/overflow/responsiveness, I dedicated some time today to make a start on fixing the issues here and making steps to ensure a responsive design forms. 

## Day 89
#### **Project:** Challenged.Dev - Next.js FrontEnd
Today I continued working on the responsiveness of the front end. 


## Day 90
#### **Project:** Challenged.Dev - Next.js FrontEnd
Again I continued working on the responsiveness of the front end today, I have made a bunch of progress and feel pretty happy with the current responsiveness of the layout.
Tomorrow I intend to continue with building out the pages. 

## Day 91
#### **Project:** Challenged.Dev - Next.js FrontEnd
Today I made a started work on the resources page. I had already made a very brief start on this page a while back, so their was a bit of tidy up and refacting required.  

## Day 92
#### **Project:** Challenged.Dev - Next.js FrontEnd
Not really much to report today, continued working on the resources page. 


## Day 93
#### **Project:** Challenged.Dev - Next.js FrontEnd
Majority of the intitial Resources funtionality is now in place, just a little styling and tweaking left. Will eventually want to add some more advanced functionality, such as filtering/sorting/searching and resource catergorisation etc. 

## Day 94
#### **Project:** Challenged.Dev - Next.js Frontend 
Unfortunately I didn't have much time today, which meant I didn't have enough time to finish up the styling from yesterday. Instead I decided to make a start on the challenge page. 


## Day 95
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I finished off implementing the challenges page and made some good progress on styling the cards for both the challenge page and the resources page. 

## Day 96
#### **Project:** Challenged.Dev - Next.js Frontend 
I continued working on the styling of the resource and challenge cards today. 


## Day 97
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I experiemented with different card layouts, mainly masonry grids and evalutating ways in which to achieve this in Next. 

## Day 98
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I continued exploring and experimenting with a couple of the masonry layouts methods. Each seem to have some tradeoffs to consider before implementation.  

## Day 99
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I have finished implementing the masonry layout for both challenges and resources and tidied up a the styling of the cards. 

## Day 100
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I worked on some more mobile optimisation. In particular the sidebar needed some work, since it never collapsed for smaller screens. 
This actually require a custom Debounce hook to ensure the resizing didn't happen too often that it created a jerky appearance. Debounce is a super cool hook.
Other tweaks includes responsive column count for the masonry cards, custom scrollbar for the sidebar and submenu icons, 

## Day 101
#### **Project:** Challenged.Dev - Next.js Frontend 
Today I made a start on implementing the 100 days of code leaderboard. I'm not 100% sure where I actually want the leaderboard to be just yet, but I can figure that out once the component is ready for a page. 

## Day 102
#### **Project:** Challenged.Dev - Next.js Frontend 
I had very little time today, so I spent an hour just working on the leaderboard again. 

## Day 103
#### **Project:** Challenged.Dev - Next.js Frontend 
I spent today working on building the footer and making some general improvements to the overall styling and theme of the site, working towards a more cohesive design.

## Day 104
#### **Project:** Challenged.Dev - Next.js Frontend 
Today, I again had very little time, so I so I continued to plug away at teh leaderboard. I have also started to consider the implementation of some of the other features I have planned. 


## Day 105
#### **Project:** Challenged.Dev - Next.js Frontend
Today I started implementing basic search for the resources component, however will also roll this out to a couple of other compontents. 

## Day 106
#### **Project:** Home Automation
Today I experimented with various Zigbee sensors in HomeAssistant. Although it has mostly been configuring YAML and JSON, there has been a bunch of learnings today... Inlcuding stripping back the Zigbee bridge and re-flashing the firmware so it can communicate with HA. Its been awesome being able to program actual pyshical devices. I am looking forward to all the posibilities and perhaps even writing some applications that can interact with components around my home. 


## Day 107
#### **Project:** Home Automation
I spend some more time today experimenting and playing with the various components, settings and sensors.  Put together a basic automation where a motion PIR flashes a hue bulb and sends a push notification. 


## Day 108
#### **Project:** Home Automation
Spent a bunch of time today building out some dashboards through YAML files for HomeAssistant. I also spend some time looking through community built extensions/addons, to see how they added the extra functionality to HA. Pretty cool to see JS is used for the theming of HA Dashboards, perhaps I can write an addoon in the near future. 

## Day 109
#### **Project:** Home Automation
Continued working on dashboards today. Its really cool what you can achieve with YAML in HA... but it can be a pain to ensure the syntax is correct.
I also explored options for creating an AI powered Discord bot. Found a couple of interesting options worth further experimenting in a future project. 


## Day 110
#### **Project:** Challenged.Dev - Next.js Frontend
Today I continued implementing the basic search functionality for the resources component.

## Day 111
#### **Project:** Challenged.Dev - Next.js Frontend
Today I started working on the challenge template page. I am hopeful I can create a unified template each challenge can share. 

## Day 112
#### **Project:** Challenged.Dev - Next.js Frontend
Today I started work on dynamic routing, using getStaticPaths to generate the routes/paths for each challenge entry in Contentful. This took a little experimenting to get working, but got it working in the end. 


## Day 113
#### **Project:** Challenged.Dev - Next.js Frontend
Unfortunately I did not have a ton of spare time today, so now that the dynamic routing is functional I continued working on the challenge page design. 

## Day 114
#### **Project:** Challenged.Dev - Next.js Frontend
Again I didnt have a ton time so I continued working on the challenge page design

## Day 115
#### **Project:** Challenged.Dev - Next.js Frontend
Another day with limited time. Continued on the challenge page, with a bit of luck I will have a bit more time tomorrow to complete the page.

## Day 116
#### **Project:** Challenged.Dev - Next.js Frontend
After loading more challenges into Contentful to get a better idea of the design, I noticed a bug in the dynamic rendering of the challenge pages. In which only the first challenge entry in Contentful is displayed regardless of the selected challenge. After some experomenting and doc reading I think I misunderstood the getStaticProps and getStaticPaths. Ran out of time to fix it today, will hopefully fix this tomorrow. 

## Day 117
#### **Project:** Challenged.Dev - Next.js Frontend
Today I found a solution for the bug the effected the dynamic rendering of the challenge, although I am not 100% sure its the best option it does appear to be the solution most commonly provided throughout various articles. It just seems odd that I can't use Contentfuls getEntry and have to use getEntries to get a single entry. 

## Day 118
#### **Project:** Challenged.Dev - Next.js Frontend
Today I worked on some more general page styling, inlcuding as creating a component for page title, the general page content container to make it easier to conform page content margins and styling. I also started adding some accent colouring to elements throughout the site. 

## Day 119
#### **Project:** Challenged.Dev - Next.js Frontend
Today I made a bunch of progress. From abstracting the Masonry grid into its own component in order to utilise it across various pages with different card components. To creating a new leader card, utilising the new masonry grid and made a couple of tweaks to the API in order to include the latest tweet on the leader card. There are definately some optimisations to be made and the load time on this page is pretty noticable, however pagination and lazy loading have not yet been implemented, so this is to be expected. 

## Day 120
#### **Project:** Challenged.Dev - Next.js Frontend
Following on from yesterday's styling improvments I continued to work on the leader card and the leader board, with the little time I had available.

## Day 121
### **Project:** Netlify Functions
After facing some difficulties with Netlify functions in another project, I decided to spend some time today learning more about them and the netlify CLI

## Day 122
### **Project:** Challenge.Dev API
Today I noticed the API was not working, so I spend some time trying to track down the issue. It took some time to figure out, but will need further investigation as I am not 100% sure its the problem. Even if its not I will need to figure out why the Digital ocean drop has upgraded its self. 

## Day 123
### **Project:** Challenge.Dev API
Yesterday I noticed that the API was not functioning correctly. This appears to be an issue with the billing/pricing plan the droplet is on. For some reason it was no longer running on the basic droplet. I was unable to downgrade the droplet apparently because of the decrease in disk space between the plans. I have there for began to backthings up and started a migration to a new server. This will likely take me a couple days to complete. 

## Day 124
### **Project:** [Google App Scripts](https://developers.google.com/apps-script)
Spend a while today learning more about Google App Scripts and experimented with them a little. Its really kinda cool what you can achieve with them. They are a really cool hidden feature that can really help your automate some of your manual processes in Google Docs/Sheets etc. 


## Day 125
### **Project:** Migrating Challenged.Dev
Today I continued migrating to a new droplet since I was unable to downgrade the droplet. Todays task was set up ssh on the ubuntu droplet and secure it. I also made a start on installing things like Node, PM2, Nginx etc, ready for congiguration tomorrow. 


## Day 126
### **Project:** Migrating Challenged.Dev
In continuation from yesterday I continued migrating to the new droplet. Todays task was to continue setting up and configuring the requirements for the application. After a little more setting up tomorrow, I should be ready to start migrating the actual application. 


## Day 127
### **Project:** Styled Components 
So I ran into some issues today in another project with dynamically apply theme styles to a styled-component based on the props passed in. Every method I tried created some really bizzare side effects. So I spent a bunch of time today learning more about styled-components and experiementing with them a little. I was eventually able to solve the issue I was having. 


## Day 128
### **Project:** Migrating Challenged.Dev
The backend has now been fully migrated to the new droplet, although I did notice this droplet had also increased in size, so I will have to keep an eye on that. 
Unfortunately this was not the underlying issue in the API not responding to certain endpoint requests. I'm wondering if the user collection in Mongo is too large and the endpoint is failing because the request is taking too long to complete. I will experiement further tomorrow hopeful and see if I can fix this issue. 


## Day 129
### **Project:** Challenged.Dev - MongoDB
I started to look into the issue with Mongo today. From my learnings today, Mongo is capable of scalling to datasets far greater than the set I am currently using with Mongo. So I spent some time learning more about Mongo Indexs to improve the efficiency of the queries that are taking too long to resolve. I did implement a couple of Index, but as of yet have not noticed an improvement in the response. I will try again tomorrow, perhaps I overlooked something. 

## Day 130
### **Project:** Challenged.Dev - MongoDB
I haven't had much spare time today to do much experimenting, but in continuation from yesterday I've done a little more research into Mongo Indexing and optimisations. 
Hopefully tomorrow I will have a little more time to experiment a little more and hopefully find a solution.


## Day 131
### **Project:** Challenged.Dev - MongoDB
So today I spent some more time experimenting with Mongo indexes and I found the Explain Plan function in Mongo Compass. It seems as if even though I have an index for the filter I am performing on the documents, its still having to examine over 4k documents. Will spend some time tomorrow looking into solutions or perhaps I need to come up with a more performant way to save the leaders or at least serve them. 


## Day 132
### **Project:** Challenged.Dev - MongoDB
Spent some time today watching some videos and reading up on Mongo and DB design practices. I haven't really come up with a solid plan to reduce the time it takes to fetch the leaders, but with a bit more research I am confident. 


## Day 133
### **Project:** Challenged.Dev
With limited time today I took a bit of a break from the Mongo issue and continued working a little on the leaderboard and fixing a couple of issues with analytics etc. 

## Day 134
### **Project:** Backend Course
Since I have been struggling a little with the architecture of the Mongo DB in order to scale it with minimal delay, I have decided to spend a little time each week on [Zero To Mastery's Node Course](https://academy.zerotomastery.io/p/learn-node-js) which alongside a bunch of interesting topics covers Mongo. I don't want my learning shedule to take over the challenge, however since I am kinda blocked on this and have limited time to dedicate, doing both together seems like a logical solution. 


## DAY 135
### **Project:** Backend Course
With limited time available today I decided to spend the time I had working through the Node.js course. At the moment I am still in the early chapters working through some of the more basic elements, but it has been helpful in filling a couple of gaps in knowledge.


## DAY 136
### **Project:** Discord Bot
Decided to take a little break from the current project as I had a couple of updates to make in order to add a new feature to a Discord bot I maintain. So today I finished the updates and made a start on the new feature, with a bit of luck I can have the new feature ready for testing tomorrow. 

## DAY 137
### **Project:** Discord Bot
Today I finished coding the new feature for the Discord bot I was working on yesterday. I have done some basic testing of the new feature, however I still want to do some more testing before I push it live, but that is a job for tomorrow.


## DAY 138
### **Project:** Discord Bot && GDS
Today was a bit of a split day. I spent a little time testing out the Discord bot functionality, in which I think its ready to go live when I have time to monitor it in production for a little bit. I also spent some time today figuring out another one of Googles tools for webmasters/web marketers. Unfortunately I am not a fan of Googles Data Sudio... Its pretty difficult to figure out how to get the data you want. Perhaps I just need to experiment with it further. 

## DAY 139
### **Project:** Multiple Projects
Again today covered multiple projects including some minor tweaks to the Discord bot, making a start on a quick temp fix of the slow load on the Mongo DB issue and then making some considering and starting plans for a future project. 

## DAY 140
### **Project:** Challenged.Dev Backend
Continued with the quick fix for the Mongo DB loading issue. I'm going to have the backend generate a JSON file periodically of the leaders, ready to serve to the front end upon request. This hopefuly should make the request alot quicker. 


## DAY 141
### **Project:** Challenged.Dev Backend
For the most part I have finished the quick fix for speeding up the fetching of the leaders for the leaderboard. So far it seems to be working as expected, but I would like to spend a little more time testing and optimisign before pushing it live. 


## DAY 142
### **Project:** New Bot Project
I spent the majority of today researching and planning a new fairly big project I want to finally make a start on. 
I am hoping to run this new project side by side with the challenged project, although it might have to take a little more focus initially. 


## DAY 143
### **Project:** New Bot Project
Made some good progress today in continuation of researching and planning out the upcoming project. 


## DAY 144
### **Project:** New Bot Project
Today I continued planning the massive bot project. For the most part I now have the bulk of it planned out and its really just a bunch of the little details left to go.
