#	Number of sheets to be paid and the number of change

When shopping, Mr.Paiza pays money so that the total of the number of coins to be paid and the number of coins to change are minimized.
For example, as in input example 1, when shopping for 128 yen, the method as shown in the table below can be considered.
There are six kinds of coins in Japan.
## 500 Yen, 100 Yen, 50 Yen, 10 Yen, 5 Yen, 1 Yen.

![gitImage](https://user-images.githubusercontent.com/16211451/54584535-d4800480-4a41-11e9-8671-53622cbddba6.jpg)

As you can see from the table above, paying with one 100 yen coin and one 50 yen coin, or by paying one 100 yen coin and three 10 yen coin, the number of coins used for payment and change is 6.

Now, Mr.Paiza is trying to shop X yen.
We have 500 yen coin, 100 yen coin, 50 yen coin, 10 yen coin, 5 yen coin, 1 yen coin, and you can freely use any coin and any number of pieces.
At this time, please minimize the total number of coins used for payment and change, and output the number of coins. However, Mr.Paiza does not use bills. Also, change can be received in such a way as to minimize the number of coins.

Input value
Input is given in the following format. X
An integer X representing the amount to pay is entered. The input is one line, and line feed is included at the end.
 
Please output the minimum value of the total number of coins used for payment and fishing as an integer.
Insert a line break at the end of the output, and do not include extra characters or blank lines.

conditions
For all test cases, the following conditions are satisfied.
·	1 ≦ X ≦ 999

### Input example 1
128
### Output example 1
6

### Input example 2
368
### Output example 2
7
