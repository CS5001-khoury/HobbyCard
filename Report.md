# Homework 01 - Report

Homework assignments will contain a report that is manually graded by TAs. The report asks more general questions 
about what you are learning, and you are encouraged to explore to figure out the answer. Just cite any resources you use.

For all these questions, it is recommended you open up the python interpreter and try out the code.  You can also use the python visualizer to help you visualize the code.  You can find the visualizer here: [http://www.pythontutor.com/visualize.html#mode=edit](http://www.pythontutor.com/visualize.html#mode=edit)


1. In the python interpreter directly, try the following code:
   ```python
   x = 10 + "5"
   ```

    a. What is the error message you get?  (copy and paste it below - you don't need to include the Traceback lines, just the error message including type of error)

    ```text
    copy error here/replace this line
    ```
    
    b. Describe in your own words the error message. What does it mean?  (you can use the internet to help you, but make sure to cite your source)


    c. There are multiple ways this error can be fixed. However, converting between types is common, and it is called "casting" (think of actors on a stage). Take time to research online how to cast between types in python.  What is the correct way to cast the string "5" to an `int`?  Write code below in the block below
    ```python
    # write your code here
    
    ```
    * Note: for HW02 we will return to casting, as it is common to take in client input as a string, and convert it to another type for processing.

2. Match the value with the correct type for `x`. Your options for types are `int`, `float`, `str`:  
   Example: x = 1.0 : float
   * x = 1
   * x = "1"
   * x = 1.0 + 1 
   * x = str(1.0)
   * x = int(1 / 2)   
    You can use the following code in the interpreter to help you:  
    ```python
    x = int(1/2)
    print(x)
    type(x)
    ```

3. In the `x = int(1 / 2)` example, what is the value of x? Why? (once again you may need to research, just cite sources)

4. If we wanted to force a range between 0 and `n-1` (let's say 6), but I could have any number as my variable. What operator would use? Why? Please write some code to show this! If you included prints in your code to test this, also include that in your code copy below. (check Lesson 1.6 if you don't recall)
   ```python
   # for example
   x = 102
   r = x ?? 6 ## with ?? being the operator you use
   ## your code below this line

   ```

5. The above is one of the unique properties of the operator you just listed. It enforces a range between 0 and `n` exclusive of n. There are a number of advantages of this that you will uncover during your CS career, and to think, it ties back to elementary school mathematics (and arguably why it is hard for us to remember it!). Can you list some real world cases/examples where you could see using this operator, as usually you are free to research just cite sources. You only need one example, but you are encouraged to come up with more. 

6. The files all have docstrings with their functions. How does this help the programmer? Beyond just reading the file, what is the command you can use to pull up the docstring of any function? (you can use the internet to help, but if you look at the bottom of the star_rating.py, you may get an idea of the command name). Use the command on print to see the docstring.  Write the command below, and the printed below that. 
   ```python
   # write your command here
   ```
   ```text
   copy the output here
   ```


## Deeper Thinking

 For star_rating and hobby_card, we built strings and then printed out the results. Why would we want to build strings, and then print out the results, than just printing out the results directly? Don't need a correct answer, but we encourage you to ponder this question and come up with reasons on why this would be a good design pattern.  Write your answer below.

---
Answer here




---

## LLM Ethics and Educational Use (Deeper Thinking Part 2)

Large Language Models such as ChatGPT, Claude, and Copilot have drastically changed how we program and code in industry. The general advice with them is they are good for experienced programmers, but they often confuse and generate bad code for new programmers! In truth, there are (at least) three stages for LLM use:

1. Learning how to ethically use LLMs to help you learn new topics
2. Learning how to ethically use LLMs to co-create (such as code generation)
3. Learning how LLMs work and programming them yourselves (A.I. courses)

We are **only** in stage one. It is risky to try to jump to stage two without an understanding of what you are doing. I will provide sample prompts to help learn stage 1, but before you use them - I would like you to explore the ethical issues around LLMs.

### Report

Find three links on the ethical use of LLMs, particularly focusing on their use in educational or programming contexts where possible. Your sources should be from credible sources such as academic papers, established technology publications, educational policy organizations, or reputable news outlets. I suggest you have at least one source that contradicts or offers a different perspective from the other sources. Look for sources that address different stakeholder perspectives - such as educators, industry professionals, ethicists, or students.

Keep track of your search terms and research process as you work - this will help you reflect on how you found and evaluated sources, which is good practice for academic research.

Then write a reflective report (maximum of three paragraphs) that synthesizes these sources and answers the following questions:

1. What are the issues surrounding LLM use, both from a creative and an engineering standpoint?

2. What are the potential benefits of using LLMs?

3. What is your current position on LLM use in society, and how might this position evolve as you gain more experience with these tools?

### Writing Expectations

You should write these paragraphs as a cohesive report - NOT as bullet points. We are also working on improving your college-level writing skills for master's-level research, so this is practice for that. Your report should demonstrate synthesis of sources, not just summary. Avoid simply stating what each source says - instead, analyze how the sources relate to each other and to your own developing perspective. Show how different viewpoints complement or contradict each other, and use this analysis to inform your own reasoned position. I am not requiring proper citations (at this time), but you need to provide the links you are using for your sources.  We are not grading on "correctness". This is your opinion, but we want you to gain practice doing research and reporting on it.

(write your report below this line)

---
