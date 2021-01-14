# Project-365

Today I am starting a very ambitious project... 365 Days of Code Challenge! Similar in nature to the [100 Days of Code Challenge](https://www.100daysofcode.com/), I will be spending a minimum of 1 hour each day of 2021 working on a personal project hopefully learning a thing or two and improving my coding abilities. I intend to work on a couple of projects, each containing elements that should push me out of my comfort zone and allow me to expand my knowledge and skill set. You can check out my plans in the video below:

[![365 Days Of Code](https://cdn.discordapp.com/attachments/743608750635483297/794663588211720192/365_Days-small.png)](https://youtu.be/e2tShvgFYaI)

It would make my day if this encourages even one person to sign up to the 100 Days Challenge. You can find out more about the challenge here: https://www.100daysofcode.com/. Reach out if you are starting a coding challenge project of your own, I'd love to check it out.

## Useful Links

- Follow me on [**Twitter**](https://twitter.com/MattCSmith_) for daily updates.
- Subscribe on [**Youtube**](https://www.youtube.com/channel/UCQnCh_U9PeXh_7FaxUB7Lsg) for weekly update videos.

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

## Day 12
Spent time refactoring the pages today. Hardcoded content on the index page is now fetched from Contenful. All of the original title bars have been replaced with the new Floating title bar component. 
Hoping tomorrow, I can look into creating an application form that is powered by Netlify forms and integrates with PlanBs Discord bot via Netlify's serverless functions. 
