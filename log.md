# 100 Days Of Code - Log

### Day 0: March 31, 2020 

**Today's Progress**: Followed a scrimba tutorial to build a Tic-Tac-Toe game in React using hooks and fuctional components. Today is day 0, it does not count.

**Thoughts:** I really enjoyed getting back into development work. I know I didn't challenge myself a lot mentally today since it was more of a 'type-after-me' exercise, but it was enjoyable to hop back on the horse after letting life get me sidetracked. 

**Link to work:** [Tic-Tac-Toe](https://github.com/MCStuart/tic-tac-toe)

### Day 1: April 1, 2020 

**Today's Progress**: Started the [Random Quote Machine](https://www.freecodecamp.org/learn/front-end-libraries/front-end-libraries-projects/build-a-random-quote-machine) project from FreeCodeCamp.org. I spent most of my time today working with Paper Quote API and not succeeding. 

**Thoughts:** I still have trouble starting projects. It took me until later in the day to *actually* sit down and start, but I did and that's what counts. I'm using React and Hooks for this project and am excited to get to use useEffect().

**Link to work:** [Random Quote Machine](https://github.com/MCStuart/random-quote-generator)

### Day 2: April 2, 2020

**Today's Progress** Successfully implemented a quote API with onClick to fetch a random tech quote! Functional twitter button to tweet out the current quote with author, suggested hashtags, and 'via @' acknowledgement. Found the encodeURI() feature so I didn't have to regex the whole quote to clean it for imbedding it in the twitter href URI.

**Thoughts** I was barking up the wrong tree with the Paper Quotes API. I found a new API, [Programming Quotes](http://quotes.stormconsultancy.co.uk/api) to use last night will watching a movie, swapped it out today and fired it up to almost instant success. Be careful, as some of the quotes can be a little raunchy, but programmers have never been known for their social prowess. I used the css grid to center the quote box, but the styling looks amature at best. I'd like to spend tomorrow giving it a real nice coat of paint. It's something I have often struggled with. 

**Link to work:** [Random Quote Machine](https://github.com/MCStuart/random-quote-generator)

### Day 3: April 3, 2020

**Today's Progress** Styled Random Quote Machine to make it look less like a 90's webpage (It still does though). Added Twitter logo as the anchor tag button, spread buttons to far bottom corners, moved author attribute to be right justified to look better stylistically 

**Thoughts** CSS is *hard*. It is something that I don't jive with. I always work until MVP and never spent any time working with styles so it is by far the weakest part of my repertoire. I think I naturally gravitate towards back-end work but I'm not experienced enough to make that declaration for sure. The problem as I see it is that styling feels like 'wasted' time for me. Making it look good doesn't make it work, but I realize it has to look good to get anyone to even look at it in the first place, unless it cures cancer or something and the product's merit is enough to carry it, which my projects certainly are not. 

**Link to work:** [Random Quote Machine](https://github.com/MCStuart/random-quote-generator)

### Day 4: April 4, 2020

**Today's Progress** Started a SMS messaging service with cron-job scheduler to send appropriate reminders to specific people for household chores (thanks corona). I have single messaging and cron-scheduled tasks down reliably, but broke everything last minute.

**Thoughts** Twilio is a lot of fun. I tried to send out a batch job without using their messaging service for batch SMS jobs and it predictably didn't work. I changed it back to just my number to make sure everything else was still working but left the loop in so accidentally sent myself a huge amount of texts, almost locking up my phone before I realized what had happened. Whoops!

**Link to work:** [House Scheduler](https://github.com/MCStuart/house-scheduler)

### Day 5: April 5, 2020

**Today's Progress** Successfuly completed MVP of Twilio SMS reminders sent daily at noon (12pm). Using Moment.js to easily parse the day of the week, appropriate housemates (with corresponding phone number) are selected and sent their assigned chore message of the day. 

**Thoughts** I had a lot of fun and easily spent twice as long as I thought did just tinkering. It is MVP and a certifiable mess of spagetti-code, but it works. I would love to find someone else to help me restructure this in a more professional way. It also needs a databse so the chores, housemates, phone numbers, etc. can be more easily altered. As it is, it's all hardcoded. There is also need for a hosting service so that I don't have to run it off my local computer. 

**Link to work:** [House Scheduler](https://github.com/MCStuart/house-scheduler)

### Day 6: April 6, 2020

**Today's Progress** Not a lot of progress or success today. Explored cloud hosting solutions for the house scheduler app I created. Settled on Heroku with event scheduling and postgres db.

**Thoughts** Not a lot of tangible work got done today, which is frustrating. Heroku was picked because of brief exposure to it months ago for another event scheduling task that barely worked. AWS seemed prohibitively esoteric and a SQL database is preferable to a noSQL one in this case. I hope to have a working product to deploy by end of day Thursday at the latest. 

**Link to work:** [House Scheduler](https://github.com/MCStuart/house-scheduler)

### Day 7: April 7, 2020

**Today's Progress** Made RDS (Relational Database Service) on AWS and connected to local pgAdmin, created tables, linked with Heroku.

**Thoughts** I had to quit out of frustration today. There is something obvious I am missing. I hope a little more reading and sleeping on the problem will help me start fresh tomorrow, as I am hopelessly frustrated and stuck today. 

**Link to work:** [House Scheduler](https://github.com/MCStuart/house-scheduler)

### Day 8: April 8, 2020

**Today's Progress** Started CS50 and programmed in Scratch today. I'm creating a spaceship-shoots-aliens game and have a mooving background, keyboard controlled rocketship that changes depending on the key-press, and laser stars that shoot out from the front when the spacebar is held down. 

**Thoughts** I had to take a break from my house-scheduler app. I don't know how to move forward so I will be talking with a friend tomorrow about it. I hope to be able to start it back up in the near future. Instead, today I started Harvard's CS50 class which I have heard so much about. The professor was exciting and explained things wonderfully. I hope to complete the class by the end of my #100DaysOfCode challenge.

**Link to work:** [Spaceship-shoots-aliens]()

### Day 9: April 10, 2020

**Today's Progress** Worked on my spaceship-shoots-aliens game to generate enemies and have them attack the ship. Will work on laser collision detection next.

**Thoughts** I missed a day yesterday, so technically I already failed the challenge. I had a personal loss due to Covid19. Reast in peace, Aunt Nancy.

**Link to work:** [Spaceship-shoots-aliens]()

### Day 10: April 11, 2020

**Today's Progress** Coded out sorting algorithms.

**Thoughts** I started studying data structures and algorithms today. I've heard it's a very critical topic that a lot of code-schools and self-taught programmers miss. It is interesting, but hard. I will have to spend more time on it. 

### Day 11: April 12, 2020

**Today's Progress** Worked on CS50 scratch project

**Thoughts** N/A

### Day 12: April 13, 2020

**Today's Progress** Connected Heroku postgres db to pgAdmin, started working on db query string again.

**Thoughts** This is way above my head. I really jumped in the deep end. The documentation assumes so much implied knowledge that it makes me feel really bad about myself. I know that this feeling will not go away any time soon so I will just have to learn how to lean into it and get through it.

### Day 13: April 14, 2020

**Today's Progress** None

**Thoughts** Beat my head against the wall for a few hours with Heroku poostgres. No progress.

### Day 14: April 15, 2020

**Today's Progress** Managed to load Node packages into Lambda as dependencies and successfully run debugging tests

**Thoughts** A lot of progress made today! Not a lot got done, but it was a big challenge to summit. Lots more work to be done. I attended my first virtual meetup event today and did algorithm practice with other people on a screen share. Very nerve wracking but fun. I forgot how much I enjoyed things like this.


### Day 15: April 17, 2020

**Today's Progress** Set up cloudwatch, IAM permissions, RDS, and Route53

**Thoughts** More AWS tomfoolery today. I would like to get back to 'real' coding soon in Lambda, but I have a fully architected project now! 
  
---
## Challenge Failed, Restarted Count

### Day 1: April 20, 2020

**Today's Progress** Did algorithm practice with someone I met on slack. They were simple string and array type problems.

**Thoughts** I'm bummed I missed more than a day in a row. I only let myself down. I'm keeping things going anyway because I would really like to say that I successfully completed the #100DaysOfCode challenge.

### Day 2: April 21, 2020

**Today's Progress** Worked in AWS on RDS trying to connect it to lambda for function data.

**Thoughts** AWS documentation is frustrating. I am obviously below their intended target demographic, knowledge wise and it shows.

### Day 3: April 22, 2020

**Today's Progress** Worked on algorithms with someone I met on the Women Who Code (WWC) slack channel.

**Thoughts** The algorithms were surprisingly harder than I expected, especially when having to work them out loud with someone else. Mental note taken for whiteboarding.

### Day 4: April, 23, 2020

**Today's Progress** Did more algorithms from freecodecamp after setting up Jest unit tests for independent verification. 

**Thoughts** Testing is sweet! I can see it helping me focus on one problem at a time. I tend to work on too many problems at once, get lost and frustrated, and quit a project. Setting up testing on more projects is a must.

**Link to work:** [Algorithms-Practice](https://github.com/MCStuart/algorithms-practice)
