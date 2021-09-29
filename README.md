# javagrade


import java.util.Scanner;
/* Program By Ghanendra Yadav
   Visit http://www.programmingwithbasics.com/
*/
class grade
{
   static Scanner sc = new Scanner(System.in);
   public static void main(String args[])
   {  

   int marks;
   
   /*This Is a Grade Checker Program*/
   while(true)
   {
   System.out.print("\n=========================================");
   System.out.print("\nThis Is a Grade Checker Program");
   System.out.print("\n-----------------------------------");
   System.out.print("\nEnter The Marks Between 0 To 100:");
   System.out.print("\n=========================================\n");
   
   System.out.print("\nEnter The Mark: ");
   marks = sc.nextInt();
   
   if(marks>100)
   {
    /* Marks greater than 100 */
    System.out.print("\nDon't Be Smart Enter your Marks Between Limit\n");
   }
   else
   {
   switch(marks/10)
   {
       case 10 :
       case 9 :
           /* Marks between 90-100 */
           System.out.print("\n=============================");
           System.out.print("\nYour Grade Is: A or Excellent");
           System.out.print("\n=============================");
           break;
       case 8 :
       case 7 :
           /* Marks between 70-89 */
           System.out.print("\n=============================");
           System.out.print("\nYour Grade Is: B or Very Good" );
           System.out.print("\n=============================");
           break;
       case 6 :
           /* Marks between 60-69 */
           System.out.print("\n========================");
           System.out.print("\nYour Grade Is: C or Fair" );
           System.out.print("\n========================");
           break;
       case 5 :
       case 4 :
           /* Marks between 40-59 */
           System.out.print("\n========================");
           System.out.print("\nYour Grade Is: D or Pass");
           System.out.print("\n========================");
           break;
       default :
           /* Marks less than 40 */
           System.out.print("\n================================================");
           System.out.print("\nYou Grade Is: F or Fail\n");
           System.out.print("\nSuggetin: Do Not show your Sheet to Your Parent");
           System.out.print("\n================================================");
   }
 }
}   
   }
}

Suggestion:- C++ Program For Find A Grade Of Given Marks Using Switch Case

Output:-

Java Program For Find A Grade Of Given Marks Using Switch Case

You May Like This

1. HackerRank Solution for 30 Days of Code

2. Java Program For Find The Gross Salary Of An Employee

3. C++ Program For School Management System ( SMS Project ) With Source Code

4. HackerRank Solution For Birthday Cake Candles

5. Java Program For Converting Temperature Celsius Into Fahrenheit
TWEET
SHARE
SHARE
SHARE
Previous Post
C++ Program For Binary Search
Next Post
C++ Program To Merge Ascending And Descending Array Into The Third Array
Ghanendra Yadav
Post Written By: Ghanendra Yadav 
Hi, I’m Ghanendra Yadav, SEO Expert, Professional Blogger, Programmer, and UI Developer. Get a Solution of More Than 500+ Programming Problems, and Practice All Programs in C, C++, and Java Languages. Get a Competitive Website Solution also Ie. Hackerrank Solutions and Geeksforgeeks Solutions. If You Are Interested to Learn a C Programming Language and You Don't Have Experience in Any Programming, You Should Star
