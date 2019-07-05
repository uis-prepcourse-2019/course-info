# UiS Preparatory Course 2019

## Course information
The purpose of the preparatory course is helping students to be ready for the necessary programming language for proceeding the course in UiS. Additionally, students can pre-experience several tools such as Autograder and Github so that they can be familiar before they start their actual class.
## Main task
Your task is completing the skeleton code that we offer. If you complete the function, our Autograder system will call the function with a different parameter to test the different cases. Therefore you should not change the function name. It is important to consider the exceptional case to pass all the test.
- We use Python 3 version.
![SampleCode](/images/sample-code.png)

## Lab Overview
This is an overview of the different exercises of this course. The chapters from the recommended reading section are from Jake VanderPlas' [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/index.html). It is also recommended to read chapters 2-8 before starting to solve the exercises.

| Lab | Assignments                                                                                              |  Recommended reading                                                                    | Topic |
| :-: | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |:-:|
|  1  | [Task 1](https://github.com/uis-prepcourse-2019/assignments/blob/master/exercise/exercise.ipynb) |  [Ch. 9](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)| Basic mathematical operation |
|  2  | [Task 2](https://github.com/uis-prepcourse-2019/assignments/blob/master/exercise/exercise.ipynb) |  [Ch. 9](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)| Advanced mathematical operation |
|  3  | [Task 3](https://github.com/uis-prepcourse-2019/assignments/blob/master/exercise/exercise.ipynb)   |  [w3schools - Classes and Objects](https://www.w3schools.com/python/python_classes.asp) | Basic data structure |
|  4  | [Task 4](https://github.com/uis-prepcourse-2019/assignments/blob/master/exercise/exercise.ipynb)                                |  [w3schools - Classes and Objects](https://www.w3schools.com/python/python_classes.asp) | Basic usage of class |
|  5  | [Task 5](https://github.com/uis-prepcourse-2019/assignments/blob/master/exercise/exercise.ipynb)                                  |  [Ch. 10](https://jakevdp.github.io/WhirlwindTourOfPython/09-errors-and-exceptions.html)| File I/O |


## How To Use
![Diagram](/images/preparatory-course-diagram.png)

It might be complicated for the first time. Please read the instruction below carefully.
### Step 1: Registering to Autograder
1. Make your Github account (if you already have you can pass this step)
1. Register to [Autograder](https://ag3.ux.uis.no) using your Github account from step 1.
1. Find the course() from the [Autograder website](https://ag3.ux.uis.no/app/student/enroll), and enroll the course
1. Wait until the admin approves your request.
* [Detailed Instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/autograder-registration.md)

### Step 2: Setting up the Github environment
![Diagram](/images/github.png)

All the submission process should be completed using Github. If you are not familiar with Github, please check this [link](https://guides.github.com/introduction/git-handbook/). 

* [Installation instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/github.md)

1. Once admin approves your enrollment request, you will receive an email (The email address is used for the Github account).
1. The url of your repository will may following pattern.
`https://github.com/uis-prepcourse-2019/username-labs`
1. Now, you need to connect the repository with your local machine(e.g., laptop)
1. In terminal, first move to your working directory (e.g., `cd Downloads`)
1. Then, type `git clone https://github.com/uis-prepcourse-2019/assignments.git`
1. Move to that directory `cd assignments`
1. Connect it to your private repository `git remote add labs https://github.com/uis-prepcourse-2019/username-labs` 
1. Push the assignments file to your repository `git push labs`
1. Check if you can find the file fromte the browesr (https://github.com/uis-prepcourse-2019/username-labs).



### Step 3: Setting up the coding environment 
We recommend you to install anaconda and work on Jupyter notebook. If you are familiar with python programming, you can choose whatever tool that you want to use. However, the final submission should be the Jupyter notebook.
* [Installation instruction](https://github.com/uis-prepcourse-2019/course-info/blob/master/environment.md#anaconda)

### Step 4: Coding and submission
1. Open Jupyter notebook using Anaconda navigator.
1. Find the assignment file (exercise.ipynb) from the folder that we set up in Step 2.
1. Complete the code and save.
1. In terminal (the same directory as Step 2), type the following git commands.
    1. `git add .`
    1. `git commit -m "any message"`
    1. `git push labs`
1. Check your scroe from the Autograder page.
1. Repeat above steps, every time you want to submit.


The submission process can be found in this [Video tutorial](https://vimeo.com/346381570).


## Getting help
* We recommend you to use the [Discussion page](https://github.com/orgs/uis-prepcourse-2019/teams/discussion) instead of sending an email. This will help other students to find a similar question regarding the environment setup.
* Most questions can be helped by searching on the internet. If you are not familiar with Python at all, we recommend you to take some online Python tutorial course(e.g., [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/index.html), [w3schools](https://www.w3schools.com/python/default.asp)).
