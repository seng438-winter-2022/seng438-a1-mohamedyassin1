>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       | 32  |
|-----------------|---|
| Student Names:  |   |
|                 |  Benson Li      |
|                 |  Henrique Andras |
|                 |  Kevin Araujo  |
|                 |   Mohamed Yassin  |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

Before this assignment, we had an introduction to brief and exploratory testing by watching Dr. Kangsoo Kim’s lectures. For exploratory testing: Our knowledge was that it is a testing strategy in which you test the system as a “real” user would test it by creating realistic usage scenarios. There is usually no strict plan that we follow for exploratory testing. Regarding Manual Scripted testing, we know that this is a testing strategy in which there are previously written test cases and test steps in a script, often written by the tester beforehand. For manual scripted testing, it is important to follow the path laid out in the script. This is a brief summary of what we knew about exploratory and manual scripted testing before starting this assignment.

# High-level description of the exploratory testing plan

For high-level description, the system must be able to withdraw and deposit money, use authentication based on card number and pin number. As well as Display information to the user in a reasonable amount of time. We will test the login function using correct and incorrect card numbers and PINs. Getting into more detail we will test more extensively input fields such as card number and input number as well, we will explore all functionalities of the ATM including withdrawal, deposit, and from all accounts, to make sure they all work properly.
Specific examples include:
We are going to try to check if the deposits are canceled if a customer fails to deposit an envelope in the allocated time frame.

We will also test all the operator functions, such as turning the ATM on and off and checking the accuracy of the log.

We will try to enter the wrong PIN number three times to see if the card is permanently retained by the machine.

We will try all the commands in the system with various amounts of money, such as 5 bills, 10 bills, and 1000 bill transactions. We will also test using unexpected values, such as negative values, characters, and values that go beyond the integer limit such as 2,147,483,648.
Our main goal with exploratory testing is to test this software as if we were real users, and see what errors we encounter. 

We will provide invalid inputs (i.e letters or symbols to a number only input)

We will attempt to interact with buttons and inputs in between loading/processing times 


# Comparison of exploratory and manual functional testing

Exploratory function testing enables testers to find a reasonable quantity of errors fast, as you explore the program and target specific functionalities following your intuition of what might break. This method comes up short in picking out the majority of errors since it follows no specific guideline but excels in giving testers a good idea of the errors on the application within a short amount of time. For manual functional testing, we test for more normal use of the system, rather than attempting to break the system in exploratory testing. This is useful for ensuring that regular functions of the system work without skipping over any important functionalities, this method, however, does not work as well for finding bugs in extreme use cases and does take a more significant amount of time compared to exploratory functional testing. 

For example: We inputted a very huge number for the card PIN, and this crashed the ATM. This is a bug that we would unlikely have found with the scripted testing, but exploratory testing made us find bugs like these. An example like this shows the difference between the types of bugs you will find in exploratory and manual scripted testing.

For manual scripting, we also got very specific bugs, such as the card numbers being different in the log and receipt, bugs such as that are quite difficult to notice with exploratory testing, as they require strong analytical skills. However, with manual scripted testing, you can find more complex bugs by following a detailed script and paying attention to the expected output.

# Notes and discussion of the peer reviews of defect reports

Looking at our peer’s defect reports, each pair thought the other pair did a good job of writing defect reports in a proper manner. The reports were written with enough clarity that we were able to recreate them without communicating with the other pairs who wrote the defect reports. Slight improvements could be made such as agreeing on a format for problem summaries, that way the look of the backlog system would be more streamlined, making it easier for developers to look through the defect reports. Regarding the bugs found, it was interesting seeing the approach our peers took when doing exploratory testing, as they used methods we may not have thought of, and likewise for the other pair. Overall, everyone agreed on the defects found and we are satisfied with our work.

# How the pair testing was managed and team work/effort was divided 

We had our group split up into pairs so we could talk separately in a voice call. In the pairs, we assigned one person for bug testing and the other for writing the bug reports. This was done so that we could effectively go through our bug testing plan without any overlap and we could be consistent with our methodologies for both testing and writing reports. 

# Difficulties encountered, challenges overcome, and lessons learned

A difficulty we encountered, particularly in the beginning, was using the backlog software. While there were clear instructions, it is hard to synchronize the software among 4 people, especially since we are working remotely right now. However, we were able to overcome this challenge with our communication skills and we got everyone set up after a few minutes. From this, we learned to be patient when setting up software on different systems and to utilize our communication and teamwork skills to solve problems. We also enjoyed the exploratory testing approach, because it taught us to be creative when testing systems to figure out bugs, but also to still be reasonable so that we can find a variety of types of bugs. We all also gained an increased understanding of exploratory, manual scripted, and regression testing through the hands-on testing we got to do in this lab. Lastly, we learned the importance of writing clear bug reports and following templates because it made the bugs easy to reproduce and read over. 


# Comments/feedback on the lab and lab document itself

The lab document was really well made, it was very complete and featured all necessary instructions so that we were not lost in any phase. However, we would like the appendices to be labeled at the bottom. The lab itself was very interesting, we really liked how it provided an interactive and understandable experience and experience with new technologies like backlog which gave us good insight into the testing lifecycle itself.
