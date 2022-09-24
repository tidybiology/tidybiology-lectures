# TidyBiology: An Introduction to Biological Data Science in R
![tidybiology](README_files/figure-gfm/tidybiology_channel_art.png)  
  
## About  
This workshop-style module provides an introduction to the emerging field of Data Science in R, including data analysis and visualization, with a particular focus on its utility for biological insight. Students will be provided with biological datasets, and introduced to R packages and code used to examine data. In the first half of each class, students will be lectured on methods and shown demonstrations; in the second half of each class, students will use tools to analyze real data; laptop computers are required. Methods for filtering, sorting, and transforming data will be discussed along with visualization tools and options. Particular attention will be paid to code interpretation and data provenance methods by learning to generate reproducible data output files. For a final project, students will be given a new dataset to analyze using the tools learned during the course, and will share findings with the class in a short oral presentation. Although specific datasets will be used for analysis in class, this workshop will provide broadly applicable tools to reproducibly analyze and visualize data across the biological sciences.  

**All of these lecture materials are now embedded in an integrated learning experience that you can access freely at [www.tidybiology.org](http://www.tidybiology.org)**

## Admin
A few notes to make it easier to create materials for subsequent classes:  
1. create a new directory based on the year, or year_special_session_name  
2. move yaml file from previous year over to new dir  
3. *optionally*: use `copy_yaml(output_dir = "2023")` from fun.R to do both steps 1 and 2  
4. update yaml.Rmd in the year dir with the appropriate session information  
5. use `generate_syllabus(output_dir = "2023")` to make the syllabus for that year using the class info you put in the yaml  
6. get the class roster, and put into the participants.xlsx file, located in the admin dir  
7. update the class roster cleaning steps in fun.R line ~150 to get only 5 variables [first_name, last_name, full_name, email_address, class (*class is also the name of the dir*)]  
8. update alumni csv with this class information (only do 1 time/year)  
9. update any class-specific information in the email blasts  
10. send test email to ensure all is working  
11. send emails to students each day of class (think about a way to automate this with information from syllabus)  

