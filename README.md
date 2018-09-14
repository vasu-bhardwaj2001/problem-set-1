# Problem Set 1

Problem Set 1 challenges your ability to print various text, shapes, and figures to the console. You'll use built-in Java methods, along with the escape sequences we've covered, to create some interesting output (as least as interesting as text on a screen can be...).

## Getting Started

To get started, you'll need to create a [GitHub](https://github.com/) repository to store your Problem Set 1 code. After cloning my skeleton repository, you'll need to setup a remote to push your code to your repository instead of mine. Steps to accomplish this are outlined below.

### Setup

1. Login to your [GitHub](https://github.com/) account and create a new repository named ```problem-set-1```.
2. Create a folder on the ```Desktop``` named ```APCSA```.
3. In GitBash, navigate to your ```APCSA``` folder.
4. Clone my skeleton repository from GitHub. This will make a copy of my repository and store it locally.
```
   >>> git clone git@github.com:rwilson-ucvts/problem-set-1-skeleton.git
```
5. The cloning process will have created a folder named ```problem-set-1-skeleton```. Rename this folder to ```pset1```.
```
   >>> mv problem-set-1-skeleton pset1
```
6. Change directories to get into your ```pset1``` folder.
```
   >>> cd pset1
```
7. Originally, the remote will be pointing at my repository. We need to overwrite this.
```
   >>> git remote rename origin upstream
```
8. Lastly, we need to add a new remote that points at the repository you created earlier.
```
   >>> git remote add pset1 git@github.com:YOUR-USERNAME/problem-set-1.git
```

## Exercises

Problem Set 1 contains 5 exercises, each of which will be written in your ```main``` method. You'll notice that there are indicators for where the code for each exercise should be written. Please adhere to these.

### Exercise 1

Print APCS to the console in large letters constructed with hashtags (i.e., #). Each letter must be 7 hashtags in height with a single space between letters. Your output should match mine exactly.
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

Print 3 consecutive diamonds to the console using forward and backslashes only. Each diamond should be 6 slashes in height with a single space between each diamond. Your output should match mine exactly.
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

Print a face to the console using only the ```System.out.print``` method. You are not allowed to use ```System.out.println``` at all. Your face should be 6 lines in height. Your output should match mine exactly.
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

Using a single print statement (either ````System.out.print``` or ```System.out.println```), print the following figure to the console. There is a single space between each letter on the top and bottom of the box. The rest of the spacing should be easily dedicible. Your output should match mine exactly. 
```
    /// EXERCISE 4 /////////////////////////////////////////////////

    H E L L O
    E       A
    L       P
    L       C
    O A P C S
    
```

### Exercise 5

Print the following text, including the quotation marks, to the console. Your output should match mine exactly.
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
