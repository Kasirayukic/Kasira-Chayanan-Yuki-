SEND "Please enter your weight" 
TO DISPLAY RECEIVE weight FROM KEYBOARD
SEND "Please enter your height" 
TO DISPLAY RECIEVE height FROM KEYBOARD
SET BMI TO weight/(height*height)
SEND BMI TO DISPLAY
    If BMI <18.5 displays Underweight
    SEND Underweight TO DISPLAY
Else
   If BMI <-24.9 then Normal weight
   SEND Normal weight TO DISPLAY
Else
    If BMI >-25 then Overweight
    SEND Overweight TO DISPLAY
END IF
END IF
END IF
