Visual-Analytics
Visual Analytics project with TABLEAU

Solved in Tableau with two large datasets as a source.

I analyzed the dataset which was provides by NOKUT. NOKUT conducts a national student survey(studiebarometeret) on study quality on behalf of the Ministry of Education and Research. The main object of the analysis is to highlight the University of Kristiania and how it is doing compared to other universities and colleges on the various quality dimensions.

Data Structure and Data Cleaning
Dataset-1
The dataset contained 1352 rows and 24 columns. The columns include identifikator, studiepgm_navn_en, instnavn, studiested, fagfelt_eng, utdanningsgruppe_eng, bama, oppr_utvalg, end_utvalg, andel_svart, stupoeng_DBH, indeks_underv_18, indeks_tilbveil_16, indeks_fysmiljo_13, indeks_organ_17, indeks_insp_14, indeks_egenteng_14, indeks_digi_18, indeks_yrkrel_19, overord_garpahelst_13, overord_altialt_13, tidsbruk_laerakt_14, tidsbruk_egeninns_14, tidsbruk_arbeid_14.
Dataset-2
The dataset contained 8969 rows and 7 columns. The columns include Timestamp, Lecture/Exercise, Session Name, Minutes Viewed, Username, Study Program, Location.
I did not do much cleaning, but I changed the column names in Dataset-1 to an English descriptive name for better understanding of the dataset.
Analysis and Insights
First part of the report is for dataset-1, 2nd part is for dataset-2 (Starting page 4).
I used tableau functions and formulas for the whole analysis. Functions used include AVG, SUM(Total).
The average hours per week spent on teaching, Exercises and Supervision at school Høyskolen Kristiania is 17 hours, for reference the most a university spent was 30 hours and the least was 9 hours
.  



Hours per week of paid work on average Høyskolen Kristiania had 11 hours. For reference the most a university was paid for work per week was kriminalomsorgens høgskole with 31 hours and the least was politihøgskolen with 2 hours.

 





How Kristiania is doing as compared to other universities and colleges on the various quality dimensions.
Top performing program based on enrollment was Bachelor in HR and industrial organizational psychology with 2280 enrollments, and the worst performing program based on enrollment was
Bachelor of Public Health and sport management with 150 enrollments. 

 

Høyskolen Kristiania vs Rest of School survey result
Two questions asked and answered, are you happy with the study program you are attending? Overall satisfaction score: 3,95.
Do you go to the study program you would like to go to? Overall satisfaction score: 4,46.
Overall satisfaction scores based on all schools scores: 3,99 & 4,42.


Study Program Performance
Which study program has most viewed hours? Cyber security has the most with 180 hours and Digital Business has the least with 6,3 hours. Thursday around 12pm is the most popular time of the day for students with the average of 77 viewed hours. 

 
Study Program Trend of Cumulative Viewing Hours (Weekly, Daily, Hourly)
For all study programs Thursday morning 9am – 12pm is by far the most viewed day with 689 hours. For reference the lowest is Saturday with 84 hours.
 
The rationale for my selected visualizations is based on my personal preference of simplicity, I find complex visualizations unnecessary for these two datasets, and I look at every visualization task as a task that needs to be answered and communicated in a simple way, which also in my opinion will be easier to understand. All my dashboards are based on this. 
When I first started developing my visualizations, I already knew I wanted to build it in a simple way, so the task was straight forward for me, except that I’m in a situation where I can’t be present with the other students, I found this to be a lot of work. I have answered the tasks in order. I chose to use Tableau for this project as this is the tool used in the course.

Dataset-1
A) Assess how Kristiania is doing as compared to other universities and colleges on the various quality dimensions.
B) Identify their best performing and worst performing study programs.

Dataset-2
A) Assess performance of lectures and exercise sessions.
B) Compare different study programs.
C) Analyze the viewing patterns across the weeks, days, and time of day.
Every dashboard except those dashboards that I could fit everything in the dashboard interface has a menu to the right where you can navigate between different institutions. When one of them is clicked the visualization will interact and output the new values. 
