![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# React | Ironbook

In this exercise, we are going to create a book to display the list of people who did the bootcamp.


## Submission

- Upon completion, run the following commands

  ```
  git add .
  git commit -m "done"
  git push origin master
  ```

- Create Pull Request so your TAs can check up your work.



## Installation

You can create a new React application by doing:

```
$ npx create-react-app starter-code
$ cd starter-code
```

Then you can move the file `users.json` to `starter-code/src/users.json`.

## Before starting

To make the exercise easier, create only 1 component `App`. We will learn later who to create more complex website with multiple components that communicate each other.



## Instructions


### Iteration 1

Display the list of all Ironhackers in a table. 

You don't have to use any state for this iteration. You can get the list of users by simply typing:
```js
import users from "./users";
```

Make sure when you do this that the file  `users.json` is in `starter-code/src/users.json`.

This is a screenshot of what you can have by the end of the iteration.

![img](https://i.imgur.com/4GAZGeQ.png)

As you can see, only some users have a LinkedIn link.

### Iteration 2

Add a search bar to search by first name or last name. You should create a new state `search` for this iteration.

![img](https://i.imgur.com/IEGLJds.png)

### Iteration 3

Add 2 checkboxes to search by type: "`teacher`" or "`student`". 

![img](https://i.imgur.com/uzbjgkp.png)


### Iteration 4

Add a select to search by country.

![img](https://i.imgur.com/FmBtj4C.png)