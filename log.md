# 100 Days Of Code - Log

### Day 0: April 20, 2021 - May 24, 2021
#####

**Month's Progress**: Finished Harvard's CS50 online course, learned GitHub basics, started working on fcc certifications and currently working on the front end library cert. Started learning react by following facebook's tic-tac-toe tutorial. Then started going through fullstackopen's react courses (finished part 1). Also started reading The Modern JavaScript Tutorial on the side to supplement my coding. Finally, I started 100 Days of Code.

**Thoughts:** I started 100 Days of Code to log my progress and keep myself accountable. However, I actually started my journey last month on 4/20/2021. So far, I have coded at least 2 hours a day. I hope to keep this up!

### Day 1: May 25, 2021 
#####

**Today's Progress**: Started on part2 of fullstackopen and finished section a. Also re-arranged my github repos.

**Thoughts:** I had a lot of syntax trouble with the exercise for part 2 section a. Mostly because the notation gets confusing when you have a multi-depth object or array (or both). I also didn't realize that when you use map (or any array function) and return the array in the render section, the top level arrays need to have identifying keys. I thought lists only needed keys. This got even more complicated when you write each list as a component. So then you need to assign a key to the component, and not the list it creates. Anyway, I finished section b and got to the exercise section and decided to call it a day. 

I have a flight in two days to go home, so I've been deciding which coding activity I should save offline. I haven't formulated a plan yet, but I'm leaning towards finishing the fcc front end lesons tomorrow so I can work on the projects during the flight. I might also save some algorithm exercises, and maybe save the react exercises from full stack open.

**Link to website:** [Full Stack Open](https://fullstackopen.com/en/)

### Day 2: May 26, 2021 
#####

**Today's Progress**: Finished exercises for part2 section b of fullstackopen. Started on part3.

**Thoughts:** I only had enough time today to finish the exercises for part2 section b. I'm still not used to setting up event handlers and states with hooks, but I think I'm getting the hang of it. I also prepared some things to work on during my flight tomorrow, like the rest of part2 plus some fcc exercises.

### Day 3: May 27, 2021 
#####

**Today's Progress**: Finished part2 section c and halfway through section d. Finished the first exercise of part2 section c. Finished fcc's redux lessons. Worked on fcc's project euler coding challenges.

**Thoughts:** Today was mostly travel. I finished the redux lesson on fcc, which is interesting considering I'm doing more exercises specifically on just react with fullstackopen. It will be interesting to see how those two work together. During the flight, I was working on the smallest multiple challenge for project euler. I didn't realize my VScode was out of date, so I couldn't launch the debugger during the flight. I had to stop working on the challenge because I couldn't debug properly. Instead, I went through fullstackopen and finished what I can. Interestingly, the section went over promises, which I just read about a couple days ago from the Modern Javascript Tutorial, so I was able to follow along.

I also found an HTML/CSS lesson online that is free: Interneting is hard. It looks very elegant and well made, so I might start reading that as well to practice my HTML/CSS skills, which is severely lacking compared to everything else.

Since today was mostly travel and catching up with my family, I might revisit some of the things I learned today just so I remember them.

**Link to website:** [Interneting is hard](https://www.internetingishard.com/)

### Day 4: May 28, 2021 
#####

**Today's Progress**: Finished all of part2 section c's exercises in fullstackopen. Finished all of part2 section d.

**Thoughts:** I went back and read over all of section c and d again just so I can retain the information. Then, I finished the last half of section c's exercise, which involved making API GET requests from third party websites. It was pretty cool getting data from another source and having it show up in something that you're working on. I also finished section d, which featured more RESTful API requests.

### Day 5: May 29, 2021 
#####

**Today's Progress**: Finished full stack open's part 2 completely. Finished React and Redux section on FCC. Started on frontend projects on FCC.

**Thoughts:** I finished part 2 of full stack open, and I'm glad I did so. I learned the basics of React, and with the exercises I followed I was able to even make API requests from other sites to render data onto the browser. I also finished the Redux + React and Redux section on FCC; however, I still don't fully understand how Redux works, nor how I can incorporate it with React. I might have to wait until full stack open introduces Redux before I can understand it. It also does not help that FCC uses classes for React, while full stack open uses hooks. I find the hooks method for using React much easier though.

I started working on the random quote generator using React (I'm excluding Redux for now and will refactor later once I understand it). At first I was trying to set a state for an array of quotes, and another state for the current quote. The current quote will initially get a value from the array of quotes. However, I kept getting errors and could not get the current quote state to work. Apparently, since React does not immediately update a component's state and usually does it in batches, the current quote state gets a null value. So after the initial render I made the component render a random quote without setting the current quote state, then set the state with a button click instead. This ensures that on the initial render, React does not render a state that is undefined.

I also tried to look for a website that provides quotes via API requests, but most of them only offer a couple of requests per hour so the quote machine will only work for a couple of clicks. Instead, I found a database of quotes from this guy: https://github.com/JamesFT. Shoutout to him.

**Link to database of quotes:** [Quotes](https://github.com/JamesFT/Database-Quotes-JSON/blob/master/quotes.json)

### Day 6: May 30, 2021 
#####

**Today's Progress**: Finished styling the random quote machine project. Started the javascript calculator project.

**Thoughts:** Today I mostly did html/css to style the projects. Since I don't usually write HTML or CSS, I figured I would put a good amount of effort on this part instead of just fulfilling the user stories. I finished styling the random quote machine, although I had some trouble setting up the animations keyframe because of one syntax error. After I figured that out, I was able to make it work. I'm pretty happy on how it looks right now, although I might revisit it in the future. I started working on the calculator project, and I mostly worked on the calculator's styling. I used flexbox and grid on the projects today, and it's interesting to see the difference between the two.

### Day 7: May 31, 2021 
#####

**Today's Progress**: Worked on the calculator project.

**Thoughts:** I worked on the calculator proejct for a little bit. I spent most of the day celebrating the holiday with my family so I couldn't code much. Tomorrow is my flight home, so I'll have enough time working on the calculator project (and potentially finishing it). I also have more coding exercises to do to fill up time.

### Day 8: June 1, 2021 
#####

**Today's Progress**: Almost done on the calculator project.

**Thoughts:** Most of the day was spent travelling and sleeping to recover from the flight. I did work on the calculator project though, and I'm almost done with it. The only missing functionality is dealing with negative numbers and changing the operator correctly (i.e. user clicks divide, then changes mind and clicks plus to add instead).

### Day 9: June 2, 2021 
#####

**Today's Progress**: Finished the calculator project.

**Thoughts:** I'm pretty happy with what I ended up with in the calculator project. It deals with normal operations, and it also deals with negative number operations. It also allows to change the current operator if you choose a different one. The code itself has a lot of conditionals and switch statements, and I tried to refactor the code so there's minimal duplications, but I'm sure there's more I can improve upon. Dealing with the minus operator was complicated than it initially seemed, since you have to decide if you're dealing with a subtraction, or a negative integer. I think I figured it out, and it runs properly.

### Day 10: June 3, 2021 
#####

**Today's Progress**: Started 25+5 clock project.

**Thoughts:** I started working on the 25+5 clock project on fcc. I finished the styling (although I might come back to make it prettier later) and structured the components. I'm still thinking on how I will design the countdown state. Currently I'm getting sidetracked with some twitch content, but I'm still getting at least 2-3 hours a day of coding practice.

### Day 11: June 4, 2021 
#####

**Today's Progress**: Worked on 25+5 clock project but got stuck.

**Thoughts:** I worked on the clock project, and got a coundown timer that works. However, when you hit pause it takes a full second before it takes it, so the app renders one more time and decrements the timer by 1 (instead of pausing immediately on click). I couldn't figure out a way to fix that so I went back to the drawing board and started reading about different ways of implementing a solution. The solutions I found online made sense, but mostly featured manipulating the Date object (which was complicated in it's own right) so I had to take a step back. I might need to revisit this tomorrow when I have more time so I can read and understand different solutions (instead of copy + pasting and not retaining).

### Day 13: June 6, 2021 
#####

**Today's Progress**: Finished 25+5 clock project

**Thoughts:** I decided to take the day off yesterday because I had a long day at work and I celebrated my girlfriend's birthday. I also wanted to take a break from the project because I was stuck on it and couldn't make any progress. I revisited it today and instead of working on the countdown timer first, I worked on the other components. Afterwards, I realized that I don't have to use the date object nor do I have to separate the minutes and seconds states from each other. Instead, I can use the seconds state on its own and just derive both the minutes and seconds from it. I was able to work through the project easily after realizing that fact. I guess taking the day off helped reset my thinking.

### Day 14: June 7, 2021 
#####

**Today's Progress**: Started drum machine project

**Thoughts:** I started the drum machine project. I mostly worked on the html/css portion of it today. I am trying to take my time on each of these projects and actually make the html/css presentable. They are not responsive right now, but at some point in the future I want to go back and fix that. Hopefully I'm not taking too much time on these projects though. I expect to finish this and the last project for fcc frontend this week, so I can start on the next part of fcc. I want to tackle fullstackopen's backend portion at the same time as fcc's backend portion.

### Day 15: June 8, 2021 
#####

**Today's Progress**: Worked on drum machine

**Thoughts:** Mostly done with the drum machine project. I just need to add a css change on the drum pads when pressed, and to add the volume slider component. It seems that for a lot of these projects, constructing the HTML and CSS takes a lot of time. I might need to incorporate SCSS soon to make my life easier.

### Day 16: June 9, 2021 
#####

**Today's Progress**: Finished drum machine

**Thoughts:** Finished the drum machine project. I incorporated keyboard events, changing the style of the buttons when clicked, and adjusting the volume via the volume-slider component. Incorporating the keyboard events was interesting, because I needed to set up event listeners on first render. However, since I was using the state for power to decide if a button click should play an audio, it was taking the initial state of the power and not changing it. At first I tried to make useEffect depend on the power state; however, that would mean the event listeners would be setup each time the power state changes. So I used useRef to keep track of power, and used that in my conditional so that I can keep track of the state without having to trigger a new render. I also used useRef for changing the styles on button press, to prevent multiple renders on consecutive button presses. Before when I used useRef in the clock project, I didn't really understand it fully. But now, I think I have a better grasp for its use case.

Shoutout to the guy who created the audio files I used for the project. I will link his work below.

**Link to database of quotes:** [Audio](https://99sounds.org/drum-samples/)

### Day 17: June 10, 2021 
#####

**Today's Progress**: Finished data visualization lessons on fcc

**Thoughts:** I wanted to take a light day, particularly because I'm going on a weekend trip starting tomorrow to Big Bear. I went over the data visualization section of fcc and finished D3 as well as Ajax. Interestingly, since I learned about API requests on fullstackopen before, I understood the Ajax section. However, after getting used to the react structure, working on plain js was painful. D3 was interesting as well, and I'm excited to do some projects with it.

### Day 22: June 15, 2021
#####

**Today's Progress**: Got back from vacation, started tictactoe project

**Thoughts:** I got back from big bear yesterday, and I decided to take most of the vacation as a break from coding (which was much needed). I did a little bit during vacation, and I started creating a tictactoe game. I found the other fcc project (Markdown Previewer) a little uninteresting so I decided to do tictactoe instead. I need to get back into the rhythm this week. I've been coding for almost two months now (one month of 100 days of code) and a month ago I didn't know React. Now, I've made four react projects without following any tutorials, and all projects have pretty decent CSS. Not only that, but I had to take two weekends as vacations, and I still had pretty good progress. My goal for this month is to use D3 with react and learn some backend.

### Day 23: June 16, 2021
#####

**Today's Progress**: Finished tictactoe, started part3 of fullstackopen

**Thoughts:** I finished the tictactoe project. Once I figured out how to find the winner, the rest of the project came easily. I decided to skip the D3 projects for now (will come back to them later) and start learning about the backend. I started on fso part3, which teaches node and express. Once I finish this section, I will go over fcc lessons on backend and the projects.

### Day 24: June 17, 2021
#####

**Today's Progress**: Finished part3-a of fso, started part3-b

**Thoughts:** Finished part3-a of fso and started part b. It's interesting to see how node and express handle the backend, compared to flask in python. When I started b, I had some problems locating my previous code in my github repo. I realized at this point that my repository directories need to be reconfigured (both for fcc and react stuff), so I started moving fcc projects into their own repositories. I might need to fix this before continuing with part b, just so I won't have problems with it later on.

### Day 25: June 18, 2021
#####

**Today's Progress**: Learned how to deploy an app to Heroku. Finished part3-b of fso; working on exercises

**Thoughts:** Finished section b of part 3 (excluding the exercises at the end), which is mostly a tutorial on deploying an app to heroku, deploying the backend, creating a frontend build and copying that inside the backend directory, creating shortcut scripts on package.json, and creating a proxy for the frontend code. I also continued fixing my github repos, and realized how much of a pain it would be to continue if I had left it in that state. It's best to put each projects on their own repo, instead of having them in the same one. I ran into a problem with heroku because of that, so I will continue fixing the repo situation tomorrow.

### Day 26: June 20, 2021
#####

**Today's Progress**: Learned how to deploy MongoDB using Atlas, finished all of fso part 3

**Thoughts:** I didn't get much done yesterday other than fixing the github repos. Today, I finished all of fso part 3. It's interesting to see how MongoDB works and how different it is from MSQL (which is what I'm generally used to). It's also cool finally knowing the basics of a fullstack application, although there are still more to learn. I still have one problem with displaying a default error message returned by Mongoose to the frontend, and I wasn't able to figure that out. Maybe tomorrow I'll figure it out.

### Day 27: June 21, 2021
#####

**Today's Progress**: Finished fcc: APIs and Microservices section

**Thoughts:** I powered through the APIs and Microservices section on FCC. However, most of the lessons were already covered in fso. FCC feels like supplementary material that cements the ideas behind fso. However, a lot of the things in FCC feel very outdated. For example, their react section used class components and never went over hooks. Now, I saw some older ideas with the mongoDB lesson. Additionally, the projects for APIs and Microservices are not very interesting, so I might have to look for some that interest me. I might also just power through fso since I learn more from there anyway.

### Day 29: June 23, 2021
#####

**Today's Progress**: Joined hackforla info session yesterday, joined hackforla CoP meeting today, started fso part 4, learned jest

**Thoughts:** I didn't update the log yesterday because I was exhausted from work, but I joined an info session about joining hackforla. I also started fso part 4 yesterday, and continued working on section a today, which involved restructuring the directory structure of node projects. I also learned about the basics of testing node apps with jest.

I am excited to join hackforla to learn how to work in a team environment. I decided to join the hackforla website team, since that's the recommended team for beginners like myself. I also looked at other teams, particularly the ones working with react, but I was hesitant in joining those projects since I'm still inexperienced. I also felt a little anxiety in joining hackforla in general since I don't know if I'm ready yet. Still, I know I should join to help my development. My plan is to first gain enough experience in the website project, then look for a react team to develop my react skills, and finally look for a team that will let me do some backend work. I'm hoping for the best!

### Day 32: June 26, 2021
#####

**Today's Progress**: finished fso part4 section b, learned more testing cases and refactoring promises to use async/await

**Thoughts:** I didn't update the log again, which I'm really slacking on. I coded the past three days though, slowly going over part 4 sections a and b since they were pretty dense. A lot of refactoring code, and learning about setting up tests. I definitely need to pick up the slack though, since I haven't been coding as much as I want to.

I will postpone sections c and d of fso part 4, and do some fcc backend projects first to solidify my knowledge on the basics.

### Day 33: June 27, 2021
#####

**Today's Progress**: started fcc microservice projects, set up wsl2 on my pc, attended hackforla-website zoom meeting

**Thoughts:** I had a meeting today with the project team I am joining in hackforla. Mostly a lot of introductory stuff and setting up my environment. I need to review the site architecture to become more familiar. I looked at it once before, but it's definitely a lot to unpack.

I also started some of the shorter fcc projects related to microservices. Instead of making individual ones, I lumped two into one site. I finished the timestamp microservice and request header parser microservice. I didn't write any tests though, so I might write some simple ones tomorrow. I might also incorporate two more microservices.

### Day 35: June 29, 2021
#####

**Today's Progress**: attended hackforla meeting, made my first pull request in github for hackforla website

**Thoughts:** Yesterday I didn't have time to code because of RL stuff. Today, however, I made my first pull request on github! I kind of missed the instruction of not putting a screenshot of the code, but otherwise I kind of know the process of making a pull request.

Other than that, the meeting kind of took a lot of energy from me so I probably will not do some code until tomorrow.

### Day 36: June 30, 2021
#####

**Today's Progress**: my pull request from yesterday got merged, started twitch-api project from fcc

**Thoughts:** My pull request from yesterday got approved and merged, so that's exciting. I also started the twitch-json-api project from fcc. However, as I was trying to implement the API request, I kept running into some issues. Apparently, twitch changed their policy recently so you need to acquire tokens through OAuth. I can't figure out how to make this work, and the farthest I've gone is getting a CORS error. I wonder if I need to switch my api request code from frontend to backend. Another annoying thing is that all guides I could find about implementing the api with react were made before twitch changed their policy, and therefore outdated. None of them work anymore. If I can't figure it out tomorrow, I may have to pivot to something else for the time being.

### Day 37: July 1, 2021
#####

**Today's Progress**: set up my xps 15 to dual boot ubuntu and windows, continued working on twitch api project

**Thoughts:** I ordered a 1TB ssd and intel 9260 wifi card to upgrade my laptop. Previously it had a 512 GB ssd and a killer wifi card, which is notorious for not playing well with ubuntu installs. So most of my day consisted of replacing the parts in my laptop, making it dual boot ubuntu, and setting up my environment. I also got distracted with installing some bells and whistles for my laptop. Overall, I like it.

I also was able to figure out the OAuth problem I had yesterday. I moved the code to the backend, and installed cors as a dependcy. The get request was now able to receive something legit back from twitch. Now I need to figure out how to actually get back a list of streamers from an API request.

### Day 38: July 2, 2021
#####

**Today's Progress**: figured out how to retrieve an authorization token from twitch, made my second PR for hackforla

**Thoughts:** I finally figured out how to retrieve an authorization token from twitch. It took some diligent reading of the documentation and experimenting with the http request. My mistake was that I used a return line on the http request when I shouldn't have.

I also made my second PR. I still need to get my head down on how the site architecture works, but I have a better understanding than before.

### Day 39: July 3, 2021
#####

**Today's Progress**: used the auth token to finally make a request to query users from twitch

**Thoughts:** I figured out how to use the auth token so I can make further API requests. I also made sure to make my node directory cleaner so that I don't have to worry about it later on. I also worked on the frontend, and for the most part the project works as it should based on the fcc user stories. I use the backend to make third party API requests to twitch, and the frontend uses that info to display the queried users and show if they are online, and if so, show their game.

I still need to figure out how to store the token properly, so I can reuse it. Right now I'm making an auth token request every time I refresh, which is unneccessary. From what I've read, I could either store the toke in a cookie or local web storage. I guess that's more reading and research for tomorrow on how to do that. I can also still make the frontend look better, and add some testing for the backend. I am debating if I should add a database, but it seems excessive for a small project.

### Day 40: July 4, 2021
#####

**Today's Progress**: Happy July 4th! Made some css changes to make the frontend look better for the twitch-json-api project, attended hfla meeting and created two github issues

**Thoughts:** Didn't get much done today other for the twitch-json-api project other than some css styling changes. It always amazes me how much time actually goes into just styling CSS. Other than that, I didn't get to look up how to properly save tokens. I also attended the hlfa meeting, and created my first (and second) github issues. I spent the rest of the day celebrating the holiday with some friends.

### Day 42: July 6, 2021
#####

**Today's Progress**: Read ideas on how to store tokens, attended hfla meeting today

**Thoughts:** Didn't really code for the past two days. I spent most of yesterday reading up on how to store tokens from Oauth, and the two solutions I thought of won't work perfectly. First of all, there are security issues to think of, so generally speaking using local or session storage is not a good idea unless I really secure it. HTTP cookies are secured much better, but there are still some work to do to secure them. Additionally, they need to be set up from the frontend side, not the backend, which is what I tried. That didn't work so I had to pivot. The other solution is to store it in a database, and I think that's the way to do it. But for the scope of this project it might be a little excessive (for now) until I add more features to it like user logins. I might pivot away from this project and work on something else first, like finishing fso part 4.

I also attended the hfla meeting today, which took longer than expected. I need to do more coding for the rest of the week to make up for it.

### Day 43: July 7, 2021
#####

**Today's Progress**: Finished fso part 4 excluding the last exercises

**Thoughts:** Just worked on fso part 4. I will work on the exercises tomorrow because it's pretty late. Sometimes it's hard to get the motivation to code. I'm almost halfway to 100 days, and I knew it wasn't going to be easy. I think part of it too is that I can't come up with a *unique* project idea. Initially I was going to add more features to the twitch project, but thinking about it I'm not that interested in adding more features to it than necessary.

### Day 44: July 8, 2021
#####

**Today's Progress**: Finished fso part 4 exercises, attended hfla meeting

**Thoughts:** My schedule for the next couple of days is different because I'm covering for my coworker's early morning shift. I finished the exercises for fso part 4. Most of it was refactoring code to make it cleaner, adding authorization using jwt tokens (interestingly, this is a subject matter I read about the past couple of days because of the twitch-json-api dilemma!), and fixing tests.

### Day 45: July 9, 2021
#####

**Today's Progress**: Did my third PR for hfla, my first medium sized issue

**Thoughts:** I did another PR for the hfla website. This time, I worked on a medium-sized issue. It was a CSS issue that involved media queries. I had to make sure that some page-cards looked consistent across two pages. It's interesting how CSS issues are simple yet always so time-consuming!

### Day 47: July 11, 2021
#####

**Today's Progress**: Did a bunch of PR reviews for hfla, attended the meeting

**Thoughts:** I learned the basics of doing pull request reviews, so I did that yesterday and today. I reviewed three PRs so far, but they were mostly first issues and small-sized issues. I can imagine PRs for bigger issues to take longer and more work. Other than that, I started with fso part 5, but got preoccupied with some real life stuff. I hope to get back on the grind this week.

### Day 48: July 12, 2021
#####

**Today's Progress**: Finished fso part 5 section a and exercises accompanying it, worked on hfla website

**Thoughts:** I finished section a of part 5. It was mostly connecting the authorization for the frontend and backend. It's also getting to the point where the code for each are getting big, so I'm interested to see how the frontend code will be refactored (or if that will be part of future sections). I also worked on hfla for a little bit, and looked at an interesting bug involving an SVG where on initial render, the width is smaller than what is in the code. I think it's related to how chrome / edge render object tags, because changing the tag to img fixes it, but I'm not really sure why it's doing that.

### Day 51: July 15, 2021
#####

**Today's Progress**: Did a bunch of work fixing and resolving merge conflicts with my PR for hfla

**Thoughts:** I pretty much spent the last three days doing hfla stuff. I attended the Tuesday and Thursday meetings, and I reworked on my PR because I had to do some CSS refactoring for two pages so that a template used between the two could be used for future stuff. I also had to merge and resolve conflicts from a different PR. I knew that refactoring code was hard from my experience with my own stuff, but refactoring CSS on a bigger page where you have to be mindful of the future + other teammates is much more difficult. It was an interesting experience though, and I'm getting experience with SCSS as well.

### Day 53: July 17, 2021
#####

**Today's Progress**: Did pair programming with a teammate from hfla, worked on fso part 5 section b

**Thoughts:** I did a pair programming session with a teammate today. Mostly, we looked at a new page she was building for the site (404 error page) and we fixed some css and mobile query issues so that her page followed the design from the design team. I also started on section b of fso part 5.

### Day 54: July 18, 2021
#####

**Today's Progress**: Finished fso part 5 section b and exercises, started on section c

**Thoughts:** I finished section b and the exercises, which were mostly code refactoring on the front end. I then started on the next section, which introduced unit testing for react. This part is interesting and seems more complicated than the backend testing, since you have to check the functionality of each components and mock some events like button clicking and form submitting. I still have not written any tests for my projects though, and I am not looking forward to that for my future projects.

### Day 55: July 19, 2021
#####

**Today's Progress**: Finished fso part 5 section c exercises, researched github API

**Thoughts:** I finished section c exercises. I understood more about react testing with the exercises, although there are still a lot of things about it that I don't know about. I just know the basics of the basics. I also researched a bit on github API for a future hfla project, specifically getting the top collaborators on a repo based on the number of commits. I also looked at getting the comments / reviews on individual PRs. Using github api was much easier than understanding the twitch api. Or maybe I just got better at reading documentations.

### Day 56: July 20, 2021
#####

**Today's Progress**: Went through fso part 5 section d and learned about cypress, attended hfla meeting, did another PR for hfla

**Thoughts:** I learned about cypress and end-to-end testing in the last section of part 5. I didn't go through the exercises yet, but if I were to rank the 3 testing libraries I learned (jest for backend, jest for frontend, and cypress) I would say cypress had the most straight forward syntax, then jest for backend, and finally jest for frontend. My last PR for hfla also got merged so I started a new one, which was easier and smaller than the last one.

### Day 57: July 21, 2021
#####

**Today's Progress**: PR got merged, started a new PR for hfla

**Thoughts:** My PR got merged immediately. Wooh! I picked up another one that involved styling with grid and flex. However, I'm unhappy with the initial result that I came up with. In my CSS grid, I have a header that takes up the entire first row. Because of that, the second row of items sit aligned to the left (instead of centered) because of how grid works. There's not enough items on the second row as well, and it'll look better centered, so I need to do some manipulations on it. Probably make that specific section flex. I don't know yet, I've been sitting on this particular issue and messing with it and nothing has worked to my liking. I might take a step back for now and look at it again tomorrow.

### Day 58: July 22, 2021
#####

**Today's Progress**: Submitted the PR I started yesterday, finished fso part 5 section d exercises

**Thoughts:** I finally settled on just making media queries to make my PR work. It took a while, but taking a break actually helped clear my mind. I also finished with the cypress e2e testing exercise for fso. Interestingly, it actually uses jQuery for some of it's functionality, so that was a little foreign for me. In terms of usefulness when it comes to testing, it is probably more useful than frontend Jest, although it's always good to have multiple tests. I don't look forward to writing tests for future projects. The next part of fso is redux, so I'm excited for that.

**Link to PR:** [#1999](https://github.com/hackforla/website/pull/1999)

##  ##  ##  ##  ##  ##  ##
**Useful Links**

[Harvard's CS50](https://cs50.harvard.edu/x/2021/)

[freeCodeCamp](https://www.freecodecamp.org/learn/)

[Full Stack Open](https://fullstackopen.com/en/)

[The Modern JavaScript Tutorial](https://javascript.info/)

[Interneting is hard](https://www.internetingishard.com/)
##  ##  ##  ##  ##  ##  ##
