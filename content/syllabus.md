---
title: "Data Analysis and statistical inference"
subtitle: "Summer 2022"
output:
  pdf_document: default
  html_document:
    df_print: paged
---

[Click here for a printable PDF](/static/syllabus/syllabus.pdf)

**Course:** STA101L-001

**Professor:** Alexander Fisher

**Contact:** [alexander.fisher\@duke.edu](alexander.fisher@duke.edu)

**Lecture:** Mon/Tue/Thu 12:30-2:35pm

**Lab:** Tue/Thu 3:30-4:45pm

**Website:** [sta101.github.io](https://sta101.github.io)

**Textbooks:** [Introduction to Modern Statistics](https://openintro-ims.netlify.app/) by Mine Çetinkaya-Rundel and Johanna Hardin. Available free at [https://openintro-ims.netlify.app/](https://openintro-ims.netlify.app/)

------------------------------------------------------------------------

### Course objectives

By the end of this course you will be able to:

0. appreciate the need for statistics in a variety of disciplines

1. create aesthetic visualizations to extract insights from data with `ggplot` 

2. build, fit, and interpret linear regression models to learn from data

3. perform statistical inference in a flexible, simulation-based framework

4. document your workflow in reproducible `.rmd` files

5. collaborate to apply statistical analyses to a question and dataset of your own choosing.

6. present, and communicate the results of your analysis

7. critically read and interpret statistical results from literature in various fields

### Grading policy

| Assignment               | Description                                                                   |
|------------------------------------|------------------------------------|
| Labs (20%)               | One to two labs per week.                                                     |
| Exams (30%)              | Two take-home, open notes exams.                                              |
| Regression project (20%) | Written report (PDF).                                                         |
| Final project (30%)      | Proposal, video presentation and written report. Students will work in teams. |

A >= 93.0, A- < 93.0, B+ < 90.0, B < 87, B- < 83, C+ <80, C < 77, C- < 73, D+ < 70, D < 67, D < 63, F < 60

---


**Labs**

In labs, you will apply the concepts discussed in lecture to various data analysis scenarios. Labs will focus on both computation and conceptualization. Lab assignments will be completed using R Markdown and submitted as PDF for grading in Gradescope. While you may collaborate with others on lab assignments, your final solution should be your own.

**Exams**   
  
There will be two take-home, open notes exams. Through these exams you have the opportunity to demonstrate what you've learned in the course thus far. Each exam will include small analyses and computational tasks related to the content in application exercises and labs. More details about the content and structure of the exams will be discussed during the semester.

**Projects**

There will be a mid-semester prediction project and a final project. The prediction project will introduce you to conducting independent analyses and writing a formal report using a pre-specified data set. The final project allows you to explore a question and data set of your own. More details about  
the projects will be provided during the semester. Projects will be completed in teams.

  
### Course policies

**Inclusive community**: It is my intent that students from all backgrounds and perspectives be
well-served by this course, that students’ learning needs be addressed both in and out of class, and that the
diversity that the students bring to this class be viewed as a resource, strength, and benefit. It is my intent
to present materials and activities that are respectful of diversity and in alignment with Duke’s Commitment
to Diversity and Inclusion. Your suggestions are encouraged and appreciated. Please let me know ways to
improve the effectiveness of the course for you personally, or for other students or student groups.

**Attendance policy related to COVID symptoms, exposure, or infection:** Student health, safety,
and well-being are the university’s top priorities. To help ensure your well-being and the well-being of those
around you, please do not come to class if you have symptoms related to COVID-19, have had a known
exposure to COVID-19, or have tested positive for COVID-19. If any of these situations apply to you, you must follow university guidance related to the ongoing COVID-19 pandemic and current health and safety
protocols.
If you are experiencing any COVID-19 symptoms, contact student health at 919-681-9355. To keep the
university community as safe and healthy as possible, you will be expected to follow these guidelines. Please reach out to me and your academic dean as soon as possible if you need to quarantine or isolate so that we can discuss arrangements for your continued participation in class.

**Academic honesty:** You should be familiar with Duke’s community standard: [https://studentaffairs.duke.edu/conduct/about-us/duke-community-standard](https://studentaffairs.duke.edu/conduct/about-us/duke-community-standard)

By enrolling in this course, you commit to upholding Duke’s community standard reproduced as follows:

- I will not lie, cheat, or steal in my academic endeavors;
- I will conduct myself honorably in all my endeavors; and
- I will act if the Standard is compromised.

Any violations in academic honesty standards as outlined in the Duke Community Standard and those
specific to this course will automatically result in a 0 for the assignment and will be reported to the Office
of Student Conduct for further action.

Please abide by the following as you work on assignments in this course:
- You may discuss lab assignments with other students; however, you may
not directly share (or copy) code or write up with other students. For team assignments, you may
collaborate freely within your team. You may discuss the assignment with other teams; however,
you may not directly share (or copy) code or write up with another team. Unauthorized sharing (or
copying) of the code or write up will be considered a violation for all students involved.
- You may not discuss or otherwise work with others on the exams. Unauthorized collaboration or using
unauthorized materials will be considered a violation for all students involved. More details will be
given closer to the exam date.
- Reusing code: Unless explicitly stated otherwise, you may make use of online resources (e.g. Stack-
Overflow) for coding examples on assignments. If you directly use code from an outside source (or
use it as inspiration), you must explicitly cite where you obtained the code. Any recycled code that is
discovered and is not explicitly cited will be treated as plagiarism.

**Late policy:**

Late work will not be accepted. To accommodate this strict policy, your lowest lab will be dropped.

Missed lab or exams can only be excused under exceptional circumstances. The Duke policy for illness requires a short-term illness report or a letter from the Dean; except in emergencies, all other absenteeism must be approved in advance (e.g., an athlete who must miss class may be excused by prior arrangement for specific days).   For emergencies, email notification is needed at the first reasonable time.

**Procedures for Requesting a Regrade**

Every effort will be made to mark your work accurately. We are on your side, and want you to receive every point you have worked to earn. However, sometimes grading mistakes happen. If you believe that an error has been made, return the paper to the instructor within seven days, stating your claim in writing.

The following claims will be considered for re-grading:

(i)    points are not totaled correctly;

(ii)   the grader did not see a correct answer that is on your paper;

(iii)  your answer is the same as the correct answer, but in a different form (e.g., you wrote a correct answer as 1/3 and the grader was looking for .333);

(iv)  your answer to a free response question is essentially correct but stated slightly differently than the grader's expectation.

The following claims will not be considered for re-grading:

(v)   arguments about the number of points lost;

(vi)  arguments about question wording.

Considering re-grades consumes time and resources that TAs and the instructor would rather spend helping you understand material.  Please bring only claims of type (i), (ii), (iii), or (iv) to our attention.

**Communication:** All lecture notes, assignment instructions, an up-to-date schedule, and other course
materials may be found on the course website.
Announcements will be emailed to the class through sakai. Please check your email regularly to ensure you
have the latest announcements for the course. For quick communication with your peers and the teaching
team, see the course slack for general questions and discussion.

**Accessibility:** If there is any portion of the course that is not accessible to you due to challenges with
technology or the course format, please let me know so we can make appropriate accommodations.
The Student Disability Access Office (SDAO) is available to ensure that students are able to engage with
their courses and related assignments. Students should be in touch with the Student Disability Access Office
to request or update accommodations under these circumstances.

### Additional resources

**Academic Resource Center:** There are times when you may need help with the class beyond what can be
provided by the teaching team. In those instances, I encourage you to visit the Academic Resource Center.
The Academic Resource Center (ARC) offers free services to all students during their undergraduate careers
at Duke. Services include Learning Consultations, Peer Tutoring and Study Groups, ADHD/LD Coaching,
Outreach Workshops, and more. Because learning is a process unique to every individual, they work with
each student to discover and develop their own academic strategy for success at Duke. Contact the ARC
to schedule an appointment. Undergraduates in any year, studying any discipline can benefit! Contact
[ARC@duke.edu](ARC@duke.edu), 919-684-5917.

**CAPS:** Duke Counseling & Pyschological Services (CAPS) helps Duke Students enhance strengths and
develop abilities to successfully live, grow and learn in their personal and academic lives. CAPS recognizes
that we are living in unprecedented times and that the changes, challenges and stressors brought on by the
COVID-19 pandemic have impacted everyone, often in ways that are tax our well-being. CAPS offers many
services to Duke undergraduate students, including brief individual and group counseling, couples counseling
and more. CAPS staff also provides outreach to student groups, particularly programs supportive of at-risk
populations, on a wide range of issues impacting them in various aspects of campus life. CAPS provides
services to students via Telehealth. To initiate services, you can contact their front desk at 919-660-1000.