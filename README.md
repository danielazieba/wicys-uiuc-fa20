# WiCyS Illinois: FA2020 - SP2021 Tech Workshop Materials

Sildes and code, where it exists, are included in this repository. My reflections on the fall 2020 semester are written below, and you can find some setup instructions for web security parts 1 and 2 in SETUP.md.

# 11/18/20 - On what the WiCyS tech team has been up to

The Fall 2020 semester has been nothing short of chaotic for everyone involved, whether they’re a student, professor, or family member of either. Within the UIUC Women in Cybersecurity club, Tianyun and I have tried our best to produce interesting and engaging tech workshops that are informative for members who want an intro to cybersecurity topics while not completely boring them with yet another Zoom call on their calendar.

At UIUC, the first security course that students can take is CS/ECE461. Most students will only be eligible to take 461 starting in their junior year due to the prerequisites, and as a class known to be very time-consuming, many students may delay it further to avoid taking it concurrently with other challenging upper-level coursework such as CS/ECE374. Whereas other topics may be introduced earlier into the curriculum for CS and ECE students, freshman and sophomores may find it more difficult to find a starting point for cybersecurity. So, that’s where WiCyS hopes to step in and help bridge that gap.

This semester, we organized 7 workshops for our members, which were hosted roughly twice a month, and lasted between 45 minutes to an hour depending on other announcements made during our meetings. We also want to host an EOH booth to raise our on-campus visibility while hopefully inspiring attendees to pursue cybersecurity or CS in general, so we started development on our EOH project by meeting every week.

## On workshops

We started out with a broad intro to different cybersecurity roles one may encounter when applying to jobs and internships, with some info on what skills such positions may look for, which companies are known for hiring for security, and a light overview of what different interviews could look like. There are many resources available for general software engineering interviewing and roles, but less so on cybersecurity specifically, so we hope this ended up being helpful. Some examples discussed for how one can get involved in security include looking for government roles, general software engineering positions with a security flavor, security consulting, and security research, as well as what each type of interview may look like.

After that came two weeks of web security. Well, we intended for it to be web security, but it ended up becoming an intro to networking! In part 1, we started with a broad intro to the web in general, emphasizing the difficulty of security due to how many components are involved in web security and covering some basic HTML, CSS, and Javascript syntax. Then, we wrote a Node.js TCP client and server which could successfully communicate for a few reasons. Learning networking in general, learning that you don’t need a complex framework to make a basic server/client, and learning more about Javascript/Node are some of these reasons. Then, in part 2, we backtracked a bit by delving into the conceptual side of the layers involved in the TCP/IP suite.  We upgraded from TCP to an HTTP client/server, also learning about both protocols in the process, as well as how to do things like handle GET vs. POST requests and send/parse different data types successfully. If you haven’t taken CS241 yet, note that our client/server code would probably work pretty well in communicating with your client/server in that MP, though I will warn that I haven’t tried it.

Especially due to a corporate tech talk falling in between two tech workshops, we wanted to host something more casual through a social engineering workshop. We only had a ~15-minute slide deck ready, after which we decided the best way to learn how to be successful at social engineering would be playing Among Us rather than listening to a lecture on how to social engineer people. I think we all had fun playing the game, and hopefully the imposters also learned how to apply social engineering techniques on everyone else (while crewmates could learn how to identify it). 

Then came, finally, an intro to bash and CTFs. Yes, we know, CTFs are very common for students interested in cybersecurity. However, feedback from past semesters of WiCyS showed that many of our members don’t feel confident in their CTF knowledge, and past attempts at working through CTF problems didn’t help when what we first needed to cover are some topics such as using the command line. So, Tianyun walked us through some CTF challenges which require using different bash commands and techniques to obtain flags which let us keep moving through the levels available. Thank you, Tianyun!

Eventually, we revisited web security again! This time, we really did get to cover high-level web security topics, for which our previous client-server intro was quite useful. We discussed some common vulnerabilities such as XSS, CSRF, and SQL injection. I’ve been a bit dissatisfied in the past by examples of such vulnerabilities which I felt didn’t actually help me understand the underlying reasons such vulnerabilities work, so our workshop tried to provide as much background knowledge as possible in the brief time we had. We also broadly covered ways you can mitigate such solutions. Lessons learned? Don’t trust anyone. Errr, well, don’t trust anyone’s inputs. Maybe not their browsers.

Our final tech workshop is actually tomorrow, which is why I’m reflecting on the rest of the semester right now. We’re collaborating with Women in ECE (WECE), and Pahki has helped us work on our slides for the final topic: machine learning security. It’s a topic which has highly interested me in the past, yet frustrated me due to my underlying lack of machine learning knowledge making it difficult for me to dive in. I’m certainly no expert, but now that I have pretty decent knowledge from two 400-level AI courses, I know enough to provide a gentle introduction. So, we’re starting with a light intro to how we classify inputs in ML/AI, and then explain how object detection differs and why it’s a bit more difficult. We then cover a broad dichotomy of different attacks, which can be classified as whitebox or blackbox, and some specific techniques such as data poisoning. Then, we’re walking through a Tensorflow notebook which provides a fun visual example of FGSM, and more broadly we will cover adversarial inputs and why this topic matters. Some potential methods of combating such vulnerabilities will also be included, as well as how you can learn more about this topic if it interests you.
 
## On our EOH project

Perhaps you want to learn more about cybersecurity, but prefer long-term projects to one-off workshops? Joining our EOH project might be something you’d enjoy. Generally, we’re building a cybersecurity-themed game which is somewhat like a CTF, but intended to be more light/accessible to middle and high school students. We were inspired by picoCTF, but want to take the accessibility a step further - all of us generally agreed that none of us knew how, or were necessarily interested in learning how, to use a terminal back in middle school. So, we want to make security a bit more fun for students like us, and stay away from the hacker aesthetic which is off putting to some.

We met once a week, usually on the weekends, to plan. We quickly found that setting up our game in Unity isn’t too challenging, but realized the larger challenge here lies in developing an interesting game with fun features and good-enough artwork. Oh, and we spent more time than I’d like to admit just figuring out how we were filling out the EOH booth application. 

So, there’s still plenty of work to be done next semester since a lot of time has gone towards game design and making the base assets we need to get started. Whether you want to take on a PM role, help us with art, or work on the game code, we would love to have you join. I promise it’s fun.

## What did we learn?

Being interactive and engaging is harder than it sounds, especially because we were frequently busy with classwork and other extracurriculars, as all students are. It’s likely we’re going to change our structure in the future to have less workshops and more of other tech events, now that we’ve had a semester to think about what security topics students want to learn about and what activities are interesting, versus which ones ended up feeling a bit dry. This is our third semester as an RSO, and many of last year’s board members graduated, so deciding what direction to take WiCyS in was challenging, and we hope to keep improving our events each semester. 

## On how you can get involved

If any of the events listed above sound interesting to you, try stopping by a WiCyS meeting or two; we tend to post events on Facebook and announce them through our mailing list. We’re open to all male, female, and nonbinary students, and seek to build up a diverse and inclusive environment for anyone and everyone who wants to learn more about security. If there’s a particular topic you’d like covered, you should either apply for a future tech role on our board to teach other students about it or fill out feedback forms we tend to send out at the end of meetings. You’re also welcome to reach out to Tianyun and I if you have any questions for us.

 &ndash; Daniela Zieba, 2020 - 2021 WiCyS tech lead. Many thanks to Tianyun Zhang, the 2020 - 2021 WiCyS tech chair!
