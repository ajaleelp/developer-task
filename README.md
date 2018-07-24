# Web Developer Task

## Emoji Search

All the companies use feedback forms to collect the user feedback on the products.

Most of these text editors in the feedback forms are way old and does not support emoji’s

Users like to express their reactions with emoji in these feedback forms.

We’d like you to build a text editor that will let users express more using emoji’s inline.

### Task 1: Write a function to search for emoji

Create a function that will search for emoji in the `assets/emojiList.json` file when you type a word starting with a colon

        Example :happy

Required:

  1, The function should return a list of emoji's with the title

  2, The function should search the title and keyword(json file) to find the match.

  3, Null responses should be handled with an appropriate message

### Task 2: Build an Emoji Search API

Use the function written in task 1 to create an API that will enable users to add a favorite tag for the selected emoji.

Required

  1, GET request that will return a list of emoji's
    
  2, POST request that will allow users to add a favorite tag for selected emoji


### Task 3: Build the front-end, consuming the API _[change title]_

The text editor in the task should 

1, Start listing the emoji's when the user starts typing with a colon

2, Replace the text with the emoji when user select an emoji



### Additional Task During Pair-Programming Session