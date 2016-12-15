**2 do List**
1.  git hub pages?  not sure what they are but should probably know that too.  
2.  
3.  Make a real porfolio page; that's a good idea I just didn't care for codepen.  I might browse a bit of codepen to just see it's templates.  Heck, I could even add the portfolio page to github as practice doing the full creation thing.  I'm in no hurry for this though.
4.  CSS layout stuff - this is last 'blah' thing I'm going to do for a bit.  


### Day 0: Dec 9, 2016

**Today's Progress**: I set this up and am going to test to see if this sync's.  

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after alot of attempts and hours spent.  <== from the original guy.  I think the algorithm's are right around the corner and I'm looking forward to it although a couple projects probably first.  
Now to figure out how to delete the other one I created.  The learning curve sometimes feels like a learning wall that I'm beating my head against.  A paper wall cause i'm done already!
OK, i'm going to make just a little more change and do this once more.  
Changed files get "git add file" to put them into the que to be sync'd.  There's got to be an automatic way instead of manually doing this.  Hrm.. so my current process.
git add log.md
git commit -m "It works"    <-- it works is better than wtf when I must have mistyped something.
OK, it says its doing something but when I look at Github, nothing changed at all.  I'm back to WTF?  
git push <-- and I'm done messing with Git and can finally get back to doing anything code related. 
Make sure I did one tiny thing at freecodecamp before filling in my weak areas. 
Practicing CSS layout actually looks fun compared to everything that I've been doing, make that bootstrap layout. 
First just plain CSS than bootstrap's grid and see if I can do everything with the grid as I can free hand.
I think I'm going to treat this as a full journal.  OK, just had a flash of myself turning into a 12 year old school girl writing in a pink book called "My Diary".   OK, it has to be code related.  Darn, still a school girl but now she's a nerd and pink book just became a macbook pro. 

**Link(s) to work**
1. [basic JS](https://www.freecodecamp.com/challenges/iterate-through-an-array-with-a-for-loop#?solution=%0A%2F%2F%20Example%0Avar%20ourArr%20%3D%20%5B%209%2C%2010%2C%2011%2C%2012%5D%3B%0Avar%20ourTotal%20%3D%200%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20ourArr.length%3B%20i%2B%2B)%20%7B%0A%20%20ourTotal%20%2B%3D%20ourArr%5Bi%5D%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArr%20%3D%20%5B%202%2C%203%2C%204%2C%205%2C%206%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0Avar%20total%3D0%3B%0Afor%20(var%20i%3D0%3B%20i%20%3C%20myArr.length%3B%20i%2B%2B)%7B%0A%20%20total%20%2B%3D%20myArr%5Bi%5D%3B%0A%7D%0A%0A)


** Just finished the first layout practice page. **  The laying out went really smooth and everything nice and scalable.  Had to tie the height in with JS and added a mouse position function to fade the goal image in and out of view.  Overall the whole thing went very smoothly.  Smooth enough to where I might start implementing more anonymous functions although I kinda like my open and easy to read / follow code right now.  Although I'm not sure if I'm going to learn anything in the next two practices; I think I'll do them anyways.  Going to only do one per day, want to do something different.  There's got to be some other little project to start or portfolio page or modify tribute page.  I want to do something different, hopefully challenging.  Whatever the next project is, I'm doing... or starting.   Maybe I'll just jump ahead to the Random Quote Machine!  Sounds boring but easy enough.  Intermediate level doesn't sound right for this. OK, the tweeting sounds like I need to setup a fake twitter account for when I get banned for tweating like madman.
1. get a list of quotes.  quote, author and hopefully can find a list made and in json format. 
2. lay page out, add CSS
3. load up json into an array of objects and just pick a random one.  
4. NOT doing it in codepen...  I want all my stuff here.  I can push it to github and even post it at the free website.  My links are also way shorter than the codepen link which builds the whole darn script in the get request. 
5 (which should be 0.  upload all new stuff to web server so make links. /sigh, this is why I did this 100 day thing.  I'm supposed to make everything public.  /broccoli.  
Alright, step 1!  
** Found some quotes ** Found some quotes that said they were in JSON format and wasn't.  It wasn't too hard to split  into lines and then substring parts into the pieces I needed to make an array of quote objects so it's going to be easy to randomize and innerhtml them into place.  I just realized where all my time disappeared to.  JSON.parse wasn't working because it wasn't a json file and I messed with that a long time.  I wonder if I can write out the quotes into a real JSON file now that it's actually sitting in that format anyways?  Gotta be a way.  Using JS as a conversion tool.  Seems silly but convenient right now.  

###   Day 1: Dec 10, 2016 
** I just did something tomorrow!  ** 
Alright, I understand why I don't have one long streak at freecodecamp.  It's calculating days according to midnight somewhere in the atlantic.   Not sure where but it's equal or greater than 3 hours ahead of central time.  It's just odd that calendar say's that I've done something everyday but streak says that I've missed two days.  Same site telling me two conflicting things.  It doesn't matter about streaks.  
Todays goals: regular expression to find non-letters in quote string to build twitter post. 
Looked and quickly found a url converter which worked simply and easily.  
[Quote Generator](http://joenapoleon.byethost15.com/CodeCamp/randomQuoteMachine/index.html)
With that done, think i'll up this to git and tell codecamp it's done too.  Than do one more CSS practice.  [CSS layout1](http://joenapoleon.byethost15.com/practiceStuff/cssLayout/01/index.html)

### Day 2: Dec 11, 2016
** CSS pages half done **  all plain CSS layout practices done.  Alot more comfortable laying stuff out although I didn't really have any issues so wondering if I learned anything.  Next half using bootstrap to lay it out I've never done so it'll be interesting.  
** Regular Expressions ** I still want or need a lot more practice with these.  I'm seeing so many possible uses just slip thru my fingers.  The one I did use was making an array of Chars from a string, one short line instead of a loop.  They're just so powerful that I need to know them more.  
Side note: the grid with bootstrap was a bit disappointing but I think I've got a way that will work good enough.  The layout work was worth the time invested even though it's a boring topic.  Still have the two complex patterns but not expecting anything difficult to have the practices done.  
** algorithms ** freecodecamp's algorithms for beginners are flying by.  There's might be one that eats up time but so far, 6 hours and most are done.  50hrs estimated seems a bit generous.  
### Day 3: Dec 12, 2016
** from 2do list ** fillezilla should have sync'd but it's not unless I upload the whole thing and just let it update only newer stuff.  Nothing fully automated :(  
** Goals ** also instead of doing this at the end of the day, going to do a log at the beginning.  I'm going to do my goals of the day anyways so if I just do it here, this costs zero extra time.  Thinking of time, balanced binary tree algorithm is still something I want to do from scratch.  I hope it shows up in intermediate algorithms.  
** Todays Goals ** blah... 1) do the other two layouts which are going to be boring but then I can be done with it.  2) Not sure if I want to dump more time into the word counter, but it would yeild more reg expression practice.  3) check all the different reg ex functions, I've only been using one and feel like reg ex is too powerful not to be really good friends with it  4)freecodecamp is last because it's excercises are actually enjoyable.  
** Monday Funday ** I need a fun day and since everyone normally hates Monday, I'll make it my friend.  Anything goes (as long as it's one of the 4 previous things listed, don't want to get too carried away).  OR I can just get the last two grid layouts done now. 
** Finished CSS layout sheets **
** Finished Basic Algorithms at freecodecamp ** 
Hoping the next bit of 'samples' will give me some use of reg exp rather than do solo freelance stuff.  I can think of one thing but that's a pretty big project I think.  

### Day 4: Dec 13, 2016 
** Finished something small **
** Starting Weather API **  call that's requiring me to have it being served by HTTPS.  
I guess it's time to figure out secure HTTP with Node.js.  This is hitting me like a curveball but not expecting it to be any more painful than bootstrap giving me 'denied access' from the link from the CDN.  
** HTTPS on node**  it works enough for chrome to allow navigator.geolocation with just a little complaining.  I can always update that later but I can now start the weather page thing.  https://github.com/Daplie/letsencrypt-express  was by far the easiest way to get the server doing ssl.  It was mindless! or nearly since I had to make just a couple changes.  
** Weather Part 1 ** So getting a location requires a secure connection, and getting the weather requires a non-secure connection.  Need two pages and pass lat/lon in the GET request.  I can do that using different ports I think.  

### Day 5: Dec 14, 2016 
** User Interface ** is a monster that eats time.  I think I am going to end up using the weather page as one of my 8 in the portfolio.  What's left to do for a 'finished' product?  
1) can't just keep dumping values into spots without clearing them.  Need to do housecleaning.
2) have a 'change location tab' that's hideable from bottom maybe and have it default to lookup some place nice.  
3) I guess I could make the background into a slide show but I just dont want to look up differnet pictures and then have to worry about the links changing.  
4) I guess I do need to spend time doing this final phase, I just have to think about it as debugging.    