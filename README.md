# String-data-structure
```
Using this program, the following operations are implemented:
1) assignment
assign the "Hello everyone," 
using assign (s, t) to the string variable string1; 
then using assign (s, t) again, "I love you!" is assigned to the string variable string2, 
and then string1 and string2 are merged 
concatenated with concat (s, t) to get the string string3, 
and display the string3 and its length on the screen. 
2) find out the sequence string 
using the substring subStr (s, k, len) string3 starts with the 7th character, 
and the continuous 4 characters after the 19th character, 
and display it on the screen.
3) delete 
string to delete 8 consecutive characters from the seventh character in the delStr (s, I, j) string3, 
and then insert the position of the seventh character of the string3 with "Data Structure". 
The inserted string string3 and its length are displayed on the screen. 
4) look for
look for the string "love" from string3, replace it with "hate", 
and finally display the modified string string3 and its length on the screen.
```
## template
* First, enter a string in the console window to assign a value to S1
* a string like "Hello everyone, "
* Then,enter another string in the console windows to assign a value to S2
* you can input this string: I love you!
* after you finish the second step, all you have to do is press the enter key to wait for the program to run without doing anything else. 
* If you want to finish the process ahead of time, you can use Ctrl C to break the program
* The expected results of the program run will look like the following
```
请输入s1:Hello everyone,
输入s2:I love you!
string1+string2=Hello everyone, I love you! 长度：27
string3第7个字符开始的连续5个字符:every
string3第19个字符后的连续4个字符:love
string3:Hello , I love you! 长度：19
string3:Hello Data Structure, I love you! 长度：33
string3:Hello Data Structure, I hate you! 长度：33
```
