# comp311-lab-6--procedure-calls-and-sorting-strings-solved
**TO GET THIS SOLUTION VISIT:** [Comp311 Lab 6- Procedure calls and sorting strings Solved](https://mantutor.com/product/comp311-lab-6-procedure-calls-and-sorting-strings-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115136&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp311 Lab 6- Procedure calls and sorting strings Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Background Information

Now that you have gotten used to looping and arrays in MIPS, we will test your mastery further by asking you to work with strings! As you surely learned through your experience in C, strings are more complicated to sort than numbers. To aid you in this task, you will write your first procedures in MIPS, which will help you compare and swap your strings.

Coding Problem

In this assignment, you will write a MIPS program that loads strings into an array, sorts them in alphabetical order (in terms of ASCII character code), and output your sorted array of strings, line by line. In particular, the step-by-step procedure is:

1. Prompt the user to enter a number between 1 and 20 (inclusive), which will be the size of the array in question.

2. Read in the string that should be stored at every index of the array.

4. Prompt the user to enter the value of the string that they would like to search for within the array.

5. Implement a bubble sort that will order the strings in the array in alphabetical order.

6. You will need to write two procedures to accommodate this functionality. The specifics of these two procedures are outlined in the Required Procedures section below.

7. Output your sorted array of strings in alphabetical order.

8. Terminate the program.

Required Procedures

lab_swap_strings

Arguments: $a0 = starting address of strA, $a1 = starting address of strB.

This procedure will be used in Step 4 during your sort.

This procedures switches the contents of two elements of your array. For example, if the string starting at $a0 = “hello” and the string starting at $a1 = “goodbye”, then lab_swap_strings($a0, $a1) will result in the string starting at address $a0 = “goodbye” and the string starting at address $a1 = “hello”.

To accomplish this, you should swap each character between both strings. Note: ensure the swapped strings are null terminated correctly after the swap.

lab_compare_strings

Arguments: $a0 = starting address of strA, $a1 = starting address of strB.

Return value: $v0 should contain either -1, 0, or 1 depending on the result of the string comparison.

This function will be used for sorting in Step 4.

The return value stored in $v0 should be -1, 0, or 1 depending on whether strA &lt; strB, strA == strB, or strA &gt; strB. Return -1 if strA &lt; strB.

Return 0 if strA == strB. Return 1 if strA &gt; strB.

In order to determine which string is “greater” than another alphabetically, utilize their ASCII character to integer encoding values. Compare character-by-character starting with the beginning of each string, and continue until you find a differing character or reach the end of one of the strings See the following examples:

apple &lt; apply. The first four characters are the same, and then e &lt; y since the ASCII integer value for character e is 101 and the ASCII integer value for character y is 121. Return -1.

apple &gt; applY. The first four characters are the same, and then e &gt; Y since the ASCII integer value for character e is 101 and the ASCII integer value for character Y is 89. Return 1. apple == apple. Each character is the same. Return 0. app &lt; apple. The first three characters are the same, and then there are no more characters left to compare. This technically means that the fourth character of â€œappâ€ is the null terminator, which has an ASCII integer value of 0 while the ASCII integer value for character l is 108. 0 &lt; 108, so we return -1.

Assignment Instructions

Please download the provided lab6.asm le from the repo.

For ease of use, all portions of the code relating to I/O have already been provided for you and you should not modify them. Additionally, numerous comments are provided which will guide you through the assignment.

Please complete the MIPS code in the three TODO sections:

PART 1 in which you will complete the body of the main procedure.

PART 2 in which you will complete the body of the string swap procedure.

PART 3 in which you will complete the body of the string compare procedure.

Example I/O

The following consist of two different input and output case examples that demonstrate the expected output for the above program.

Example 1 Enter array size [between 1 and 20]: 5 A[0] = Super Mario Galaxy A[1] = Wii Sports A[2] = Animal

Crossing City Folk A[3] = Legend of Zelda Skyward Sword A[4] = Donkey Kong Country Returns The sorted array of strings is… A[0] = Animal Crossing City Folk A[1] = Donkey Kong Country Returns A[2] = Legend of Zelda Skyward Sword A[3] = Super Mario Galaxy A[4] = Wii Sports

Example 2 Enter array size [between 1 and 20]: 10 A[0] = iPhone A[1] = Nintendo Switch A[2] = Apple Pencil A[3]

= Fitbit A[4] = MacBook A[5] = iPad A[6] = Samsung Galaxy A[7] = Thinkpad A[8] = amazon Alexa A[9] = Surface

Pro The sorted array of strings is… A[0] = Apple Pencil A[1] = Fitbit A[2] = Macbook A[3] = Nintendo Switch A[4] = Samsung Galaxy A[5] = Surface Pro A[6] = Thinkpad A[7] = amazon Alexa A[8] = iPad A[9] = iPhone

Note that lowercase characters have greater ASCII values than uppercase characters.

Program Specications

Exception / Error handling is not required. That is, assume only valid values are entered by the user. Valid values consist of strings of 100 characters or less.

Important:

The input and output must be the same as the examples provided above, in terms of: spelling, spacing, cases, etc.

We will use an auto-grader that compares your input-output solution with the correct one. You will lose points if they are formatted differently.

Assignment Submission and Grading Rubric

Assignment submissions will be made through GradeScope.

1. Submit modifications using the commit Github Desktop instructions.

2. Update remote (origin) repository using the push Github Desktop instructions.

3. Go to the COMP 311 course in GradeScope and click on the assignment called Lab 06.

5. You should see a list of your public repositories. Select the one named lab-06-yourname and submit it.

6. Your assignment should be autograded within a few seconds and you will receive feedback.
