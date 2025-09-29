# EECS Lecture Slides

## About this repository

This repository contains the lecture slides and some other course materials for some EECS courses at the University of Michigan, plus some non-EECS courses that I thought taught some useful information.

The semester listed next to each directory name is the semester that the slides/resources are from. Most, if not all, of the lecture slides should be present for each given course, but this repository is somewhat opinionated- I have chosen which courses' resources are in this repository, and which lecture slides are in this repository. Some lecture slides are missing because I could not find them (though I usually inserted a best-effort replacement in this case), the course didn't hold a traditional lecture for certain class sessions (such as bakeoffs in EECS 493, guest lectures in EECS 481, or playtesting sessions in EECS 493), or I omitted them because I thought the content was fairly useless (especially apparent for EECS 493 and EECS 481). I have also chosen names for each of the lecture slide decks that will hopefully help you quickly find the topics you're looking for.

For some courses, I have included the course's notes written by the course staff, the course's textbook, or other course-related material, usually because I thought those resources were really good. I have added some of my own written notes to this too, which should be denoted with "My ", but the quality and accuracy of the information in those is not guaranteed. Some of my own written notes contain code- DO NOT COPY THE CODE! You could get honor coded.

The purpose of this repository is not to cheat on assignments, or create exam cheat sheets for you, so I have not included any graded assignments in this repository. This is purely meant for people who want to self-study or review material for these courses, or to help people learn more about courses they're considering enrolling in. Feel free to send me more slides via pull requests.

## My thoughts on these courses

I don't comment on required courses for Computer Science majors (with the exception being EECS 280) or provide my personal opinion about courses I didn't enroll in (EECS 484 and EECS 489).

- ### Highly recommend
    - **EECS 280**
        - If you're still trying to figure out whether you want to major in Computer Science, take this course. This course taught a lot of useful information, but was still challenging enough to be interesting unlike ENGR 101, while not being too challenging to the point of being stressful like EECS 281. You may have heard that the Euchre project was really hard, but personally I think that is exaggerated.
    - **EECS 201**
        - This course is a must-take for Computer Science majors who had little to no coding experience prior to college. It's also great even if you just want to become better with various tools. My most important takeaways from this course were making me much more comfortable using the terminal/command line interface and git and GitHub, which are useful for so many courses. The course also touches on how Makefiles work if you're interested. There are a couple of downsides to this course. One, all of the lectures are pre-recorded and classtime is just for asking questions and doing homework, so attending the lecture times is kind of useless. Two, the course is a lot of work for only granting 1 credit hour. However, if the workload is the only thing discouraging you from taking this, you can also watch the lecture videos on YouTube without enrolling in the course. There are no exams.
    - **IOE 373**
        - The perfect flex-tech for Computer Science majors. It's both relatively easy yet pretty useful, which is hard to find. This course teaches SQL, Visual Basic for Applications (basically programming in Excel), and some Python. I never enrolled in EECS 484, but I've heard the course is somewhat difficult and poorly taught, so this is a good alternative to learn SQL at a more basic level. Attending a portion of the labs was required, but the lab assignments were usually pretty easy. The exams were easy too since they were multiple choice.
    - **EECS 485**
        - Unless you are a CS theory nerd that detests web development like David P., this is a great survey course. I am a little biased because I really like web stuff, but it's very practical since we all use the internet, and I thought the lecture content was interesting, though you might be bored during the second half of the semester if you don't care about how to scale up the web. This course gave me my first exposure to HTML, CSS, JavaScript, SQL, and Python at U of M- it's a great opportunity to learn them if you didn't know them before, though you'll naturally have to put in a little more work to catch up to peers who already do. Note that the projects can be a lot of work. For me, Project 4 (the MapReduce project) was especially difficult. Luckily, the exams for the course weren't bad at all- I recommend copy/pasting a bunch of your project code on the cheat sheets because the code I had to write on the exams was pretty similar to the projects' code.
    - **EECS 482**
        - Honestly, I did not want to enroll in this course because I had heard so many people warn about its extreme workload, but ended up taking it anyway and do not regret it. Yes, this course is a lot of work so you should plan for the rest of your schedule to be lighter accordingly. But it is worth it. A big part of the reason I enjoyed this course was that I found the content very interesting, in large part because Peter Chen is an excellent teacher. Unlike EECS 388 where it felt like they were trying to force as much knowledge down students' throats as they could in 1 hour and 20 minutes, the lectures were well-paced and taught in a way that even difficult concepts seemed very manageable. Regarding the course content, I found it interesting to see how electronic devices multi-task, and it was also interesting to learn more about how software runs on the hardware (though not as low-level as EECS 370 which discusses about gates and transistors), which is surprising because I generally don't care about how hardware works. The content is very applicable because operating systems are present in virtually anything with a processor, and because the principles taught are useful even outside operating systems. The course also goes into detail about how to write multi-threaded code, which is when a program runs multiple snippets of code at the same time. Additionally, it taught me how to use smart pointers in C++. I don't usually read the textbooks for my courses, but the one recommended for this class (Operating Systems: Principles and Practice by Michael Dahlin and Thomas E. Anderson) was pretty helpful, particularly with project 2. Regarding the projects, they are hard, but I think pretty much everyone can complete them if they put enough effort in, and it's less painful if you find the concepts interesting. Probably the main reason that the projects are so hard is that 3 of them are multi-threaded, and it can be very difficult to debug and figure out where the issue is when the output is non-deterministic (that is, changes with each execution). Every course tells you to find a good team and start the projects early, and that is advice you should listen to for this course, especially since students get only 1 autograder submit per day that gives feedback about which test cases were passed and failed. Regarding the exams, this is one of the only EECS courses I enrolled in that did not let me bring a cheat sheet to the exams. They were a bit difficult, but there was nothing unreasonably hard. I recommend understanding your project code well and basically having it memorized.

- ### Pretty good
    - **EEECS 388**
        - EECS 388 touched on many different topics, including cryptography, HTTPS, networks, authentication, and control hijacking, so there was a lot of information to memorize. I never felt like I understood any single topic deeply because it was fast-paced for me, though I could just be slow. The most interesting course content for me was about how we can have secure communications and connections on the internet even when both parties don't trust each other. Some of the content in this course was useful for me when I made a website that used authentication. The projects were sometimes frustrating, but overall they were pretty cool. Project 5 in particular was a lot of work but also the most creative and unique project I did in any course. The exams were extremely difficult and felt more like a test of students' ability to think on the spot and come up with new applications for concepts that weren't discussed in class. Luckily, they were also generously curved- I think even the worst scorers received over 60% after the curve.
    - **EECS 390**
        - A nice course to take if you just want to become a better programmer. It teaches some useful features in programming languages that aren't studied too deeply in other courses including as lambdas, templates, macros, and regular expressions. Some of the course content was more theoretical and less interesting to me, such as the lecture about lambda calculus. It also goes into some detail about programming language design choices and how compilers and program runtime work, though not to the extent of EECS 490. There is an emphasis on functional programming, and to that end it teaches a minimal functional programming language called Scheme which is used for multiple projects. This course also made me more comfortable with recursion. I personally found the projects for this course boring, but at least they weren't as difficult as other EECS courses. The exams were alright too.

- ### Mid
    - **STATS 315**
        - Like an easier version of EECS 445. It makes for a decent flex-tech for Computer Science majors, though I honestly had a hard time staying engaged during the lectures. Sometimes the homework assignments were really easy, and then suddenly the next homework assignment would be really difficult. The exams weren't bad and had a lot of the same questions as the quizzes. 
    - **EECS 445**
        - I enrolled in this course because AI was popping off and I wanted to learn more about it and see if it was something I could go into as a career. This course helped me figure out that I am NOT interested in AI. The lectures were pretty mathy for me. I appreciated Professor Kutty's enthusiasm for deriving some Machine Learning algorithms, but I could not share in that joy. The course briefly touches on transformers, which is the technology behind Chat GPT, but if you were hoping to learn a lot about how generative AI works from this course you will be disappointed. I found the projects boring and a little confusing, though that's probably just a skill issue. The exams were difficult for me too.
    - **EECS 494**
        - This course was my MDE even though I barely play video games. I'm sure the course is more enjoyable for people who really like video games or want to become game developers. Of all the courses I enrolled in, this one had the highest workload for me, even more than EECS 482, but it was due to the sheer volume of tasks to complete rather than the conceptual difficulty. Professor Yarger is clearly passionate about video games and made the lectures engaging even though most people didn't show up for lectures. Regarding the course content, the main takeaways are learning how to use the Unity game engine, how to design video games, and how to work in a team. The majority of the lectures were not technical, so going to them didn't feel necessary, but there were 5 playtesting sessions with mandatory attendance. It was nerve-wracking to have other people play my team's game and point out how much it sucked, but it was also fun to play other people's games, and I was impressed by how artistically talented some of the other students were. Regarding the projects, there are 3 projects in this course, and all of them were tons of work. The first one was recreating either a portion of the original Zelda game or Metroid for NES in Unity with a partner. Me and my partner chose Zelda, and by the end of it I was SO sick of the Zelda soundtrack. The second one was an indivudal project where students could create any game they wanted (with the main restrictions being that it could not be web-based and could only be 1- or 2-player), but only had 2 weeks to make it. The final project was the main one for the course that was showcased at the end of the semester, where students created a video game in teams of up to 5 people. The second half of the semester was dedicated to this final project, and a lot of teams built off one of their team member's second project (a good idea). To save yourself a lot of pain, I suggest making a 2D game instead of a 3D game, and to not hesitate to use public assets from the internet that others made. Additionally, there were some homework assignments which were mostly casual reflection papers or writing about video games which I found boring. Because this course has no exams, it's pretty much a guaranteed A if you put the work in.

- ### Waste of time
    - **EECS 493**
        - Decent if you just want an easy EECS course, but not super useful. One strange thing about this course is that homework code is submitted to Canvas instead of an autograder, so the grading is a bit more arbitrary. The best part of this course is that it teaches some HTML, CSS, and JavaScript, but if you already knew those or have taken or plan to take EECS 485, then this course is useless. Rather than teach how to design a website, it teaches how to conduct user tests through an annoying group project where they students create a Figma prototype for an idea they have for an application. The exams were pretty easy, but overall I don't recommend this course unless you want easy credits rather than a course where you'll learn something useful.
    - **EECS 481**
        - Among all the ULCS courses that I enrolled in, this is the one that I wrote the least amount of code for. It focuses more on what working as a software engineer is actually like and interacting with code in ways besides writing it from scratch. In particular, there is a big emphasis on planning and meeting project deadlines, reading code other people wrote, code maintainability, testing code, and debugging code. Westley Weimer taught this course the semester I enrolled in it, and he is an awesome lecturer who can make even very boring topics engaging. But there were several things I did not like about this course. First, lecture attendance was required. Second, there were readings assigned every class. The assigned readings were typically long academic papers that were really boring and felt like busy work, but questions about them would show up on quizzes and tests so they couldn't be skipped completely. Third, several of the lectures felt like a waste of time, particularly a couple of the guest lectures and this one lecture that went into detail about how MRI works. Regarding the homeworks, they were usually boring and a lot of writing papers but not too hard, with the exception of Homework 3 (Mutation Testing) being really annoying. Homework 6 is the big assignment for the course where students contribute to an open-source project with a partner, and I actually liked the idea of the assignment, though I didn't like how much writing we had to do about it. Regarding the exams, they were open-note and asynchronous, and Professor Weimer even let students use the free version of generative AI models such as Chat GPT on it, but the exams were still really annoying. The exams had a 2-hour time limit and were really long, and felt less like a test of our understanding of the lecture material and more like an exercise in how quickly students could search the course readings to find extremely specific details. Overall, this course teaches some useful things, but there is a lot of bloat mixed in there as well.

## Sources

Some links may require a University of Michigan Google account to access.
Sources that don't have links probably can't be accessed without being enrolled in the course.
Note that links are subject to change and may no longer be accessible or valid.

- **ENGR 101** (FA21)
    - Slides - Laura Burdick and Laura Alford's slides at https://engr101staff.github.io/engr101.org/archive/f21_site.html
- **EECS 201** (FA23)
    - Slides - Brandon Nguyen's slides at https://www.eecs.umich.edu/courses/eecs201/fa2023/ 
    - Note - All of the lectures for this course are pre-recorded and also on this site!
- **EECS 203** (WN22)
    - Slides - Kimberly Diaz's slides at course's Canvas Files
- **EECS 280** (WN22)
    - Slides - James Juett's slides at https://drive.google.com/drive/folders/1e5JY27eSnnLMkqbQEqT6qSGq6OvhCixZ
    - Class notes- Amir Kamil's class notes at https://eecs280staff.github.io/notes/
- **EECS 281** (FA22)
    - Slides - Marcus Darden's slides at course's Canvas Files
    - IA Notes - Andrew Zhou's IA Notes at https://ajzhou.gitlab.io/eecs281/notes/
    - Note - All University of Michigan students can access lecture videos at https://eecs281staff.github.io/eecs281.org/ ! Also note that the IA Notes file is massive- around 230 MB! It is the single reason why I had to use Git LFS for this repository. Normally, I wouldn't have bothered doing all that and would've instead simply excluded it, but the material it contains is too good to not put here.
- **EECS 370** (WN23) 
    - Slides - Jonathan Beaumont's slides at https://drive.google.com/drive/folders/1ylbXTnGTGtJ2gscbgfE0tXns7ZncRn4b
- **EECS 376** (WN23)
    - Slides - Chris Peikert's slides at https://drive.google.com/drive/u/0/folders/1NmikEZ64U5sRsWvRYh1gGayNc1InwJmq
    - Class notes - Amir Kamil and Chris Peikert's class notes at https://eecs376.github.io/notes/
- **EECS 388** (FA23)
    - Slides - J. Alex Halderman and Roya Ensafi's slides at course's Piazza Resources
- **EECS 390** (WN24)
    - Slides - Amir Kamil's slides at https://drive.google.com/drive/folders/1OdtGZV9y93JVuE0x1oS_JfCemGaMq5J8
    - Class notes - Amir Kamil's class notes at https://eecs390.github.io/notes/
- **EECS 445** (WN24)
    - Slides - Sindhu Kutty and Maggie Makar's slides at course's Canvas Files
- **EECS 481** (FA24)
    - Slides - Westley Weimer's slides at https://web.eecs.umich.edu/~weimerw/2024-481F/lectures.html
    - Note - You can watch the lecture recordings from Fall 2022 at https://leccap.engin.umich.edu/leccap/site/ve4jwhsol34majk7b5t !
- **EECS 482** (WN25)
    - Slides - Ryan Huang's slides at https://os.eecs.umich.edu/lec/
    - Note - Generally this course is stingy about who can access their resources. Normally, you can't access any course resources unless you are currently enrolled in the course, but for some reason this link works. You can also get the lab slides at https://os.eecs.umich.edu/lab/ though both only contain slides up to the current point in the semester (so if you check the links right now, it won't show the same slides I saw).
- **EECS 484** (FA24)
    - Slides - H. V. Jagadish and Lin Ma's slides at https://github.com/Pyh2002/EECS484/tree/master
    - Note - These slides were by far the hardest for me to find. Shoutout to Pyh2002 for uploading them.
- **EECS 485** (FA23)
    - Slides - Andrew DeOrio's studio slides at https://drive.google.com/drive/folders/1WlgnyPCZGJT2n32WQRu_eVC-HW7vQFmk
- **EECS 489** (WN25)
    - Slides - Mosharaf Chowdhury's slides at https://github.com/mosharaf/eecs489
- **EECS 493** (WN25)
    - Slides - Mark Ackerman and Xu Wang's slides at course's Canvas Files
- **EECS 494** (WN25)
    - Slides (sort of) - Austin Yarger's documents at course schedule on Canvas
    - Note - All of the lectures for this course are uploaded to YouTube at https://www.youtube.com/@austinyarger9170 !
- **IOE 373** (FA23)
    - Slides - Luis Guzman's slides at course's Canvas Files
- **STATS 315** (WN24)
    - Slides - Ambuj Tewari's slides at https://www.ambujtewari.com/stats315-winter2024/
