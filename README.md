# cs2204-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CS2204 Homework 2 Solved](https://www.ankitcodinghub.com/product/cs2204-homework-group-assignments-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116682&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2204 Homework 2  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Objectives

Learn to read existing Python code

Find and correct syntax errors in code

Find and correct logical errors in code Understand PEP 8 style requirements

Background

Also, the results of the program is supposed to look like this

Student One

Student Two …

Student Three

Student Four …

Student Five

Student Six …

Tasks

1. There are a few syntax errors in the provided script ( group_assignment.py ). You have to x this rst (30 pts)

2. There is a logical error in the program. It does not implement the assignment properly (see the requirements, above). Understand and x this problem by modifying the existing code, or – if it feels easier – by completely rewriting the algorithm (50 pts)

3. Make sure, you maintain the proper output format. The current script might do this right, just make sure you do not ruin it. (20 pts)

4. There are several PEP 8 style errors in the code. Fix these, otherwise you will be penalized.

Hints

There are a few constructs in the code, which might be new to you. While most of these are not critical to understand to x the program, here are some brief explanations (we learn about these more, later).

random.sample(population, k) : it picks k number of samples (without replacement) from population . Both population and the returned samples are Python lists. If k equals to the

length of the population list, the result is effectively a randomly shu ed version of that list.

Example:

1from random import sample

2

3vals = [1, 2, 3, 4, 5, 6, 7]

4shuffled = sample(vals, len(vals)) 5print(shuffled)

zip(list_a, list_b, …) : returns a new list (more properly, an iterator object), containing

tuples by merging the original lists elementwise. The most typical use-case is with for loops, so we can iterate over the elements of multiple lists in parallel.

Examples:

1list_a = “one”, “two”, “three”

2list_b = “uno”, “dos”, “tres”

3print(list(zip(list_a, list_b)))

1for a, b in zip(list_a, list_b): 2 print(a, “–“, b)

Grading

Penalties

Points will be deducted if you fail to set __author__ variable (-10 pts) and for each PEP 8 style errors (-1 pt for each) in your program.

Submission

Please, upload the nal version of the following le(s) (and only those le(s)) to Brightspace:

group_assignment.py
