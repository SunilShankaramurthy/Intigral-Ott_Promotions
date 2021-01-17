# Intigral-Ott_Promotions

#Table of Content
1. API Description
2. Framework Architecture
3. Framework - PreRequisite
4. Run Command
5. Conclusion

# API Description
   This project contains Inteigral-ott.net popcorn API verification and validation TestCases.
#Framework Architecture
  This is a Maven project develped using Java RestAssured and TestNG.
    - Maven take cares of dependency jars and plugins.
    - Allows easy acessing methods to validate JSON Response 
    - Provides parallel run option 
    - Provides access to produce user defined Test Reports.
    - Update assertion values from properties files thus redusing change rquired to alter the code.
    
  
#Framework - PreRequisite
  Java 8
#Run Command
  1. To run the Test on Non-Prod
      mvn clean install nonProd
  2.  To run the test on Pre-Prod
      mvn clean install PreProd
      
 #Conclusion
     This is a complete framework bult to add and test API's..
      
