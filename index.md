---
# Do not edit the text between these lines!
layout: default
---

# Summary of Analysis:
## Idea for Analysis:
Our idea for this analysis is that the course should not allow students who have completed a previous UNC COMP classes to enroll in this class because they have already learned much of the information taught in this course. This will make space for other students to be able to enroll in COMP 110. We chose this idea because students who have taken a COMP class at UNC already will be learning the same information again. We can analyze this idea with available data because the survey asks the student if they have taken a COMP course at UNC before. Therefore, we can see which students have taken a previous COMP course. To determine if students find this course easier, we can look at their average difficulty and pace scores. We believe this idea is valulable because all students in the class would be on a more level playing field as no one would have experienced a COMP class at UNC before enrolling in the class. The curves would be more fair as students who have already learned the information would not be in the class and would not have their advantage of previous knowledge. It would be a simple change for improvement because during class registration, students who have a previous COMP class at UNC in their transcript would not be able to register for the class.

## Figure 1:

<img src="{{ site.baseurl }}/static/imgs/Figure1.png" alt="Figure 1. "  width="500"/>

<span style="color:pink ">**Figure 1: Distribution of Difficulty Scores of Students Who Have Taken a UNC COMP Course Before and Students Who Have Not Taken a Previous UNC COMP Class.** </span>

*We created Figure 1 because we  hypothesized that students who have taken a prior UNC COMP class would have lower difficulty scores compared to students who hav not taken a COMP class at UNC. Figure 1 highlights this slight disparity.*

## Figure 2:

<img src="{{ site.baseurl }}/static/imgs/Figure2.png" alt="Figure 2. "  width="500"/>

<span style="color:pink ">**Figure 2: Distribution of Pace Scores of Students Who Have Taken a UNC COMP Course Prior to COMP 110 Compared to Students Who Have Not** </span>

*If students who have taken a UNC COMP class prior to COMP 110 already know the material, we would expect that they found the pace of the class to be slower than students who have not taken already taken a COMP class at UNC. Figure 2 does not support this hypothesis, so we investigate further with Figure 3.*

## Figure 3:

<img src="{{ site.baseurl }}/static/imgs/Figure3.png" alt="Figure 3. "  width="500"/>
<span style="color:pink ">**Figure 3: Distribution of Prior Formal Computer Science Experience** </span>

*This figure shows how many students actually have prior formal computer science experience. In this analysis, we are defining formal experience as an instructional course that is IB, AP, online, or taught by a community college. While taking the survey, students could respond to the question about prior experience with any of 6 options: `UNC`, `Another college or community college`, `High school course (IB or other)`, `On-line course`, `Other`, or `None`. These are the possible values for `other_comp`. There were two additional questions about if students had taken AP Computer Science Principles or AP Computer Science A. The possible values for these questions in the data are `Yes` and `No`. Figure 3 is a critial visual for this analysis because it highlights why Figure 2 does not support our hypothesis. Clearly, there are many students in COMP 110 that have had formal computer science experience.*


<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->

# Conclusion:

**Summary of Data Analysis**
We believed that students who have already taken a UNC COMP class should not be able to enroll in COMP 110 because they have learned a lot of 
the same information already. Unforunately, our analysis of the data was *inconclusive*. Figure 1 highlighted that students who had taken a COMP course at UNC prior to COMP 110 had less difficulty than students who had not taken a COMP course at UNC before enrolling in COMP 110. The difference is not drastic, but the group that had neve taken a COMP course had higher ratings of difficulty; however, Figure 2 did not support our claim. We expected that students who had taken a COMP class before would find the pace of the course to be slower than those who had not. Yet, Figure 2 exhibits that the opposite was true. We wanted to analyze why this was the case with Figure 3. Figure 3 shows the distribution of prior formal computer science experience. We defined "formal" as a instructional course such as an AP, IB, online, or community college courses. As we can see with Figure 3, the amount of students who have taken prior formal courses is large. Therefore, they may have influenced the distribution in Figure 1 and 2 as these figures only considered COMP courses that were taught at UNC.

**Experimental Idea Implementation / Additional Data Collection**
It would be beneficial if the data including which specific UNC COMP courses students had taken. While the survey included prerequisite classes, we could not see the specific UNC COMP classes that students had taken with the values from `other_comp`. They may have worked with C++, Java, or another language that is not similar to Python and therefore would not influence their difficulty scores. If the data included when the UNC COMP course was taken as well as the grade the student recieved, we could be more confident in our results. Ideally, we could have a prospective study in which we tracked multiple cohorts over time with survey data. We could compare the difficulty and pace scores of students with no prior computer science experience, students with only non-UNC computer science experience, and students who have already taken a UNC COMP course. This design would allow us to determine whether it is UNC specific courseowrk or any prior computer science experience that drives the disparity in percieved difficulty and pace. 

**Experimental Idea Implementation / Additional Data Collection**
It would be beneficial if the data including which specific UNC COMP courses students had taken. While the survey included prerequisite classes, we could not see the specific UNC COMP classes that students had taken with the values from `other_comp`. They may have worked with C++, Java, or another language that is not similar to Python and therefore would not influence their difficulty scores. If the data included when the UNC COMP course was taken as well as the grade the student recieved, we could be more confident in our results. Ideally, we could have a prospective study in which we tracked multiple cohorts over time with survey data. We could compare the difficulty and pace scores of students with no prior computer science experience, students with only non-UNC computer science experience, and students who have already taken a UNC COMP course. This design would allow us to determine whether it is UNC specific courseowrk or any prior computer science experience that drives the disparity in percieved difficulty and pace. 