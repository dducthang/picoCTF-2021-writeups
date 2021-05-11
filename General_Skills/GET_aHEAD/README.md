# GET aHEAD
point: 20

## Category
Web exploitation 

## Solution 
1. Using an app to catch packet when accessing the link in the description, I used Burp Suite to do that
2. Catch the packet when pressing "chosse red" or "choss blue"
3. Send the packet with GET head to Reapeter then change the head from GET into HEAD
4. Send the packet has just been modified to get the respone 
5. the flag should be in respone packet 

## Flag 
flag: picoCTF{r3j3ct_th3_du4l1ty_70bc61c4}
