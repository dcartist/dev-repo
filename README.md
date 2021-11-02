# README

When it comes to programming, it's more than just syntax; it's a way of thinking, a way to look at problems and solve them. I found many developers fried and highly stressed because they aren't really in the right mindset to see problems for what they are. This page is to help those who are looking for that help with tools and techniques.

## Developer Depot

[**GitBook**](https://dcartist.gitbook.io/life-with-code/) **View**: ([https://dcartist.gitbook.io/life-with-code](https://dcartist.gitbook.io/life-with-code/)) The better visual version of this repo

#### Disclaimer:

> For those going through the general assembly's skills gym and reading this documentation, congrats on making it this far and **thank you for reading**. What I have to say is beneficial to what you are about to go through. To give you a heads up about your debugging challenge, you will have a moment where you wonder why you are given the questions and what you should do with them on earth. Well, here is one of the best ways to work through it, copy the code and run it, then fix it. Sometimes "fixing" means you actually have to build functions to get it to make it work. The only one you should **NOT** edit the original code is the last one. Work through it to find how to get to what needs to be printed out.

### Links:

[Steps to think when debugging \[click here\]](./#steps-to-debugging)\
[Debugging mindset tools \[click here\]](./#mindset-tools)

[Planning \[click here\]](planning.md)\
[Project ideas \[click here\]](project-ideas.md)\
[Resources \[click here\]](resources.md)\
[About \[click here\]](about.md)

## Debugging

### Steps to think when debugging <a href="steps-to-debugging" id="steps-to-debugging"></a>

1. Acknowledging, understanding your mistakes, and that no one is perfect.
2. **Read your error messages**, and say out loud what the error is telling you.
3. **READ DOCUMENTATION** carefully.&#x20;
4. Console log (or Print) to view what is going on with your code.
5. Think of the **simplest** ways of handling challenges.
6. **SPELLING SPELLING SPELLING** is essential; some of the biggest mistakes are caused by spelling errors. The same goes for Case Sensitivity. \
   **`Apple`** `is not the same as` **`apple`** \
   **`Apple`** `is not the same as` **`Aple`**
7. **Pseudo code**!!! Plan it out! Draw it out! Break everything down into the smallest pieces possible to make things easier on yourself when building.&#x20;
8. **Breathe!**
9. **Rubber Duckie**. The rubber duckie is having either a person or an object that you can explain your code to see where your error might be. [https://en.wikipedia.org/wiki/Rubber\_duck\_debugging](https://en.wikipedia.org/wiki/Rubber\_duck\_debugging)
10. Point and say: The _shisa kanko_ (指差喚呼) method is where you point and say what you are about to accomplish. Reading your code aloud (in detail, line by line) helps show yourself where you might have gone off the rails. [https://en.wikipedia.org/wiki/Pointing\_and\_calling](https://en.wikipedia.org/wiki/Pointing\_and\_calling)
11. **Manage your time wisely**; you can end up in tunnel vision. It's another piece of stepping back from code to be able to go further in code.
12. **Take notes**. Creating a snippet library of code you know that works will help when it comes to building. Also, going back through your notes and finding more ways to update the code will help with your development.
13. **What you think** vs. **What it is**. Going through code, there are moments where you think something happens a certain way but happens in a different way altogether. For example:

    * **Name of variables**: You could have a variable declared in one spot thinking you have used it for a certain but, but end up inserting a  different variable instead of the one you needed, which causes chaos down the line.

    **Example:**

#### Python:

```python
//Make a function that prints out the argument to the console log
apple = "Something completely else"

def thePrinter(insertData):
    print(apple) // this is the wrong variable 


thePrinter("The should print out")
```

#### Javascript

```javascript
//Make a function that prints out the argument to the console log
let apple = "Something completely else"

function thePrinter(insertData){
console.log(apple) // this is the wrong variable 
}

thePrinter("The should print out")
```

* **Objects (dictionary), arrays (lists), string, or integer?** A gotcha moment is figuring out what you are using. Ask yourself, is it an **object (dictionary), array (lists), string, or integer**? We ask this because one huge bug-causing moment is treating what we are working with incorrectly, leading to error messages.&#x20;

### Ask yourself some of these questions:

* What do I need to do?
* What data do I need to pull?
* What and where am I storing my data?
* How much do I need to pull?
* Am I actually pulling the right thing?
* What am I looking at?
* What am I doing?
* What am I supposed to do?

## Mindset tools:

When dealing with debugging, there are some mindset tools to help visualize your problems.

1. Remember, your errors are not permanent failures or make you a terrible programmer but are learning processes.&#x20;
2. In a couple of months, no one knows everything about coding; don't expect yourself to know everything.&#x20;
3. Sometimes understanding "**why**" will not happen quickly, sometimes it can take **days**, **months**, and even **years** to understand why certain things happen in code. Repeating code over time will help you to start to understand it. So don't stress yourself if you don't get it at first.
4. Senior Devs are developers who experienced more error messages than you. So be prepared for a life filled with error messages. Your code will never always be perfect but can be worked towards something incredible.
5. There will be tears. There will be moments where you want to cry, so let those tears flow.
6. **Take a break**. If things are stressful, take a break; when you haven't eaten anything, take a break.&#x20;
7. Allow yourself to be a mad scientist. When the questions come of wondering what will happen, don't stop on, just wonder. Test out the theory and document the outcome.
8. Along with the mad scientist, keep building projects (outside of Udemy/Youtube courses) to help you understand coding.
9. Telling yourself that you are terrible keeps you in a repeated mindset that you will be terrible. You will be more likely to sabotage yourself to stay in that mindset.
10. Be proud and embrace the errors. Seeing errors, not as the end of the world but a moment in code, helps bring the stress level down some to be able to focus. Also, you now know how to work through that error when it shows up again.
11. **Maya Angelou Quote**: If you don't like something, change it. If you can't change it, change your attitude. **Don't complain**.
12. You are not your code; you just built some small wonky code.
13. You are not a machine, and no one expects you to be one.
14. Always study, keep learning and keep going. Never settle. There's a reason why things constantly update!
15. **I don't know** vs. **I haven't grasped it yet**. It's a part of the growth mindset. Your mind is in constant change, especially when learning. Just like plants, we need certain things for growth, and when it comes to learning, what you say can determine how you grow.
    * Growth Mindset Cliffnotes youtube version: [https://www.youtube.com/watch?v=M1CHPnZfFmU](https://www.youtube.com/watch?v=M1CHPnZfFmU)
    * Understanding mindset: [https://www.understood.org/articles/en/growth-mindset](https://www.understood.org/articles/en/growth-mindset)
    * Growth Mindset youtube: [https://www.youtube.com/watch?v=hiiEeMN7vbQ](https://www.youtube.com/watch?v=hiiEeMN7vbQ)
16. Sleeping and allowing your body to rest are important tools in debugging.

![Maya Angelos](.gitbook/assets/maya.jpg)

### “You don’t learn to walk by following rules. You learn by doing, and by falling over”. \~ Richard Branson

Trying to become more comfortable with falling over.
