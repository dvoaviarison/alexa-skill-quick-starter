# Alexa Skill Quick Starter

This will show you an easy way to learn how to create, deploy and test a skill for amazon alexa in 5 minutes.

## Pre-req
- Go [HERE](https://aws.amazon.com/console/) and create a free account then log in
- Create an AMI user with access key as explained [HERE](https://aws.amazon.com/premiumsupport/knowledge-center/create-access-key/). Make sure you take good note of the created `access` and `secret` key. They will be used to give you proper CLI access so you will later do everything from command line without the need of navigating in the browser.
- Install node.js from [HERE](https://nodejs.org)
- Install Ask CLI by running the following in your terminal

   `npm uninstall -g ask-cli`

   `ask init`

## Create your first skill
- Create a skill by running the following 
   
   `ask new`

  Then provide with a skill name. E.g. `Hello World`
  
  A node js project is automatically created for you.

- You can open the project with you preferred IDE, and modify the skill as you like. I recommend vs-code as it is very light ang has gain an incredibly large trend due to the simplicity and extensibility it offers.


## Deploy your first skill
- Go inside you skill root folder and run the following

   `ask deploy`

## Test your first skill
- Once deployed, you can go [HERE](https://developer.amazon.com/alexa/console/ask#). Click on your newly deployed skill and go to the "Test" tab.
Now you can enter 

   `ask <your skill name>`

    and get the response back from alexa.
