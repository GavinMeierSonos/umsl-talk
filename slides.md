---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-up
# use UnoCSS
css: unocss
---

# Lunch n' Learn

Life in software


<!--
Welcome thanks for having me and for coming
- I hope that you all can walk away with a little more knowledge to help you 
- If you are confused after this talk I am happy to chat with you after and help you where I can
- I am excited to be back here at UMSL where my journey started.
-->

---
transition: fade-out
layout: two-cols
preload: false
---
<span v-motion :initial="{opacity: 0, scale: .2}" :enter="{opacity: 1, scale: 1, transition: { type: 'keyframes', duration: 1200, ease: 'easeIn'}}">

# Who am I?
little bit more about me

</span>

<v-click>

- My name is Gavin Meier 👋🏻

</v-click>

<v-click>

- Currently work at Sonos 🔊

</v-click>

<v-click>

- Started learning how to program in 2016 🧑🏻‍💻

</v-click>

<v-click>

- Graduated in 2018 🧑🏻‍🎓

</v-click>

<v-click>

- Live in St. Louis County 🏠

</v-click>

<v-click>

- Getting married in September 💍

</v-click>


<v-click>

- I have a dog named Finn 🐩

</v-click>

::right::

<div v-motion :initial="{opacity: 0, scale: .2}" :enter="{opacity: 1, scale: 1, transition: { type: 'keyframes', duration: 700, ease: 'easeIn'}}" class='flex items-center h-full'>
  <Intro />
</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>



<!--

hot takes
micro services
complexity
multi language

-->

---
layout: default
transition: slide-right
preload: false
---

<div v-motion :initial="{ scale: .2}" :enter="{scale: 1, transition: {type: 'keyframes', ease: 'easeOut', duration: 500 }}">

# Time spent at UMSL
What was life like as a student through the years

</div>

<v-click>

- Started as an accounting major, didn't like class though

</v-click>
<v-click>

- Got a mentor, he recommended:
  - I drop accounting for IS and IB
  - Sign up for the clubs for each

</v-click>

<v-click>

- Started attending events for:
  - IS Programming Club
  - IB Honor Society

</v-click>


<v-click>

- Realized I wanted to write code, not manage people

</v-click>

<v-click>

- Co-op Monsanto (6 months)

</v-click>

<v-click>

- Full time gig at TDK (left after 6 months)

</v-click>

<v-click>

- Graduated December 2018

</v-click>

<div class="w-full flex justify-end items-start -mt-42">

<div v-motion :initial="{y: 200, scale: 2}" :enter="{y: 0, scale: 1, transition: {type: 'spring', stiffness: 20, damping: 10, mass: 3 }}" class='w-md'>

<Graduation />

</div>

</div>

<!-- 
- Accounting Major
  - Came from a community college transfer degree
  - I made a lot of mistakes before hand
  - I was not always laser focused, 
  - for reference I graduated from an alternative school due to missing too much high school. 
  - So pretty much 8th grade to STLCC, 
  - still didn't apply myself all the way there. 
  - Looking back it was due to lack of vision 
  - Dropped out of college, worked in logistics and waste management (trucking for my father)
  - After that I gained more vision, the vision I didn't want to do this shit the rest of my life

- Grandparents friend, Dick Narvarro
  - Sadly he passed away this past year,  as well as my grandfather
  - Great guy though, both worked at Boeing 
  - probably the smartest guy I have ever met
  - Didn't know him that much before joining UMSL
  - Just up time to meet with him to just chat
  - First week and ironically, I didn't like accounting I realized
  - Mind mapping
  - Meet every other week for a few months
  - Words mentioned pointed to joining IS and IB
  - Was able to keep classes but switch majors
  - He recommended I get involved! (VERY IMPORTANT)

- Met Dr Merc and Mo
  - Just showed up 
  - Didn't really know what was going on
  - Met other students, they seemed they had it more together though
  - Ended up voluter to be VP of both the IB HS and IS PC
  - FIgured why not bc I was there anyways
  - General theme in my talk is show up, and prepare as you learn more

- Figured I would be a PM before
  - Took JAVA with Brian
  - Didn't even think it was possible for me to do but ended up liking it so I just did a lot of the work right off the bat
  - Asked him for more work 
  - He asked me if I wanted to be a dev
  - He told me that the salary was high off the bat
  - Interest gained
  - Already making halfway decent money working at Charlie Gittos
  - Paid for school myself didn't want to get job making same amount after graduating
  - Someething he says that has stuck with me all these years, if you got the skills you don't need to worry about the job, bc you are in demand

- I will shoot you straight on the money out there bc its important to know and these are not my pay anymore so I will share the numbers here for awareness
-  Scored Coop more of this later
- Scored salary job making 75k while I was a student
- Graduated with salary of 100k offer
 -->

---
transition: slide-up
layout: center
level: 2
preload: false
---

<div class="text-center" v-motion :initial="{y: -100, scale: 2, opacity: .3}" :enter="{y: 0, scale: 1, opacity: 1, transition: {type: 'keyframes', duration: 1000, ease: 'backInOut'}}">

# How I got my first gig
What it took to get into Monsanto's Co-op and why it was important

</div>

<div class="flex justify-center items-center">

<div v-motion :initial="{opacity: .2, scale: .2}" :enter="{opacity: 1, scale: 1, transition: {type: 'keyframes', duration: 1000, ease: 'backInOut'}}" class="w-md">
  <Vision />
</div>
</div>

---
layout: statement
---

# Set myself up
## for luck

<!-- 
- By attending the meetings and clubs I had exposure to events
- Found out that umsl was open hosting interviews for Monsanto
- Signed up
- Got job
- Had I not been in the club for IS or IB I would not have heard about this stuff
 -->
---
layout: quote
---

"The meeting of preparation with opportunity generates the offspring we call luck." - Tony Robbins

<!-- 
The facts at the time
- Barely knew programming, for reference it took me two weeks to untangle how npm install worked when I did my java two side project
- Had no idea wht I was signing myself up for our how apps worked
- But I knew I wanted to learn how
- Able to see gap in school knowledge vs what for instance my friend from 
the programming club Mo had.
 -->

---
layout: two-cols
---

# Why it mattered
Training on the job and beyond

- Was able to work with a group of other new employees
- Everyone else in the group was a fresh college graduate though
- Learned about new tools and how pieces fit together
- Learned how big of an impact watching some videos on the side could have

::right::

<Learning />

<!-- 
- Able to see how teams should work
- Great place to work in STL
- Honestly might still be there if they had given me a job
- Young people excited about code!!!
- Cutting edge stuff
- Skills in action -> BRIAN SHOUT OUT
- Spent my days learning and then nights watching videos
- I can not stress how important the videos are in the beginning 

 -->
---
layout: center
---

<span class="text-center">

# Filling in the gaps
My last six months of UMSL


<v-click>

TDK

</v-click>

<v-click>

Capstone

</v-click>

<v-click>

Perficient

</v-click>

</span>

<!-- 
- TDK was a place I knew about because I had meet someone who worked
there through yet again attending the IS meetings

  - Because of this I was able to come on as a team member while still in college

- Differences between TDK and Monsanto


- Capstone work start
  - Driver app
  - Deadlines 
  - Pushing myself to the max
  - Nice working app
  - 3 apps actually (2 front ends and one backend)

- Leaving TDk, joining Perficient 
  - Making educated choices
  - Finding people that actually have interests that align with yours
  - Questions to ask
    - Team structure
    - Tooling used
    - Work expectation 
    - Experience of team members
    - Interviews in stl companies in the begining are usually more chats
  - Must haves!!
 -->

---
layout: two-cols
---

# Fast forward
speeding through the years

- Worked with TDA through Perficient
- Taught at Launch Code as the lead instructor (brief)
- Started three companies
- Eventually joined Sonos in May

<!-- 
- I LOVED my team at TDA
- The team is one of the most important aspects
- started as first consultant for TDA for Perficient 
- ended with TDA being one of the biggest accounts
- Built frameworks
- Learned deep knowledge from team lead
- Challenged myself to work on hard stuff
- Realizing my knowledge wasn't complete

- Taught at launch code
- Difference in opinions on delivery (I was still pretty fresh)

- Started
  - EZ Trucking -> Failed to launch in time, beat to market (company that launched made 23-ish million that year in rev)
  - Point Blank Digital -> consulting company with friends 
  - Digitial ART -> Launched NFT project

- Ended up at Sonos
 -->

---

# Focus on your goals
Don't get caught up doing stuff that doesn't help you in the long run

- Decide early on if you want technical path
- Know the road for advancing
- Avoid burn out
- Know when to cut your losses
- Never be the smartest person in the room

<!-- 
- What I mean by this, is your goal to be in meetings 
- Or is your goal to spend time writing code
- Hard to navigate in certain companies (bc its often viewed as the same thing)

- Know what it takes to reach the next promotion or raise
- Make sure goals are clear
- Hold the boss responsible
- If they tell you a certain time, make them hold to it, or leave
- Find the right balance
- Don't overwork yourself
- Spent probably 90 to 100 hours a week coding for a year and a half
- COVID HIT and app failed === Gavin doesn't want to code for fun
- Know when you have reached the point where you are not going to advance
- Know when you are not being challenged 
- If you are doing stuff you don't want to do do something else
- Don't be a lead in your first five years
- Always have others on your team to compete with even if they hit the same level 
 -->
 
---

# Mistakes I have made in my career
Stepping stones on the path

- Doing glue work at too low of a level
- Don't do manager stuff if you don't want to be a manager
- Knowing the road for advancing and not holding the powers that be accountable
- Hitting a stall point
- Burning out (big time 👀)
- Spending time on the wrong things
- Being one the smartest guys in the room (figure out speech I am not that cocky)

[read this!](https://noidea.dog/glue)

<!-- 
- Doing glue work at too low of a level
  - Spending a lot of time in meetings
  - Planning and wasting time
  - Not really having code to work on
  - Getting rusty

- Don't do manager stuff if you don't want to be a manager
  - Don't let PMs failing, make you do their jobs
  - Let them fail
  - They will expect it from you, and you wiill be that person then

- Hitting a stall point
  - Not really being interested in the work
  - NOt really feeling connected with the team
  - Doing dev manager stuff
  - Babysitting teams
- Letting deadlines slide when I should have left (sept oh jan wait now june)
- Learning stuff to just learn stuff that I lost knowledge on
  - Use it or lose it
-->

---

# Successes I have had
The **s\*\*t**  I did right 🤬

- Joining the clubs
- Being involved
- Always learning
- Reading books
- Finding balance
- Taking on the hard work
- Syncing exploration with work
- Learning how to be self managed


---
layout: default
---

# Interviewing 
What matters

- Problem solving
- Explaining yourself
- Asking the right questions
- Knowing that its ok to not know
- Understanding that no doesn't mean never


---

# Local Interview
If you are interviewing in St. Louis

  
- Meeting with the hiring manager or recruiter
  - Coding challenge
  - Behavioral interview
  - Sometimes third challenge

---

# Tech Focused Role Interview
If you are interviewing outside of St. Louis (or a few companies here)

- Recuiter meeting
- Meeting with hiring manager
- Vetting code challenge
- Panel interview (4 hours), sometimes referred to as "On Site Interview"
  - Code challenge
  - Code challenge with existing code (fixing bugs)
  - Behavioral
  - System Design
- Gaps in process sometimes
  - Lots of candidates at once (500 plus sometimes for vetting)

---
# Offers
What to know

- Sometimes signing bonuses are offered
- Base (important)
- Stock
- Bonuses
- Benefits

---
# Daily life
for me at least

- Web technology
- Senior engineer
- Self managed

---
# Hot takes
things I have realized over the years

- Microservices are a solution to an organizational problem
- Java is usually not the right choice
  - I love the JVM but their is a stigma around it
- Multiple git repos is more manageable
- Remove blockers and manual processes
- Not everything needs a meeting
- Don't write pointless tests
  - less unit
  - more integration
- Find the sweet spot on working on stuff you like to learn about
- Teams usually don't change their minds
- Reduce complexity
- Don't re-invent the wheel
  - Know how to make one 
  - Know when to use one
  - Strive for less complexity over redundancy
- Debugging is everything

---
layout: center
---
# Questions
