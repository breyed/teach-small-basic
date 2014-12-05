# Teach Small Basic

**Programs for teaching Small Basic to beginning programmers**

Students start with "recipes", which are Small Basic programs consisting step-by-step English instructions in the form of program comments. The teacher helps the students learn to create actual programs using the recipes as a starting point. As the programs become more advanced, the recipes become more abstract, moving to higher level descriptions of multiple lines of code and then to summaries of entire methods.

The programs are organized into a series of 10 lessons. The amount of material introduced in each lesson is designed for 90 minutes of instruction per lesson (a 15 minute break is recommended).

There are Small Basic files for recipes and finished programs, some with multiple iterations. Teachers should feel free to help the class make more enhancements as a group and to encourage students to invent still more enhancements individually. Using iterations helps reinforce concepts while exemplifying the creative potential of programming. Some recipes leave room for improvement, which the teacher can help students discover, for example input error checking.

The file name convention is like this:

* `Bubbles 1 Recipe.sb` - the recipe for the first iteration of the Bubbles program
* `Bubbles 1.sb` - the completed Bubbles program (first iteration)
* `Bubbles 2 Recipe.sb` - the recipe for another iteration of the Bubbles program
* `Bubbles 2.sb` - the completed Bubbles program (second iteration)


## Lessons

### Lesson 1: Square

Draws a simple square using turtle graphics.

New concepts:

* Tools
* Built-in objects, methods, and properties
* Integer variables
* "For" loops

### Lesson 2: Spiral and Simple Houses

Spiral: Draws a colorful spiral using turtle graphics.

Simple Houses: Draws houses using turtle graphics.

New concept:

* User-defined methods

### Lesson 3: Fancy Houses

Draws houses with various roof styles using turtle graphics.

New concepts:

* Nested methods
* "If" statements
* Nested "If" statements

### Lesson 4: Hi-low

Picks a number that you try to guess.

New concepts:
    
* "Else If"
* Console
* Sound

### Lesson 5: Number Guesser

Guesses a number that you pick.

New concept:

* "While" loops

### Lesson 6: Bubbles

Displays bubbles and images where you click. Try to make the Olympic rings logo.

New concepts:

* Arrays
* Events
* Mouse
* Shapes
* Images

### Lesson 7: Whack-a-Mole

See how many dots you can click before they disappear.

New concepts:

* Timer
* Screen geometry

### Lessons 8, 9, and 10: Word Guesser

You try to guess a randomly chooses a word given a definition and picture.

***NOTE:** 2014-12-04 - This program no longer works because the Small Basic functions `Network.DownloadFile` and `Flickr.GetRandomPicture` no longer work.*

New concepts:

* Grid layout
* UI Controls
* String manipulation
* Files
* Animation

As a bonus for the last lesson, a teacher can choose his favorite into application in a "real" language, and demo it to encourage the students to continue the journey.

## Call On

Often students are shy about volunteering what they know, especially when they are uncertain. The "Call On" program is a fun way to randomly choose a student to call on to answer a question. To use it, customize `Call On.sb` by changing the number of student and call items in their respective arrays to match your class, and set the name and preferred bugle call for each student.

## Small Basic resources

* [Small Basic Getting Started Guide](http://msdn.microsoft.com/en-us/beginner/hh304480.aspx)
* [Small Basic Curriculum](http://social.technet.microsoft.com/wiki/contents/articles/16982.small-basic-curriculum-online.aspx)

## Beyond Small Basic

The simplicity and minimalism of Small Basic make it well suited for beginners. Its limitations also provide healthy incentive for new programmers growing in skill to move past Small Basic. Here are some suggestions:

### Online courses
*	[Learn to Program: The Fundamentals](https://www.coursera.org/course/programming1) (Toronto)
*	[Introduction to Computer Science](https://www.edx.org/course/harvardx/harvardx-cs50x-introduction-computer-1022) (Harvard)
*	[Introduction to Computer Science](https://www.udacity.com/course/cs101) (Udacity)

### Further study
*	[C# for Sharp Kids](http://msdn.microsoft.com/en-us/beginner/bb308756.aspx) – e-Book
*	[Accelerated C# Fundamentals](http://pluralsight.com/training/Courses/TableOfContents/csharp-fundamentals) – video ([free with DreamSpark](https://www.dreamspark.com/Product/Product.aspx?productid=21))
*	[Code Rules](http://msdn.microsoft.com/en-us/beginner/bb308755.aspx) – curriculum for classroom or self-teaching Visual Basic .NET
*	[Microsoft Virtual Academy](http://www.microsoftvirtualacademy.com/)

## Acknowledgment

Thanks to the [Extend Small Basic](http://extendsmallbasic.codeplex.com) project for programs and ideas that inspired Teach Small Basic.
