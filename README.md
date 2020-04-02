# STAT 201: Statistical Inference for Data Science

## Time and Place
TBD January 2021

## Description
Fundamental concepts in probability. The statistical and probabilistic foundations of inference, the frequentist paradigm. Concepts first introduced through simulation followed with an introduction and exploration of asymptotic theory.

## Prerequisites for STAT 201
- DSCI 100 Introduction to Data Science


## Textbook
We are using an open source textbook available free on the web: [ModernDive: Statistical Inference via Data Science](https://moderndive.com/) developed by Chester Ismay and Albert Y. Kim.      
We may also make some references to [OpenIntro Statistics](https://leanpub.com/openintro-statistics) by David Diez, Mine Cetinkaya-Rundel, and Christopher Barr which is available by donation.


## Expanded Course Description
Data Science skills and tools have been increasingly in demand in the last few years. This course is designed as a method of furthering experience and gaining such skills in the specific area of applications of statistical inference. STAT 201 will explain key concepts through the analysis of data while exploring various and diverse case studies. Special attention will be given to writing computer scripts to create reproducible analyses. In this course, students will be introduced to classical results based on exact and approximate distributional theory in comparison with results derived from simulation-based or resampling approaches, such as permutation and bootstrapping. The resampling framework allows the course to go beyond inference for means and proportions to other parameters needed in practice. This course will be computationally heavy, therefore, students will become well versed in implementing these concepts by writing computer scripts suitable for modern data analysis (e.g. R). There will be an emphasis on reproducible workflows, clear communication of findings and a general understanding of key concepts decontextualized from specific applications.

## Course Software Platforms
Students will learn to perform their analysis using the [R programming language](https://cran.r-project.org/). Worksheets and tutorial problem sets as well as the final project analysis, development, and reports will be done using [Jupyter Notebooks](http://jupyter.org/). Students will access the worksheets and tutorials in [Jupyter Notebooks](https://ubc-dsci.github.io/introduction-to-datascience/index.html#jupyter-notebooks) through [Canvas](https://canvas.ubc.ca/courses/19078). Students will require a laptop, chromebook or tablet in both lectures and tutorials. If a student does not their own laptop or chromebook, students may be able to [loan a laptop from the UBC library](https://services.library.ubc.ca/computers-technology/technology-borrowing/).

## Learning Outcomes
By the end of the course, students will be able to:
- Describe real-world examples of questions that can be answered with the statistical inference methods presented in this course (e.g., estimation, hypothesis testing) and apply inference skills and concepts to answer such questions.
- Explain what random and representative samples are and how they can influence estimation.
- Write computer scripts to perform estimation and hypothesis testing via simulation-based inference approaches, as well as by applying results from exact and approximate distributional theory.
- Interpret and explain results from confidence intervals and hypothesis tests.
- Compare the application of simulation-based inference approaches with the application of exact and approximate distributional results.
- Effectively visualize point estimates and different measures of uncertainty (e.g., confidence intervals, standard errors) by writing computer scripts.
- Discuss the impact of type I & II errors as well as responsible use and reporting of p-values on hypothesis tests.
- Explain estimator bias and uncertainty, and write a computer script to calculate it.
- Discuss how an estimator’s bias arises (e.g., sample bias, study design), and its implications in statistical inference.
- Perform all aspects of a statistical analysis (from data consumption to reporting) using reproducible and transparent computer scripts.

## Teaching Team


| Position | Name  | Email | Office Hours | Office Location |
|----------|-------|-------|--------------|-----------------|
| Instructor  | [Instructor Name ](https://trevorcampbell.me/) | email@stat.ubc.ca | Day at hh:mm | EARTH7777 |
| Instructor | [Instructor Name ](https://trevorcampbell.me/) | email@stat.ubc.ca | Day at hh:mm | EARTH7777 |
| TA | Name, Name | | Day at hh:mm | EARTH7777 |
| TA | Name, Name | | Day at hh:mm | EARTH7777 |
| TA | Name, Name | | Day at hh:mm | EARTH7777 |
| TA | Name, Name | | Day at hh:mm | EARTH7777 |

## Assessment

In each class (lecture and tutorial) there will be an assignment. Lecture worksheets are due **Day at hh:mm**, and tutorial worksheets are due **Day at hh:mm**. To open the assignment, click the link (e.g. `worksheet_01`) from Canvas. To submit your assignment, just make sure your work is saved (File -> Save and Checkpoint to be sure) **on our server** (i.e., using the link from Canvas) before the deadline. Our server will automatically snapshot at the due date/time.

### Course breakdown

| Deliverable | Percent Grade |
|-------------|---------------|
| Lecture worksheets | 5 |
| Tutorial problem sets | 15 |
| Group project | 20 |
| Two Midterms | 30 |
| Final exam | 30 |

### Group project breakdown

| Deliverable | Percent Grade |
|-------------|---------------|
| Proposal | 3 |
| Peer review | 2 |
| Final report | 10 |
| Team work | 5 |

## Schedule

_Lectures are held on **Day**. Tutorials are held on **Day** and build on the concepts learned in lecture._ 
- _**MD** refers to [ModernDive](https://moderndive.com/)_
- _**OIS** refers to [OpenInto Statistics](https://www.openintro.org/download.php?file=os3&referrer=/stat/textbook.php)_ 

| Week | Topic       | Readings   |
|------|-------------|------------|
| [1](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-1-introduction-to-statistical-inference-and-sampling) | Introduction to Statistical Inference and Sampling  | <ul><li>[MD: Chapter 7 - 7.3 Sampling](https://moderndive.com/7-sampling.html)</li></ul>|
| [2](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-2-populations-and-sampling) | Populations and Sampling   | <ul><li>[MD Chapter 7.3.3 onwards Sampling](https://moderndive.com/7-sampling.html#sampling-framework)</li><li> OIS: Chapter 4.2.1 Bernoulli distribution</li> OIS: Chapter 2.4 Random variables</li></ul>|
| [3](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-3-bootstrapping-and-its-relationship-to-the-sampling-distribution) | Bootstrapping and its Relationship to the Sampling Distribution   | <ul><li>[ MD: Chapter 8 - 8.3 Bootstrapping](https://moderndive.com/8-confidence-intervals.html)</li><li>[MD: Chapter 8 Conclusion](https://moderndive.com/8-confidence-intervals.html#ci-conclusion)</li></ul>|
| [4](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-4-confidence-intervals-via-bootstrapping) | Confidence Intervals via Bootstrapping   | <ul><li>[MD: Chapter 8.3- 8.7 Confidence Intervals](https://moderndive.com/8-confidence-intervals.html#ci-build-up)</li></ul>|
| 5 | Mid-term #1 and Preparation for Projects  | |
| [6](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-6-estimators-and-additional-measures-of-their-uncertainty) | Estimators and Additional Measures of their Uncertainty  |  <ul><li>OIS Chapter 1.4 Experiments </li></ul>|
| [7](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-7-hypothesis-testing-via-simulationrandomization) | Hypothesis Testing via Simulation/Randomization | <ul><li>[MD: Chapter 9 - 9.4.2 Hypothesis Testing ](https://moderndive.com/9-hypothesis-testing.html)</li></ul>|
| 8 | Mid-term #2 Introduction of Methods Based on Exact and Asymptotic Distributional Theory  | <ul><li> OIS Chapter 3.1.2 Probability</li></ul>|
| [9](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-9-confidence-intervals-based-on-the-assumption-of-normality-or-the-central-limit-theorem) | Confidence Intervals Based on the Assumption of Normality or the Central Limit Theorem   | <ul><li> OIS: Chapter 5.2 Confidence intervals for a proportion </li><li> [MD: Chapter 7.5.2 Central Limit Theorem ](https://moderndive.com/7-sampling.html) </li><li> [MD: Appendix A Normal Distribution ](https://moderndive.com/A-appendixA.html#appendix-normal-curve)</li><li>[MD: Chapter 8.7.2 Theory-based confidence intervals](https://moderndive.com/8-confidence-intervals.html#theory-based-confidence-intervals)</li></ul> |
| [10](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-10-classical-tests-based-on-normal-and-t--distributions) | Classical Tests Based on Normal and t- Distributions   | <ul><li>[MD: Chapter 9.6.1 Theory-based hypothesis tests](https://moderndive.com/9-hypothesis-testing.html#conclusion)</li></ul>|
| [11](https://github.ubc.ca/UBC-DSCI/stat-201/blob/master/lecture-learning-outcomes.md#week-11-errors-in-inference) | Errors in Inference  | <ul><li>[MD: Chapter 9.4.2 Types of errors](https://moderndive.com/9-hypothesis-testing.html#types-of-errors)</li><li>[MD: Chapter 9.6.3 Problems with p-values](https://moderndive.com/9-hypothesis-testing.html#)</li></ul>|
| 12 | Project Week | |
| Exam period  | Final Exam | |

## Policies

### Late/Absence
Regular attendance to lecture and tutorials is expected of students. Students who are unavoidably absent because of illness or other reasons should inform the instructor(s) of the course as soon as possible, preferably, prior to the start of the lecture/tutorial. Students who miss quizzes 1 or 2 or an assignment need to provide a self-declaration and make arrangements (e.g., schedule an oral make-up quiz) with the Instructor as soon as possible. Failing to present a declaration may result in a grade of zero.

Late lecture and tutorial worksheets will receive a grade of 0. For other assessments, a late submission is defined as any work submitted after the deadline. For a late submission, the student will receive a 50% deducation of their grade for the first occurrence. Hence a maximum attainable grade for the first piece of work submitted late is 50%. Any additional pieces of work that are submitted late will receive a grade of 0 for subsequent occurrences.

### Autograder Policy
Many of the questions in assignments are graded automatically by software. The grading computer has exactly the same hardware setup as the server that students work on. No assignment, when completed, should take longer than 5 minutes to run on the server. The autograder will automatically stop (time out) for each student assignment after a maximum of 5 minutes; **any ungraded questions at that point will receive a score of 0.**

Furthermore, students are responsible for making sure their assignments are *reproducible*, and run from beginning to end on the autograding computer. In particular, **please ensure that any data that needs to be downloaded is done so by the assignment notebook with the correct filename to the correct folder.** A common mistake is to manually download data when working on the assignment, making the autograder unable to find the data and often resulting in an assignment grade of 0.

In short: whatever grade the autograder returns after 5 minutes (assuming the teaching team did not make an error) is the grade that will be assigned.

### Re-grading
If you have concerns about the way your work was graded, please contact the TA who graded it within one week of having the grade returned to you. After this one-week window, we may deny your request for re-evaluation. Also, please keep in mind that your grade may go up or down as a result of re-grading.

### Device/Browser
Students are responsible for using a device and browser compatible with all functionality of Canvas. Chrome or Firefox browsers are recommended; Safari has had issues with Canvas quizzes in the past.

### Mid-terms Exams
Two 45-minute mid-terms will be administered at the start of the lecture in Weeks 5 and 8. Notwithstanding the grading weights [above](#course-breakdown), students must pass the final exam to pass the course.

### Missed Final Exam
Students who miss the final exam must report to their faculty advising office within 72 hours of the missed exam, and must supply supporting documentation. Only your faculty advising office can grant deferred standing in a course. You must also notify your instructor prior to (if possible) or immediately after the exam. Your instructor will let you know when you are expected to write your deferred exam. Deferred exams will ONLY be provided to students who have applied for and received deferred standing from their faculty.

### Academic Concession Policy
Please see [UBC's concession policy](http://www.calendar.ubc.ca/vancouver/index.cfm?tree=3,329,0,0) for detailed information on dealing with missed coursework, quizzes, and exams under circumstances of an acute and unanticipated nature.

### Academic Integrity
The academic enterprise is founded on honesty, civility, and integrity. As members of this enterprise, all students are expected to know, understand, and follow the codes of conduct regarding academic integrity. At the most basic level, this means submitting only original work done by you and acknowledging all sources of information or ideas and attributing them to others as required. This also means you should not cheat, copy, or mislead others about what is your work. Violations of academic integrity (i.e., misconduct) lead to the breakdown of the academic enterprise, and therefore serious consequences arise and harsh sanctions are imposed. For example, incidences of plagiarism or cheating may result in a mark of zero on the
assignment or exam and more serious consequences may apply if the matter is referred to the President’s Advisory Committee on Student Discipline. Careful records are kept in order to monitor and prevent recurrences.

A more detailed description of academic integrity, including the University’s policies and procedures, may be found in the Academic Calendar at http://calendar.ubc.ca/vancouver/index.cfm?tree=3,54,111,0.

### Plagiarism
Students must correctly cite any code or text that has been authored by someone else or by the student themselves for other assignments. Cases of plagiarism may include, but are not limited to:

- the reproduction (copying and pasting) of code or text with none or minimal reformatting (e.g., changing the name of the variables)
- the translation of an algorithm or a script from a language to another
- the generation of code by automatic code-generation software

An “adequate acknowledgement” requires a detailed identification of the (parts of the) code or text reused and a full citation of the original source code that has been reused.

The above attribution policy applies only to assignments. **No code or text may be copied (with or without attribution) from any source during a quiz or exam. Answers must always be in your own words. At a minimum, copying will result in a grade of 0 for the related question.**

**Repeated plagiarism of any form could result in larger penalties, including failure of the course.**

## Attribution

Parts of this syllabus (particularly the policies) have been copied and derived from the [UBC MDS Policies](https://ubc-mds.github.io/policies/).
