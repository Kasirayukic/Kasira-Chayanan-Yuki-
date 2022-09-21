Start
SET mystNumb to 3
SEND "Please enter mystNumb" TO DISPLAY
RECIEVE guess from keyboard
IF guess>10 THEN
SEND "Too high!" TO DISPLAY
ELSE
    IF guess=mystNumb THEN
    SEND "WELL DONE" TO DISPLAY
ELSE
    SEND "BAD LUCK" TO DISPLAY
 END IF
 END IF
