SET mystNumb to 3
SEND "Please enter mystNumb" TO DISPLAY
RECIEVE mystNumb FROM KEYBOARD
IF mystNumb >= 3 THEN 
       SEND 'A' TO DISPLAY
ELSE
    IF mystNumb >= 2 THEN 
           SEND 'B' TO DISPLAY
    ELSE
        IF mystNumb >= 1 THEN
               SEND 'C' TO DISPLAY
        ELSE
            IF mystNumb >= 0 THEN
                   SEND 'D' TO DISPLAY
            ELSE
                SEND 'FAIL' TO DISPLAY
            END IF
        END IF
    END IF  
END IF

            
      
            
           
        
     
