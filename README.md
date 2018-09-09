# Cole Vahey Journal
### 02102018  
First journal entry  
### 02102018  
Been working on cracking into the Schoology api and also a little on pickem. The API is being a pain because it uses OAuth and a RESTful API which I haven't used before. The API presents a lot of options for a lot of development with schoology information. I also haven't found a way yet to generate a token for the Schoology API which will be very important. If I can get this up and working, I may be able to work with the attendance data with python rather than dumb web node.  
### 02112018  
I think I have fixed my journal program... Changing the file type from txt to markdown helped immensely with the line breaks.  
### 02112018   
Ok *now* I've fixed it  
### 02122018  
I found the schoology api key generation. While this is a positive step forward, I'm not sure with what I'll be implementing the api. I was thinking python, but there aren't any great modules for oauth2 that I could find. We'll see what the coming week brings in terms of ideas and possibilities for api calls.  
### 02212018  
Today I continued to work on the schoology api after a few days off and with a clear head. While talking to a friend of mine, he brought up his past work with the oauth authentication in the Schoology API which I looked at on Github and now have a working prototype with. My pip continues to stump me as to its intall location and why it won't redirect to my python3 directory even though that's where my PYTHONPATH points. Anyway, progress made today, and I see considerable progress being made in the near future.  
### 02232018  
Up doing some late night research, I found a way to interface between my arduino and python running on the local computer! I am super excited to explore this library when I get a chance. Progress, progress, progress.  
### 02272018  
Began working with haskell. It looks like a lot of fun. Hopefully tomorrow at school, I can get my virtual schoology class and can make considerable progress with the attendance project.  
### 03022018  
Added more to arduino code base... Tomorrow I meet with Ms. Connie to discuss the schoology api dilemma, which I am looking forward to. On another note, I am thinking of adding a timestamp as well as datestamp to my journal entries... Currently it is 12:00AM so all I am getting is 000 for the time. Will test with it at a different time.  
### 03032018  
Continued today with haskell. It is a little slow moving, but I am learning a lot of important aspects of functional programming. Looking forward to continuing  
### 03032018 19:35  
Added a timestamp to my journal program which will show up on all journal entries in the future. Perfect for seeing how much sleep I am losing while researching random topics.  
### 03052018 22:01  
Thought it was worth noting, I fixed a 3D printer today at my high school. I wanted to print the spaceman riding in the tesla sent to space by spacex, but there were a bunch of problems with the 3D printer. An axis sensor was off, a piece of the nozzle was falling off, and the tape on our baseboard was warping due to the heat. I successfully dealt with all of these problems, with a little help from other classmates, and my project should be done printing by now.  
### 03132018 19:41  
DO NOT FALL FOR THE DUNNING-KRUGER EFFECT! aka Do not become complacent with your programming ability, and continue to pursue more and more knowledge.  
### 03132018 19:46  
Ok... my data work can all be found in my SQLWork repo on github. I have a lot of working code in postgres, and a moderate amount in mongo. GraphQL has shown me some new things through the github api, but otherwise, I have not been able to create a web interface to my local data through postgres or mongo (aka FULL STACK). I would really like to get a web interface done which would solidify my skills as a data engineer.  
### 03132018 20:57  
Got back to working on my data classwork tonight... I am trying to create a selector in javascript which will return the salaries of all players on a random NBA team from 2015. Still working, but I should be able to finish it next time I work on it. Kinda irritated with js for not having a `for (foo in bar){}` option which is quite challenging working around. Anyway, I am close to done and I will see what else I can see with this program in the future.  
### 03172018 17:29  
I finally finished the random team selector to show the salaries of each of their players. However, I will continue to work on the part of getting the teams to select from because I settled with creating the array of teams myself, rather than grabbing them from the database. Also, I added a function which will allow a user to input any player in the NBA in the 2015 season, and the program will return their salary, who they played for, and who the highest paid player on their team was and the salary of the second player. This has been working great, except for the long error message I receive if I input a player who was not in the league at that time. A second error I will have to deal with is player names such as **L**e**B**ron **J**ames who does not follow standard title case. All in all, I got a lot done today.  
### 03172018 23:39  
Was having a conversation with my dad when he asked me what the average score in the NCAA national championship has been since 1985. I had the idea to go out and find a csv with the information then query it with psql. I found one with scoring totals from every game in march madness history! I can not wait to see what cool data I can get out of this set.  
### 03202018 21:01  
Created psql queries for my march madness database. I think I have met all the requirements for the psql database initiate certificate. However, I will have to reacquaint myself with mongo before I can say that I have a good representation of my work in that language. One of my more useful queries in psql was to look at all the games in which the seeds of the teams were the same. Obviously, these games were in either the final four or the championship, then I narrowed the search to teams that were not one seeds. Interesting results. More to come.  
### 03242018 14:03  
I added a ton of stuff to my marchmadness queries, including an average functionality that takes all the scores from all games ever in the tournament and finds the average of all those scores. Also, I am trying to create a function which will find the average scores in the championship game alone. The struggle there is that I have to make sure I am taking the higher scores and averaging those together and taking the lower scores and averaging them together, rather than just randomly averaging the scores. I made a lot of progress, and I am looking forward to doing more in the coming days.  
### 03272018 20:54  
I added a bunch of stuff to the march madness queries. First off, I created a query which will match every national champion with its mascot through an inner join. I then added a query which goes through the dataset and finds all instances in which a double-digit seeded team has reached the final four. Another query I added was one that would look at the number of 12-5 upsets and compare it to the number of years data has been recorded for this set. Lastly, I fixed the championship average score finding query, by updating the table so that the winning team will always be listed as "team1" and the loser will always be "team2". A great day of progress tonight.  
### 03272018 20:56  
Fixed a typo in my journal!  
### 04072018 17:31  
I did an object oriented lesson with Rob today, and it was awesome. It was good to get a refresher on the history of OOP and the terminology I need to know. I worked on a SIMPLE battle engine in the last 40 minutes of class that is very close to done, using mostly all OOP. I want to finish this in tech class on Monday, and compare it to my past battle engines that were likely much more clunky.  
### 04102018 20:54  
Got mongo up and running for my march madness data! I think I have met around 90% of what is going to be on the database certificate which is awesome. I still need to fix my join query in mongo and add an upsert to name a few things still left to be done. However, considerable progress was made today, and I am feeling great about where this project is going. Tomorrow at school I will be starting to teach web/js to my tech class alongside a younger skilstak student named Ethan Baker. I am looking forward to this too.  
### 04172018 20:58  
I believe I have finished all of the original data requirements which were set out by Rob. I still need to practice more with some of the commands, but I think I have a good grasp of the data concepts. After I completed that work, I kept working on the tic-tac-toe project I started today to help me practice with object oriented programming. All good, progress is being made, and I think I can do more with the tic-tac-toe at school tomorrow.  
### 04242018 21:02  
Had an awesome lesson tonight. Bit-wise mathematics lesson which included encoding that I had not learned about before. From 64 bit, 32 bit, with different encoding such as ascii and hexidecimal. Looking forward to pursuing more knowledge about the bare bones of computer science. I feel that I have a bit of a gap in my knowledge in terms of very small simplicities of computers. Will look into further.  
### 04262018 21:49  
Finished my tic-tac-toe game earlier this week, and its pretty cool. I have shifted my attention back towards a project I had begun and abandoned in the past: sudoku. The problem with sudoku for me has been the generation of a complete sudoku table. I think this will continue my trials with object oriented programming, and should be quite a challenge.  
### 04292018 23:20  
Continuing to make progress with the sudoku... I am starting to get into the algorithm for generation, but I have been treading lightly because I know how challenging it got last time. Trying to set myself up for success with normalized datasets for all of the classifications. I think I will try a method I saw online of randomly selecting a character, checking it against occupied neighbors, and then placing it. If all neighbors are already taken, I will have to backtrack to the last available location for changing the value until I can create a complete board. I think I can code it, I just have to have the time and the energy to grind out the algorithm in python. Looking forward to it.  
### 05242018 15:37  
I am just coming back to my sudoku program after about a month off, and I am reminded again how complicated it is. I am having trouble even coming up with a function which will print the board properly. Anyway, I am getting reacquainted with the program, and hopefully soon I will be able to get back into the nitty gritty part of programming sudoku and can stop worrying about my `print_board` function.  
### 05242018 15:45  
OK I got that whole `print_board` function thing figured out. Code is pretty clean.  
### 05242018 16:07  
Sudoku project moving along, I think I am on the brink of a breakthrough.  
### 06082018 14:46  
I AM BACK! The end of the school year was a little hectic and I did not get a chance to journal often in the midst of studying for finals and such. I worked a little more on my sudoku, but it is challenging and I still cannot get around the bug I have had for a while. This morning I decided to pick back up on my attendance project which I think I can make a lot of progress on soon with the new idea I am working on. If instead of trying to do **all** the work with the schoology api, I may instead serve a webpage with the data for the class and let the teachers do the actual entering of the data into schoology. This way, it is still quite secure, and I will not have to dredge through the api docs as much. I think I will get the static site working with javascript this summer, and get a full implementation in tech class during the start of the school year come August and September. Looking forward to the progress I will make!  
### 08022018 17:52  
I finally got back to my attendance project today because I grabbed my arduino on the way out of my school. I AM SO EXCITED! In just a few hours, I have been able to get the javascript serialport working so that all of the data from the arduino is being translated to javascript and I can serve it on a website which is not all I want this project to do, but it is a strong start while I wait for the go-ahead to fully automate things. Anyway, the only bug right now is that I can only serve to a specific port using express one time. This is a problem because I am trying to serve after every person gets checked in. I think I can fix this bug in the near future, I just need a little more time for it. All in all, this has come along very nicely in just one afternoon!   
### 08032018 19:10  
Big progress made again today. I got it so that I can use the timestamps to determine tardiness, and I decided I will simply use the end of class as the time to serve the site so I only have to do it once. At this point, I can confidently decifer if someone is on time or late, but I am having trouble with when to serve the site. I should be able to finish this prototype soon, hopefully in time to install it during my class at CSD which will prove I have the skillz to fully automate the process. Wish me luck!  
### 08042018 21:10  
Just added my first ever Version on Github! My attendance project is complete if only on a rudimentary level. If I can get permission to automate it, this project could be **very very** cool. For now, it is operable and should provide at least a little help to Mr. Joe with our tech class this year!  
### 08192018 19:06  
Finally updated my pickem to incorporate javascript ES6 with first class functions and I feel great. I think this project will suffice to show my DOM capabilities, and I will probably open an issue on it that \@s Rob to show him the work. I think this is all that is required for me to be considered a Skilstak developer, but going through the codecademy javascript lessons wont hurt  
### 08212018 19:38  
I have been doing a lot of work with the pickem program, it is coming along nicely now. I think I will save the user data to a file on their computer, which can then be opened in a subsequent session where their games will be checked. All in all, making a lot of progress on this project.  
#### Sep-08-2018 20:27  
Trying a little something different  
