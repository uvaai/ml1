# Introduction to Machine Learning 1

University of Amsterdam / Programming Lab / 50821ITM6Y

## Syllabus<br><small>Fall 2024</small>

This course serves as an introduction to the basics of machine learning and
artificial intelligence. It consists of 6 modules, where each of these modules
is expected to take about one week, and will focus on exploring one or more
techniques from machine learning. In general, there will be 4 components to
each module:

* **Theory videos:** These will mostly introduce the required machine learning concepts for the topics that week.
* **Programming Notebook:** Here you will implement some of the machine learning algorithms yourself in *Python*.
* **Written Assignment:** Here you'll read articles or blog posts related to the philosophical and societal implication of ML, and answer questions about them.
* **SOWISO:** An online platform we'll use to introduct foundational mathematical concepts that are the driving force behind a lot of the algorithms we'll explore.

Log in with your UvAnetID and create an account to get access to the modules.

## Staff

Tim Doolan (coordinator)

Wouter Vrielink (teacher)

You can reach us at <ai@proglab.nl> for any practical matters or other
questions. Note that any code related questions should always be asked on
campus during the practical assistance sessions in the main room **L0.11**.

## Deadlines

The first module is just a basic notebook introduction, and should already be handed
in on Tuesday of the first week. The deadlines for the other 6 modules is listed below.
Note that not all the modules are exactly the same size, so some modules take a little
less than a week and others a little more. As result, not all deadline will be on the same day:

* **Module 0:** *Tuesday September 2nd at 23:59*
* **Module 1:** *Monday September 8th at 23:59*
* **Module 2:** *Monday September 15th at 23:59*
* **Module 3:** *Tuesday September 23rd at 23:59*
* **Module 4:** *Thursday October 2nd at 23:59*
* **Module 5:** *Thursday October 9th at 23:59*
* **Module 6:** *Friday October 17th at 23:59*

### Absences and calling in sick

If you are sick or are otherwise unable to come to campus, you should inform
your group TA you will be absent by sending them a message on Slack. When you
are feeling better, inform your TA again, so your period of absence can be
registered.

Depending on how long you were sick, and if you are behind with the module, you
can then also contact the course staff to discuss an alternate planning for the
module. Note that this option requires you to have also already messaged your
TA at the start of your absense. Any exceptions or extensions required for this
will need to be discussed with course staff (so not your TA). See the extension
policy below for more details.

### Extension policy and late days

There are two types of extension; staff extensions and late days.

Staff extensions usually require meeting with staff and will generally also
include making an alternative planning for the module. If any circumstances
arise that would make it hard for you to make the deadline, send us an
email at <ai@proglab.nl> so we can discuss your situation. Please do this as
soon as the problem arises, rather than on the day of deadline, so we can
schedule a meeting and still have room in the module for an alternative planning.
Note that a meeting does not always guarantee an extension, as this might still
depend on the details of your circumstances.

In addition, you have a total of 2 late days, each of which you can use to get
a single 24 hour extension for the module deadline. You can request a late day
using the submit forms linked in the sidebar of the main
[minor AI website](https://minai.proglab.nl/). You must always submit your
request *before* the deadline expires. Any submissions received after the
deadline without a requested late day will not be graded, meaning your grade
will default to a 1.

You can use only 1 late day per module to get a 24 hour extension on the
deadline. This extension is for the whole module, so applies to all submits
for the course. If the deadline is on a Friday, using a single late day will
instead grant a 48 hour extension over the weekend, meaning your deadline will
move to Sunday. If you have used both late days, or require more than 24 hours
of extension, you may still try and request a staff extension.

Any staff extension request needs to be agreed upon before the deadline expires,
which means your request must be sent at least 2 hours before the actual deadline.
If you do not receive a reply in time, you should *always* still submit your
current version of the assignment before the deadline, so this part can still be
graded. Staff extension requests should be emailed to <ai@proglab.nl>

## Lectures & practical assistance

This course has one introductory lecture, but the rest of the classes consist of
frequent opportunities to come and ask questions during practical assistance hours.
During these hours you can ask any questions to the TA's and lecturers of the course,
and get additional explanations, either individually or in small groups.

Questions can be about any part of the course, including explanation of the theory
for that module or help with solving bugs in the assignments. On *Thursdays* the
lecturers of the course will also be present, so you can ask any more advanced
questions you might have. Note that these moments are intended to really replace the
lectures, so please do come and use these opportunities to get more explanation
on the material or ask in-depth questions if you have them.

During the practical assistance hours
you can use the "Assistance" feature on the main [minor AI website](https://minai.proglab.nl/),
using the question mark symbol in the top right corner of that page. Please use
this feature instead of raising your hand in class, as it ensures that all
questions get handled in the order that they are asked. Questions can of be
about any part of the course, just make sure to mention what assignment
you're working on. For your location, please list the table you are working at,
so the staff member handling your question knows where to find you when it is your turn.

### Practical assistance schedule

There are 5 slots of 3 hours scheduled every week for practical assistance.
All practical assistance will be in the main room of the minor AI, **L0.11** in
the Lab42 building of Science Park, and will be scheduled as follows:

* Monday 10:00 to 13:00
* Tuesday 14:00 to 17:00
* Wednesday 14:00 to 17:00
* Thursday 14:00 to 17:00 *- Lecturer Q&A*
* Friday 14:00 to 17:00

You may join any of these scheduled slots to ask your questions. Note that attendance
might be taken during the practicals, even though attendance is not mandatory. This is
mainly to monitor the usage of each of the sessions, and ensure there is enough space
and assistance for those present.

### TA Slack

There will also be a Slack you can use to contact your own TA, the link for which
will be shared once the course starts. This Slack can be used to ask clarification
on some of the feedback you got for your assignments, or to call in sick as
described in the section on absences above. Note that this Slack is only intended
for quick clarifying questions, and *not* for help with the assignments. Help
with the assignments, or longer explanations on how to write better code, are
only given in person as part of the practical assistance.

## Passing the course

The programming and writing assignment will both be graded on a 1 to 10 scale.
and at the end of the course an average for both these elements will be
computed. The minimum satisfactory average grade from the
assignments is a 4.5 and the minimum grade for the exam is also a 4.5. If all
elements are completed satisfactorily, your final grade for the course is
computed as:

    40% programming average + 20% written average + 40% exam grade

### Programming Grades

All programming notebooks should run from top to bottom without errors, using
`Cell > Run All`. Your grade for the programming notebooks depends on 3
factors: Correctness of the produced output, answers to the open questions, and
the style and design of the code.

The main goal of the programming notebooks in ML1 is **not** to learn
programming, but to better understand the algorithms you are implementing. Your
answers to the open question and checking that the produced output for each
step makes sense, are the main ways to show this understanding. Writing clear
code with good comments is also only possible when you understand what you're
implementing well enough.

If all coding cells are completed, all open questions are answered and your
notebook runs top to bottom without errors, your grade starts at a 6. The
remainder of your grade is then determined as follows:

* 0 - Some code cells produce incorrect or incomplete results. Answers to some open questions are incorrect or lack motivations.

* 1 - All code cells produce mostly correct results, but may still contain small mistakes. Same goes for the answers to open questions. Style and design have had some attention, but can be improved.

* 2 - All code cells produce correct results. Answers to all open questions are correct and are motivated. Style and design are good.

* 3 - All code cells produce correct and nicely formatted results. Answers to all open questions are correct and consistently well motivated based on the theory of the algorithm. Style and design are very good.

* 4 - Above, and in addition: Output, answers and code cells are beyond what is expected for the course.

### Writing Grades

The writing assignments for this course might be different from writing
assignments you've done in your own studies. We'll start by outlining the
basic concept, in order to avoid confusion of what you are exactly graded on.

The most important aspect of your writing assignments is to show you've read
the week's material and have thought carefully about the accompanying
questions. Some questions might even just ask your opinion, which means all
that is required is that you've thought about the topic enough to clearly argue
*why* you think it is one way or the other. Specifically, this also means that
not every statement you make necessarily requires a reference or citation.
However, if you do look up other sources as part of formulating your answers,
you can of course use and cite them.

Your grade for each writing assignment is determined as the sum of your points for each of the three aspects listed in the rubric below.

|                   | *Unsatisfactory*               | *Satisfactory*                  | *Good*                          | *Exceptional*                      |
|-------------------|--------------------------------|---------------------------------|---------------------------------|------------------------------------|
| **Instructions**  | **1:** Significant parts of the assignment are missing and/or the writing contains too few words. | **3:** The student has almost completed the assignment, but minor aspects of the assignment are missing, like incomplete answers, or a missing question. | **5:** The writing contains a sufficient number of words, refers back to the concepts covered the reading material, and contains answers to all of the questions from the assignment. | - |
|-------------------|--------------------------------|---------------------------------|---------------------------------|------------------------------------|
| **Structure<br>& style** | **0:** The writing contains (almost) no structure, and/or the style is (at some points) unclear, thereby making the answers more difficult to understand. | **1:** Overall the answers are well structured and the style is clear, making the answers in general easy to understand. | - | **2:** The answers are very well structured and the style is very clear and accessible, beyond what is expected for the course. |
|-------------------|--------------------------------|---------------------------------|---------------------------------|------------------------------------|
| **Argumentation** | **0:** A concept from the reading material is misrepresented and/or some motivations are missing. | **1:** The writing shows a general understanding of the reading material and the corresponding concepts. All answers are motivated, but one or two motivations might be incomplete or inconsistent. | **2:** The writing shows clear understanding of the reading material and the corresponding concepts. All answers are well motivated using these concepts. | **3:** In addition to showing a clear understanding and well-motivated answers, the writing contains other sources or examples from the author’s field of study, thereby providing relevant novel perspectives. |
|-------------------|--------------------------------|---------------------------------|---------------------------------|------------------------------------|

### Exam

The exam at the end of the course will consist mainly of open questions on the
theory and algorithms covered. More details on the exam will follow later.


## Academic honesty

This course's philosophy on academic honesty is best stated as "be reasonable".
The course recognizes that interactions with classmates and others can
facilitate mastery of the course's material. However, there remains a line
between enlisting the help of another and submitting the work of another. This
policy characterizes both sides of that line.

### Collaboration

The essence of all work that you submit in this course must be your own.
This means that for collaboration with other students you can discuss
the material and consider possible approaches together, but you should then
always still each write your own code. So, conferring together using language
and whiteboards is permitted and even encouraged, but sharing lines of code is
not.

Note that looking at another students screen or solution file at this stage
will usually result in that option becoming *the* solution to the problem, and
so instead of learning and considering all the possibilities, you just end up
trying to recreate the solution you already saw. As there usually quite a few
different ways to solve programming problems, this can even end up with code
that is similar enough in structure that it is caught by our automated
plagiarism detection.

### Helping other students

Once you've completed a part of an assignment, viewing another student's solution
is fine and can even be very helpful. At this point you can help other students
to find bugs in their code, or even do a code review together when you're both
done. Helping other students to find bugs in their code is something that is
also definitely encouraged, but this should always be limited to suggestions on
what to try next, not fixing the code for them. If you are trying to suggest a
fix, but cannot do so without sharing your own code (which is common enough
when you are still learning!), then you should refer the problem to a TA or
teacher instead.

The general principle here is that you can look at another's code to help fix a
bug, but they cannot look at your code for ideas on how to solve it. Note that
sharing a solution with someone who has not yet completed that part of the
assignment is considered plagiarism just as much as handing in another students
solution. Doing this deprives the other student from learning what they need
to learn in that assignment, which will only make it more difficult for them to
solve subsequent assignments on their own.

### Using online tools

Searching for solutions to (parts of) the assignments online is obviously not
permitted. This explicitly also includes asking ChatGPT or other large language
models to write the code for you, which is considered plagiarism just as much as
copying a solution written by another human.

What is permitted though, is searching for explanations on how to use certain
functions or perform specific operations in Python. So, searching for *"how do
I add an element to a list in Python"* would be perfectly fine, while searching
for *"how do I print a Mario pyramid in Python"* would not. If your search
leads to a Stack Overflow page or similar resource, which gives an example of
how to perform an operation, you should always cite the source as a comment
in your own code. This citation comment should contain the original link and
clearly indicate which parts you did not write yourself, but came from the
online example.

As a student it can sometimes be hard to estimate what is and isn't ok to
search for online, which is logical while you are still learning. We strongly
recommend that you err on the side of caution with this, and ask staff
permission beforehand for a specific search when in doubt. As this is an
introductory course, you should actually be able to find all the relevant
Python instructions on the pages of this course without needing to search
online at all.

### Rules and guidelines

Below are rules of thumb that (inexhaustively) characterize acts that the
course considers reasonable and not reasonable. If in doubt as to whether some
act is reasonable, do not commit it until you solicit and receive approval in
writing from the course's staff. Acts considered not reasonable by the course
are handled harshly.

In all cases we follow the directives regarding fraud and plagiarism of the
University of Amsterdam and of the Kunstmatige Intelligentie BSc programme.
Find them here in [English] and [Dutch].

[Dutch]: http://uva.nl/plagiaat
[English]: https://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html

#### Reasonable

- Communicating with classmates about assignments in English, Dutch, or some other spoken language.

- Discussing the course's material with others in order to understand it better.

- Helping a classmate identify a bug in his or her code, elsewhere, or even online, as by viewing, or running his or her code, even on your own computer.

- Incorporating a few lines of code that you find online or elsewhere into your own code, provided that those lines are not themselves solutions to assigned problems and that you cite the lines' origins.

- Sending or showing code that you've written to someone, possibly a classmate, so that he or she might help you identify and fix a bug.

- Sharing a few lines of your own code online so that others might help you identify and fix a bug.

- Turning to the web or elsewhere for instruction beyond the course's own, for references, and for solutions to technical difficulties, but not for outright solutions to assignment problems.

- Whiteboarding solutions to problem sets with others using diagrams or pseudocode but not actual code.

- Working with (and even paying) a tutor to help you with the course, provided the tutor does not do your work for you.

#### Not Reasonable

- Searching for or soliciting outright solutions to assignments online or elsewhere.

- Asking a classmate to see his or her solution to a problem set's problem before (re-)submitting your own.

- Asking ChatGPT or other large language models to write the code for (part of) an assignment for you.

- Failing to cite (as with comments) the origins of code or techniques that you discover outside of the course's own lessons and integrate into your own work, even while respecting this policy's other constraints.

- Giving or showing to a classmate a solution to part of an assignment when it is he or she, and not you, who is struggling to solve it.

- Paying or offering to pay an individual for work that you may submit as (part of) your own.

- Providing or making available solutions to assignments to individuals who might take this course in the future.

- Splitting an assignment's workload with another individual and combining your work.

- Submitting (after possibly modifying) the work of another individual.
