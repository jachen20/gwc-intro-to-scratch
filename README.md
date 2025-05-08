# Intro to Scratch!

## What is Scratch?

Scratch is what I would call a block based programming language. A single block can contain a instruction to say "hello" or to walk 5 blocks. When you drag and connect these blocks together, you can create a list of instructions to give to the community and that's what writing code is all about! It's an interactive and fun way to code! You can create digital stories, games, and animation with Scratch.

Here's the Scratch website: https://scratch.mit.edu/

## Signing up for Scratch

First, we'll set up an account with Scratch so you can come back to your projects anytime!

![join scratch](https://github.com/user-attachments/assets/cb240225-a824-435a-bf0f-5097b56946de)

Next, click the create button to create your very first project!

![image](https://github.com/user-attachments/assets/eeeb317e-d1ff-4d4a-a10e-c12a1441a073)

Next, we'll go through a tutorial to show you what you can do with Scratch! A lot of the steps are taken from Stanford's Introduction to Computer Science class, specifically this lesson: https://cs50.harvard.edu/x/2025/weeks/0/.

## Making the cat say, "Hello, world!"

You should see a green flag and a red stop button above the cat. 

![image](https://github.com/user-attachments/assets/5791f4f2-1835-4179-a5d8-b2f3dda539b2)

The green flag stands for GO and the red stop stands for STOP. We want to make it so when we click the green flag, the cat says "hello, world". Go to the Events section and drag this block into the center: 

![image](https://github.com/user-attachments/assets/9257534f-d470-435f-b4dc-11fadb401720)

Next, go to the Looks section and drag this block right underneath the first one:

![image](https://github.com/user-attachments/assets/926c852d-4d7f-4ccf-9a9f-f9419b64b9fd)

We'll change "Hello!" into "Hello, world!"

![image](https://github.com/user-attachments/assets/2722f9c1-a052-4154-888c-52a32f0aaeff)

Press the green flag, and your cat should say "Hello, world!"

![image](https://github.com/user-attachments/assets/10882aec-c36e-4534-a982-8d22b9a63b7d)

## Teaching the cat your name!

Let's remove all of the blocks except for the first one we added, and head to the Sensing section. Drag this block underneath the first one:

![image](https://github.com/user-attachments/assets/6f80cba5-72a6-47b5-af40-2cfef2c0935b)

Try running the program:

![image](https://github.com/user-attachments/assets/17c70fae-3cac-47ad-8847-e4f22519e9ac)

We can type our name here, but once we enter, nothing really happens. That's because your name will be stored in a variable named *answer*. Let's drag the say hello block in the Looks section once again, and this time under the Sensing section, we will drag answer into the say block.

![image](https://github.com/user-attachments/assets/43bb27b5-787d-4d7c-a375-0d8b46cbfd2c)

Run the program again, and once you type your name in and press enter, the cat should repeat back your name to you. We're almost there, but we want to hear something like "Hello, Jacqui" instead of just "Jacqui". Luckily for us, we can use the join button in the Operators section! We replace answer with a combination of "Hello, " and answer:

![image](https://github.com/user-attachments/assets/28763978-329b-4e80-b7a6-a43aa01a4ac4)

Run it again, and you should get something like this: 

![image](https://github.com/user-attachments/assets/a6111e48-d1a3-4fb7-acaa-00b56648c22c)

Awesome! Let's do one final step!

## Playing with Text to Speech

![image](https://github.com/user-attachments/assets/e8e1b189-3de6-4db5-b775-1c1e9b8cc476)
