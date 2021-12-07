Our applications language is Python and we decided to use PyLint as a linting tool.
First we need to install it. Then we use it from commandline with command pylint --filename-- to get full report from different files.
We can also run it inside Visual Studio which makes it easier to use. 

For testing our application we decided to use PyTest library. Then we can just create test files to our application in study_pytest folder. 
After writing the tests for the code we can run those tests with command "py.test" then we get the output of the tests. It tells us why the test failed.

Last library is PyBuilder and we are going to use it for building our application. 
It is pretty simple to use with command "pyb" and it should build the project. 

There is also GitLab its almost the same as Jenkins but you have to pay 4$/month to use it. It uses on premise and could for hosting and there is free version of it.
There is only one disadvantage it doesnt support windows or mac as OS. 
Also there is teamCity, circleci and bamboo which can be used to set up CI. 
These are expencive but they support windows, mac and linux. And they are almost the same as jenkins. 

We decided to use could-based environment for CI setup, because it would be too much work for our 6 man team to make all the fixes etc.
And usually people don't use self-hosted setup environments because they don't have time or skills. 
So we are going to use it in this project.

How much time and money its going to take to host it, is there any security issues, expenses are lower when using cloud-based, clients wishes.