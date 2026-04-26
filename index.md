---
# Do not edit the text between these lines!
layout: default
---

# Josh's Repository

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="Joshs-Repository/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## COMP 110 - EX09 - 2026

For this exercise, I used survey data from COMP 110 students to determine whether the curriculum should create a virtual lecture option. This would allow students to see a livestream of the lecture and see it published online.

We took the survey CSV into a row-style dictionary, which we converted to a column-style table. We then selected the survey questions that related to the question: add_livestream (prefernce for a livestream) and ls_effective (effectivity of lesson videos). Additionally, we included questions that determined the student's academic standing: own_notes (frequency of writing notes) and interested_connections (interest in the applications of computer science). We determined own_notes and interested_connections to be correlated with academic effort and standing, because the best students most likely to take notes and are genuinely interested in coputer science as a field. To make the sample consist of those with decent academic standing, we eliminated rows that didn't meet certain criteria. own_notes must be >3 out of 7 and interested_connections > 3 out of 7. Out of those with good academic standing, we wanted to see what the frequency of those who want a virtual lecture option are. This ultimately showed that the best and most effortful students in the class want to have a virtual lecture. Finally, we graphed the relationship between academic effort and wanting a virtual lecture open. For this, we used the unfiltered data.

<img src="Joshs-Repository/static/imgs/line_graph.png" alt="Line Graph. "  width="500"/>
<img src="Joshs-Repository/static/imgs/freq_tabe1.png" alt="Freq_table1. "  width="500"/>
<img src="Joshs-Repository/static/imgs/freq_table2.png" alt="Freq_table2. "  width="500"/>

The data shows that most people find the lesson videos to be effective and want to have a livestream of the lecture online. This is shown by the two frequency tables that are significantly skewed right, and the line graph that shows a clear correlation between a student taking notes, a sign of academic standing, and finding lesson videos to be effective. The evidence shows that the COMP 110 curriculum should impliment a virtual lecture so that students can use videos and livestreams  to suppliment or eventually replace in-person lectures. While this can cut down resources for the University and help those who prefer a virtual lecture, it may be harmful for the education of those who prefer in-person lectures and would not want to see the curriculum's educational priority to be in virtual lectures. Therefore, in the short-term, it is best to keep the virtual lecture to be optional and supplimental rather than becoming a replacement for the in-person lecture. Ultimately, COMP 110 should impliment a virtual lecture option due to the educational preferences of the students and the correlation between academic standing and lesson video viewership.