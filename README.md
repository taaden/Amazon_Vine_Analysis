# Amazon_Vine_Analysis
## Overview of the analysis
 * The purpose of ths project is to analyse the Amazon Vine program using one of the available 50 Datasets to determine
   if there is any bias toward favorable reviews from Vine members in our chosen dataset and for this anlysis we are 
   analysing the US review of Vidoe games.
 * The Analysis entails :
    * First,pick the US review of Vidoe games dataset and use PySpark to perform the ETL process to extract
      the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
    * And then use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.
 
### Results
  * Total Number of Reviews
    
      * Vine Reviews
                  
      ![image](https://user-images.githubusercontent.com/64270455/202854839-1cd145e2-a859-40f9-a7cf-aac21146c770.png)
               
   
    
    
      * Non Vine Reviews
     
     
     ![image](https://user-images.githubusercontent.com/64270455/202854922-99233f8d-4ec2-41a8-9210-9e535166bbdf.png)
     
     
  * Total Number of 5 Stars Reviews
  
        
      *  Vine 5 Stars reviews
      
     ![image](https://user-images.githubusercontent.com/64270455/202855399-0fcb0b2c-6436-4957-b659-f9aae5eb7f42.png)
     
     
      * Non Vine 5 Stars Reviews 
    
      
     ![image](https://user-images.githubusercontent.com/64270455/202855680-cf8ef24d-8308-48f6-995e-b24100b3fea3.png)
     
     
   *  Percentage of 5 Stars Reviews
   
   
      * Precentage Vine 5 Stars Reviews
      
      
      ![image](https://user-images.githubusercontent.com/64270455/202855925-017afdd5-9337-40e5-bd46-fc336bfa3b79.png)



      * Percentage Non Vine 5 Stars Reviews
      
      
      ![image](https://user-images.githubusercontent.com/64270455/202856072-dbba739f-73b4-48c3-b13d-a46dd1a1a415.png)


#### Summary
   We can infer with 51% of reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39% 
   that there is a positivity bias for reviews in the Vine program.
   Additionally we could do chi-square test of the star rating for the Vine and non-Vine reviews to determine if a difference between observed data expected data is      due to chance or if it is due to a relationship between the variables.
    

