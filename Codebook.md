---
title: "Human Activity Recognition Using Smartphones Data Set"
author: "Lim Poh Guan"
date: "Sunday, March 15, 2015"
output: html_document
---
Getting and Cleaning Data: Course Project

Codebook.md (describes the variables, the data, and any transformations or work that performed to clean up the data)


#Variables and Data

Classes 'data.table' and 'data.frame':  10299 obs. of  88 variables:
   
   **TimeBodyAccelerometerMean()-X**
   
   : num
   
   0.289 0.278 0.28 0.279 0.277 ...
  
   **TimeBodyAccelerometerMean()-Y**                             
	 
   : num  
	 
   0.0203 -0.0164 -0.0195 -0.0262 -0.0166 ...
   
   **TimeBodyAccelerometerMean()-Z**
   
   : num  
   
   -0.133 -0.124 -0.113 -0.123 -0.115 ...
   
   **TimeBodyAccelerometerStandardDeviation()-X**                
   
   : num  
   
   -0.995 -0.998 -0.995 -0.996 -0.998 ...
   
   **TimeBodyAccelerometerStandardDeviation()-Y**                
   
   : num  
   
   -0.983 -0.975 -0.967 -0.983 -0.981 ...
  
   **TimeBodyAccelerometerStandardDeviation()-Z**                
   
   : num  
   
   -0.914 -0.96 -0.979 -0.991 -0.99 ...
  
   **TimeGravityAccelerometerMean()-X**                          
   
   : num  
   
   0.963 0.967 0.967 0.968 0.968 ...
  
   **TimeGravityAccelerometerMean()-Y**                          
   
   : num  
   
   -0.141 -0.142 -0.142 -0.144 -0.149 ...
   
   **TimeGravityAccelerometerMean()-Z**                          
   
   : num  
   
   0.1154 0.1094 0.1019 0.0999 0.0945 ...
   
   **TimeGravityAccelerometerStandardDeviation()-X**             
   
   : num  
   
   -0.985 -0.997 -1 -0.997 -0.998 ...
   
   **TimeGravityAccelerometerStandardDeviation()-Y**             
   
   : num  
   
   -0.982 -0.989 -0.993 -0.981 -0.988 ...
   
   **TimeGravityAccelerometerStandardDeviation()-Z**             
   
   : num  
   
   -0.878 -0.932 -0.993 -0.978 -0.979 ...
   
   **TimeBodyAccelerometerJerkMean()-X**                         
   
   : num  
   
   0.078 0.074 0.0736 0.0773 0.0734 ...
   
   **TimeBodyAccelerometerJerkMean()-Y**                         
   
   : num  
   
   0.005 0.00577 0.0031 0.02006 0.01912 ...
   
   **TimeBodyAccelerometerJerkMean()-Z**                         
   
   : num  
   
   -0.06783 0.02938 -0.00905 -0.00986 0.01678 ...
   
   **TimeBodyAccelerometerJerkStandardDeviation()-X**            
   
   : num  
   
   -0.994 -0.996 -0.991 -0.993 -0.996 ...
   
   **TimeBodyAccelerometerJerkStandardDeviation()-Y**            
   
   : num  
   
   -0.988 -0.981 -0.981 -0.988 -0.988 ...
   
   **TimeBodyAccelerometerJerkStandardDeviation()-Z**            
   
   : num  
   
   -0.994 -0.992 -0.99 -0.993 -0.992 ...
   
   **TimeBodyGyroscopeMean()-X**                                 
   
   : num  
   
   -0.0061 -0.0161 -0.0317 -0.0434 -0.034 ...
   
   **TimeBodyGyroscopeMean()-Y**                                 
   
   : num  
   
   -0.0314 -0.0839 -0.1023 -0.0914 -0.0747 ...
   
   **TimeBodyGyroscopeMean()-Z**                                 
   
   : num  
   
   0.1077 0.1006 0.0961 0.0855 0.0774 ...
   
   **TimeBodyGyroscopeStandardDeviation()-X**                    
   
   : num  
   
   -0.985 -0.983 -0.976 -0.991 -0.985 ...
   
   **TimeBodyGyroscopeStandardDeviation()-Y**                    
   
   : num  
   
   -0.977 -0.989 -0.994 -0.992 -0.992 ...
   
   **TimeBodyGyroscopeStandardDeviation()-Z**                    
   
   : num  
   
   -0.992 -0.989 -0.986 -0.988 -0.987 ...
   
   **TimeBodyGyroscopeJerkMean()-X**                             
   
   : num  
   
   -0.0992 
   
   -0.1105 -0.1085 -0.0912 -0.0908 ...
   
   **TimeBodyGyroscopeJerkMean()-Y**                             
   
   : num  
   
   -0.0555 -0.0448 -0.0424 -0.0363 -0.0376 ...
   
   **TimeBodyGyroscopeJerkMean()-Z**                             
   
   : num  
   
   -0.062 -0.0592 -0.0558 -0.0605 -0.0583 ...
   
   **TimeBodyGyroscopeJerkStandardDeviation()-X**                
   
   : num  
   
   -0.992 -0.99 -0.988 -0.991 -0.991 ...
   
   **TimeBodyGyroscopeJerkStandardDeviation()-Y**                
   
   : num  
   
   -0.993 -0.997 -0.996 -0.997 -0.996 ...
   
   **TimeBodyGyroscopeJerkStandardDeviation()-Z**                
   
   : num  
   
   -0.992 -0.994 -0.992 -0.993 -0.995 ...
   
   **TimeBodyAccelerometerMagnitudeMean()**                      
   
   : num  
   
   -0.959 -0.979 -0.984 -0.987 -0.993 ...
   
   **TimeBodyAccelerometerMagnitudeStandardDeviation()**         
   
   : num  
   
   -0.951 -0.976 -0.988 -0.986 -0.991 ...
   
   **TimeGravityAccelerometerMagnitudeMean()**                   
   
   : num  
   
   -0.959 -0.979 -0.984 -0.987 -0.993 ...
   
   **TimeGravityAccelerometerMagnitudeStandardDeviation()**      
   
   : num  
   
   -0.951 -0.976 -0.988 -0.986 -0.991 ...
   
   **TimeBodyAccelerometerJerkMagnitudeMean()**                  
   
   : num  
   
   -0.993 -0.991 -0.989 -0.993 -0.993 ...
   
   **TimeBodyAccelerometerJerkMagnitudeStandardDeviation()**     
   
   : num  
   
   -0.994 -0.992 -0.99 -0.993 -0.996 ...
   
   **TimeBodyGyroscopeMagnitudeMean()**                          
   
   : num  
   
   -0.969 
   
   -0.981 -0.976 -0.982 -0.985 ...
   
   **TimeBodyGyroscopeMagnitudeStandardDeviation()**             
   
   : num  
   
   -0.964 -0.984 -0.986 -0.987 -0.989 ...
   
   **TimeBodyGyroscopeJerkMagnitudeMean()**                      
   
   : num  
   
   -0.994 
   
   -0.995 -0.993 -0.996 -0.996 ...
   
   **TimeBodyGyroscopeJerkMagnitudeStandardDeviation()**         
   
   : num  
   
   -0.991 
   
   -0.996 -0.995 -0.995 -0.995 ...
   
   **FrequencyBodyAccelerometerMean()-X**                        
   
   : num  
   
   -0.995 -0.997 -0.994 -0.995 -0.997 ...
   
   **FrequencyBodyAccelerometerMean()-Y**                        
   
   : num  
   
   -0.983 -0.977 -0.973 -0.984 -0.982 ...
   
   **FrequencyBodyAccelerometerMean()-Z**                        
   
   : num  
   
   -0.939 -0.974 -0.983 -0.991 -0.988 ...
   
   **FrequencyBodyAccelerometerStandardDeviation()-X**           
   
   : num  
   
   -0.995 -0.999 -0.996 -0.996 -0.999 ...
   
   **FrequencyBodyAccelerometerStandardDeviation()-Y**           
   
   : num  
   
   -0.983 -0.975 -0.966 -0.983 -0.98 ...
   
   **FrequencyBodyAccelerometerStandardDeviation()-Z**           
   
   : num  
   
   -0.906 -0.955 -0.977 -0.99 -0.992 ...
   
   **FrequencyBodyAccelerometerMeanFreq()-X**                    
   
   : num  
   
   0.252 0.271 0.125 0.029 0.181 ...
   
   **FrequencyBodyAccelerometerMeanFreq()-Y**                    
   
   : num  
   
   0.1318 0.0429 -0.0646 0.0803 0.058 ...
   
   **FrequencyBodyAccelerometerMeanFreq()-Z**                    
   
   : num 
   
   -0.0521 -0.0143 0.0827 0.1857 0.5598 ...
   
   **FrequencyBodyAccelerometerJerkMean()-X**                    
   
   : num  
   
   -0.992 -0.995 -0.991 -0.994 -0.996 ...
   
   **FrequencyBodyAccelerometerJerkMean()-Y**                    
   
   : num  
   
   -0.987 -0.981 -0.982 -0.989 -0.989 ...
   
   **FrequencyBodyAccelerometerJerkMean()-Z**                    
   
   : num  
   
   -0.99 -0.99 -0.988 -0.991 -0.991 ...
   
   **FrequencyBodyAccelerometerJerkStandardDeviation()-X**       
   
   : num  
   
   -0.996 -0.997 -0.991 -0.991 -0.997 ...
   
   **FrequencyBodyAccelerometerJerkStandardDeviation()-Y**       
   
   : num  
   
   -0.991 -0.982 -0.981 -0.987 -0.989 ...
   
   **FrequencyBodyAccelerometerJerkStandardDeviation()-Z**       
   
   : num  
   
   -0.997 -0.993 -0.99 -0.994 -0.993 ...
   
   **FrequencyBodyAccelerometerJerkMeanFreq()-X**                
   
   : num  
   
   0.8704 0.6085 0.1154 0.0358 0.2734 ...
   
   **FrequencyBodyAccelerometerJerkMeanFreq()-Y**                
   
   : num  
   
   0.2107 -0.0537 -0.1934 -0.093 0.0791 ...
   
   **FrequencyBodyAccelerometerJerkMeanFreq()-Z**                
   
   : num  
   
   0.2637 0.0631 0.0383 0.1681 0.2924 ...
   
   **FrequencyBodyGyroscopeMean()-X**                            
   
   : num  
   
   -0.987 -0.977 -0.975 -0.987 -0.982 ...
   
   **FrequencyBodyGyroscopeMean()-Y**                            
   
   : num  
   
   -0.982 -0.993 -0.994 -0.994 -0.993 ...
   
   **FrequencyBodyGyroscopeMean()-Z**                            
   
   : num  
   
   -0.99 -0.99 -0.987 -0.987 -0.989 ...
   
   **FrequencyBodyGyroscopeStandardDeviation()-X**               
   
   : num  
   
   -0.985 -0.985 -0.977 -0.993 -0.986 ...
   
   **FrequencyBodyGyroscopeStandardDeviation()-Y**               
   
   : num  
   
   -0.974 -0.987 -0.993 -0.992 -0.992 ...
   
   **FrequencyBodyGyroscopeStandardDeviation()-Z**               
   
   : num  
   
   -0.994 -0.99 -0.987 -0.989 -0.988 ...
   
   **FrequencyBodyGyroscopeMeanFreq()-X**                        
   
   : num  
   
   -0.2575 -0.0482 -0.2167 0.2169 -0.1533 ...
   
   **FrequencyBodyGyroscopeMeanFreq()-Y**                        
   
   : num  
   
   0.0979 -0.4016 -0.0173 -0.1352 -0.0884 ...
   
   **FrequencyBodyGyroscopeMeanFreq()-Z**                        
   
   : num  
   
   0.5472 -0.0682 -0.1107 -0.0497 -0.1622 ...
   
   **FrequencyBodyAccelerometerMagnitudeMean()**                 
   
   : num  
   
   -0.952 -0.981 -0.988 -0.988 -0.994 ...
   
   **FrequencyBodyAccelerometerMagnitudeStandardDeviation()**    
   
   : num  
   
   -0.956 -0.976 -0.989 -0.987 -0.99 ...
   
   **FrequencyBodyAccelerometerMagnitudeMeanFreq()**             
   
   : num  
   
   -0.0884 -0.0441 0.2579 0.0736 0.3943 ...
   
   **FrequencyBodyAccelerometerJerkMagnitudeMean()**             
   
   : num  
   
   -0.994 -0.99 -0.989 -0.993 -0.996 ...
   
   **FrequencyBodyAccelerometerJerkMagnitudeStandardDeviation()**
   
   : num  
   
   -0.994 -0.992 -0.991 -0.992 -0.994 ...
   
   **FrequencyBodyAccelerometerJerkMagnitudeMeanFreq()**         
   
   : num  0.347 0.532 0.661 0.679 0.559 ...
   
   **FrequencyBodyGyroscopeMagnitudeMean()**                     
   
   : num  
   
   -0.98 -0.988 -0.989 -0.989 -0.991 ...
   
   **FrequencyBodyGyroscopeMagnitudeStandardDeviation()**        
   
   : num  
   
   -0.961 -0.983 -0.986 -0.988 -0.989 ...
   
   **FrequencyBodyGyroscopeMagnitudeMeanFreq()**                 
   
   : num  
   
   -0.129 -0.272 -0.2127 -0.0357 -0.2736 ...
   
   **FrequencyBodyGyroscopeJerkMagnitudeMean()**                 
   
   : num  
   
   -0.992 -0.996 -0.995 -0.995 -0.995 ...
   
   **FrequencyBodyGyroscopeJerkMagnitudeStandardDeviation()**    
   
   : num  
   
   -0.991 -0.996 -0.995 -0.995 -0.995 ...
   
   **FrequencyBodyGyroscopeJerkMagnitudeMeanFreq()**             
   
   : num  
   
   -0.0743 0.1581 0.4145 0.4046 0.0878 ...
   
   **Angle(TimeBodyAccelerometerMean,Gravity)**                  
   
   : num  
   
   -0.1128 0.0535 -0.1186 -0.0368 0.1233 ...
   
   **Angle(TimeBodyAccelerometerJerkMean),GravityMean)**         
   
   : num  
   
   0.0304 -0.00743 0.1779 -0.01289 0.12254 ...
   
   **Angle(TimeBodyGyroscopeMean,GravityMean)**                  
   
   : num  
   
   -0.465 -0.733 0.101 0.64 0.694 ...
   
   **Angle(TimeBodyGyroscopeJerkMean,GravityMean)**              
   
   : num  
   
   -0.0184 0.7035 0.8085 -0.4854 -0.616 ...
   
   **Angle(X,GravityMean)**                                      
   
   : num  
   
   -0.841 -0.845 -0.849 -0.849 -0.848 ...
   
   **Angle(Y,GravityMean)**                                      
   
   : num  
   
   0.18 0.18 0.181 0.182 0.185 ...
   
   **Angle(Z,GravityMean)**                                      
   
   : num  
   
   -0.0586 -0.0543 -0.0491 -0.0477 -0.0439 ...
   
   **Activity**                                                  
   
   : Factor w/ 6 levels 
   
   "LAYING","SITTING",..: 3 3 3 3 3 3 3 3 3 3 ...
   
   **Subject**                                                   
   
   : Factor w/ 30 levels 
   
   "1","2","3","4",..: 1 1 1 1 1 1 1 1 1 1 ...
 
 
#Data transformation

1. Process the raw data sets with run_analysis.R script to create a tidy data set.

2. Merge Training and Test sets, and label the variables with the names assigned by original collectors.


3. Extract the mean and standard deviation variables with only the values of estimated mean (variables with labels that contain "mean") and standard deviation (variables with labels that contain "std").


4. Display the current Activity names and replace it with more descriptive names


5. Create a tidy data set
