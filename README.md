# comp250---solved
**TO GET THIS SOLUTION VISIT:** [COMP250 – Solved](https://www.ankitcodinghub.com/product/comp250-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110745&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP250 -  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Prepared by Prof. Michael Langer

General Instructions

• The T.A.s handing this assignment are:

o Abhisek (abhisek.konar@mail.mcgill.ca) o Brennan (brennan.nichyporuk@mail.mcgill.ca) o Charles (peiyong.liu@mail.mcgill.ca) o Akshatha (akshatha.arodi@mail.mcgill.ca) o Anand (anand.kamat@mail.mcgill.ca)

• Do not change any of the starter code that is given to you except (1) Add code only instructed, namely in the “ADD CODE HERE” block, and (2) add helper methods if you need them.

• You can use whatever package name you like. (Unlike in Assignment 1, here you do not need to use the default package in Eclipse.) Make sure the package name is the first line of the file. The grader code will ignore your package name declaration. To learn more about packages, see the Java tutorials.

• The starter code includes a tester class that you can run to test if your methods are correct. Your code will be tested on a more extensive and challenging set of examples. We encourage you modify this tester code and to share your tester code with other students on the discussion board. You do not need to hand in your tester code.

Your code will be tested on valid inputs only. For example, “12000101” is an invalid base 2 representation. Another example is “0004753” which is invalid because of the leading 0’s.

Submission Instructions:

Submit a single zipped file A2.zip that contains the modified MyBigInteger.java file to the myCourses assignment A2 folder. Do not just submit the java file on its own because this will cause problems with Minerva when we download the files. Include your name and student ID number within the comment at the top of the MyBigInteger.java file.

If you submit late, then you will receive a late penalty. It is your responsibility to submit correctly in the first place.

We will remove all package declarations and import statements and add back only the imports that are given in the starter code. Therefore if you use other imports, then your code will not compile when we test it.

You will receive 0 for a submission that does not compile.

If you have any issues that you wish the TAs (graders) to be aware of, include them in the comment field in mycourses along with your submission. Otherwise leave the mycourses comment field blank. Please do not write things like “Here is my submission for A1” with student name and ID number. We already know this info.

Late assignment policy:

Late assignments will be accepted up to only 2 days late and will be penalized by 10 points per day. If you submit one minute late, this is equivalent to submitting 23 hours and 59 minutes late, etc. So make sure you are nowhere near that threshold when you submit.

Introduction

Computers represent integers as binary numbers (base 2), typically using a relatively small number of bits e.g. 16, 32, or 64. In Java, integer primitive types short, int and long use these fixed number of bits, respectively. For certain applications such as in cryptography, however, one needs to work with very large positive numbers and do arithmetic operations on them. For such applications, it is necessary to go beyond the primitive type representation.

How can one represent a very large positive integer? For any base, one can represent any positive integer m uniquely as the sum of powers of the base. This defines a polynomial:

𝑛−1

𝑚 = ∑ 𝑎𝑖 𝑏𝑎𝑠𝑒𝑖 = 𝑎0 + 𝑎1 𝑏𝑎𝑠𝑒 + 𝑎2 𝑏𝑎𝑠𝑒2 + … + 𝑎𝑛−1𝑏𝑎𝑠𝑒𝑛−1

𝑖=0

where 𝑏𝑎𝑠𝑒 is some number (e.g. 2, 10), and the coefficients 𝑎𝑖 satisfy 0 ≤ 𝑎𝑖 &lt; 𝑏𝑎𝑠𝑒 and 𝑎𝑛−1 &gt; 0 for any 𝑚 &gt; 0. [ADDED: Nov 14] Note that the condition 𝑎𝑛−1 &gt; 0 is required for a unique representation. Also note that when a positive integer m is represented as a list of coefficients (𝑎0 ,𝑎1 ,𝑎2 , … 𝑎𝑛−1), the ordering of the coefficients is opposite to the usual ordering that we use to write out the number, namely 𝑎𝑛−1 … 𝑎2 ,𝑎1 ,𝑎0 . For example, the integer 35461 is represented as a list of coefficients (1,6,4,5,3). Note 𝑚 = 0 is represented as (0).

In this assignment, we will work with arithmetic operations on large positive integers. Java has built-in class for doing so, called BigInteger. You are not allowed to use this class. Instead you will work with a partially implemented class MyBigInteger. Whereas the Java class BigInteger can be used for negative and positive, our class MyBigInteger only allows us to represent non-negative integers.

The MyBigInteger class has two fields: base and coefficients. The base field is an int with values in {2, 3, …, 10}. We could have allowed for larger bases but that would have required using special symbols for the numbers greater than 10, e.g. as in hexadecimal, and these extra symbols would just complicate things. The coefficients field is an ArrayList&lt;Integer&gt; which represents the 𝑎𝑖 values above.

We include several helper methods as well.

• timesBaseToThePower()

• mod()

• clone()

• compareTo()

• toString()

• primesToN().

For all of the methods, you should read the comments in the code to see what the methods do.

You are also given code stubs of the methods that you are required to implement, and a Tester class with a simple example. Feel free to modify this Tester class as you wish.

What will you learn by doing this assignment?

There are several learning goals for this assignment.

Second, the assignment will help understand how to represent numbers in different bases. The definition of this representation was given on the previous page. But there are some subtleties in that definition that arise. For example, converting a number from one base representation to another can be tricky since the base itself that is used for the conversion method is a number that needs to be represented in some base.

Third, one of your tasks is to work with prime numbers. Although prime numbers will arise only occasionally in this course, they are extremely important in some application areas of computer science such as in cryptography. Those of you taking MATH 240 Discrete Structures 1 or MATH 346 Number Theory will be working with prime numbers. Your experience here should complement what you will learn in those courses.

Fourth, you will get some experience working with lists. In particular, you will use methods from the Java ArrayList class.

Lastly, this assignment will also give you more practice programming in Java! Although COMP 250 is not a course about how to program, programming is a core part of computer science and the more practice you get, the better you will become at it.

Your Tasks

Implement the following methods. The signatures of the methods are given in the starter code. You are not allowed to change the signatures.

Question 1: dividedBy (30 points)

Implement the dividedBy method using long division. An example of long division is given in the lecture 1 notes PDF. This example gives the main idea of how the algorithm works.

Before attempting to write any code, study the implementations of the plus(), times(), minus() and the various helper methods that are given to you. Make sure you understand about how they work, since similar ideas can be used to implement dividedBy().

We will test your dividedBy() method on moderate size numbers, with the intention of detecting relatively slow implementation. The time complexity of your dividedBy() method should be 𝑶(𝑵𝟐) whereas the time complexity of slowdividedBy() is 𝑶(𝒃𝒂𝒔𝒆𝑵), where 𝑵 is the number of digits of the dividend. If your implementation runs extremely slowly, e.g. if you were to just copy the code from the slowdividedBy() method, then you will not receive any points for this question.

Question 2: Base conversion (40 points)

Implement a method convert( int newBase ) that converts a MyBigInteger object from one base to another. The convert method is called by a MyBigInteger object that represents a positive integer in some base, and returns the same positive integer represented in the new base. The bases can be any of {2, 3, 4, …, 10}.

Begin by testing your methods on numbers that are written in base 10. Once that is working, test it on combinations of different bases from 2 to 10. Use an online converter to verify your answers e.g. http://www.cleavebooks.co.uk/scol/calnumba.htm for small numbers. Your code will be tested on very big numbers.

Question 3: Prime Numbers (30 points)

A prime number is a positive integer 𝑚 &gt; 1 whose factors are only 1 and itself. So, a number 𝑚 is prime if dividing it by any number in {2, …, 𝑚 − 1} produces a non-zero remainder. By definition, 𝑚 = 1 is not prime.

Any positive integer 𝑚 can be written uniquely as a product of primes:

𝑚 = 𝑝1𝛼1𝑝2𝛼2 … 𝑝𝑘𝛼𝑘

where 𝑝𝑖 are called prime factors and 𝛼𝑖 &gt; 0 are the non-zero orders of the prime factors. For example, 24 = 23 3 .

One can determine if a number 𝑚 is prime by brute force checking all the integers from 2 up to 𝑚 − 1 to see if any of them divides evenly with no remainder. However, this method is very inefficient. It is enough to check potential factors less than or equal to . Think why.1 Your task is to implement a method primeFactors().

The method must return an ArrayList&lt;MyBigInteger&gt; whose elements are the prime factors of 𝑚, where 𝑚 is ‘this’ MyBigInteger object. The number of copies of the prime factor in the returned list must be the order of that prime factor, and the prime factors in the list must go from smallest to largest. For example, if 𝑚 = 24, the method must return a list (2, 2, 2, 3). If 𝑚 is prime or if the method cannot find any prime factors, then the returned list will just contain one element, namely, the returned list will be (𝑚). You do not need to handle the case 𝑚 = 0,1.

Other Notes

Eclipse does proper indentation automatically, as do other excellent IDEs. So please use it.

Be sure to use Java naming conventions for variable names. In particular, variables and method names should be mixed case with a lower case first letter.

Get started early! Have fun! Good luck!
