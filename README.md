# Clean Code

# Index

1. [Clean Code](#clean-code)

# 1. Clean Code
## There Will Be Code
* Nonsense! We will never be rid of code, because code represents the details of the requirements. At some level those details cannot be ignored or abstracted; they have to be specified. And specifying requirements in such detail that a machine can execute them is programming. Such a specification is code.
* Remember that code is really the language in which we ultimately express the require- ments. We may create languages that are closer to the requirements. We may create tools that help us parse and assemble those requirements into formal structures. But we will never eliminate necessary precision—so there will always be code.

## Bad Code
* We know good code matters because we’ve had to deal for so long with its lack.
* Bad code brought a company down.
* Have you ever been significantly impeded by bad code? If you are a programmer of any experience then you’ve felt this impediment many times.
Of course you have been impeded by bad code. So then—why did you write it? Were you trying to go fast? Were you in a rush? 

## The Total Cost of Owing a Mess
* Over the span of a year or two, teams that were moving very fast at the beginning of a project can find themselves moving at a snail’s pace. Every change they make to the code breaks two or three other parts of the code. No change is trivial.
* Every addition or modification to the system requires that the tangles, twists, and knots be “understood” so that more tangles, twists, and knots can be added. Over time the mess becomes so big and so deep and so tall, they can not clean it up. There is no way at all.
* As the mess builds, the productivity of the team continues to decrease, asymptotically approaching zero.

### The Grand Redesign in the Sky
* Spending time keeping your code clean is not just cost effective; it’s a matter of professional survival.

### Attitude
* Why does this happen to code? Why does good code rot so quickly into bad code? We have lots of explanations for it. We complain that the requirements changed in ways that thwart the original design. We bemoan the schedules that were too tight to do things right. We blather about stupid managers and intolerant customers and useless marketing types and telephone sanitizers. But the fault, dear Dilbert, is not in our stars, but in ourselves. We are unprofessional.
* We are deeply complicit in the planning of the project and share a great deal of the responsibility for any failures; especially if those failures have to do with bad code!
* Most managers want good code, even when they are obsessing about the schedule. They may defend the schedule and requirements with passion; but that’s their job. It’s your job to defend the code with equal passion.
* To drive this point home, what if you were a doctor and had a patient who demanded that you stop all the silly hand-washing in preparation for surgery because it was taking too much time?2 Clearly the patient is the boss; and yet the doctor should absolutely refuse to comply. Why? Because the doctor knows more than the patient about the risks of dis- ease and infection. It would be unprofessional (never mind criminal) for the doctor to comply with the patient.
So too it is unprofessional for programmers to bend to the will of managers who don’t understand the risks of making messes.

### The Primal Conundrum
* True professionals know that the second part of the conundrum is wrong. 
You will _not_ make the deadline by making the mess. Indeed, _the mess will_ slow you down instantly, and will force you to miss the deadline. 
The _only way_ to make the deadline—the only way to go fast—is to _keep the code as clean as possible_ at all times.

### The Art of Clean Code?
* The bad news is that _writing clean code is a lot like painting a picture_. 
_Most_ of us _know when a picture is painted well or badly_. 
But _being able to recognize good art from bad does not mean that we know how to paint_. 
So too being able to recognize clean code from dirty code does not mean that we know how to write clean code!
* A programmer without “code-sense” can look at a messy module and recognize the mess but will have no idea what to do about it.
* A programmer with “code-sense” will look at a messy module and see options and variations. The “code-sense” will help that pro- grammer choose the best variation and guide him or her to plot a sequence of behavior preserving transformations to get from here to there.

## We are Authors
* The `@author` field of a Javadoc tells us who we are. We are authors. And one thing about authors is that they have readers.
* Indeed, authors are responsible for communicating well with their readers.
* The next time you write a line of code, remember you are an author, writing for readers who will judge your effort.