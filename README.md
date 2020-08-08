
# Git Cheatsheet
Ensure that you are in the proper directory. 

#### First, Pull the changes made by your collaborator. 
```
git pull
```

#### After you make changes in your local folder 
#### Check the status
```
git status
```
#### Add the files or folders you want to push to repo
```
git add .
```
#### Make the local commit 
Example:
```
git commit -m "modified file test.py"
```

#### Push your changes to the repo 

```
git push
```

#### Clone the Repo in your local machine 
One Time process

```
git clone $Link
```

#### Homework Hint
* First get two inputs from user - start & end
```python
start = input("Starting number")
end = input("Starting number")
```

* Create a random number between these two numbers ( import random package, use randrange function) 
```python
import random
target = random.randrange(start, end)
```

* Get inputs from user until the input matches with the target. Hint : Use while loop
```python
guess = input(" Please guess") 
```

* Based on guess, print feedback, "smaller" or "greater"
* Store all the results in a list. Initialize a list and append all the guesses to it. 
* Finally, print the number of guesses, list of guesses, and success rate. 





