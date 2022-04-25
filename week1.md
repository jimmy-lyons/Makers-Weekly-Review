# Week 1

## Goals - (Taken from Makers Curriculum)

By the end of the week all developers can:

* Test-drive a simple program using objects and methods
* Pair using the driver-navigator style
* Follow an effective debugging process
* Describe some basic OO principles like encapsulation, SRP


## My Responses to Goals
### Test-drive a simple program using objects and methods

*I completed this objective multiple times over this first week, in the following tasks: piggy_bank, boris_bikes and airport:*

* [airport_challenge](https://github.com/jimmy-lyons/airport_challenge.git)
* [boris_bikes](https://github.com/jimmy-lyons/Boris_Bikes.git)

*In all tasks I followed a methodology of writing unit/feature tests in IRB and/or RSpec to get a 'successfully failing' test. I would then write the minimum amount of code in my program to pass the test I had just written. I would build up the program, increasing its complexity, using this methodology and would take time to refeactor periodically.*

*I feel that I've learnt how to use some basic RSpec syntax - enough to drive simple programs. I would like to further my understanding by practising implimenting 'before' and 'context' to refactor my RSpec tests. I also would like to further my understanding of stubbing, doubles and mocking.*

*I understand the fundamentals of writing RSpec tests and can untilise the three A's to write a succinct and useful test. I understand what I need each test to do in order to drive the next feature of the code.*

### Pair using the driver-navigator style

*I had done a small amount of pair programming in the pre-course, but gained a lot more experience of it this week. I wouldn't say that I perfected the driver-navigator relationship this week, but I did find myself becoming more aware of when I wasn't practicing the technique properly. I think that I have room for imporvement in pair programming, but I think this will develop as I practice more. My goal going forward is to keep the methodology in mind and to continue to be aware if I'm being too dominant or passive. I will keep asking questions when I don't understand what my partner has done.*

### Follow an effective debugging process

*I find myself naturally following an effective debugging process. First I follow the error message and try to read the code thoroughly to understand what is happening at each step. When I can't find the issue, I tend to try to get visability on the problem. I have found IRB very helpful for this.*

### Describe some basic OO principles like encapsulation, SRP

* *Encapsulation is where data and methods can be grouped together inside of a class. Issues with encapsulation can include when access is restricted to data within a class. You need an attribute accessor to read or write this data.* 
* *SRP (Single-Responsibility Principle) dictates that each thing in your program should only be responsible for one function. For me in practice this week, this meant that all methods should be refactored so that they were only performing one function. Where secondary functions were required to get the method to work, these should have been refactored into private methods.*