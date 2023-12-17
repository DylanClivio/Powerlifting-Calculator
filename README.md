(Summarize the project and what problem it was solving)
The prjoect was made using Java. I am more comfortable with Java but I implemented things that we went over throughout this course in C++.
This program allows a user to use one of their powerlifting PRs (personal records) to calculate their theoretical stregth in other lifts. 
For example. If you bench-press 225lb, you can use this lift to calculate your estimated strength in the Squat and Deadlift.
This is calculated using a simple formula and ratio that is representative of the majority of powerlifters.

(What did you do particularly well?)
I made my code a bit overly complex for the sake of demonstrating proficiency in certain aspects of java that wouldn’t otherwise be necessary in my simple program.

(Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?)
I could enhance this code by making it more efficient. As you can see with the pseudocode, the actual algorithm the program uses to calculate its answers is pretty simple.
I definitely did not need to make a seperate "Lifter" class for these calculations but I did because I thought it would be fun.

(Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?)
The most difficult part of this program was figuring out how to format the communication with the user. I wasn't sure how I wanted the program to prompt the user.
I decided to do the same thing I've done in similiar projects where I prompt the user for their name and then associate each lift with a number that the user can choose from.

(What skills from this project will be particularly transferable to other projects or course work?)
I think the use of loops is something that was good to practice because its done pretty similiarly in a number of programming languages.

(How did you make this program maintainable, readable, and adaptable?)
I made this program with simplicity in mind. I think having a simple program allows for greater flexibility if I wanted to take this program and adapt it to solving other problems.
The organization for the code has a good foundation if I wanted to reuse it for something else.

Program start
Collect users name
Collect users lift
Collect users lift weight in lbs
If lift = Benchpress
        Squat = (benchpress/3)* 4
        Deadlift = (benchpress/3)* 5
If lift = Squat
        Benchpress = (squat/4)* 3
        Deadlift = (squat/4) * 5
If lift = Deadlift
        Benchpress = (deadlift/5)* 3
        Squat = (deadlift/5)* 3

Array = (benchpress, squat, deadlift)
Declare sum of lifts
