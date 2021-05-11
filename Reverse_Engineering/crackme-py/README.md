# crackme-py
point: 30

## Category
Reverse Engineering 

## Solution 
1. After get the given script, open it using "nano crackme.py"
2. I found that stuff inside the script tend to decode something related to "secret"
3. Notice that the upper part of the "crackme.py" there is a string with the name of "bezos_cc_secret"
4. Run the function name "decode_secret" and put the "bezos_cc_secret" in as a parameter
5. Challenge solved!!

## Flag 
picoCTF{1|\/|_4_p34|\|ut_a79b6c2d}
