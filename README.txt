# PASSNYC: Data Science for Good Challenge
## Help PASSNYC determine which schools need their services the most
### I. Definition
#### Project Overview

PASSNYC is a not-for-profit organization that facilitates a collective impact that is
dedicated to broadening educational opportunities for New York City’s talented and
underserved students. New York City is home to some of the most impressive
educational institutions in the world, yet in recent years, the City’s specialized high
schools - institutions with historically transformative impact on student outcomes - have
seen a shift toward more homogeneous student body demographics.
PASSNYC uses public data to identify students within New York City’s under-performing
school districts and, through consulting and collaboration with partners, aims to
increase the diversity of students taking the Specialized High School Admissions Test
(SHSAT). By focusing efforts in under-performing areas that are historically
underrepresented in SHSAT registration, we will help pave the path to specialized high
schools for a more diverse group of students.
What is the Specialized High School Admissions Test (SHSAT) exactly?
The Specialized High School Admissions Test (SHSAT) is the only criterion for admissions
to eight of the nine New York City Specialized High Schools. The only exception is the
Fiorello H. LaGuardia High School of Music & Art and Performing Arts, which requires an
audition or portfolio for admission.
The SHSAT is administered by the New York City Department of Education and is only
available to New York City residents in the 8th grade. 9th grade students may also
choose to take the 9th grade version of the SHSAT for a very limited number of seats
that may become available at the Specialized High Schools.
The maximum score is 800, and Mathematics and English Language Arts (Verbal) are
weighted equally. The Specialized High Schools that require the SHSAT are:
Bronx High School of Science
Brooklyn Latin School
Brooklyn Technical High School
High School for Math, Science and Engineering at City College
High School for American Studies at Lehman College
Queens High School for Sciences at York College
Staten Island Technical High School
Stuyvesant High School
In 2016, approximately 28,000+ students took the SHSAT; less than 20% of those
students were accepted to a New York City Specialized High School
English Language Learners (ELLs) taking the SHSAT are granted extended testing time
(2.0x standard testing time). Bilingual mathematics glossaries will also be provided by
the NYCDOE on the day of the SHSAT at each test administration site in the NYCDOE’s
nine major languages: Arabic, Bengali, Chinese (Traditional and Simplified), French,
Haitian-Creole, Korean, Russian, Spanish, and Urdu. Note: Students are not permitted to
bring their own bilingual mathematics glossaries.

### Problem Statement

PASSNYC and its partners provide outreach services that improve the chances of
students taking the SHSAT and receiving placements in these specialized high schools.
The current process of identifying schools is effective, but PASSNYC could have an even
greater impact with a more informed, granular approach to quantifying the potential for
outreach at a given school. Proxies that have been good indicators of these types of 
schools include data on English Language Learners, Students with Disabilities, Students
on Free/Reduced Lunch, and Students with Temporary Housing.
Part of this challenge is to assess the needs of students by using publicly available data
to quantify the challenges they face in taking the SHSAT. The best solutions will enable
PASSNYC to identify the schools where minority and underserved students stand to gain
the most from services like after school programs, test preparation, mentoring, or
resources for parents.

### Metrics

To better evaluate the need of students at different schools and help PASSNYC prioritize
its outreach effort, I will create a simple index score, the Underrepresentation Score, will
be assigned to each middle school to quantify how likely students at a given school are
underperforming during SPHS application process as the origin in the plot represents
middle school without Hispanic, Black and low-income student.
Underrepresentation Score = Scaled Euclidean distance between a given point and
the origin
Underrepresentation Score closer to 1 indicates high level of underrepresentation at
SPHS. Please see Table 1 in the appendix for the full list of middle schools with their
corresponding Underrepresentation Scores.
