# tech-employer-red-flags
A master list of red flags developers should use to evaluate companies they're interviewing at, as well as red flags to look for when they've just started the job


## Job Description

Describes its environment as "fast-paced"

"Should know all 12 principles of the Agile Manifesto"

## In interviewing

Doesn't let you use a mac for iOS development

Can't tell you how new your computer will be

The general sense that people are going to be difficult to work with is for me the biggest reason.

When you get the sense that the lead/manager want someone just to parrot their positions

Bad reactions to your asking about NIH solutions they came up with

If a manager/interviewer puts you down during the interview (e.g. during a coding challenge, calls you non-challant, asks you "where is the passiion?")

Rapid fires you with technical questions and when falter says "You should know this"

If they lull you into what you think will be an introductory or behavior interview, and then they hit you unprepared with challenging technical questions

If they intentionally quiz you on topics in which you had specifically said you have no experience

If you ask them about work life balance and they say "if you love your job, work life balance isn’t an issue”.

When they have more services than people

They have former Amazon people in your reporting 

If they haven't shipped much in the last two years, or if they only shipped stuff that nobody really needed. If this is the case, it might mean:
* There's no real work to do. Sign of a layoff.
* There's a lot of internal conflict between leads
* People are engaging in "resume-driven development" and care more about their own promo than the good of the team

If the team is led by a so-called 'people manager' / 'non-technical manager'

If some of the team members are barely able to conceal their animosity towards each other e.g. during interviews

If nothing seems wrong on the surface, but the team has been suffering from high attrition.

The team is described as "rockstars"

Teams without a good development lifecycle or process

Teams with an uptight culture. Weird dress codes, e.g.

Where the lead 

Cryptobros.

If they make you spend substantial amounts of money going to multiple interviews

If they switch out the location you'd be working at on you

If a manager is rude to one of their subordinates during one of the later interviews.

If they put out a lot of buzzwords, which when reading between the lines, indicate that there are no proper schedules or planning, and that the team routinely does overtime to achieve such poorly planned/estimated targets.

If I get the feeling during latter rounds of an interview, that the managers/leads are obsessed and dogmatic about metrics and agile practices (or for that matter, even any engineering practice). hose metrics-centered where a PM or similar talks about 23% of your effort should be focused on X, 36,22% on Y, etc. We need to deliver 62 story points today but look at the burnout chart, is looking flat... that obsession to convert people in just predictable machines which deliver some average story points per sprint 

any reporting structure where the person who does your performance reviews doesn't directly benefit from the fruits of your labor. Because then there's no incentive to promote productive people.

Also any team talking about being "rockstars" need not even apply for my time. "We ship every two weeks! We're a team of rockstars on the cutting edge!" You run, and don't look back. Can't say I've never signed offers when the recruiter sounds antsy about you signing that day, though, but it's never a good sign.

I don’t work at any company that uses ‘software developer III’ as a title. They are generally top-heavy and will treat you like a robot.

I never work for any team that has a person with the title ‘Scrum Master’. They have no technical knowledge and their job is a joke that has just enough power to make your life miserable.

I never work for a team where no real smiles are shown during the interview. They will not appreciate your ideas, and take the approach that it’s better to drive with three wheels than suffer one that squeaks.

I never work for a team that places more value in meeting an arbitrary deadline than in doing the job right. They will write horrible code and will attack you if you try to refactor. Management will not back you.

People who quibble over minutia in code. I once had an interviewer criticise my take home test as having too many tests (it was about a dozen). It doesn’t matter. They also criticised me splitting some DB queries into their own files instead of one big file - either approach is fine and it does not matter. It’s a red flag as I don’t want to have refinements and PR reviews quibbling over irrelevance.

People who are too confident about their team being exceptional team. I’ve been burnt by this several times. My experience is you get in, the team is shit, and their attitude is blocking improvements. I’d much rather hear in an interview that things are okay, writing some tests, sometimes bugs slip through, and you need to do better. That sounds like healthy reflection to me.

In small places you may hear they have a founding engineer, he’s awesome, and the plan is to let him continue going off doing awesome things. He is trusted to set their own work and should be left alone to important things. To me this screams a senior lone programmer who works in a silo pushing out tonnes of stuff. Often poorly tested. Pissing off other teams. Stuck in their ways and ignores attempts to improve things. They ignore the board and planned work. No one has a clue what they are working on. With poor communication and organisation skills. Who management protects because they ship a high line count. I’ve seen that happen at three companies and it was a pain at all three. Often their work isn’t even that great.

 those places where the human resources department is not called human resources, like "people team" for example

 Hard to understand accents. I have some team members with thick accents and half the time I don't understand what they are saying. If I had a team full of people with hard accents, I don't think I could communicate effectively

 If they don’t have any coding standards. I’ve been on enough teams not to care too much about specific practices, but the team better have them and work according to them. If they don’t, it’s a sign that the team is missing something. Could be organizational, could be cohesiveness, could be skill.

 elitist stances on stuff, signs there's no psychological safety in the team

 For my current role, during the technical testing, one of the engineers wouldn't stop micromanaging what I was doing before I'd even finished reading what they'd asked me to do. I was 99% of the way to declining it but took it anyway after much deliberation. I've regretted that for the last 18 months. Even though that guy got fired from the team, it comes from up top...

I had a screening call with a hiring manager today for an incredible opportunity for me to move into application security and penetration testing. He really wanted to progress me, but from minute 1 he was a dick. Verbally trashed his own prior employees and companies on my CV. I can't work for someone like that.

Leet code questions that have nothing to do with the business.

Unclear source of income. If they cant explain who pays for the software, and why.

Offshore/H1B manager or an excessive number of offshore/H1B employees (>1).


If I’m going to have to constantly backfill unit tests to get anything done.

## What to ask

"What have been your most technical or organizational challenges during your time at company X?"

---
I ask about the workflow for devs, their development environment, and their release process. I've also been working a lot in infrastructure for the past few years, so these are especially relevant to me.

What's the dev workflow like?
What do you use for issue management? Jira, GitHub Issues, etc.?
What version control system do you use, and are they any conventions or rules around it?
Tell me about the development environment. Do people have their own Kubernetes pods, Docker Compose stacks, or virtual machines? How much control do they have? Are their shared resources?
Roughly how often do you release, and how long does each release take?
Depending on how detailed they get with the first dev workflow question, some of the other questions may end up being answered automatically or by natural flow of the conversation.

I might get an answer like:

They pull the next issue they feel like they have some expertise in from the Ready column on the Kanban board in Jira, make a new branch in Git, and start working on their local Docker Compose stack. There's a shared test environment they can push their changes to when they feel like it's ready for review, but we don't have automated tests in that environment.
That lets me know a lot about how they work and the fact that they know they would like to have automated tests, but currently don't. That's not an ideal workplace, but it shows their on the right track.

Unfortunate about the lack of automated tests; that must slow down your release process. How often do you push updates, and how long does it take to get a release ready and out to customers?
If they get defensive about these kinds of questions, I'd consider it a red flag.

If they respond more like, "Yeah, it slows us down a bit. We're still able to release every week, but it takes a lot of manual effort from a handful of people," it shows that they recognize all these problems and would like to improve. I offer to help with that.

If the interviewer just kind of sucks at giving me the details I'm after, I keep getting more specific with the other questions from above. In my experience, it's usually less that they're being cagey about disclosing those things and more that people don't often ask and they don't have an answer ready.

What I’ve done a few times (post job offer) is ask to come in and spend a day with the team. It’s often illuminating.

I've managed to cut the shit by just outright asking people "would you say that your team is good, and would you recommend it to others". If they can't give a straight answer that doesn't list a negative, don't join.

If the are doing agile, ask about the ceremonies they use(the more means they are micromanaging), how long are the stand ups(if they're supposed to be 15 mins but always go over, that's a bad sign), how big is the team(the bigger, the more you need to run), and who really is driving the work; the PO or the team (if it's the PO, run like hell)

--

## After you start

Laptop has the bare miniumum RAM

Leadership does Agile but it hyper-concerned about predictability.

