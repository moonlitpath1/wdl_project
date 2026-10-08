# Personality Test

> This was my first website project ever. I'd made this in my first year of college. So, dont mind the bad UI or flaky wording of this README.^^"

**Welcome to the Personality Test Website!**

This test helps determine whether you have an optimistic, pessimistic, intoverted or extroverted personality.


## **Get Started:**

**Instructions to set up local server:**

   Note: First you must navigate to the folder where you saved the extracted version of the project
                  use: cd <folder path> to reach directory

Before starting the test, you must be on a local server port: 8000 located in the directory of the folder containing all files, since all files' links are on that port. This drawback will certainly be modified in the future.

Here's how you can create a local server at port 8000:

1. Using Python:
   
   If you have Python installed, you can quickly create a local server, by navigating to the directory in command prompt and entering the command:
   
             python3 -m http.server 8000
   
3. Using Node.js
   
   If you use Node.js, you can create a local server using the http-server package:

     i. First install the http-server package
   
             npm install -g http-server
   
    ii. Then navigate to the directory and run:
   
             http-server -p 8000
   
4. Using PHP
   
  If you have PHP installed you can use its built in server:
  
            php -S localhost:8000
            
5. Using Ruby:
   
   If you have Ruby installed you can use its built in server:
   
           ruby -run -e httpd . -p 8000
