﻿# ESTECO-Training

input ---string
output---string

---------------------------------------conditions------------------------------------

input only--0,1,2 [example-- allowed--- " ", "1", "1,2" not allowed---- "1.1", "1,,1"]

empty string will retrun '0'

use \n as separator "1\n2,1"== 1+2+1=4

(err) "175.2,\n35" == Number expected but '\n' found at position 6."

',' at the end not allowed [Number expected but EOF found]

custom separators [//[delimiter]\n inputs] allowed---//;\n1;2;3 notallowed-- //;\n1;2,2 or //;\n1;2\n2 7)negative number not allowed "-1,2"=Negative not allowed : -1 8)(err) multiple errors --"-1,,-1"= -ve 1 not allowed \n "," founeded \n -ve 2 not allowed




------------------------------------------------------- # ADDITION PROGRAM--------------------------------------------------------

INPUT= "2,4\n-3,5,-2"  

input contain 2,4,-3,5,-2  TWO NUMBERS ARE NEGATIVE

--> The 1st two IF LOOP STATEMENT will be skipped due to ots not a empty nad donesnot contain a '//' delimiter

--> now we will take the string in the ARRAY for more separation

--> three element String, sum, result 

--> number.isEmpty() there is not empty part in the array ["2","4","-3","5","-2"]

--> check if num < 0  ,  so we will get -3,-2 and store in the 'negativeNumbers' variable

--> check if num <= 1000 , so we will get 2,4,5 and stroe in the 'result' varible

--> we will check for negativeNumbers variable and we have two items, means we have encountered error 'result.toString()'

--> result:  Negative not allowed : -3 \n Negative not allowed : -2
