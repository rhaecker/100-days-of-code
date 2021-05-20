# 100 Days Of Code - Log

### Day 0: April 26, 2021

**Today's Progress**: Wrote about my problem with starting out, set up this repository

**Thoughts:** Wow, it took me a lot of time to write just the one page. I need to practise this kind of writing more, but it is fun, which is a good point for improving on it.

**Link to work:** [dev.to post about starting](https://dev.to/raphael_haecker/my-problem-with-starting-out-4a7b)

### Day 1: April 27, 2021

**Today's Progress**: Spent some time planning for the app. Created a repository for it and one for the backend as well. I scaffolded the NestJS Backend.

**Thoughts:** I need to brush up my Markdown Knowledge, so for now I'm using this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). As much as I enjoyed planning and thinking about the app, I'm looking forward to actually code something.

**Link to work:** [repository for the plan](https://github.com/rhaecker/buzzz), [repository for the backend](https://github.com/rhaecker/buzzz-backend)

### Day 2: April 28, 2021

**Today's Progress**: I began working with the backend. Made not much progress, because I got lost trying to figure out how to not commit the connection data to the mongo db.

**Thoughts:** I never worked with a public repository, so I need to keep in mind not to accidently leak some information like the database connection data. 

**Link to work:** [commit](https://github.com/rhaecker/buzzz-backend/commit/91b77fbb2410df4ebc85ed0f94a7df92669d2600)

### Day 3: April 29, 2021

**Today's Progress**: I worked on different configuration options and als started writing something about it.

**Thoughts:** Testing stuff and writing about it, takes me a lot of time, I think I need to improve my workflow here.

**Link to work:** sadly nothing. It took me longer than expected, so I have nothing that I could commit or upload yet.

### Day 4: May 01, 2021

**Today's Progress**: I wrote a lengthy piece, just to realize, I need to learn to read. Will decide tomorrow if I publish it anyway.

**Thoughts:** I'm still slow at writing. Maybe I can spend tomorrow looking for tips on it. Also I didn't manage to code on friday, so I spend some more time today.

**Link to work:** sadly nothing. It took me longer than expected, so I have nothing that I could commit or upload yet.

### Day 5: May 03, 2021

**Today's Progress**: Finally added the database configuration from the .env file. I managed to do it in a way, so I can configure multiple databases from there.

**Thoughts:** Wow, I suck at this. I skipped 2 days within the first week, which would technically make me fail this callenge already.

**Link to work:** https://github.com/rhaecker/buzzz-backend/commit/6e013b3431faf4422005984d27b178c8fdaaa70b

### Day 6: May 04, 2021

**Today's Progress**: Finished a short write up of my adventures with configuring the database. It contains mostly the results.

**Thoughts:** Not much. Forgot to write the log and commit.

**Link to work:** https://dev.to/raphael_haecker/nestjs-and-typeorm-database-configuration-15ob

### Day 7: May 06, 2021

**Today's Progress**: Finished the story about me and the database config. Also started adding CRUD functionality for Hosts of Buzzz.

**Thoughts:** The CLI of Nest ist cool. Takes away a lot of work with creating the basic structures of the modules.

**Link to work:** [dev.to](posthttps://dev.to/raphael_haecker/what-i-learned-about-external-configuration-of-the-database-connection-in-nestjs-3jhh)
[code](https://github.com/rhaecker/buzzz-backend/commit/3df7982726babb3511296876d6fff8541e08ad38)

### Day 8: May 16, 2021

**Today's Progress**: I have a working CRUD example for the Host. Started reading on how to work with mongodb.

**Thoughts:** Had to take a break, because something else came up and needed my attention. On the project: I'm new to mongo, so I need to look into how things work.

**Link to work:** [code](https://github.com/rhaecker/buzzz-backend/commit/2001d0b83311e43c70584706ec4353146a27f9cf)

### Day 9: May 17, 2021

**Today's Progress**: Worked on checking the email of the host, before adding a new, so there is only one.

**Thoughts:** I'm not sure yet, what is the better approach, querying the db for objects with the email or adding a unique index and trying to add the new object. I will read on it. 

**Link to work:** nothing committed, because it's all unfinished pieces I used for testing. 

### Day 10: May 18, 2021

**Today's Progress**: I didn't work on the buzzz project today, instead I prepared an exam for a student.

**Thoughts:** I really don't like this, there is too much on stake for me to feeld comfortable in this situation.

**Link to work:** Obviously can't link the exam.

### Day 11: May 20, 2021

**Today's Progress**: Added an unique index to email and also an endpoint to check if the email is already taken (let's see if I actually need that).

**Thoughts:** Slowly starting to feel comfortable with this and having ideas how to solve some of the problems I encounter. 

**Link to work:** [code](https://github.com/rhaecker/buzzz-backend/commit/6cd3c365dac61f387af174aca108d31b744a5fb5)
