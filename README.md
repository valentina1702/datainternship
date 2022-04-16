# **Part 1: Coding Answers:** 

# **How to set up and run the code.**  
Please change the path for the file while reading it in, depending on the position of files on your computer.  
Run as explained in the image below, also the instructions are in comments of the notebook
![image](https://user-images.githubusercontent.com/63582428/163691367-f26dd986-1bd4-43ca-ae59-20cd4807ac66.png)  


Code in the notebook named "particle_health_task.ipynb":  
- Find the patient with the most encounters:  
![image](https://user-images.githubusercontent.com/63582428/163691794-280e95fd-afe5-45ee-8916-840ae6655b36.png)

- Calculate the number of vaccine appointments by gender:  
![image](https://user-images.githubusercontent.com/63582428/163691766-460654df-c01b-4ab5-ac47-b55c8495b491.png)

- Calculate the number of encounters per year:  
![image](https://user-images.githubusercontent.com/63582428/163691775-e569a8e1-774c-4d7a-ad63-0d1e42116e9f.png)

- Visualization of choice:  
### For viewing the app with the visualizations: 
Either:
- You can go the link displayed after the secon-last code chunk is executed  

Or:
- You can do it inline using the last code chunk




# **Part 2 :Answers for the Questions**
 

### **What are future improvements you might make for your code?**     
*I would try to look at ways to improvise on my function update_figure for the app, since now it is very case specific for two types of inputs, I would like to build   more on it and make it more generalizable, one way to do it would be setting the data frame itself in the right format.* 

### **Let's say we want to run this code as a nightly job. What changes/additions would you make to it?**   
*Since, it would be designed for a nightly job, and also just focusing on the visualization I made, the things that would be changing would be the data itself. I will make provisions for new/ updated data to be pulled every day, and run the app based off these updates, and do a build every night, to have most up-to-date information in place.*

### **What are some issues you noticed with the data?**
*One think was it being distributed through two files, the presence of duplicate patient-ids, although they had different information, it would have been better if they could have been integrated all in one row, as this possibly made the merging operation a bit longer, as had to deal with duplicate values post merging. The start and end time for encounters was not interpretable, although I agree it might be for de-identification puroposes, but it should have been somewhat interpretable, maybe could have just shifted the years in future.*  

### **What data do you wish you had?**    
*I wish I had other vital signs, and any other information collected or measured during a particular encounter, as it would have been interesting to visualize some of the vital signs stratified by disease type as well.*
