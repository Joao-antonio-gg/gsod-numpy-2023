# Script Review Meeting
Reviewed with Mukulika and Ross, the NumPy Project Mentors on July 12 2023.

- Overall message: NumPy is driven by people who use it: in this case, scientists!
- Characters
  - 3 students:
    - 3 stooges energy
    - Most informed (spirit of OS), potential user-contributor "let's do that!"
    - Least informed (let's just get this done), ordinary user, "why would you do that?!"
    - Straight man (no strong preference), eager to please "um, what is that, exactly?"

- Professor
  - Starts students journey by making NumPy used for class
  - Later revealed to be part of NumPy core team
- PR maker (Ganesh)
  - Seen through screen (open source contributors across the world)
- Maintainer (Sebastian)
  - Seen through screen (open source contributors across the world)

- Format:
  - **Narrative with informational diagrams throughout**

- Target audience:
  - **Strongest appeal to academia** probably: professors, scientists, students
  - will this resonate to a general audience? I think the story will get them started but understandable if there's some fall-off when things get detailed
  - Industry: ?

- Will not:
  - Explain in too much detail how to set up environment, how Git works
  - what open source is
  - How numpy differs from other projects

- Goals:
  - the **early contributor journey**
  - NumPy's relationship to open science
  - illustrate to those who've been around for a while what it's like to be a newcomer
  - importance of **guiding figure in entering open source**
  - **want OS people to hand to their friends to answer the 'what do you do' question**
- Informative sections/themes
  - Very brief introduction to **Open Science**
  - How **NPZ archiv** e works and it's usability to scientists
  - **How usability problems affect scientists**
  - How website and **documentation guide newcomers**
  - Process of writing an issue for NumPy
  - Relationship between issues and PRs: how one leads to another
  - Very brief introduction to Git for PRs: cloning, branching
  - **Contributor workflow** and role of maintainer
  - **Demystify and humanize: Who is the core team of NumPy?**
  - **How PRs are reviewed and new features weighed in NumPy, an old codebase with downstream projects,** thus the focus on backward compatibility
  - When PRs are merged and release cycle
  - Seeing your feature implemented!
  - How credit is given
  - The **importance of user-contributor in NumPy and Open Science**
  - How to **continue to be involved in the NumPy community and it's various channels**
- **Comments and Questions on Overview**
  - Is this a story that will continue with same characters?
  - Difference between big picture contributor pathways and smaller scope story, early contributor experience
  - OK to no go into detail about NPZ example
  - Understable to scope smaller
  - Great to have high-level goals: eg target audience, aim to please everyone will not please anyone
  - Solid foundation with reasonable scope: expanding can get too much
  - Coming at complete opposite approach: start with narrative, highlight how a community driven open source looks like
    - eg this is the contributor workflow diagram vs virtue of story itself where students try to solve problems themselves

## Opening scene

- Purpose: Establish setting, characters and goal of story
- Setting: Opening shot to library, University of Monty

  - Three students settling down to table, carrying books, coffee, etc

- Students chat about previous class

  - Happy we finished the lab section
  - mention professor, let's move to using NumPy to look at Cell imaging data, -Actions while chatting: Opening laptop, drinking coffee

- Opening lines

  - Thanks for coming here guys, called meeting after class, want your help in running NumPy, never used it before, looks intimidating, Hope I don't mess up (not confident)
  - No problem, happy to help (narrative parallel of supporting each other like NumPy community supporting each other), I've played around with in my Python class (Comp Sci class? Is there a more specific class)

## Rising Action: Discover the problem

- Purpose: Running through scientific process for both reader and newbie to NumPy character
- Setting: Library
- Diagram explaining process

  - Well, you remember what we did in the lab right?
  - single cell microscope data stored as numpy arrays
  - Need advice on this section

- Visuals: Terminal

  - Ok, let's start with opening the terminal
  - Make a .py file?
  - Open editor

    - import numpy as np
    - data = np.load, achive npz, downloaded the dataset

- Hitting the problem

  - Open NPZ archive
  - Named arrays inside archive, couldn't find out where the names where
  - 3rd person, looking at… worksheet? The docs have a files attribute that tells you the name
  - why can't you see the names as is? why won't it work like a dictionary?
  - We can just follow the worksheet, whatever
  - No, I don't like that… that's a usability shortcoming (or another phrase, that sounds more informed)
  - We can go forward with this archive contains arrays, access them, get this done quick

## Rising Action: Confusion, Deciding Next Steps, Disagreement

- Purpose: Showing the difficult transition from finding a problem to taking action
- Setting: Library

  - I think this is worth bringing up…
  - Um, to who? The professor?
  - No, not just the professor. We can actually bring this up as an issue.
  - Brief description of open source: its like

    - Diagram: what numpy means to scientists, students, labs, etc

  - All this talk, but I've never actually interacted with the NumPy community, heh… just attended a talk about it/scientific reproducability
  - Man, I just want to get this over with vs let's take a bigger action
  - Stare off!
  - I mean, our professor likes NumPy, i'm sure he would say this is relevant haha
  - OK, let's try it out, since we got time and all.
  - Hey I've never used Github before, Oh I have an account but only uploaded my code, not repo, I've made forks but not contributed….
  - So we're lost then….

## Taking Action, Making the Issue

- Purpose: Show experience, how do people find out more about open source, using only documentation? No in-person next to them
- Setting: Library
- Let's start by looking at the NumPy website!

  - Look up NumPy.com, show scrolling experience, keyword extraction, huh! Oh! What?

    - Zoom in making a issue, if you see a byg

  - OK, so we need to use one account
  - Oh gosh, do I really make a issue?

    - Go through options, clicking, writing

  - One person on Github writing issue, one person open terminal describing issue, last person staring at them OK, submit! Off into the ether! Hmm, did anything happen? Well I have notifications open, we'll hear back
  - Do we need to complete the assingment now?
  - I guess.. lol no

## Next Action #1: What is the contribution flow? Making a PR and Role of Maintainer

- Purpose: Show understanding of open source growing, not just magically completed, introduce another character
- a few hours later at canteen? silly student stuff, eating 36 chicken nuggets. moved away from library

  - oh someone responded!
  - "This also bothers me! I will Write implementation attempt"

- yay! But who is this person? Do we need to do anything?
- No, I think they'll make a PR… for us?
- Wait, how does this all work? what is this person doing?
- Diagram of clarifying the character's confusion about forking branching, submitting a PR
- Scroll down more, see comment of maintainer talk about how it fits with everything else (backward compatibility)

  - What's a maintainer?
  - Diagram Role of maintainers, helpful (not want to use word gatekeeper… moderate? give direction?)
  - Why doesn't maintainer implement this themselves?
  - Point is that different people work together

- Well, we'll hear about it i guess

## Next Action #2: What happens to a PR, Review stage

- Next week/class/lecture, gathering before class

  - Email notifcation on phone
  - Group gathers around phone
  - A PR that mentions our issue!
  - I want to check it out! Look at code, I don't understand a lot, even though we use Python it's written C I want to understand more!

- See professor typing away at laptop during Lab downtime

  - Oh look! Is that our professor commenting on the issue?

    - Does he live a double life? What's going on?
    - Might as well ask

## Next Action #3: What does it take a PR to be implemented?

Suggestion: Remove professor, 9000 miles away, PR maker, no direct communication between PR maker to students, which is often the reality. See through screen and Github, know it's a real person, no one directly tells them yes or or no until someone else comments. Reflects asynchronous and distributed nature.

See the email notification: students response of 'OMG what now?' again

Students follow along discussion in email thread, there's a maintainer comments or approve it, what does that

See comment about "impleemnt a \_\_repr\_\_ in the direction…" , students wouldn't know what that means but PR maker know

Separating development and release difference? Comment, someone comments back "change will be revealed next release"

Maybe too much info
 One implementation: two panels:

Hey did you see the PR related to our issue got merged last night?

Yeah I think that means that it will be changed in next release cycle

Could be another feature

- Purpose: More technical, talking to professor, relationship with maintainer, how this ties to research
- Setting: After class

  - Hey professor! Um… is this you?
  - Oh yeah! (seeing behind the screen, who are these people?)
  - I didn't bring it up in class because want to focus on getting started, not brag
  - Oh, but you should have! Cool!
  - Uh, to be honest, even if you did I don't I would have understood… But I sort of get it nows
  - what does your comment mean?

    - Show text of comment
    - Dialogue overlaid
    - Explanation about **Backwards compatibility**?"I wish this function accepted these arguments, unpacked tuples", "We're not likely to accept it, propose it to the mailing list" "Here's the reason why, not because you're idea, we might have wished we designed this way, snapshot to grad students code, if change than breaks"

      - Many people not learn about backwards compatibility formally in school, abosrob via osmoosis, how ties to decision making

  - What does the PR submitter do?

    - Respond to the comment

  - Review, make changes,
  - Merge at end by maintainer (need to mention release cycle?)

## Closing Action: PR merged

- Purpose: Recognition

  - 1 months later: Students gather again at library, talking about mid terms done
  - Oh, hey, check out this email!
  - new microscope data, that was our idea, version release,
  - type in file name, says 'cell'! Success! High five!
  - Implementator has Credit in Github history, mailing list release
-
## Resolution, teaser for future actions in open source

- Setting: class

  - Hey professor, check this out!

- Usability, hope it makes better, different ways people contribute

  - Let's go on community meeting next week, saw it on the mailing list
  - I've been thinking about what our professor said…
  - Spirit of open source, open science

## Credits and Ending Notes

- Credit specific people and actual PRs
- Make QR code for the links?
- Note to new to open source: real story! You could too!

  - Links

    - Issue Ross made: https://github.com/numpy/numpy/issues/23319
    - PR Ganesh implemented: https://github.com/numpy/numpy/pull/23357
    - Sebastian and Ross review: https://github.com/numpy/numpy/pull/23357#pullrequestreview-1336728619

- Worksheet on your own open source journey?

**Comments and Questions on Script**
- Demonstrates but not over explains
- Documentation has not told story yet, in dry text, contributor guide, how it's supposed to work 'please comment on mailing list' but in practice, people may not read in full,
- Everyone's impression of 'how does NumPy get developed?', demystify
- Concept of authority figure: Maybe dropping the Professor entirely?
  - Ross motivation: if not professor, "how do raise this issue", rely on themselves, no appeal to higher authority for first idea, less top dow, don't need phD already
  - Constrict the scopes: more focused on open source part, professor reinforces the academic angle, "who do we tell?!", find the issue tracker
- Suggestion: Remove professor, 9000 miles away, PR maker, no direct communication between PR maker to students, which is often the reality. See through screen and Github, know it's a real person, no one directly tells them yes or or no until someone else comments. Reflects asynchronous and distributed nature.
  - See the email notification: students response of 'OMG what now?' again
  - If remove professor, can be a more general scenario, eg hobbyists
- When students are making the issue: sort issue tracker to see if anyone has made an issue
  - IRL: npz archive issue from 10 years ago,
    - Maybe for narrative, no previous issue shows up
  - Opportunity to highlight that best practice
  - How much information it ends up being?
  - 3 factors:
    - scope
    - how much would these characters actually know
    - best practice
  - maybe someone comments later, "can you show code more specific"
  - Lead to question about 'ask the mailing list first'
    - Answer: For bigger feature request that may break backwards compatibility, should ask mailing list, even if not aware it could.
    - In reality of asking mailing list, more stringest side, more about mailing list, could lead to another rabbit hold
    - What usually happens: people make issue, then move bigger conversation to mailing list
- Tendency for documentation to overexplain,
- Can use comic narrative to open conversation about templates as possibly univiting, or to ask mailing list
- Next steps: Answer on document, Slack, meet at next NumPy Docs
