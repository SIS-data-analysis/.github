# SIS-750: Data Analysis

Professor Austin Hart (ahart@american.edu)  

Office: SIS 345  
Office hours:	M/Tu/Th 2:00-4:00pm, SIS 345

Meetings: Tuesdays, 5:30-8:00pm  
Classroom: Kerwin Hall ST01 computer lab

## Overview
This course introduces the art and practice of data analysis. It focuses on the preparation of data (data wrangling or munging), professional presentation of data and analysis, and the process of producing scalable, replicable work (programming). More than just learning the requisite code, I emphasize the professional outputs associated with a career in data analysis. This semester is a chance to get your hands dirty in the world of analysis and explore the new and challenging puzzles you face every day in this profession.

## Learning outcomes and objectives
Students who complete this course will be proficient junior analysts. They will be able to:
- build, clean, and manipulate quantitative data
- generate professional data visualizations
- present data-driven research to a professional audience
- write clear, efficient, reproducible code in the R programming language

## Expectations and workload
This is an advanced graduate course. The material is challenging, and the workload is intense. However, my expectations for the course and of your performance are appropriate to your standing as professionals and aspiring professionals in a top graduate program. 

> Success in this course will require 10-15 hours of work outside of class each week. Please do not enroll in this course if you cannot commit to these hours.

## Course material and software
I will post handouts, data, R scripts, and links to reading materials on our course github site. While there is no textbook to purchase, I will draw regularly on the following:
- Winston Chang's [Cookbook for R](http://www.cookbook-r.com/)
- Jenny Bryan's [Stat 545 collection](https://stat545.com/)
- Claus Wilke's foundational text on visualization, [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/)
- A basic introduction to R, my own [Survival Guide](https://austin-hart-pols.github.io/SurvivalGuide/)
- Annie Wang's indispensable [guide to careers in data analytics](https://www.guide.progressivedatajobs.org/)

You need regular and reliable access to R and RStudio, and I urge you to bring your laptop to class each week. These programs work across platforms and are available for free. Just download and install.
- R, the workhorse of modern data analysis, is available from the [CRAN website](https://mirrors.nics.utk.edu/cran/).
- RStudio is a front-end interface for R. RStudio Desktop is free. [Download and install](https://www.rstudio.com/products/rstudio/download/).

Becoming proficient with these programs is a challenging, though necessary, part of this course. When you run into trouble (i) Review course materials, (ii) search online (seriously, Google knows the answer), (iii) ask your classmates, and (iv) ASK ME.

## Assignments and grading
Grades for the course will be assigned based on performance in the following areas:
- [**Problem sets and Deliverables (80%)**](https://github.com/SIS-data-analysis/Assessments)  
Hands-on experience is the only way to build proficiency. So you will complete eight, equally-weighted exercises that ask you to put into practice what we cover in class. Problem sets (4) feature a series of discrete questions of varying degree of difficulty for you to answer. Deliverables (4) will include two recorded slide presentations, a poster presentation, and a codebook. I will distribute assignments in class, typically two weeks in advance of the due date, and/or link to them in this syllabus. Budget 10-15 hours to complete each exercise. While I encourage you to consult with classmates, your code and your written answers must be yours and yours alone. If someone else wrote or executed your code, it is not individual work and I will not grade it. If you sent your code or scripts to someone else, you did not participate earnestly in the process of individual work. You may not consult with anyone not currently enrolled in or teaching this course. 
- **Analyst Portfolio (10%)**  
At the end of the semester, you will submit an updated resume tailored to a position in data analytics along with an edited collection of your best work and mock answers to common questions in data analytic job interviews.
- **Participation and professionalism (10%)**  
Professionalism is a critical part of success in the data analytics profession. So it will be an integral part of our training in this course.  Aside from what they can do on a laptop, a good analyst is someone who can engage with peers constructively and respectfully, who can ask questions when expectations are unclear,  and who can create inclusive environments for co-workers and clients. I will evaluate participation and professionalism throughout the semester in terms of your engagement with peers, with myself, and with the material during class-related activities. Do you come to class prepared? Do you ask and answer questions? Are you contributing to a constructive and inclusive environment?

Please take note of the assignment due dates and plan accordingly. Except in truly unusual and unavoidable circumstances I will not accept late work.

## Schedule Overview
We will proceed according to the outline below. Note that details on required materials for each week are available in the repositories linked below (and available on our github site). 

| Date    | Description                                   | Due in class   |
| :-----  | :-------------------------------------------- | :------------- |
| Jan 17  | [Intro and Monty Hall](https://github.com/SIS-data-analysis/01-Intro)                 |                |
| Jan 24  | [R Programming cRash couRse](https://github.com/SIS-data-analysis/02-IntroR)                             | Draft resume   |
| Jan 31  | [Visualization 1: grammar of graphics](https://github.com/SIS-data-analysis/03-Viz1)         | [PS 1](https://github.com/SIS-data-analysis/Assessments/tree/main/PS1)           |
| Feb 7   | [Visualization 2: layers, facets, patchwork](https://github.com/SIS-data-analysis/04-Viz2)   | [PS 2](https://github.com/SIS-data-analysis/Assessments/tree/main/PS2)           |
| Feb 14  | [Wrangling 1: frames, tibbles, lists](https://github.com/SIS-data-analysis/05-wrangling1)    | [Presentation 1](https://github.com/SIS-data-analysis/Assessments/tree/main/Presentation1) |
| Feb 21  | [Wrangling 2: reshape, merge, append](https://github.com/SIS-data-analysis/06-wrangling2)    |                |
| Feb 28  | [Wrangling 3: all about variables](https://github.com/SIS-data-analysis/07-wrangling3)       | [PS 3](https://github.com/SIS-data-analysis/Assessments/tree/main/PS3)           |
| Mar 7   | [Wrangling round-up](https://github.com/SIS-data-analysis/08-codebooks)                      | Updated resume |
| Mar 21  | [Markdown 1: code while you write](https://github.com/SIS-data-analysis/09-markdown)         | [Codebook](https://github.com/SIS-data-analysis/Assessments/tree/main/Codebook)       |
| Mar 28  | [Markdown 2: slide decks](https://github.com/SIS-data-analysis/10-markdown-slides)           | [PS 4](https://github.com/SIS-data-analysis/Assessments/tree/main/PS4)           |
| Apr 4   | Careers in analytics                          | [Presentation 2](https://github.com/SIS-data-analysis/Assessments/tree/main/Presentation2) |
| Apr 11  | Analysis 1: describe distributions            |                |
| Apr 18  | Analysis 2: describe relationships            | [Poster](https://github.com/SIS-data-analysis/Assessments/tree/main/Poster)         |
| Apr 25  | Analysis round-up                             | ExCr memo      |
| May 9   | Submit Analyst Porfolio                       | Portfolio      |
  

## Contacting me
I strongly encourage you to drop in during office hours or set up a meeting on a semi-regular basis. I'm happy to discuss the course, the field of data analysis, your professional goals, and whatever else is on your mind. I love working with students in this course, and I will do my best to help you think through challenges both big and small. The sooner you come in to consult, the better. Please note that broad substantive questions and detailed technical questions need to be addressed in person.

## Academic integrity
Standards of academic conduct are set forth in the University's [Academic Integrity Code](https://www.american.edu/policies/students/academic-integrity-code.cfm). By registering for classes, you have acknowledged your awareness of the Academic Integrity Code, and you are obliged to become familiar with your rights and responsibilities as defined by the Code. Violations of the Academic Integrity Code will not be treated lightly, and disciplinary actions will be taken should such violations occur. Please see me if you have any questions about the academic violations described in the Code in general or as they relate to particular requirements for this course.

## Background knowledge
A background in introductory statistics—equivalent to SIS-600—is necessary for this course. So I will assume familiarity with descriptive statistics (e.g., means, standard deviations), hypothesis testing (through linear regression), and basic statistical computing (e.g., R or Stata).

## Snow days, COVID, and random apocalypses
If we're unable to meet for our regular class time due to a University closure (e.g., snow day) or something on my end (e.g., I get COVID), we will hold class virtually on Zoom. If you are sick (e.g., you get COVID), do not come to our cramped lab. Join virtually instead. Let me know that you'll be virtual and contact a classmate to dial you in for class (I can set you up with someone if you're not sure who to ask). 

## Support services
I will make every effort to enable full participation in this course by all students. Students needing ongoing special accommodations should contact me as early as possible (within the first two weeks of the semester, or as soon as those needs arise) to discuss how they can be met within the structure of the course. Every effort will be made to maintain the confidentiality of personal information. You may also wish to contact [Disability Support Services](http://www.american.edu/ocl/dss/) (Mary Graydon Center, Room 206) or the [Counseling Center](http://www.american.edu/ocl/counseling/) (Mary Graydon Center, Room 214) if you have questions about campus policies and services or wish to register for specific accommodations or assistance with physical, medical, or psychological disabilities.

## Requests for special accommodations
Students anticipating any difficulty in completing assigned work on time should consult with the professor well in advance of course deadlines. Any student seeking exceptions to course policies or requesting special accommodations due to medical or familial issues must first consult with the Office of the Dean of Students (Butler Pavilion, Room 408). Should the Office of the Dean of Students determine that accommodations are appropriate, a letter will be issued from the [Office of the Dean of Students](http://www.american.edu/ocl/dos/) to the student's professors. Students must then follow up with their professors either in person or via email as soon as circumstances permit in order to discuss new arrangements for required work and deadlines. Simply providing a letter from the Office of the Dean of Students does not constitute a waiver for course requirements or deadlines, nor does such a letter excuse work missed prior to the provision of documentation unless the Office of the Dean of Students specifically indicates that the accommodations are retroactive. Late penalties and other course policies will apply to any revised assignment arrangements or deadlines.


