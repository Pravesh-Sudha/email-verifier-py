# Email-Verifier-Python-Program

<h2>How to run the app</h2>

* Copy the content by using git clone command </br>
  ```git clone https://github.com/Pravesh-Sudha/email-verifier-py.git```
* Run the programm with help of:</br>
  ```python3 main.py```

<h2>How the Program Works</h2>

* This program simply takes up Your email as an input.</br>
* The input passes through several conditions to check its validity.</br>
   * <b>First</b> condition: It checks the length of email which should be more than or equal to 6.</br>
   * <b>Second</b> condition: It checks that the starting index of email should not be a non-alpha input.</br>
   * <b>Third</b> conditon: It checks the place of '@' and its count in the email input. </br>
   * <b>Fourth</b> condition: It checks the the place of '.' which should be before 2 or 3 index at the end of input. </br>
   * <b>Fifth</b> condition: It checks whether the email doesn't contains ' ' or any UpperCase alaphabet.</br>
* If all the condition fulfill, It prints "Right Email" in the output.  
