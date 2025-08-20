Problem 1: Basic
Calculate the factorial of a number

Input: A positive integer N

Output: N! (N factorial)

Algorithm : 
1. START
2. Read the integer N.
3. Initialize the variable fact = 1.
4. Repeat for i = 1 to N:
5.   Multipy fact = fact * i.
6.   After the loop ends,fact with hold the value of N!
7.   Print fact.
8.   Stop.

Psudo code :
1. Begin Factorialofnumber
2. Input N
3. Variable fact = 1
4. For I=1 to N do
5. Variable fact = Fact *I
6. End for
7. Output " Fact is; ", Fact
8. End Factorialofnumber

   Flow chart
   
   ![Factorial Image](Untitled%20Diagram.drawio%20(1).png)


---

Problem 2: Intermediate
Check if a number is prime

Input: A positive integer N

Output: "Prime" or "Not Prime"
 Algorithm :
   1. START
   2. Input: Positive integer N.
   3. If N ≤ 1, output "Not Prime" and stop.
   4. For i from 2 to √N (i*i ≤ N)
   5.If N is divisible by i (, N % i == 0):
   6.Output "Not Prime" and stop.
   7.If no divisors found in the above loop:
   8. Output "Prime".

 Pseudo code:
  1. START   
  2.INPUT N   
  3.IF N <= 1 THEN    
  4.PRINT "Not Prime"   
  5.STOP    
  6.ENDIF    
  7.SET is Prime = true   
  8.FOR i = 2 To square root of (N) DO    
  9.IF N % i == 0 THEN    
  10.PRINT "Not Prime"    
  11.STOP     
  12.END for    
  13.PRINT "Prime"    
  14.END    

   Flow chart
 

<img width="561" height="521" alt="Problem 2" src="https://github.com/user-attachments/assets/877f1c6d-ef1b-4e37-9f37-5447d3e4d17d" />

