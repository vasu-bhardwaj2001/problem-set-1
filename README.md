# Problem Set 1

Problem Set 1 challenges your ability to print various text, shapes, and figures to the console. You'll use built-in Java methods, along with the escape sequences we've covered, to create some interesting output (as least as interesting as text on a screen can be...).

## Getting Started

To get started, you'll need to create a [GitHub](https://github.com/) repository to store your Problem Set 1 code. After cloning my skeleton repository, you'll need to setup a remote to push your code to your repository instead of mine. Steps to accomplish this are outlined below.

### Setup

01. Login to your [GitHub](https://github.com/) account and create a new repository named ```problem-set-1```.
02. Create a folder on the ```Desktop``` named ```APCSA```.
03. In GitBash, navigate to your ```APCSA``` folder.
04. Clone my skeleton repository from [GitHub](https://github.com/). This will make a copy of my repository and store it locally.
```
   >>> git clone git@github.com:rwilson-ucvts/problem-set-1-skeleton.git
```
05. The cloning process will have created a folder named ```problem-set-1-skeleton```. Rename this folder to ```pset1```.
```
   >>> mv problem-set-1-skeleton pset1
```
06. Change directories to get into your ```pset1``` folder.
```
   >>> cd pset1
```
07. Originally, the remote will be pointing at my repository. We need to overwrite this.
```
   >>> git remote rename origin upstream
```
08. Lastly, we need to add a new remote that points at the repository you created earlier.
```
   >>> git remote add pset1 git@github.com:YOUR-USERNAME/problem-set-1.git
```
09. Launch Eclipse and set the ```Workspace``` to the ```APCSA``` folder you created on your ```Desktop```.
10. From within the ```Package Explorer``` (the left-most panel), right-click and select ```Import...```.
11. Select ```Git > Projects from Git```, and click ```Next >```.
12. Select ```Existing local repository``` and click ```Next >```.
13. Click the ```Add...``` button, and then the ```Browse...``` button.
14. Navigate to the ```APCSA``` folder on your ```Desktop```, click the ```pset1``` project folder, and click ```Open```.
15. Select the checkbox next to your project and click ```Finish```.
16. Now that we've imported the Git project, we can click ```Next >```, ```Next >```, and ```Finish``` once more.

## Exercises

Problem Set 1 contains 5 exercises, each of which will be written in your ```main``` method. You'll notice that there are indicators for where the code for each exercise should be written. Please adhere to these. And perhaps most importantly, challenge yourself! I know you can copy and paste the samepl outputs or find the answers on Google. Try to work through these on your own. You'll thank me later when the exercises become far more complex and the solutions not-so-easily implemented.

### Exercise 1

Print APCS to the console in large letters constructed with hashtags (i.e., #). Each letter must be 7 hashtags in height with a single space between letters. You cannot use String concatenation (i.e., the + operator) in your print statements. Your output should match mine exactly.
```
/// EXERCISE 1 /////////////////////////////////////////////////

   ##    ######  ######## ########
  #  #   #     # #        #
 #    #  #     # #        #
######## ######  #        ########
#      # #       #               #
#      # #       #               #
#      # #       ######## ########
```

### Exercise 2

Print 3 consecutive diamonds to the console using forward and backslashes only. Each diamond should be 6 slashes in height with a single space between each diamond. You cannot use String concatenation (i.e., the + operator) in your print statements. Your output should match mine exactly.
```
/// EXERCISE 2 /////////////////////////////////////////////////

  /\     /\     /\
 /  \   /  \   /  \
/    \ /    \ /    \
\    / \    / \    /
 \  /   \  /   \  /
  \/     \/     \/
```

### Exercise 3

Print a face to the console using only the ```System.out.print``` method. You are not allowed to use ```System.out.println``` at all. Your face should be 6 lines in height. You cannot use String concatenation (i.e., the + operator) in your print statements. Your output should match mine exactly.
```
/// EXERCISE 3 /////////////////////////////////////////////////

   \\\\\
  +"""""+
(|  0 0  |)
 |   ^   |
 |  '-'  |
  +-----+
```

### Exercise 4

Using a single print statement (either ```System.out.print``` or ```System.out.println```), print the following figure to the console. There is a single space between each letter on the top and bottom of the box. The rest of the spacing should be easily dedicible. You cannot use String concatenation (i.e., the + operator) in your print statements. Your output should match mine exactly. 
```
/// EXERCISE 4 /////////////////////////////////////////////////

H E L L O
E       A
L       P
L       C
O A P C S
```

### Exercise 5

Print the following text, including the quotation marks, to the console. You cannot use String concatenation (i.e., the + operator) in your print statements. Your output should match mine exactly.
```
/// EXERCISE 5 /////////////////////////////////////////////////

"The answer's quite simple," the professor said. "Just think outside the box!"
```

## Deadline

Your Canvas submission is due at or before 11:59pm on your section-specific due date.
* September 18, 2018 (A 9/10)
* September 20, 2018 (B 1/2)

### Submission Requirements

All that is required for submission is the URL to your [GitHub](https://github.com/) repository for this problem set.
