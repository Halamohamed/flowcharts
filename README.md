"# Algorithm and Flowcharts" 
------

## Exercise 1

A  program asks the user to enter their age.

- If age is **18 or older**, display: _"You are eligible to vote."_
- If age is **less than 18**, display: _"You are not eligible to vote."_
- End the program.

### ✓ Pseudocode

````text
START
    INPUT age
    IF age >= 18 THEN
        PRINT "You are eligible to vote."
    ELSE
        PRINT "You are not eligible to vote."
    ENDIF
END
````

### ✓ Flowchart - Image

![alt text](images/Practice%201.png)

---

## Exercise 2

A program takes student marks (0-100).

- **90 and above → Grade A**
- **75-89 → Grade B**
- **50-74 → Grade C**
- **Below 50 → Fail**

### ✓ Pseudocode

```text
START
    INPUT marks
    IF marks >= 90 THEN
        PRINT "Grade A"
    ELSE IF marks >= 75 THEN
        PRINT "Grade B"
    ELSE IF marks >= 50 THEN
        PRINT "Grade C"
    ELSE
        PRINT "Fail"
    ENDIF
END
```
![alt text](images/Practice%202.png)

----

## Exercise 3

A program that:

- Prompts user to enter **5 numbers**
- Keeps a **running total**
- Displays the **sum**
- Ends program

### ✓ Pseudocode

```text
START
    total = 0
    REPEAT 5 TIMES
        INPUT number
        total = total + number
    ENDREPEAT
    PRINT "Total sum = ", total
END
```
![alt text](images/Practice%203.png)

## Exercise 4

A program that:

- Takes **A**, **B**, **C** as inputs
- Finds the **largest**
- Displays result
- Ends program

#### ✓ Pseudocode

```text
START
    INPUT A
    INPUT B
    INPUT C
    IF A >= B AND A >= C THEN
        PRINT "A is largest"
    ELSE IF B >= A AND B >= C THEN
        PRINT "B is largest"
    ELSE
        PRINT "C is largest"
    ENDIF
END
```
![alt text](images/Practice%204.png)


