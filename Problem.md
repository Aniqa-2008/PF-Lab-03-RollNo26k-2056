# Display Student Information Using Different Data Types
START
    DECLARE name AS STRING
    DECLARE rollNumber AS INTEGER
    DECLARE percentage AS FLOAT
    DECLARE grade AS CHARACTER
    DECLARE isPassed AS BOOLEAN (or CHAR 'Y'/'N')
    OUTPUT "Enter student name: "
    INPUT name
    OUTPUT "Enter roll number: "
    INPUT rollNumber
    OUTPUT "Enter percentage: "
    INPUT percentage
    OUTPUT "Enter grade: "
    INPUT grade
    OUTPUT "Has passed (Y/N): "
    INPUT isPassed
    DISPLAY "Student Name: " + name
    DISPLAY "Roll Number: " + rollNumber
    DISPLAY "Percentage: " + percentage
    DISPLAY "Grade: " + grade
    DISPLAY "Passed: " + isPassed
END
# Read and Display a Character Using getchar() and putchar()
START
DECLARE ch AS CHARACTER
OUTPUT "Enter a character: "
ch = getchar()      
OUTPUT "You entered: "
putchar(ch)         
END
# Display a Floating-Point Value Using Different Precision Settings
START
DECLARE value AS FLOAT
OUTPUT "Enter a floating-point value: "
INPUT value
DISPLAY value WITH 0 DECIMAL PLACES
DISPLAY value WITH 1 DECIMAL PLACE
DISPLAY value WITH 2 DECIMAL PLACES
DISPLAY value WITH 4 DECIMAL PLACES
END
