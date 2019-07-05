# UiS Preparatory Course 2019

## Course information
The purpose of the preparatory course is helping students to be ready for the necessary programming language for proceeding the course in UiS. Additionally, students can pre-experience several tools such as Autograder and Github so that they can be familiar before they start their actual class.
## Main task
Your task is completing the skeleton code that we offer.

![SampleCode](/images/sample-code.png)

## Lab Overview
This is an overview of the different exercises of this course. The chapters from the recommended reading section are from Jake VanderPlas' [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/index.html). It is also recommended to read chapters 2-8 before starting to solve the exercises.

| Lab | Assignments                                                                                              | Grading   | Recommended reading                                                                    | Topic |
| :-: | -------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------- |:-:|
|  1  | [Exercise 1](https://github.com/uis-prepcourse-test/assignments/tree/master/exercise1) | Pass/Fail | [Ch. 9](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)| Basic mathematical operation |
|  2  | [Exercise 2](https://github.com/uis-prepcourse-test/assignments/tree/master/exercise2) | Pass/Fail | [Ch. 9](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)| Advanced mathematical operation |
|  3  | [Exercise 3](https://github.com/uis-prepcourse-test/assignments/tree/master/exercise3)   | Pass/Fail | [w3schools - Classes and Objects](https://www.w3schools.com/python/python_classes.asp) | Basic data structure |
|  4  | [Exercise 4](https://github.com/uis-prepcourse-test/assignments)                                | Pass/Fail | [w3schools - Classes and Objects](https://www.w3schools.com/python/python_classes.asp) | Basic usage of class |
|  5  | [Exercise 5](https://github.com/uis-prepcourse-test/assignments)                                  | Pass/Fail | [Ch. 10](https://jakevdp.github.io/WhirlwindTourOfPython/09-errors-and-exceptions.html)| File I/O |


## How To Use
![Diagram](/images/preparatory-course-diagram.png)

There are several steps to set up the environment.
### Step 1: Registering to Autograder
1. Make your Github account (if you already have you can pass this step)
1. Register to [Autograder](https://ag3.ux.uis.no) using your Github account from step 1.
1. Find the course() from the [Autograder website](https://ag3.ux.uis.no/app/student/enroll), and enroll the course
1. Wait until the admin approves your request.
* [Detailed Instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/autograder-registration.md)
* [Video Tutorial(TBD)]()
### Step 2: Setting up the Github environment
![Diagram](/images/github.png)

All the submission process should be completed using Github. If you are not familiar with Github, please check this [link](https://guides.github.com/introduction/git-handbook/). 
1. Once admin approves your enrollment request, you will receive an email (The email address is used for the Github account).
1. The url of your repository will may following pattern.
`https://github.com/uis-prepcourse-2019/username-labs`
1. Now, you need to connect the repository with your local machine(e.g., laptop)
1. In terminal, first move to your working directory (e.g., `cd Downloads`)
1. Then, type `git clone https://github.com/uis-dat110-fall19/assignments.git`
1. Move to that directory `cd assignments`
1. Connect it to your private repository `git remote add labs https://github.com/uis-dat550-spring19/username-labs` 
1. Push the assignments file to your repository `git push labs`
1. Check if you can find the file fromte the browesr (https://github.com/uis-prepcourse-2019/username-labs).
* [Detailed Instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/github.md)
* [Video Tutorial(TBD)]()

### Step 3: Setting up the coding environment 
We recommend you to install anaconda and work on Jupyternotebook. If you are familiar with python programming, you can choose whatever tool that you want to use. However, the final submission should be the Jupyter notebook.
* [Detailed Instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/environment.md#anaconda)
* [Video Tutorial(TBD)]()

## Getting help
* We recommend you to use the [Discussion page](https://github.com/orgs/uis-prepcourse-2019/teams/discussion) instead of sending an email. This will help other students to find a similar question regarding the environment setup.
* For the questions directly related to the test will not be answered. However, if the description is considered ambiguous, you can ask about that to have a more precise explanation.
* Most questions can be helped by searching on the internet. If you are not familiar with Python at all, we recommend you to taks some online Python tutorial course(e.g., [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/index.html), [w3schools](https://www.w3schools.com/python/default.asp)).
