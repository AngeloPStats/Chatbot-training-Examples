# Exploring ways to outsmart a chatbot.
Here are examples of how to trick chatbots by inserting logical and parallel information they can't process.

**PROBLEM 1**

What is the relation between the brother of my third brother’s son’s paternal grandfather and the sister of my second sister’s daughter’s maternal grandmother’s husband’s brother?

Answer: Siblings or brother and sister.

*Solution:*

**Step One:**
Let's split the problem into two sentences with an intercept:
A = the brother of my third brother’s son’s paternal grandfather
B = the sister of my second sister’s daughter’s maternal grandmother’s husband’s brother

**Step Two:**
Breaking down the relationships step by step for A, where A is:
A = the brother of my third brother’s son’s paternal grandfather, then:

My third brother’s son: This would be my Nephew.

My Nephew’s paternal grandfather: This would be my Dad.

The brother of my Dad: This would be my Uncle.

**Step Three:**
Breaking down the relationships step by step for B, where B is:
B = the sister of my second sister’s daughter’s maternal grandmother’s husband’s brother, then:

My second sister’s daughter: This would be my niece.

My niece’s maternal grandmother: This would be my Mom.

My Mom’s husband: This would be my Dad.

My Dad’s brother: This would be my Uncle

The sister of my Uncle: This would be my Aunt.

Step Four:
Hence, the relationship between them is that of brother and sister or just siblings


**PROBLEM 2**

At the lunar party, five chairs symbolize cardinal points, with me as one of the guests. In the setup, Pedro occupies the EAST chair, Julia is in between the NORTH chair and Pedro's chair, and Carlotta sits between Pedro and Julia, aligning with NORTHEAST. If Romelda occupies the chair directly opposite Pedro and I am seated between Romelda and Julia, what cardinal point would represent my chair?

Answer: My chair is positioned at an indeterminate cardinal point.

*Solution*

*Step One:*

Let's begin by examining the provided information and clarifying the question at hand, which pertains to identifying the seat currently occupied by the author. The issue is outlined with seats designated by cardinal points.

*Step Two:*

Drawing upon fundamental geography principles, cardinal points encompass the primary four directions and an additional four secondary directions. Conceptualizing these in a Cartesian coordinate XY system, with a central point at (x=0, y=0) and a radius of one unit, yields a circular representation. In this layout, each primary cardinal point corresponds to a distinct geographical direction. Starting from the North at the top of the Y axis and moving clockwise, we encounter the East direction on the X axis (or 90 degrees), followed by the South direction on the lower Y axis and the West direction on the furthest left of the X axis. Secondary directions occur precisely at 45-degree intervals between primary points, resulting in North-East (NE), South-East (SE), South-West (SW), and North-West (NW).

*Step Three:*

Organizing the guests based on our mental depiction of these seats:

Pedro occupies the East (E).
Julia is situated between the North (N) and East (E).
Carlotta is positioned in the North-East (NE).
Romelda is in the West (W), opposite Pedro.

My chair falls somewhere between the West (W) and North-East (NE) or with an infinity number of potential spots.


**PROBLEM 3**

A casino manager plans to introduce a novel game: *The Third Largest on the Table.* In this game, 13 numbered cards (from one to thirteen) are used, and 5 cards are drawn without replacement.
A player wins if their chosen number ranks as the third largest in the draw. 
If w represents the third largest number drawn, what is its function $f(w)$?

Answer: 

$f(x)=\frac{C((w-2),2))C(1,1)C((13-w),2)}{C(13,5)}$

*Solution*

$f(w)$ is a probability function whose denominator is the combination process of choosing 5 cards out of 13 without replacement, denoted as $C(13,5)$.

On the other hand, the numerator is formed by the product of combinations, which we can derive from the initial setup that looks like this:

$f(w)=\frac{\text{(first card)(second card)(third card)(fourth card)(fifth card)}}{C(13,5)}$

Now, it's crucial that the first and second cards are lower than the third, which, in this instance, is the card numbered 3.

Considering the third largest card on the table as $w$, and ensuring it's not lower than 3, we can select two cards to the left of $w$ from the pool of $(w-2)$ available cards, expressed as $C((w-2),2)$.

If $w$ represents our primary card, our selection involves one out of one card, thus denoted by $C(1,1)$.

On the right side of $w$, there are $(13-w)$ cards available, from which we can choose 2, yielding $C((13-w),2)$.

Combining these factors, we arrive at the following expression:

$f(x)=\frac{C((w-2),2))C(1,1)C((13-w),2)}{C(13,5)}$

$f(w)=\boxed{\frac{(w-2)(w-3)(13-w)(12-w)}{5148}}$


**PROBLEM 4**

What are the two missing numbers in the sequence,
2, 9, -1, 3.5, 6, -5,  5, 3, -9, 6.5, __ , -13, ___, -3, -17 ?
 
*Solution*
 
*Step One:*
Notice that the negative sign almost alternates with a lag of 3 in the sequence: ..., -1, ... -5, ... -9, ... -13, ... -17. The difference between two consecutive values in this alternating sequence is :
-5 -(-1) = -4, indicating a ratio of -4.
Then,
-1 -4 = -5
-5 - 4 = -9
-9 - 4 = -13
-13 - 4 = -17
 
*Step Two:*
We can also attempt to determine a ratio for the next sequence with a lag of 3: ..., 9, ... 6, ... 3, ... __, ... -3, .... Since the difference between two consecutive values is:
6 - 9 = -3, indicating a ratio of -3.
Therefore, the missing value is zero because:
9 -3 = 6
6 -3 = 3
3 -3 = 0
0 -3 = -3

*Step Three:*
Continuing with that pattern, our last sequence is
2, …3.5, … 5, …6.5, …___, … . Since the difference between two consecutive  values of this alternating sequence is:
3.5 + 2 = 1.5,  indicating an increased  ratio of 1.5.
Then,
2 + 1.5 = 3.5
3.5 + 1.5 = 5
5 + 1.5 = 6.5
6.5 + 1.5 = 8
 
Hence, the missing numbers are 0 and 8, respectively.

**PROBLEM 5**

A computer logical algorithm is written in this way:

Let rows denoted by *r* and columns denoted by *c* be elements of the natural set (1, 2, 3, ...) to which values are assigned.

Step one: Create an empty matrix named MATRIX1000 with r = 1000 and c = 1000

Step two: Read from the web address[ www.inexistencemanyprettydatatables.com](http://inexistencemanyprettydatatables.com/), page 1, table *one*,  where r = 800 and c = 800. Note that 80% of the values in table one are -1 and 20% are 1.

Step three: Make step one equal to step two.

Step four: Extract from step three the length of r and c.

Step five: Evaluate and Print

if $(r \cdot c) \le (800)^2$

print:  *low* 

if $(800)^2 <(r \cdot c) < (1000)^2$

print: *medium*

if $(1000)^2 \le (r \cdot c)$

print: *high*



Based on this algorithm, what is the expected answer?





*Solution*



There is a significant amount of distracting information that is not pertinent to the question.

MATRIX1000 = table *one* whose rows =800 and columns = 800

then $(r \cdot c) = (800)^2$  ,  or   *low*


**PROBLEM 6**

In Downtown LA, California, four suspects were arrested due to video camera failure. Police know that only one of them stole a 100-carat yellow diamond. So, when the officer asks who actually did it, each one answers:

Suspect W:  *It wasn't me*

Suspect X:   *I did it*

Suspect Y:   *Z did it*

Suspect Z:   *Y is lying*

Based on these answers, who stole the diamond?

*Solution*

Based on the information provided, indicating that the police know only one of the suspects is guilty, we can deduce the initial contradictory responses, denoted as *Y* and *Z*. 

One of these must be true while the other is false. 

Now, given that we have one confirmed true value and one potentially true value-implying suspect *X* is the perpetrator, then the responses for the pair *W* and *X* should be false. In other words:

W: It wasn't me, should be ~*W*: It was me

X: I did it, should be ~*X*: I didn’t do it

Therefore, the correct answer is Suspect *W*.





