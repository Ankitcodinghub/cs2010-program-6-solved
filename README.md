# cs2010-program-6-solved
**TO GET THIS SOLUTION VISIT:** [CS2010 Program 6 Solved](https://www.ankitcodinghub.com/product/cs2010-program-purpose-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115408&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2010 Program 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Always bring to class

1. Gaddis’ book, How-to handouts from the Blackboard and your class notes.

2. This assignment sheet &amp; the grade sheet for this lab already printed out.

3. USB Flash drive(s) or other storage media.

Mandatory Instructions

Work with a partner on this program. Make sure to include the partner’s name in the grade sheet. Each of you needs to upload the zip file and provide own grade sheet.

Write a program that will check if a word or a sentence is a palindrome. A palindrome is a word (or sentence) that is the same when read front to back and back to front. For example: race car, mom, poop, etc. Sentences can also be palindromes, for example “Ten animals I slam in a net” is a palindrome.

Example:

Initial input: Ten Animals I slam in a net.

Compressed: TenAnimalsIslaminanet

Lower cased: TENANIMALSISLAMINANET Reversed: TENANIMALSISLAMINANET

The last two are the same  so this sentence is a palindrome.

You will need to set up the main processing of your program as a DO WHILE loop. After one word or sentence is entered and processed you will ask the user if he/she wants to enter another. If they answer “Yes” or “yes” then the loop should continue and capture more input from the console window. If the user answers anything else then program should end. Keepgoing should be declared as a bool variable.

do {

// Processing for a word/sentence

} while (keepgoing != false)

Inside this main loop you should do the following:

1. Get user input from the console window

2. Compress the input, i.e., remove all punctuation characters and blanks and upper case each letter (this MUST be a separate loop inside of the main processing loop)

3. Reverse compressed string (this MUST be another separate loop inside the main processing loop)

4. Compare compressed string to reversed string… show appropriate message to the user

5. Ask if the user wants to provide another input word/sentence

* * * NOTES * * *

1. The step 2 and 3 above MUST be implemented as while loops (no built in functions to do your work are allowed here!!! — for example to reverse a string)

2. When capturing word, sentence, choice of whether to continue or not, use getline(cin, yourinputvar);

3. The input sentences can have the following punctuation characters: ! , . ‘ ? ; “ ( ) – and space

BONUS Instructions

When the user decides not to keepgoing process the input file “prog4_input.txt” and translate all sentences found in the file producing an output file “prog4_report.txt”. There should be one message shown on screen “File processing done” when file is closed. Here are some sample palindromes that you will find in the file:

Milestones? Oh, ’twas I saw those, not Selim.

No, it’s a bar of gold, a bad log for a bastion.

“Naomi, sex at noon taxes”, I moan.

Snug &amp; raw was I ere I saw war &amp; guns.

Doc, note, I dissent. A fast never prevents a fatness. I diet on cod. Live was I ere I saw evil.

Program Documentation &amp; Style:

1. Declare all variables and constants that your program uses at the beginning of your program.

2. Your program should include two types of comments:

a. Header Comments at the top including lines with:

– Your name, course name, and class time

– A sentence or two explaining the purpose of the program

– A description of the input data needed by the program when you run it

– A description of the processing (calculations) done by the program

– A description of the results (output) produced by the program

b. In-line comments: There should be an in-line comment for each main step in your program. In general, this means a comment with each group of C++ statements that handle the declarations, input, processing, and the output steps of your program

3. Use meaningful identifier names

4. Include clear prompts for the user about entering the data 5. Include clear descriptions of the results when you display them

What to turn in?

1. Log into Canvas, locate this assignment, and upload the compressed project folders.

2. Upload the grade sheet (Word document) after you have edited it to provide requested information.

3. You’re done.
