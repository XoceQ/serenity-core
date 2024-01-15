tart with creating on your IDE a new Java Maven project with the name "SerenityBDDIntro". Add the following Maven dependencies to work with Serenity BDD


Start by creating a new SerenityTest class in your project, and write a simple test using the @Narrative and @WithTags annotations. Your class should look like this (Don't forget to add the imports for each required element)



 As the test is already created, then you can create your own step definitions, on a new SampleSteps Java class. 
 
When the class is created, add code in the performSomeAction() method to sum two numbers received as parameters, and assign the result to a SampleSteps class attribute. Then, add an assertion on the verifyResult() method to check if the value of the previously assigned attribute matches the result of the sum of the two given numbers.

Run your test using your IDE, and then,  review the Serenity BDD report generated in the target/site/serenity directory. It provides detailed information about the test execution.

Congratulations! You have successfully completed the installation of Serenity BDD and created a simple Serenity BDD test project. 
 
