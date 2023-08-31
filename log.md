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
