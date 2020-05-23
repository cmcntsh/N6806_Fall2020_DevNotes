# Setting up Environments and Installing Packages Using Conda

## Skills in this exercise

1. Fork this repository so you can work on your own copy.
3. Edit this README.md file.
4. Push your updated file to your GitHub repository.

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/N6806_Fall2020_DevNotes/blob/master/Projects/002%20-%20Practice%20Using%20Git%20and%20GitHub/README.md

## Edit your README.md file

* In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.

## Conda Concepts

* [ ] Describe the Conda concepts in the table below.
* [ ] Open a regular Command Prompt.
* [ ] Check your python version by running the code `python --version`
* [ ] Enter the result in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |(enter description or short answer here)|
|What is the default package manager in Python?            |(enter description or short answer here)|
|How do you manage environments and packages in Anaconda?  |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda env list`       |(enter description or short answer here)|
|How do you keep your base environment unchanged?       |(enter description or short answer here)|
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |(enter description or short answer here)|
|`conda create --name XXXX`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|
|`conda list`       |(enter description or short answer here)|

* After creating the environments he created in the video, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
# conda environments:
#
base     /miniconda3

```

* If you didn't get a result in the regular command prompt, it means Python didn't get added to your path variable.
* It's not strictly necessary. It just means you should run Python from the CLI using Anaconda Prompt instead of a regular command prompt. Or you need to add the path to Python to your path variable.

## Find your path to Python interpreter

* Instruction on how to find the path to the Python interpreter in Anaconda can be found here: https://docs.anaconda.com/anaconda/user-guide/tasks/integration/python-path/
* Add Python and Conda to Windows path using command line: https://www.youtube.com/watch?v=dgjEUcccRwM
* Add Python and Conda to Windows path using GUI: https://www.youtube.com/watch?v=uOwCiZKj2rg
* He checks the Mac path variables around time 8-12 minutes: https://www.youtube.com/watch?v=9mAmZIRfJBs&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=8&t=868s
