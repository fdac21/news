
# Class on Aug 26
   - [Follow instructions to make sure your ssh is set up to connect to your docker container](https://github.com/fdac21/news/blob/master/Preliminary.md)
   - Work on fdac20/Practice0: due before class on Aug 31
      - It involves 
         - forking
         - ssh and clone to your docker container
         - rename the notebook on your container
         - completing notebook in your browser (while connected to yor container)
         - adding/commiting/pushing from your container
         - creating pull request from your fork
      - If you need a refresher on unix tools: [edX on unix for data science](https://www.edx.org/course/unix-tools-data-software-and-production-engineering)
   - [Critical Tools](https://github.com/fdac21/lectures/blob/master/tools.pdf)
   - [Version Control](https://github.com/fdac21/lectures/blob/master/version_control-FDAC.pdf)

# Class on Aug 24
   - Please accept your [invitation to fdac21 organization](https://github.com/orgs/fdac21) while logged in to GH via handle you used to submit pull request
   - If you have not done so yet, please accept github fdac21 invitation (ahillhou)
   - then 
      - fork repo students 
      - create your utid.md file providing your name and interests:
        see per fdac21/students/README.md, and also provide your
        utid.key with your public ssh key. Once done, please
	  - submit a pull request to fdac21/students
      - still missing.md files: ahillhou, jmuncy2
   - [Introductory lecture](https://github.com/orgs/fdac21/lectures/blob/master/prelim.pdf)

# Class on Aug 19
   - Create your github account 
      - fork repo students 
      - create your utid.md file providing your name and interests:
        see per fdac21/students/README.md, and also provide your
        utid.key with your public ssh key. Once done, please
	  - submit a pull request to fdac21/students
   - Make sure you do it a day before the next class so we can start ready


# Information for remote participation via Zoom
   - [recorded lectures](https://drive.google.com/drive/folders/1zJXAgIA4wwCoV-DrDc9grWLIPHVTyPKW?usp=sharing)

   - Join from a PC, Mac, iPad, iPhone or Android device:
      Please click this URL to start or join. https://tennessee.zoom.us/j/2766448345
      Or, go to https://tennessee.zoom.us/join and enter class session/meeting ID: 276 644 8345

   - Join from dial-in phone line: (Note: these are NOT toll-free numbers)
      Dial: +1 646 558 8656 or +1 408 638 0968
      Meeting ID: 276 644 8345
      Participant ID: Shown after joining the meeting
      International numbers available: https://tennessee.zoom.us/zoomconference?m=leg4C6yjhpfGHE-_Q9EYRNHXCUMBC-2T


# Syllabus for "Fundamentals of Digital Archeology"
* **Course:** [COSCS-445/COSCS-545]
* **  MK404 and Zoom link above  **
* **  TTh 4:30-5:45
* **Instructor:** Audris Mockus, [audris@utk.edu](mailto:audris@utk.edu) office hours - upon request
* **TA:** James Hammer and TBD. Office hours - TBD
* * [** Syllabus **](https://github.com/fdac21/news/blob/master/course.pdf)
* **Need help?**

Simple rules: 

1. There are no stupid questions. However, it may be worth going over the following steps:
1. Think of what the right answer may be.
1. Search online: stack overflow, etc.
     - code snippets: On GH [gist.github.com](https://gist.github.com/) or, if anyone contributes, [for this class](https://github.com/snippets/fdac20/)
     - answers to questions: [Stack Overflow](http://stackoverflow.com/)
1. Look through [issues](https://github.com/fdac20/news/issues)
1. Post the question as an issue.
1. Ask instructor: [email](mailto:audris@utk.edu) for 1-on-1 help, or
   to set up a time to meet 


## Objectives

The course will combine theoretical underpinning of big data with
intense practice. In particular, approaches to ethical concerns,
reproducibility of the results, absence of context, missing data,
and incorrect data will be both discussed and practiced by writing
programs to discover the data in the cloud, to retrieve it by
scraping the deep web, and by structuring, storing, and sampling it
in a way suitable for subsequent decision making.  At the end of the
course students will be able to discover, collect, and
clean digital traces, to use such traces to construct meaningful
measures, and to create tools that help with decision making.

## Expected Outcomes
Upon completion, students will be able to discover, gather, and analyze
digital traces, will learn how to avoid mistakes common in
the analysis of low-quality data, and will have produced a working
analytics application.

In particular, in addition to practicing critical thinking,
students will acquire the following skills:

*  Use Python and other tools to discover, retrieve, and process data.
  
*  Use data management techniques to store data locally and in the cloud.
  
*  Use data analysis methods to explore data and to make predictions.

## Course Description

A great volume of complex data is generated as a result of human
activities, including both work and play. To exploit that data for
decision making it is necessary to create software that discovers,
collects, and integrates the data.

Digital archeology relies on traces that are left over in the course
of ordinary activities, for example the logs generated by sensors in
mobile phones, the commits in version control systems, or the email
sent and the documents edited by a knowledge worker. Understanding
such traces is complicated in contrast to data collected using
traditional measurement approaches.

Traditional approaches rely on a highly controlled and well-designed
measurement system. In meteorology, for example, the temperature is
taken in specially designed and carefully selected locations to
avoid direct sunlight and to be at a fixed distance from the ground.
Such measurement can then be trusted to represent these controlled
conditions and the analysis of such data is, consequently, fairly
straightforward.

The measurements from geolocation or other sensors in mobile phones
are affected by numerous (yet not recorded) factors: was the phone
kept in the pocket, was it indoors or outside?  The devices are not
calibrated or may not work properly, so the corresponding
measurements would be inaccurate.  Locations (without mobile phones)
may not have any measurement, yet may be of the greatest interest.
This lack of context and inaccurate or missing data necessitates
fundamentally new approaches that rely on patterns of behavior to
correct the data, to fill in missing observations, and to elucidate
unrecorded context factors. These steps are needed to obtain
meaningful results from a subsequent analysis.

The course will cover basic principles and effective practices to
increase the integrity of the results obtained from voluminous but
highly unreliable sources.

*   Ethics: legal aspects, privacy, confidentiality, governance
   
*   Reproducibility: version control, ipython notebook
   
*   Fundamentals of big data analysis:
    extreme distributions, transformations, quantiles,
    sampling strategies, and
    logistic regression

*   The nature of digital traces:
    lack of context,
    missing values, and
    incorrect data

## Prerequisites

Students are expected to have basic programming skills, in
particular, be able to use regular expressions, programming concepts
such as variables, functions, loops, and data structures like lists
and dictionaries (for example, COSC 365)

Being familiar with version control systems (e.g., COSC 340), Python
(e.g., COSC 370), and introductory level probability (e.g., ECE 313)
and statistics, such as, random variables, distributions and
regression would be beneficial but is not expected. Everyone is
expected, however, to be willing and highly motivated to catch up in
the areas where they have gaps in the relevant skills.

All the assignments and projects for this class will use github and
Python. Knowledge of Python is not a prerequisite for this course,
provided you are comfortable learning on your own as needed. While
we have strived to make the programming component of this course
straightforward, we will not devote much time to teaching
programming, Python syntax, or any of the libraries and APIs.  You
should feel comfortable with:

1. How to look up Python syntax on Google and StackOverflow.
1. Basic programming concepts like functions, loops, arrays, dictionaries, strings, and if statements.
1. How to learn new libraries by reading documentation and reusing examples
1. Asking questions on StackOverflow or as a GitHub issue.


### Requirements

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Optimize for readability
* Bonus points for:
    * Creativity (as long as requirements are fulfilled)

## Teaming Tips

* Agree on an editor and environment that you're comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to others on the team

## Evaluation

* Class Participation – 15%: students are expected to read all
   material covered in a week and come to class prepared to take
   part in the classroom discussions (online). Asking and responding to other student
   questions (issues) counts as a key factor for classroom participation. With online
   format and collaborative nature of the projects, this should not
   be hard to accomplish. 

* Assignments - 40%: Each assignment will involve writing (or modifying a template of)
   a small Python program.

* Project - 45%: one original project done alone or in a group of 2 or 3
   students. The project will explore one or more of the themes covered
   in the course that students find particularly compelling.  The
   group needs to submit a project proposal (2 pages IEEE format)
   approximately 1.5 months before the end of term.  The proposal
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.

## Other considerations

As a programmer you will never write anything from scratch, but will
reuse code, frameworks, or ideas.  You are encouraged to
learn from the work of your peers. However, if you don't try to do
it yourself, you will not learn. [deliberate-practice](https://web.archive.org/web/20190801180936/https://psy.fsu.edu/faculty/ericssonk/ericsson.exp.perf.html)
(activities designed for the sole purpose of effectively improving
specific aspects of an individual's performance) is the only way to
reach perfection.

Please respect the terms of use and/or license of any code you find,
and if you re-implement or duplicate an algorithm or code from
elsewhere, credit the original source with an inline comment.

## Resources
### Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* [Python for beginners](https://www.python.org/about/gettingstarted/)
  and [Python Dictionaries](http://pythonprogramminglanguage.com/dictionary/)

#### Other

* [Mining the Social Web, 2nd Edition](http://shop.oreilly.com/product/0636920030195.do)

##### Databases

* [A MongoDB Schema Analyzer](https://github.com/variety/variety). One JavaScript file that you run with the mongo shell command on a database collection and it attempts to come up with a generalized schema of the datastore. It was also written about on the official MongoDB blog.

##### R and data analysis
* Modern Applied Statistics with S (4th Edition) by William
  N. Venables, Brian D. Ripley. ISBN0387954570
* [R](https://www.coursera.org/learn/r-programming) 
* [Code School](http://www.codeschool.com/courses/try-r)
* [Quick-R](http://www.statmethods.net)

##### Tutorials written as ipython-notebooks
* [python-data-cleaning](http://nbviewer.ipython.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_21_pandas_processing.ipynb)
* [python tutorial for engineers](http://nbviewer.ipython.org/gist/rpmuller/5920182)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
	* [GitHub Issues](https://guides.github.com/features/issues/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


<!-- Links -->
[docker]:http://www.eecs.utk.edu/resources/it/kb/docker
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: https://help.github.com/en/articles/cloning-a-repository
[ref-commit]: https://readwrite.com/2013/10/02/github-for-beginners-part-2/
[ref-push]: https://help.github.com/en/articles/pushing-commits-to-a-remote-repository
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
