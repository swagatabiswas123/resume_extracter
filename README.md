# resume_extracter
This is a Algorithm for extract name,job_title,current_job_date from the the resume and reaname the file name accoding to title and change the file to pdf
#Basic information
This is a nlp bases algorithm using hugging face (transformer) use to extract name,
Also used fuzzywuzzy for job title extraction from the resume match the code present jobtile library indside a varibale 
Jobtitle = ['software engineer','team lead','SQL developer', ......]

#Further Improve Scope
1. Add a pretrained nlp and fine tune to search for job title
2. change the docx,doc file to pdf file
3. add a if and else part to output resumes catagories into different file types
   example:
    if output_resume == 'java developer':
         move.output_resume(/content/mydrive/javadevelopersfolder
    if output_resume == 'data anaylst':
         move.output_resume(/content/mydrive/dataanalystfolder)
4. change the code which way that canbe implemented throught azure blob storage and azure database ##IMPORTANT
