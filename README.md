# ONE-vs-REST-in-Logistic-regression
for multiclass classification problem



# USE of logistics REgression:
logistic regression work on binary calssification problem and also it work on multiclass classification problem as well this is called as one vs rest concept 


# ONE vs REST CONCEPT: 


![image](https://user-images.githubusercontent.com/83450364/120438632-3ddc5b80-c39f-11eb-9790-d2f4a95cbebe.png)
   
   
   
   
  in above multclassification figure it is  3 class classification problems 
  1.green line says separate those points .the point above green line treated as +ve points and below line points treated as -ve   points .it like this +1 ,  -1 , -1
  and create model M1 by these vales 
  2.red line separates red points and reaming two color point then red points treated as +ve points and  reaming two category points treated as -ve points. it like -1, +1, -1
  here  create mode M2 using this values
  3.blue line separates blue points by reaming two category points then the blue points are treated as +ve points and  remaing two category  treated as -ve point .it like this -1, -1, +1
  here create model M3 by using this values 
  
  
  # when testing time :
  when ever giving new test data the hole data set gotothe model M1 and model M2 and Model M3 then this models give coresponding probility values like this  [0.20,0.25,0.55] .here sumof all probabilties equal to 1.
  then in which model M3  probility is high then given new dat set belongs to Category 3
  
  
  ![Uploading image.png…](C:\Users\HP\Downloads\sample-data.csv)
  



  
  


