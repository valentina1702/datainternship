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
- You can go the link displayed after the second-last code chunk is executed  

Or:
- You can do it inline using the last code chunk  


### Explanation for Non-Technical audience:
- So in the app that i created below, I included 2 drop-down menus. One to select the criteria to be visualized, being the comparison among different age gropus or across different disease types. Second being the criteria you want to distinguish between for the above selected type. i.e distinguish them by age or by encounter type.    
- I feel this is useful because we can first get a sense of what population we are looking at if we see the graph of age stratified by gender. We can see which disease type is most prevelant across which sex if we look at graph with disease type stratified by gender. We can also observe the different encounters across each group to sense of understand which encounter is common across which age group, if we select age stratified by encounter type. Also can look at which encounter is common across different disease types, if we select disease type stratified by encounter type.   
- I included the dropdown, to let the visualizers have the liberty to choose what they wish to see, and also not overwhelm them by presenting all information all at once. 
- The graphs are interactive, meaning you can hover over each bar to get more information.


# **Part 2 :Answers for the Questions**
 

### **What are future improvements you might make for your code?**     
*I would try to look at ways to improvise on my function update_figure for the app, since now it is very case specific for two types of inputs, I would like to build   more on it and make it more generalizable, one way to do it would be setting the data frame itself in the right format.* 

### **Let's say we want to run this code as a nightly job. What changes/additions would you make to it?**   
*Since, it would be designed for a nightly job, and also just focusing on the visualization I made, the things that would be changing would be the data itself. I will make provisions for new/ updated data to be pulled every day, and run the app based off these updates, and do a build every night, to have most up-to-date information in place.*

### **What are some issues you noticed with the data?**
*One think was it being distributed through two files, the presence of duplicate patient-ids, although they had different information, it would have been better if they could have been integrated all in one row, as this possibly made the merging operation a bit longer, as had to deal with duplicate values post merging. The start and end time for encounters was not interpretable, although I agree it might be for de-identification purposes, but it should have been somewhat interpretable, maybe could have just shifted the years in future.*  

### **What data do you wish you had?**    
*I wish I had other vital signs, and any other information collected or measured during a particular encounter, as it would have been interesting to visualize some of the vital signs stratified by disease type as well.*
