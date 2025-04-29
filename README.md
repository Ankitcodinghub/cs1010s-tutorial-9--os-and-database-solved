# cs1010s-tutorial-9--os-and-database-solved
**TO GET THIS SOLUTION VISIT:** [CS1010S Tutorial 9- OS and Database Solved](https://www.ankitcodinghub.com/product/cs1010s-tutorial-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115106&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1010S  Tutorial 9- OS and Database Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Brief Look at OS and Database

• Input/Output (IO)-Activity: e.g. waiting for user input ( scanf() ), reading from a file

( fgets() ), printing information on screen ( printf() ), etc. OR

• CPU-Activity: e.g. performing heavy calculation.

(a) Discuss the behavior of the following processes:

i. The “desktop” interface commonly seen in most modern OSes.

ii. The “Sieve of Erathoses” on a HUGE array (say 500 million entries).

(b) On a system with an active user (e.g. you are coding actively on your laptop), discuss how should the OS prioritizes processes based on their behavior. As a guide, you should be thinking about, “if a process P is doing a lot I/O activity, then . . . ”. You can also use (a) as a guide.

2. [File Management] Let us write a simple C program simulate how the OS uses File Allocation Table (FAT) to find out the disk blocks used by a file.

You are given an input file which contains the entries of a FAT table. The first number in the file indicate the size S of the FAT, the subsequent S integers are the content of the FAT.

For example, the “sample_fat.txt” contains:

Write a program that:

(a) Ask user for the input file name FN .

(b) Reads from the file FN and initializes the FAT. You can assume that the largest FAT has 128 entries.

(c) Repeatedly reads a single integer X from user, then:

i. Print the disk block number D at FAT[ X ]

1

ii. Set X = D , then repeat step i, until D is -1

Below is a sample execution session (user input in bold):

File name: fat32.txt //Sample input file is “fat32.txt”

FAT size is 32 //Show the size of FAT read from fat32.txt

0[-1] //Print the FAT entries after storing them.

1[13]

2[ 6]

…

31[16] //This is the start of step (c)

1 13 //File at location 1 continues with block 13

5

5 15 30 20 21 23 8 0

&lt;ctrl-d&gt; //to stop the program

You are free to design the program in any way. (If you are unsure where to start, take a look at the last page of this tutorial for some suggestions).

3. [Database] Given the following person table:

name height weight age IQ

Abigail 152.5 55 17 180

Trigun 175.4 85 25 135

Shelcard 195.0 120 55 120

Maurice 145.4 48 46 108

Liam 170.5 60 18 100

(a) Give the SQL statement to create the table above. You can make reasonable assumptions on the datatype of each column.

(b) Give the SQL statements to insert the 5 rows above.

(c) Give the SQL statements to find out the following information. Note that you are free to make reasonable assumptions.

iii. The Joes (not tall, not bulky, not genius, i.e. average person)

Hints / Suggestions for Question 2 (Don’t look if you want to challenge yourself)

1. The FAT is simply an integer array.

2. Write the following functions as a start:

(a) int readFAT( FILE* input, int fat[])

• Read the FAT entries from input

• Output: the array fat[] contains the FAT entries read

• Return: the size of the fat[]

(b) void printFAT( int fat[], int size)

• Print the FAT entries in the form of “idx [content]”

• The size of the FAT array is given as size.

(c) void printFileAt( int fat[], int start)

• Print the disk blocks used by the “file” starting at block start

3. The main loop for step (c) can be achieved via: while ( scanf(“%d”, &amp;start) == 1) { … }

This loop will read until the user press &lt;ctrl-D&gt; which sends an “EOF” signal to the program.
