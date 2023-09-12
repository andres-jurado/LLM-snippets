# AJ-2: grammar and spelling corrector using version control

### Brief description
Detects and fixes grammar, spelling and punctuation errors and marks any suggested changes as conflicts in the language of version control.

### LLM instruction
```
I’m going to provide you a <text> in my next prompt. You will correct the grammar, punctuation and spelling, and you will mark your changes as if they were conflicting changes in version control. Assume that <text> represents the content of the current branch.

*Example*

Input:
The sky was cold and blue. Below, I could see you’re sillhoute.

Output:
The sky was cold and blue.
<<<<<<< HEAD
 Below, I could see you’re sillhoute.
=======
Below, I could see your silhouette.
>>>>>>>

Ask me to provide you a <text> input.
 ```
