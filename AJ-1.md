# AJ-1: General purpose program

### Brief description
performs basic functions on <text>

### Syntax

`AJ-1 command1 command2 …. <text>  [options]`

Input: <text>; Output: <text>

### Example
AJ-1 EMAIL QUESTION <text> [rules(“Use only positive language”) from=”Andres” to=”Gu” formal=4]

### LLM Instruction

```
I will define a function for you, which I'll call AJ-1. Its syntax is as follows:

**AJ-1 command1 command2 …. <text>  [options]**

Here is the list of possible **commands**:

* Whenever I type "**BULLET** <text>", you will condense the text into a bullet-point list.<br>
* Whenever I type "**EMAIL** <text>", you will generate an email based on the text I have provided.<br>
* Whenever I type "**GRAMMAR** <text>", you will rewrite the text, correcting any grammar or style errors while preserving the text's structure, including bullet points and overall meaning.<br>
* Whenever I type "**LOGIC** <text>", you will identify a set of fundamental facts that could undermine the veracity of the text if any of them prove incorrect.<br>
* Whenever I type “**NEGATE** <text>”, you will explain and justify why <text> is likely false.<br>
* Whenever I type "**QUESTION** <text>", you will generate a bullet-point list of questions based on the text.<br>
* Whenever I type "**SUMMARIZE** <N> <text>", you will summarize the text in N paragraphs.<br>

Here is the list of **options**:
* **rules**(<text>): requests that the output follows a given set of rules.<br>
* **tone**=int(1, 10) requests that the output's tone be adjusted according to the scale, where 1 means extremely negative, 5 means neutral, and 10 means extremely positive.<br>
* **type**(p|b|n) specifies that the desired output should be presented in paragraphs ("p"), bullet points ("b"), or a numbered list ("n").<br>
* **from**=<person> indicates that the message originates from person <person>.<br>
* **as**=<person> requests that the output is written as if it came originally from person <person>.<br>
* **for**=<person> requests that the output is tailored for person <person>.<br>
* **formal**=int(1,10) defines how formal the output is with 1 being "extremely informal" and 10 being "extremely formal".<br>

I will provide you the <text> in my next prompt.
```
