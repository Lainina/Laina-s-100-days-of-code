# 100 Days Of Code - Log

### Day 1: August 23, 2023 

**Today's Progress**: Dug up and dusted off the timetable tracker bot project, its #BackTo~~School~~Uni in a week anyway. Decided to not use an API library, but to write the interface myself, started figuring it out. 

**Thoughts:** Turns out API requests are a lot simpler than I thought, I think I would have been figuring out the library longer than writing it myself. Also, I'm back to coding! I had forgotten how good it feels to solve problems and see your actually code working (after at least an hour of debugging, of course). 

**Link to work:** [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/3ef60b0fbdb3be0e4ef8bdb8b58f1952f11dad00)

### Day 2: August 24, 2023

**Today's Progress**: Schedule for the next semester just dropped (weird, so early?): wrote that in, tweaking the database along the way. Wrote the logic of API polling, will probably finish it tomorrow. Wanted to start on scheduling, but was tired.

**Thoughts**: Woke up and got straight back to coding — sleep is just an obstacle i guess lol. Spent basically the whole day at it, going slow but going. Wanted to continue but was really tired, the brain was refusing to do the braining. Probably shouldn't overdo it — risk burning out having barely started.

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/22300020d8f86b5c85284115db6bd4d30a5828ff)

### Day 3: August 25, 2023

**Today's progress**: Wrote reminder logic. Eventually got stuck with an error, didn't feel like figuring it out so didn't commit.

**Thoughts**: Programming is fun, but boy is it tiring.

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/e67a957f5ed7cd48fe7314e4d32fd0f89ca6fa72)

### Day 4: August 26, 2023

**Today's progress**: Fixed yesterday's error, did some refactoring, had an existential crisis over OOP principles and structuring.

**Thoughts**: Continuing to realise how little I know. So many practies, guidelines, rules, everything. There's so much to learn, it seems very intimidating. Feel like Jon Snow.

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/e67a957f5ed7cd48fe7314e4d32fd0f89ca6fa72)

### Day 5: August 27, 2023

**Today's progress**: Formatted a couple responses, did a little more refactoring. Basically the bot is almost done, the only thing left is the incomming message processing (which is by no means small or simple) and actual testing in work. Through blood and sweat prepped everything for deploy on Repl. Boy is that site buggy.

**Thoughts**: I have no clue what is the best way to structure this, or if there even is one. All the time I'm like "Is this the right way to do it? Should I do this in a separate method? Should I get rid of this method? In which class should this method be?.." and so on, and so on. Kinda winging it right now, but trying to keep at least some standarts, so that I don't fall into my usual habit of writing shitty unreadable code that holds together on a wing and a prayer but hey, it works, right?..

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/67681a36db10d44cc505cc92f7a487b66dd3ed4e), 
                     [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/d5e1947ec719f213c652b55b0dd04e35139432db)

### Day 6: August 28, 2023

**Today's progress**: Made it so that the bot schedules things for today even if started in the morning, also added a logger.

**Thoughts**: Very tired today, so coded for just a little bit. Not my best code, there definetly are better ways to do this, but the brain ain't braining.

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/0ff13db0b70bafa94cb5222e8323827aeab43c79),
                      [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/280654392b949f904e0b4619ec63937394fa3a94)

### Day 7: August 29, 2023

**Today's progress**: Added some more logs for reminders, used a regular expression bc why not, tested the reminders, so far everything works correctly (weirdly). Deployed everythingto repl, we'll see how it goes. Should definetly convert the database to dataclasses soon, it's becoming a mess. 

**Thoughts**: The bot is basically done and functional. Yeah, I should finish the message handling, but no one really uses it anyway, so i dunno. I'll get to it at some point.

**Link(s) to work**: [Redemption Bot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/6bf259f32850e753c9b518500a3053da555fc35b)

### Day 8: August 30, 2023

**Today's progress**: Added a log for sending messages for easier debug, repl's been doing some random stuff. Remade the entire (well, almost) scheduling logic, now should work better (definetly looks better). Finally made a separate module for all the todays and tomorrows, don't know whether that is the best decision, but so far it makes everything look a lot simpler and removes a lot of redundancy (well, by adding a dependency, but I think it's the lesser evil here).

**Thoughts**: Boy, a sweaty day today, barely got myself to actually do anything, almost missed the day. But then decided to relax for a bit, whatch a couple episodes of House M.D. and then get to work. Worked wonders! Shouldn't force stuff when really tired, better take a break, rest, and then do everything. Ended up coding twice as long as planned (planned on the bare minimum of an hour).

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/0cffb70e577b24cd43b3d93893c2c174b788cc3a)

### Day 9: August 31, 2023

**Today's progress**: New schedule dropped (again...), now with online classes. Rewrote the schedule, then restructured like half of the database, now with long-awaited dataclasses. No clue whether I did it right or not, but it works so far and looks better (I think).

**Thoughts**: Last day of summer! Meaning I had to rush the bot to the working version. Perfect day to do a massive refactor... But well I did it anyway. Repl keeps on doing weird stuff, the server is just turning off and on randomly, which results in a bunch of glitches. Until I find a different place to deploy the bot it's gonna have to run on my old laptop at home. Not a problem for now with online classes since I'm at home, but will have to find a way to keep it in check from far away later. 

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/4332b2350231711b4f37a8e50426caf51ec0d4d5), 
                     [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/04558e95037e8154ed0e66194c65806a07ad34ea)

### Day 10: September 1, 2023

**Today's progress**: Made a lil' fix and then proceded to spend half the day trying to deploy this mess onto my old laptop. I think I succeded. (Maybe. I hope.) Also sorted the imports and made an example config. Not a lot, but it's at least something, am too tired to do more.

**Thoughts**: 1/10th of the challenge done, yay! Also, the first day of Autumn everyone. My uni classes are starting, slowly (actually, very slowly) but surely (actually, not really surely...). Soon I'll most likely have a lot less time for this stuff. Well, I hope to finish whatever I plan on doing here within the next week and start on a new project already. Not sure yet what it's gonna be, I don't think I'm even remotely ready for the Big Project X that I've got planned, should find something simpler for now.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/b9215272521906513649edc53448a16980f28ae6), 
                     [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/4055c630f4e49e07ded263f28f8e4b731d207e94),
                     [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/280bc78cc4f7fd1075c3256f705bc0b7fe128b71)

### Day 11: September 3, 2023

**Today's progress**: Some fixes, debugging and tests, also a batch file to start the bot in one click on my laptop/server at home. (Can't share it in the links, sadly)

**Thoughts**: "1/10th of the challenge done," I said, and then proceded to skip a day. Great. Tbf I just blanked the entire day out, was too dissosiated to do anything at all, so it wasn't really a "skipped coding" issue. But well, I'm back today, 'cause as the rules go, I can skip a day, but never two in a row. Didn't do a lot, some debugging and fixing and minor changes. I don't think I'm gonna finish all the TODOs I have in the bot, should start new project ASAP. Between two options right now: a playlist converter from Youtube to Apple Music or some small fullstack app to learn basics of Django and React JS for future Big Project X.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/7c4052a42f24ecd7a5226db98ed74387071757a6), [2](https://github.com/Lainina/uni_VK_timetable_tracker/commit/be04e53643c8a95f686a326840f6f44c05fac00f), [3](https://github.com/Lainina/uni_VK_timetable_tracker/commit/60306dcef216652bbd6ca0ac2da50df6b2d81fe7), [4](https://github.com/Lainina/uni_VK_timetable_tracker/commit/65e8eb3f4949ee7b6cf755d1845d9d09d374d693)

### Day 12: September 4, 2023

**Today's progress**: Minor improvements, finally started doing message handler logic, but got stuck so didn't commit.

**Thoughts**: I should really stop doing this in the middle of the night...

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/e6b9f35098fcc754643ea5765a5eb49ffbbbea61)

### Day 13: September 5, 2023

**Today's progress**: Added database sorting function and most of the /edit_class command. Still got a lot of work though: need to differenciate between edits and adds, also should add the plain removing feature, and well the current code is very hacky, should fix that too.

**Thoughts**: I gotta wake up in 4 hours for uni... But hey, I got this feature working. I think for me music in the background is essential: without it it's really difficult to get into the 'coding zone', with it — time practically flies by. So far [this](https://www.youtube.com/watch?v=q-NoDGhyQ8A) playlist has been the absolute MVP, I just turn it on and I'm gone for the hour. Gotta find some more though, or it's going to get old real quick.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/8f9f9207ebcd068df95050f85cc7aa689b670dda),
                     [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/cb194ed3e7ae80c197cfcb46cedc781b6f8c70b8)

### Day 14: September 6, 2023

**Today's progress**: Finished /edit_class, added /add_class. Should add the remove_class one. The code is an absolute hot garbage, it's in a deserate need of refactoring, will get to it at some point (I hope...)

**Thoughts**: This time did a little speedrunning — didn't want to end up sleeping for two hours like I did today, really wanna get at least a little bit of my sleep schedule back. So tested what I learnt yesterday: turned on the MVP playlist, started coding. And my hypothesis was correct: I immideately got into the zone, time essentially flew by. Realised how much time had passed only when my internet died and the music stopped at the 50'th minute. Reloaded it, quickly wrapped up and was done with 1 minute left on the clock. It's like magic! Yesterday's point still stands though: no matter how good that playlist is, I need to find some more or it will inevitably get old.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/2e3105ad87fa12c08b320706a3efcfbd475c93b2)

### Day 15: September 7, 2023

**Today's progress**: Made it so that reminders now update whenever the database is updated. Used class inheritance for the first time! Did the observer pattern. Turns out at its core it's pretty simple.

**Thoughts**: I will do more than the bare minimum I will do more than the bare minimum I will do more than the bare minimum I will do more than the bare minimum I will do more than the bare minimum I will do more tha-

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/5793ca6a567b46a1c6dbffff4127990178545d25)

### Day 16: September 8, 2023

**Today's progress**: I. Hate. VK API. Both the vk-api lib AND the API itself. AND BOTH DOCUMENTATIONS. It's like both the code and the docs were written by goddamn chickens on booze. Spent like an hour trying to figure out how to add the buttons and then 3 more trying to figure out why they didn't work. But hey, in the end after dissecting hundreds of lines of the lib's code I finally did it, they show up! Now just gotta make them also do something...

**Thoughts**: Oh boy did I do more than the bare minimum. (Ok, to be fair it still wasn't as much as I was doing in the beginning of the challenge, but it's still a good amount of coding.) Tried out a couple other playlists while coding, they were ok, but not nearly as good as the MVP. Lo-Fi just kinda falls flat on me, even though I usually like it a lot, it's kinda distracting for me. Gotta try more different genres.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/8cb158da5158ecc3d813708a5e7412c2fbe66130)

### Day 17: September 9, 2023

**Today's progress**: Continued with the buttons, a bit more smoothly this time. Still, I've got absolutely no clue how to properly structure this, seems very hacky, but I don't know how to write it better. Guess I'm gonna have to live with this for now, maybe I'll rewrite it once I have a better vision.

**Thoughts**: Was very chill today since I had a rather good sleep, started early and didn't procrastinate 'till the absolute last minute while stressing out about procrastinating 'till the absolute last minute. Should really stop doing this procrastination thing. Feeling pretty neutural after today, but I'm getting kinda tired of this project. I really want to start the new one, but at the same it seems intimidating. A whole new thing, from zero, which is incredibly fun because I get to write everything from the ground up, and incredibly terrifying because I have to write everything from the ground up... Welp, I'll deal with it later I guess.

**Link(s) to work**: [RedemptionBot](https://github.com/Lainina/uni_VK_timetable_tracker/commit/1a74ddfbb5d2f6b7cb4e6a3a41b878077cdabe2f)

### Day 18: September 10, 2023

**Today's progress**: Started learning HTML.

**Thoughts**: Welp, I officially said fuck it and went in a completely differnt direction — I guess I'm now a front-ender, ha-ha. (No. Nope. Noooooooooooooooooo. Not in a million years.) Found a cool [roadmap site](https://roadmap.sh), for now consulting with the full-stack roadmap just to cover the bases. Nothing much today — raw HTML sites are really painful to look at, so didn't even commit. Should probably make a repo with just test projects so that I can put them here. Anyway, I'm officially counting this as not breaking the rules of the challenge, since I'm learning a new language and know way too little to build. (I still wrote a mock site though.) Will try to write and commit something tomorrow as soon as I get to CSS and make the pages look... tolerable. 

**Link(s) to work**: —

### Day 19: September 12, 2023

**Today's progress**: Made a skeleton of a site with HTML, started figuring out CSS.

**Thoughts**: Well, I missed yesterday. Kinda. I mean I did open the sites and finished watching the video on HTML, wrote a little bit more... But that wasn't really enough honestly. Today life also kinda got in the way, but I wrote a bit of something, and tried to write a bit of CSS. Still not really enough, but I'm counting yesterday + today as one whole day I guess. Also, decided that I'm going to write a simple TODO-list (literally everybody has written at least one... Why be the exception?) website, since I recently tried using Google Sheets for keeping track of my uni assignments, but I'm waaaaay too lasy to figure out how to make it work properly. (I would probably need Excel for that anyway.) And so I decided to write it myself from scratch, genius, yeah, I know. Anyway, It's going to need some kind of logic on like sorting and saving stuff, so I'm going to need some sort of backend. Thinking of writing everything with vanilla JS just to get familliar with it. 

**Link(s) to work**: —

### Day 20: September 13, 2023

**Today's progress**: Ditched CSS and HTML and started learning JavaScript syntax since I was aready tired of figuring out styling and margins and all that bull instead of actually coding. Wrote the pseudocode for the backend, layed out some possible ways to implement the functionality using JS.

**Thoughts**: Holy fucking hell JS is such a mess. I haven't even really started yet, but just reading through the basic syntax I'm already imagining how much "fun" it's going to be to debug. How do people even use this thing? And, more importantly, why? It just seems like the developers were really annoyed by errors in the terminal and decided that their language is going to just pull through at any cost, no matter how many type coercions and scope leaks will happen, the code is just going to burn and crash and scream and wail, but execute. 
Okay, tbf there are some pretty cool features that I like and would have loved to have in Python, but damn, everything else just seems like such a headache to deal with. But I guess we'll see how it goes, maybe it's not going to be as much of a problem in practice as it is on paper (though I really doubt it). 

P.S. I will make the repo at some point, I promise... I just got my hands a bit full atm, but I'll do it! (I hope.)

P.P.S. Is it me or are these logs getting progressively longer and longer?..

**Link(s) to work**: —

### Day 21: September 14, 2023

**Today's progress**: Fuck it, I'm any% speedrunning through The Odin Project to get the basics of html+cc+js, because otherwise I'm constantly just jumping from resource to resource, from concept to concept, from rabbithole to rabbithole, I will never get anything done that way (well, at least not until I know enough to actualy write something and work from there). So started speedrunning, also ditched the TODO-list project for now, since it kinda needs the backend, and I haven't even figured out the front yet. So, wrote the html skeleton for the new practice project — just the uni schedule and homework on a website because why not.

**Thoughts**: I reaaaaally gotta figure out that little tiny thing called time bloody managment. I'm just angry because I can't actually progress since I can't find enough time to do so. An hour a day? Heck, even two is nothing, I barely get into the zone, figure out what I wanna do, find where I left off, turn on the music... and the time is up and I have to wake up in 5 hours. Great. Seruously though, I have to make this entire thing more efficient, because I really can't learn nor work like that.

**Link(s) to work**: —
