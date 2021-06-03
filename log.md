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


##  ##  ##  ##  ##  ##  ##
**Useful Links**

[Harvard's CS50](https://cs50.harvard.edu/x/2021/)

[freeCodeCamp](https://www.freecodecamp.org/learn/)

[Full Stack Open](https://fullstackopen.com/en/)

[The Modern JavaScript Tutorial](https://javascript.info/)

[Interneting is hard](https://www.internetingishard.com/)
##  ##  ##  ##  ##  ##  ##
