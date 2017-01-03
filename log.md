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
### Day 6: Dec 15, 2016
** Boot CRAP **  90 percent of last two days is just dealing with bootstrap crap.  It's STILL not doing a simple little text input box right, still not keeping the a col that's pushed and pulled into the center, in the center.  DONE WITH BOOT CRAP!  Normal CSS was so much easier and consistent.  LAST time with bootcrap.  Complete waste of my time.  
** Weather Done ** 
All the aspects that work good are NOT bootstrap.  Like the bottom ZIP field, it's stuck to the bottom of the window unless the window pushes it into the stuff above it, then it becomes relative to that (and undoes it if getting bigger).  I used regular expressions in a couple places which I'm happy about.  This is good enough.  Banging my head against the wall with bootcrap for 1.5 days really took it out of me.  I need to mess with some algorithm to put some fun back into this stuff.  
I'll try to mix in some git hub practice too.  
** Twitch Done **  I skipped the wiki page, I just didn't care about it and at first error, I moved on.  
I didn't care about this twitch either but I couldn't skip two things in a row.  hahaha, since I didn't care and just wanted a quick layout, I used bootcrap.   Still hate it though and I doubt I saved any time.  
Now I'm up to intermediate algorithms.  
** Shiffman ** I checked git hub for shiffman's pixel sorting and didn't find it.  I wanted to do his search in two different ways and see which was faster.  .sort ( some function )  would probably beat me building a balanced binary tree.  There's some name for those but I just wanted to do it just to do it.  Try to do it only from memory of how it worked.  It was the whole 'turn' the thing that was interesting.  
** Intermediate Algorithms ** 5 of 21 done so far, that 50 hours to do this seems very generous.  I'm watching abe lincoln vampire hunter and did one and it's only half over.  It's so difficult to tell if the girl is hot when she's got vampire crap on.  That's what IMDB is for. Erin Wasson has a hot body, definitely have to do another algorithm right now.   Pig Latin.   I don't know that at all. OH, consonant(s) and yep, she's hot.  I'll just get this done first in an easy way and mess with a regex way later if I want.  
I got 6 done, so 15 more to go in two days.  Very doable. Just did one in 2 minutes or so, maybe less.  I'm tired and just wanted something to think about during sleep but it got done too fast.  These are getting too easy.  OK, I'm down to just 11 left, so nearly half done in one night. 
### Day 7: Dec 15, 2016
** People of the world you may now refer to me as King! ** 
LOL, regex is starting to make sense!  Fantastic feeling when it started making sense.  
/([a-z]+|[A-Z][a-z]+)(|[_-])/ turns out I got rid of second group and let it group itself and did better so I shouldn't be King yet.  Still a great feeling when it finally starts to click.   It's 9pm and it's the only one I've done today but I wasted a ton of time doing it the wrong way which is why I just said, "If I'm going to dump time into figuring this thing out old school, why not do REGEX and then I won't regret dumping the time."  
REGEX is too strong not to know fully. 
Night is still young, 9 left to do in Intermediate (I must have done some earlier but were simple or something).  So many don't even make you think.  
### Day 9: Dec 19, 2016 
** Finished Intermediate yesterday.  I think I used regex to mess with the last couple puzzles, and now first one in Advanced is also a Regex one.  I got tired of messing in codepens after I seen that I would have caught the information that was being tested were strings but getting interpretted as all kinds of different things, arrays, double args... i need to flatten em.  
Anyways, I would have caught it there instead of trying to troulbe shoot my regex pattern and I'm really doubting regex's ability to do an "if, then" thing.  I didn't look at it too much but don't think it works in js.  
So, the puzzle has a bunch of different numbers that i'm not going to manually put in, I shouldn't and I won't.  I will copy and paste it into a file (rather than try to scrape it) and then save the argument in a json file. I have it just as an array of json objects right now and am about to save it as a file.  
This is a good puzzle because it uses both of the challenges from the intermediate algorithms that I liked.
Plan: make a json file with 'number':'teststring'  
in original challenge, load that and test all numbers all time.  
note: keep eyes open for a real flatten function, although I think in practice it'd be easier to fix the argument at the origin rather than try to handle crazy requests.  
I find myself using regex for little stuff, var end = line.match(/"\)/);  I needed to find 
indexOf ") and I guess I could have just did it that way, 
var end = line.match(/"\)/);		
var test2 = line.indexOf('")');
console.log("reg = "+ end.index +"index = "+ test2);
Same thing exactly, how ever the regex failed when using it as line.indexOf(/"\)/);
match has an index prop so who cares, solution = solution.
And this is why stuff takes a while!  All these little side quests.  I've burnt up hours and still haven't even restarted looking at the original puzzle.  
ok, save file, load file and parse, than do puzzle.  Heck, for this one I could just add one more bit and have it have it's correct value and give me a score, filter out all but the ones I need to see.  nah on the filter, but correct value is worth doing.
closing this log, want to do rather than type about doing.
NOTE: 1 minute to add the boolean to the json object. 
save and load file now. 
// feel like i'm chasing ghosts here.  This should be simple look up / use.  nothing working 
   but now I HAVE to figure this out. 
### Day 10: Dec 20, 2016 
*** save/load/test and filter all done ***  Ofcourse it's now 1am can't sleep so going to actually start on the advanced algorithm challenge 1.  Wait, I did start and did one regex filter just to make my check button work.. and it does. Yes, i'm very happy that it does.  Getting the darn save file to work was frustrating.  Interesting, ** more frustration = more happy **  when you get it.
### Day 11: Dec 21, 2016 starts in 10 mins so close enough.  There is a clear NEED to spend more time with puppy training immediately so it will impact code but Living things rank higher before imaginary bits.  Anyways, I got some Sym challenge done but with way too many lines of code and made a recursive loops to do it. It wasn't good looking at all and even if I clean it up; it still wasn't the best way by any means.  The hint said to look up something.. lol, i just watched a bunch of dog training videos and didn't do the code yet.  REDUCE!  my first reaction was to try to use filter's function call as a type of recursive loop thing, but reduce has the ability for a function call too.  It would be actually pretty darn cool to use, nevermind, filter is an array too also.  Array of arrays, I'm still not sure how reduce works.  I'm pretty sure I can do it with filter.  
Day 11: Dec 21, 2016  
I had several issues with this last challenge.  Copying the array of args into an array ends up with an object that's neither array nor not array.  That seemed impossible, add ! and it still passes.  
When I finally decided to just find a video that had a working model of .reduce he was returning {} objects.  With my other issue of array's not staying arrays, this really through me for a loop and took me a long time to eliminate everything except the reduce.  It's odd because I got a small clue on how it works, but want more practice; I would not have guessed what .reduce instructions labelel  "index" controlled what type of object you got back in the interation/function.  I got it working with only a bare bones knowledge of .reduce.  I need more practice with that.  
Not sure what I want to do next, think I might do another challenge and try to use .reduce when I get the chance.  I'd like to use a .map too.  Not a clue on how to use it, just ran across it and it looked superuseful. 
OK, next is just another adv alg one since the one shiffman challenge I wanted to fork isn't on github.  It was perfect because one minor change and huge improvement AND it would have been a good excuse to make a balanced binary sort.  Guess I'll do the change machine now.
### Day 12: Dec 22, 2016 
Puppy taking a lot of time but needed or she's going to become a nightmare.  JS throwing number errors at me. 20 - 0.4 = 19.59999..  Math.floor kills it, and math.round(number, -2) was still trashing all the decimal points and really annoying me.  Well, I ended up with some ugly code so redoing it.  .toFixed(2)  Breaking it down to basics and nothing fancy, although I'll use the foreach because I think it's what fits best.
OK, When I FINALLY get a freaking number rounding function that works, it changes the damn number to string.  WTF is that?  It's probably going to do shit when I change the string to a value. 
15 == 14.954 and I'll be back to a long freaking line just to round a damn number.  
### Day 13: Dec 23rd .. did some algorithm and codepen seen it correct.  Did another one (and I thought the code looked nice and readable, easy to follow and had recursion with a safety net)  I don't know how the codepen can put the output showing it matching and not have it pass the tests.  I'm not going to let it get to me right now and I'm just glad that I have pictures showing it.  I don't even want to waste my time dealing with it.  I did enjoy the recursive bit of code.  I had put on a video and they made it look so complicated and testing for all kinds of crazy stuff; my way was simple.  Going to do some date conversion thing, that's really all it is... a conversion program.  I don't think it should be in the advanced algorithms at all.  SideNote: need to update git and up files to webserver.  
### Day 14: Dec 24th Done with the advanced algorithms, only had those two that had issues with recognition of correct answer.  Yes, i'm positive I have the correct answers since I even wrote a checking program where you can just copy and paste from left side of the screen to the code and have 
it check.  I made pictures and satisfied my paranoia but I just don't want to bother with the little things like that right now.  
### Day 16: Dec 26th started Tomato clock yesterday, only did layout.  I started to make everything scalable than I stopped myself because, this really isn't going to be used.  One timer and a toggle to that switches between one setting or the other.  Some clickies to adjust times and start/stop timer. I think I'm going to use recursion rahter than setInterval because I really don't want to use any globals and not sure if I'd be able to turn it off from a different function.  I should check it, why not.... I'll do that first.  
### Day 17: Dec 27th Finished basic Tomato Clock, it looks and acts like the demonstration model.  I might add some fireworks or other visual to it but not till after all 4 projects are done. Starting on calculator now.  Maybe not now, I first have to make a fire.  That seems like a huge dichotomy but it's the 'burn wood to stay warm' thing that makes me feel real dealing with so many ideas that are purely imaginary.  OK, time to do this git stuff.
Calculator has all it's buttons and layed out, has shadow but still doens't look at good as the example.  I have no plans on taking it there either.  I was trying to do all the buttons in a loop and I succeeded so far.  I'm further than I thought I'd be right now so going to sleep.
### day 20: December 30th  I spend more time doing tweets than here.  I guess it's because people read those.  More 'on stage' like now, I tweeted I'm going to do tic tac toe.  I still haven't started.   I have to play with dog a little more and upload her videos.  10pm and just about to start my hour.  
### day 22: January 1st  Tic Tac Toe is pretty much done but I'm not liking my code.  Sitting on a fence whether to trash it .. yeah, going to trash it and redo it. Yeah, I can make a ton leaner.
Had flaw in game logic in original and really want to make this code look very readable.  Leaner is going out the window for easy to understand.  Totally going to keep my over complicated square object. 
### Day 23: January 2nd Tic Tac Toe is still not finished.  I need to have the computer be able to create a fork when it can, check for win (which is simple), make splash screen for X or O selection. 
This puppy is a HUGE distraction and is now my shadow.  Hard to schedule time when she's still at this critical part of new house and training.  If I don't spend the time now, it'll cost me much more time/energy later in trying to break the bad habits.  


