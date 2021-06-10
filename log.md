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

**Link to database of quotes:** [Audio](https://sampleswap.org/)

##  ##  ##  ##  ##  ##  ##
**Useful Links**

[Harvard's CS50](https://cs50.harvard.edu/x/2021/)

[freeCodeCamp](https://www.freecodecamp.org/learn/)

[Full Stack Open](https://fullstackopen.com/en/)

[The Modern JavaScript Tutorial](https://javascript.info/)

[Interneting is hard](https://www.internetingishard.com/)
##  ##  ##  ##  ##  ##  ##
