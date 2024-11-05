# **Clean Code**
This book is about a wealth of advice and lessons from Robert C.Martin of how should be a clean code while we are programming. Throughout the book, he is very clear about one thing. Always try to make our code as clear as we can, highlighting how horrible it is to work on code that's been written in a messy way. And we, the programmers,should be focusing on what the code does and not trying to understand what is going on the screen.

## *Clean code?*

The first thing Robert let us know is that it is obvious how "bad code" affects every programmer in his life and how horrible and hard it is trying to make the slightest change in a code that looks like being through a morass of tangled brambles and hidden pitfalls.
And how this affects everyone involved, lowering the productivity and morale of every person involved in the project.

So he tries to give us a solution, asking several well-known programmers about what is clean code for them. In conclusion, this are the main thing we are going to look at in our code to make it clear as water.

- It must be readable, it has to be self-explanatory and anyone who reads the code should be able to understand it and make changes without being a problem.
- It needs to be as concise as we can make it, basically simple and direct.
- Information must not be duplicated, and it should not be information that is not needed.

## *Meaningful Names*

One thing should be clear by now. We need our code to be as understanding as we can make it. And that's the reason why they talk about how we name constants, variables, functions, etc... is very important.

The names must be as revealing as possible, without having very similar or confusing names, and they have to be easy to search it. And within the measure we should try to make it as short as we can, but it is always preferable to have an understandable name than a short one. He also recommends using names that are pronounceable because it is easier to discuss with the members of our team.

The conclusion in this subject is that if someone tries to read your code and gets confused but the names you used, that's not clean code.

## *Functions*

In this section, we can retake what was said in the last chapter.  We need meaningful names!
It must be clear what the function intends to do just for the name, it can't be very complicated and should be as direct as we can make it.

Functions should be as small as we can make it and keep in mind that they have to do one thing.
As the author said on the book : "Functions should do one thing. They should do it well. They should do it only."

To achieve our objective, we need to try to have the same level of abstraction inside the functions. Is preferable to use exceptions than return error codes. It also makes it very clear that there shouldn't be a lot of arguments, the ideal range being zero between two.

## *Comments*

We need to keep in mind that comments don't make up for bad code, and it will always be better to explain ourselves with code than using a comment.

That being said, some comments are useful and beneficial. Basically, we can use it for clarification, to amplify the importance of the code, warning about something that is not finished or trying to explain our intent when you don't have a good solution.

And we always must avoid redundant, misleading and out of place comments.

## *Formating*

In this chapter, we are told how important is the formatting is for how readable will be the code.
It is important to know what size the file should be and how it will be organized, both vertically and horizontally.

For the vertical formmating, the size depends on the project. The important part here is how we display our code. We need to have spaces (blank lines) between different concepts and the lines of code that imply close association are going to be together. In the case of functions closely related to others, we want function call dependencies to point in a downward direction.

And for the horizontal formmating, the line should not be bigger than 120 characters. In this case, we will also be using blank spaces to structure the code. We have to keep in mind that overusing the blank space can be confusing and even counterproductive.

## *Error Handling* 

Even if our code is very good, sometimes we can have problems and don't be sure about how to handle them.
It will always be better to use exceptions than return errors. We can do that using "Try-Catch-Finally".
Each of the exceptions must provide enough context to determine the source and location of the problem. 