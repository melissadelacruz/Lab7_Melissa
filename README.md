# Lab 7 - Melissa De La Cruz

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

        Within a Github action that runs whenever code is pushed. This ensures immediate feedback, allowing developers to catch and fix issues early in the development process. 

        It also promotes consistency by running tests in a controlled environment, which helps avoid problems that might only appear in certain local setups. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   
        No, I would use a unit test to do so. End to end is supposed to replicate user behavior to verify the behavior of the application such as clicking buttons or filling out forms. Unit tests isolates and directly tests individual functions for correctness.






