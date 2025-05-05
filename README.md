# cse344-homework-3-semaphores-solved
**TO GET THIS SOLUTION VISIT:** [CSE344 Homework 3-Semaphores Solved](https://www.ankitcodinghub.com/product/cse344-homework-3-semaphores-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94782&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE344 Homework 3-Semaphores Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Semaphores

</div>
</div>
<div class="layoutArea">
<div class="column">
You will prepare a small bakers simulation inspired by a classic synchronization problem. Let’s assume for the sake of simplicity that one needs exactly 4 ingredients for preparing güllaç:

– milk (M)

– flour (F)

– walnuts (W)

– and sugar (S).

6 x Chef

There are 6 chefs in the main street of Gebze, and each has an endless supply of two distinct ingredients and lacks the remaining two:

chef0 has an endless supply of milk and flour but lacks walnuts and sugar, chef1 has an endless supply of milk and sugar but lacks flour and walnuts, chef2 has an endless supply of milk and walnuts but lacks sugar and flour, chef3 has an endless supply of sugar and walnuts but lacks milk and flour, chef4 has an endless supply of sugar and flour but lacks milk and walnuts, chef5 has an endless supply of flour and walnuts but lacks sugar and milk.

Every chef sits in front of her/his store and waits for the remaining two ingredients to arrive in order to go and prepare güllaç. Once the güllaç is ready they deliver it to the wholesaler and continue to wait for more ingredients. In case of termination, each chef process will return (and by “return” I actually mean return, not print on screen) the total number of desserts it has prepared so far.

1 x Wholesaler

There is also a wholesaler that every once in a while delivers two distinct ingredients out of the four to the street of the chefs, lets the chefs know that the ingredients have arrived and then waits for the dessert to be ready.

to

Once the güllaç is ready, the wholesaler takes it for sale and the chefs must wait again for the next visit of the wholesaler.

The wholesaler will read the ingredients to deliver from an input file containing two capital letters at each line, representing the ingredients to deliver; e.g.

MS

FM

WS SM etc

Assume the file has valid content and at least 1 row. The ingredients will be stored in a character array taking place in a shared memory segment; if the wholesaler for instance delivers SM, the array will contain ‘S’ and ‘M’. After the wholesaler is done (i.e. he has no more ingredients to

</div>
</div>
<div class="layoutArea">
<div class="column">
April 20th, 2022

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
However, do not assume that

</div>
</div>
<div class="layoutArea">
<div class="column">
the wholesaler knows which chef needs which ingredients

</div>
</div>
<div class="layoutArea">
<div class="column">
. So do

</div>
</div>
<div class="layoutArea">
<div class="column">
not make the mistake of signaling

</div>
</div>
<div class="layoutArea">
<div class="column">
directly from the wholesaler only the chef corresponding

</div>
</div>
<div class="layoutArea">
<div class="column">
the delivered ingredients. Example: if the wholesaler delivers F and M, don’t just signal/sem_post

</div>
</div>
<div class="layoutArea">
<div class="column">
the chef waiting for F and M.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
deliver, he must notify the chefs that the procedure is over – how? That’s up tp you.) It will collect the return values of the chef processes, and print the total number of desserts delivered to him.

How

You will implement the program as the chefs and the wholesaler in the form of 6+1 processes that print on screen their activities. You will implement two version of the program, one solving it with named semaphores and another solving it with unnamed semaphores.

<pre>                    ./hw3named -i inputFilePath -n name
                        ./hw3unnamed -i inputFilePath
</pre>
-i: denotes the input file path (absolute or relative)

hw3named: must use named semaphores for synchronization (you can include additional args if necessary).

hw3unnamed: must use unnamed semaphores for synchronization.

Output

Chefs (print the contents of the character array containing the ingredients at the end of every output line):

Initially (replace the bold parts; e.g. i becomes the chef id, ingredient becomes Milk, etc): chefi (pid XYZ) is waiting for ingredient1 and ingredient2

After obtaining the ingredients (replace the bold parts): chefi (pid XYZ) has taken the ingredient1 chefi (pid XYZ) has taken the ingredient2 chefi (pid XYZ) is preparing the dessert chefi (pid XYZ) has delivered the dessert

At exit (replace the bold parts): chefi (pid XYZ) is exiting

The wholesaler (replace the bold parts):

the wholesaler (pid XYZ) delivers ingredient1 and ingredient2 the wholesaler (pid XYZ) is waiting for the dessert

the wholesaler (pid XYZ) has obtained the dessert and left the wholesaler (pid XYZ) is done (total desserts: 34)

Evaluation rules

1) Compilation error: grade set to 1; if the error is resolved during the demo, then evaluation continues.

2) Compilation warning (with respect to the -Wall flag); -1 for every warning until 10. -20 points if there are more than 10 warnings; no chance of correction at demo.

3) No makefile: -30

4) No pdf report submitted (or submitted but insufficient, e.g. 3 lines of text with no design explanation, etc): -20. Other file formats are not admissible.

5) If the required command line arguments are missing/invalid, your program must print usage information and exit. Otherwise: -10

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6) The program crashes or doesn’t produce the expected output with valid input: -50 for each of the two versions.

7) The program doesn’t satisfy a requirement: -100

8) Presence of memory leak (regardless of amount – checked with valgrind) -30

9) Late submissions will not be accepted

10) In case of an arbitrary error, exit by printing to stderr a nicely formatted informative message. Otherwise: -10

11) Cleanup after the children processes, no zombie processes, -50 otherwise.

Is my homework submission valid?

It is valid if given a correct input file, it creates all necessary processes.

</div>
</div>
</div>
