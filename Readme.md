# Pycascades 2022

Notes from the virtual conference

Schedule: <https://2022.pycascades.com/program/schedule/>

## Welcome to Pycascades 2022

<https://pretalx.com/pycascades-2022/talk/MVLLML/>

> A huge welcome to everyone leading into our morning talks.

<https://photobooth.pycascades.com/>

---

## Meet & Greet with PSF D&I workgroup

<https://pretalx.com/pycascades-2022/talk/3HKZTJ/>

> Python has become one of the most popular programming languages in the world,
> meaning that along with this growth the Python community has continued to
> expand, in every continent around the globe. While this growth has been
> exciting, it has also brought new challenges and opportunities to improve our
> global community. Through this panel, we would like to address those
> challenges and understand our community better.

![Technical Difficulties](pictures/technical_difficulties.png)

---

## Supporting the George Floyd Protests in Portland: Demonstrations, Legal Support, and Django Apps

<https://pretalx.com/pycascades-2022/talk/CZRPCJ/>

> Portland’s protests following the murder of George Floyd involved thousands of
> people. Providing bail and legal support to those arrested at the protests
> required a massive amount of volunteers, resources, and an incredibly
> hard-working Django app.

Link to blog post about talk, slides, etc:
<https://www.thursdaybram.com/talk-supporting-the-george-floyd-protests-in-portland-demonstrations-legal-support-and-django-apps>

Challenges of supporting legal funding for protestors.

Scraping data from public judicial systems.

Misreporting of race on arrest reports by Police.

Use of Django to build app to manage this data & how successful it was.

---

## Python’s tale of concurrency

<https://pretalx.com/pycascades-2022/talk/WEYYJG/>

> Python is underrated when it comes to concurrency. The main aim of the talk
> would focus on exploring the general concept of concurrency and how we can
> utilise those concepts to write Python programs that are more scalable and
> more efficient in terms of I/0 bound operations. From the threading module and
> its limitations, to the asyncio module with its async and await keywords. We
> will look into different types of concurrent programming techniques available
> in Python though the major focus would be on the asyncio module, exploring
> best practises and common pitfalls while using asyncio.

![parallelism is not concurrency](pictures/parallelism_is_not_concurrency.png)

---

## AMA with Brett Cannon

In the MS booth, overlapped with the concurrency talk so bounced between the two.

<https://repl.ethanhs.me/> - Python 3.11alpha running via WASM in a browser.

---

## Intellicode Demo

Extension: Visual Studio code intellicode API examples

---

## Building Elegant API Contracts: From Zero to Hero

<https://pretalx.com/pycascades-2022/talk/ESCJLQ/>

>Learn how one can write efficient APIs with high-quality API specifications
>using Open API and RAML specs to create API contracts and achieve a better
>experience using the API with more reliable unit tests and increased response
>consistency.

Presenter's Twitter: <https://twitter.com/BishtPradhvan>

Slides <http://bit.ly/3rtM5Gt>

API Contracts:

* <https://apiblueprint.org/>
* <https://raml.org/>
* <https://swagger.io/specification/>

![API Principles](pictures/api_elements_principles.png)

![API Contracts](pictures/api_contracts.png)

---

## Cyber Security Investigations with Jupyter Notebooks

<https://pretalx.com/pycascades-2022/talk/RF3L8D/>

> upyter notebooks are growing in popularity among CyberSec analysts. For threat
> hunting and incident investigations, notebooks give you flexibility not found
> in most Security Operations Center (SOC) toolsets.
>
> However, threat hunting requires specialized tools, analytics and
> visualizations that aren't part of the typical data science libraries. We'll
> show some of the features of the MSTICPy CyberTools library that we built to
> address these gaps.

<https://github.com/microsoft/msticpy>

---

## How (Not) to Start a Python User Group

<https://pretalx.com/pycascades-2022/talk/9KJWWL/>

> Starting a local Python User Group is hard. Keeping it running month after
> month is even harder. As a Python User Group organizer, I've had my fair share
> of mess ups.
>
> In this talk, we'll examine some ways not to run your own Python User Group
> based on my own experiences as an organizer. By looking back at my own
> missteps, we'll determine some best practices for getting your own User Group
> off the ground. By the end of the talk, you'll be well equipped to run your
> User Group long-term. Come laugh and learn as we journey through my meetup
> misadventures and prepare you for your own.

Fun presentation, lots of good advice around organizing a UG.

* check for existing group, see if you can join
* throw your UG on a wiki, if your group ends, remove from wiki
* keep your website in sync (don't let cert/domains expire, etc)
* reach out to local businesses about hosting meetups
* for other organizer, find someone reliable, etc, be kind when asking
* getting people to come: reach out to friends/colleagues, but not spammy
* check local universities for mailing lists, etc
* use social media (low cost ad campaigns?)
* create eye-catching graphics
* there is an official Python channels of communication (wiki, email lists)
* get feedback from meeting members & take it seriously
* inform attendees about meeting structure beforehand (should they bring a
  computer? is there food? what are they in for?)
* if presenting, prepare!
* get the community involved, find others who might be willing to present or do
  lightning talks

Spokane Python User Group <https://spokanepython.com/>

---

## Invisible Walls: Isolating Your Python

<https://pretalx.com/pycascades-2022/talk/YLBZLQ/>

> Stop building projects that only "work on my machine", Learn how to isolate
> your python application by executing in an isolated, reproducible environment
> that extends beyond the code you write.

Speaker's twitter: <https://twitter.com/ucodery>

---

## Literature Text Translation and Audio Synthesis using AI Services

<https://pretalx.com/pycascades-2022/talk/FP87MV/>

> Ever wanted to read your favourite literature book or poetry but language is a
> barrier? Worry not! Enjoy the world literature in your preferred language
> along with audio book with just a click of a button. "Literature Love" uses AI
> services to translate and generate audio format for literature texts

Did not attend, as wasn't interested in the topic.

---

## MS Booth: What's New in VS Code Python?

Luciana Abud demoing some of the new features of Python in VS Code.

Change to how the Python interpreter is selected, no longer is the
`config:python.pythonPath` setting in settings.json, now is stored in config.
To reference this in a tasks.json file, use "command:python.interpreterPath".

In settings.json can specify a default interpreter to show in the select
interpreter list: python.defaultInterpreterPath

Python Environment Manager extension:
<https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-environment-manager>

New rename file assistance, on renaming a module gives a refactoring preview of
propagating that change to other files.

New selection keyboard shortcuts (expanding selections)

Visual Studio Intellicode, integrated into hover tips

Demoing the debugger, remembers last-used config for workspace

Showing integrated test explorer

Python: Report Issue item in the command pallette for filing bugs on the Python
Extension.

---

## Tests as Classifiers

<https://pretalx.com/pycascades-2022/talk/UVFAMG/>

> The reason to write, and run, tests on the code is to detect bugs before the
> code is being used by the customer. Too often, this purpose is forgotten when
> deciding how, and what, to test. What makes a good test? What makes a good
> test-suite? How can you measure it?
>
> By modeling tests as a "classifier", where the label is "buggy" or "not
> buggy", the general theory of classification can be applied. The basics of the
> theory, such as precision, recall, and F-score, will be explored, as well as
> how it applies to test suites. Specific techniques for measuring test quality,
> using tools such as mutation testing, tracing, and CI systems, will be
> presented.

Think of test (suites) as classifiers

Input: Code change
Output: Is the code buggy?

Possible way to show value of test suite

```code
# rewards not-alarming
precision = (
    true_alarms /
    (true_alarms + false_alarms)
)

# rewards alarming:
recall = (
    true_alarms /
    (true_alarms + missing_alarms)
)
```

Need to balance precision & recall -- F score (harmonic mean).

What if precision & recall shouldn't be evenly weighted -- F beta score.  Beta
param encodes utility what error hurts harder. Beta 2 == very sensitive to bugs.
Beta 0.5 == missing alarms are half as painful as false alarms

False Alarms (bring down F score, as it brings down precision):

* flaky test, fails "randomly"
* implementation test (test implementation details), mock example, unit test
  fails but code is still good
* Missing Alarm: Non-covered code, what is not run does not affect result of tests
* Missing Alarm: Loose/imprecise Assertions (ex: asserting > instead of ==)

Adam's thought: TDD heavily contributes to true alarms: you write a test first,
see it fail, then see it pass.  By definition that test is a true alarm.

Watch out for Goodhart's law - numbers are extremely gamable.

Fascinating idea, not entirely sure how to do in practice.

---

## Closing Remarks Day 1

<https://pretalx.com/pycascades-2022/talk/8YFUUC/>

> Wrapping up an exciting weekend of talks and activities.

Evening Social: <https://spatial.chat/s/pycascades2022>

---

## END OF DAY 1

---

## Diversity in Neurodiversity: Help for Underrepresented Folks in Tech and Allies with New Mental Health Diagnoses

<https://pretalx.com/pycascades-2022/talk/3UBEKS/>

> Many people from underrepresented backgrounds are being diagnosed for the
> first time or getting treatment well into their careers.
>
> This talk aims to be a resource for folks learning to work with their
> neurodiversities and their colleagues.

Four Myths to Dispel:

* Having X Means I Can't Focus
* Medication turns you into a Zombie
* Being Neurodiverse Makes Me a Bad Employee
* My Diagnosis Isn't a Protected Disability

TIRE Technique

* Time
* Intuition
* Resources
* Energy

Priority Matrix

* ~~Do~~
* Delegate
* Defer
* Delete

For Allies:

* Intersectionality is a force multiplier for and against those suffering
  * do what you can to lighten the load
* People may not be ready for your help
  * don't take it personal, prove that you can be trusted
* Minimization is what got us here
  * don't minimize their situation, it's not a competition
* No Two Cases are the Same
  * Don't assume that's worked for one will work for all
  * Showcase many different solutions and treat all of them as valid

Instead ask:

* What have you tried that worked in the past
* If you want to talk about it, aI can make time.  I may not understand9i t all
  but if you can help me I'll try my best
* Let me know how I can help you. Even if you just need me to cover for you
  while you adjust.

The standard comes from leadership

Don't Let Work Take Precedence Over Self Care

Normalize Diversity and Neurodiversity

Empathy training: <https://compassionatecoding.com>

Global Peer Mental Health Network <https://www.gmhpn.org/>

---

## Council Data Project: Infrastructure-as-code for civic transparency and accessibility

<https://pretalx.com/pycascades-2022/talk/7FZC9R/>

> Council Data Project (CDP) is an open source project that provides tools for
> making city council transcripts, legislation, and voting records searchable
> through a single website. This is achieved through a Python-powered
> Infrastructure-as-code architecture. CDP provides an entire backend and
> frontend that can be easily deployed for a governing body of any size or
> location. As long as the deployer provides data for events in a pre-defined
> yet flexible structure, CDP provides a database, file storage, speech-to-text
> transcription, and natural language search.
>
> During this session, we will cover CDP’s backend, primarily focusing on how we
> created ETL pipelines and an Infrastructure-as-code setup to be as low cost
> and easily forkable as possible. Because of this, backend-focused developers
> may get the most out of this talk. Additionally, this session is intended for
> people of all levels of Python experience. Instead of covering in-depth
> features or niches of the language itself, we will showcase some neat tools
> and open-source projects in the Python ecosystem that we use to build our
> infrastructure!
>
> And this session is especially for anyone interested in civic tech or
> generally just making democracy more transparent!

---

## Security considerations in Python Packaging

<https://pretalx.com/pycascades-2022/talk/HWAFCC/>

> Popular programming language index websites (TIOBE index) and developer
> surveys (Stack Overflow) place Python as one of the fastest-growing
> programming languages. However, this popularity also puts in the target range
> of attackers. The attackers perform malicious dependency attacks and use
> misconfiguration tools to reveal confidential information. Jukka Ruohonen,
> Kalle Hjerppe, and Kalle Rindell in their research paper “A Large-Scale
> Security-Oriented Static Analysis of Python Packages in PyPI” claimed that
> they scanned PyPI for security issues in Python packages and found the
> presence of at least one security issue in about 46% of the Python packages.
> In addition, security vulnerabilities can be present in the source code of the
> package. In this talk, we will address the security issues related to python
> packaging and possible solutions to make python packages secure.

Good motivation of the problem, then discussed a few tools (Bandit, Safety) for
finding security issues.

---

## Programming Your Way up a Skyscraper - Python in the Built World

<https://pretalx.com/pycascades-2022/talk/XFUZCM/>

> When I started working on the latest high rise for San Francisco a challenge
> stood before me: How am I going to do this without losing my mind? Thankfully
> Python coding came to the rescue. This talk will showcase all the tools built
> around Python that can make architecture dreams come true!

Interesting talk about the use of modern OSS tools for building construction.
