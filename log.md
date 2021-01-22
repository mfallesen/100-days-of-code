# 100 Days Of Code - Log

### Day 0: Friday, January 1st, 2021

**Today's Progress**: Worked on the shoppies awards page and got most of the basic markup done along with a start into the styling.

**Thoughts:** 
This app screams to be made as a react application but i want to give it a go making it in Pure HTML, CSS and Javascript(Thats right not even Jquery but dont hold me to that). Since its been a while that ive worked with just the basics there was a little bit of googling involved but after an hour and a half of work im pretty happy where its at. Tomorrow I hope to get a few more hours in and begin working on the interactive elements once everything is styled up.

**Sucesses:**
  Starting with basic html ccss and akavascript reminded me of how much I still have to learn to write good code. I did learn several new VScode key Shortcuts now that im not trying to folow an instructior or tutorial. 
**Failures:**
  I seem to have forgotten exactly how flexbox works. It took a bit of stepping away and going back to look at it before things became clear again and i was able to press forward. However, this also led me down several rabbitholes that I definetly did not intend to get stuck in. I have to work on not getting easily distracted.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 1: Saturday, January 2nd, 2021

**Today's Progress**: Finished working on the styling of the page and immedieatly began refactoring the CSS into a more concise and readable format. 

**Thoughts:** 
The styling is where I want it, for now anyways. I'm happy to have gotten through it since ive always struggled with CSS. It's by far my least favortie part of development which is part of the reason I'm forcing myself to not use a framework and instead style each piece individually. To that end I've started building myself a little personal frameworkfor this project that I may take an make a standard template for myself for future projects. I definetly need some more work using pseudo classes but thats something I'll tackle when I have the Basic JS implemented.

**Sucesses:**
Finished most of the basic styling relatively quickly and managed to get a good way into refactoring whats there. Focus was significantly better today and the rabbit holes I ended up going down were all related to the topic I was looking into so it wasn't time wasted. 

**Failures:**
Still spent far too much time going through and looking up the different CSS rules. It took longer than it should have to get my head wrapped around some of the concepts but hopefuly thats an issue I'll get better at over time.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 2: Sunday, January 3rd 2021 

**Today's Progress**: Finished refactoring CSS, Added some interation effects, and wrote the basic call to the OMDB API and got a successful response.

**Thoughts** 
I need to go back and tweak the CSS and add some other options but everything is in a good place for now. Eventually I'll have the page significantly more interactive than simply just being able to search but baby steps for right now. CSS is becoming easier and I felt much more comfortable working with it today. Instead of wrestling with it it felt like it was cooperating for once which is a really good feeling. This is my first time using fetch and it was significantly easier to use than I had thought it would be. The plus side of that being that tomorrows work should be siginificantly easier and quicker to do than I originally had planned for. 

**Sucesses:**
Was able to finish CSS quicker than originally planned and go be able to get an API response using fetch() instead of AJAX. It puts me a few hours ahead of where I had planned on being which means ive got more time to work on the bug fixing and/or adding other functionality.

**Failures:**
Only Able to work on the project for an hour today. Ideally I'd have prefered to work another 3-4 hours like yesterday.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 3: Monday, January 4th 2021 

**Today's Progress**: Finished the search functionality, finished rendering the search results as card, started tracking nominated movies and got them ready to be put onto cards tomorrow. 

**Thoughts** 
I managed to learn 2 new things today the .insertAdjacentHTML method and debouncing. Both of which made life easier for me. I managed to get the data for the API call onto the cards fairly quick (thats there the .insertAdjacentHTML comes in) and read the search field input to make the call. And then I though I should be able to take out the button entirely and just have a live search. Which is where the debouncing comes in. It took quite a bit of reading and googling examples before I was able to replicate the effect I wanted. I'm gonna keep the button and give the user the option to turn the search as you type on or off. 

**Sucesses:**
Figuring out debouncing was huge. I can see its usefulness in many other places and not just on an input field. also need to check out its cousin throttling 

**Failures:**
I can't find an elegant solution to the fact that some of the titles on the cards change the way the card looks because of the titles wrapping onto other lines. One of the bigger problems I'm having is that I only get 10 results returned from the API. I dont know if its because I'm using the query wrong of if its because thats its limit. 

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 4: Tuesday, January 5th 2021 

**Today's Progress**: Added code to disable button once a movie was nominated and to save items to localStorage

**Thoughts** 
Worked late into the night so this update is the next morning. Everything went well for the most part until I had to compare two values from seperate places. Think I may have solution which I'll try and implement using the data- attribute in HTML. finding that as the code gets more complicated im wondering if it wouldn't be worth splitting the code into more readable modules. For now Things will stay the way they are.

**Sucesses:**
Pulling Items in and out of local storage proved far easier than I had remembered and saved me quite a bit of time.

**Failures:**
The logic to compare to see if a movie is already nominated is faulty and im going to have to rework it. 

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 5-6: Wednesday, January 6rd AND Thursday, January 7th 2021

**Today's Progress**: Combining Day 6 and 7 for what should be obvious reasons. Wednesday I got most of the information moving freely in and out of localstorage and rendering properly into their elements. Today I tidied that up and added a banner to let users know once theyve reached a certain limit of items as well as actually limiting them from adding more. 

**Thoughts** Today was more productive than yesterday for sure. I managed to get a very good amount of work done in the three or so hours that I managed to dedicate to the work today. Tomorrow should mark the completion of this project. Then I can start adding a few nice to haves onto the page to give it a bit more utility.

**Sucesses:**
Lots of work completed between yesterday and today. The information needed to display thing on the page is there and just needs to be manipulated into place

**Failures:**
Still feels like work is going too slow.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 7: Friday, January 8th 2021 

**Today's Progress**: 
Enabled the removal of the elements if being un nominated but not from the stored array.

**Thoughts** 
Today was rough. I spent almost my entire time working trying to figure out something because i decided that i needed to overcomplicate things. Which puts me behind schedule. I did end the day with everything figured out just not coded yet (unless you count my chicken scratch on a notepad about what needs to be done coding). Tomorrow should see the end of the biggest JS problems and instead give me the freedom to work on making the page livelier with animations and interactivity.

**Sucesses:**
Kept working despite frustration at inability to solve problem.

**Failures:**
Took way to long to solve the problem. 

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 8: Saturday, January 9th 2021 

**Today's Progress**: 
Finished the page to the minimum requirements.

**Thoughts** 
Finally done with the basic work and its a fully functioning page! took a bit longer than I would have like but it is finished and ready to be deployed in a working state. Time to add a few extras, the ability to favorite movies, cleaning up the CSS and adding some animations to the effects. along with tooltips and ways to give the user some more information about the movie they have picked.

**Sucesses:**
Today went really well and I managed to get the page to MVP

**Failures:**
The project took longer than I would have liked.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 9: Sunday, January 10th 2021 

**Today's Progress**: Worked for a little over an hour today. Finished troubleshooting some render issues.

**Thoughts** 
Today was a quick day and this is being written retrospectively. I've spent most of the time troubleshooting a rendering issue and trying to find a way to implement it that wouldnt cause too big of an issue. 

**Sucesses:**
Page now renders correctly on page load and when nominating and renominating movies. This was a quick fix all things considered.

**Failures:**
Too little time spent on the code today.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 10: Monday, January 11th 2021 

**Today's Progress**: Finished the application in its entirety

**Thoughts** 
Today was spent working on and finishing up the entire page. From cleaning up a bit of Javascript, ensuring comments were readable and made sense to finalizing the CSS I can say im happy with the status of the page. I've got some improvements that I can think of making but I think its time that I went ahead and moved on to another project. 

**Sucesses:**
The Application is finished and looks well polished for what I wanted. 

**Failures:**
This took too long to finish for basic Javascript and CSS

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 11: Tuesday, January 12th 2021 

**Today's Progress**: Site is finished and published.

**Thoughts** 
Today was spent putting the final touches on the site and minifying both the css and JS files. Not much else was done but the page is up and live on github pages. I'm quite pleased with how its turned out for being just javascript and no framework

**Sucesses:**


**Failures:**
This whole task took longer that id have liked.

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

### Day 12-13: Wednesday, January 13th and Thursday, January 14th 2021 

**Today's Progress**: 
Double update again and its finally on a new subject. Working on a new application thats going to run a Node server, with a MySQL DB and a React front end. 

**Thoughts** 
Yesterday was mostly working on getting the environments set up so that I could start working on them and today was the start of actually sitting down to code the start of the server. The server itself is running, the databases have been created locally and working on the models for the user. Taking a break from making the ERD for the Database to update this log.

**Sucesses:**
New project is always fun and its an idea that I will actually want to use for myself. gotten much further today than I had first imagined I would. 

**Failures:**
Perhaps a little unoriginal ( I havent bothered to check if there are any applications like this out there)

**Link to work:** [A Spicy Front](https://github.com/mfallesen/spicy-front)
[A Spicy API](https://github.com/mfallesen/spicy-api)


### Day 14: Friday, January 15th 2021 

**Today's Progress**: 
Finished sequelize models and was able to spin up the server locally and have sequalize interact with it.

**Thoughts** 
Spent a little bit of time this morning to finish off the ERD and then spent the rest of the time working on writing the models for the database to interact with. After a few hiccups and being able to troubleshoot through some of them I was finally able to spin up the server locally and make interact with the database. Tomorrow is going to be starting on the controllers or perhaps the authentication portion of the server. Not much longer before I can start working on the front end. 

**Sucesses:**
got a good amount of work done with relatively few distractions. 

**Failures:**
Spent too much time troubleshooting the sequelize associations that were initially causing errors. 

**Link to work:** [A Spicy Front](https://github.com/mfallesen/spicy-front)
[A Spicy API](https://github.com/mfallesen/spicy-api)

### Day 15: Saturday, January 16th 2021 

**Today's Progress**: added authentication and creation capabilites for users

**Thoughts** 
Today was short and productive. The create users route was finished and tested along with their password encryption using passport and bcrypt. It was a nice change of pace and hopefully tomorrow I'll have a bit more time to spend on working on this. I'm itching to get a start on the Front end but I'm also aware that I should finish the back end first. ive yet to implement CORS but thats becaus eim waiting on actually having a front end to send requests from. 

**Sucesses:**
able to use postman to create a user in the DB and encrypt their password. 

**Failures:**
Not enough time spent working today. Well over an hour but I could have done more. 

**Link to work:** [A Spicy Front](https://github.com/mfallesen/spicy-front)
[A Spicy API](https://github.com/mfallesen/spicy-api)

### Day 16-17: Sunday, January 17th and Monday, January 18th 2021 

**Today's Progress**: finished some more of the models. realized my relationships are all wrong so im pulling the database apart and rebuilding the models.

**Thoughts** 
Good progress on Sunday was hampered by terrible progress on Monday. Looking at how I had my relationships set up I realized that I'm going to have to redo the model and rethink my database. So thats what I've been doing for most of the day. Actually mostly reading documentation but thats gotta count right? I was expecting to be demoralized but instead in more fired up to get this reworked so ican get back to wrok 

**Sucesses:**
Got routes for adding spices to the database up and working

**Failures:**
having to redo my entire model and association tables. 

**Link to work:** [A Spicy Front](https://github.com/mfallesen/spicy-front)
[A Spicy API](https://github.com/mfallesen/spicy-api)

### Day 18: Tuesday, January 19th 2021 

**Today's Progress**: finished some more models and routes after

**Thoughts** 
Today was also productive. Much time was spent reading documentation again (not that thats ever not going to be a thing). but i still managed to get a good amount of work finished and left only a single thing for tomorrow. that said its the most complicated route yet and relies on several promises and isn't as easy to just throw into an async fucntion and await the result. 

**Sucesses:**
Lots of work got done after reworking the database yeasterday

**Failures:**
No real failures unless you count not reading codumentation and understainding it fast enough one. 

**Link to work:** [A Spicy Front](https://github.com/mfallesen/spicy-front)
[A Spicy API](https://github.com/mfallesen/spicy-api)

### Day 19: Wednesday, January 20th 2021 

**Today's Progress**: worked on updating my Portfolio

**Thoughts** 
Spent a good amount of time going through my portfolio and editing some minor mistakes as well as adding some more functionality to the portfolio section. 

**Sucesses:**
Had no issue replacing the modals withones better suited to describe the projects. 

**Lessons Learned:**
theres always room for improvement in the code. Going over old projects makes that Painfully Obvious. 

**Link to work:** [mikefallesen.codes](https://github.com/mfallesen/mfallesen-codes)

### Day 2: Thursday, January 21st 2021 

**Today's Progress**: Reworked an old weather dashboard. 

**Thoughts** 
Spent a decent amount of time reworking the weather app and making small adjustments here and there. Figured out how to get the data into the object much quicker than I had in a previous iteration. I think I might well redo this application again but start from scratch and make it much nicer looking. Maybe even as a React Application

**Sucesses:**
Was able to rework and get the application back to a more acceptable level of completeness. 

**Lessons Learned:**
Theres always room for improvement, especially in code thats month or years old. 

**Link to work:** [WeatherDash](https://github.com/mfallesen/weather-api)

### Day 2: Sunday, January 3rd 2021 

**Today's Progress**: 

**Thoughts** 

**Sucesses:**

**Lessons Learned:**

**Link to work:** [theshoppies](https://github.com/mfallesen/theshoppies)

