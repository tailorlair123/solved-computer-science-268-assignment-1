Download Link: https://assignmentchef.com/product/solved-computer-science-268-assignment-1
<br>
<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">This assignment comprises ten questions. Each question is worth 10 marks. You are expected to complete this assignment before you start Unit 4.</span>

Upload your completed assignment to the Assignment 1 link on the course home page for marking and tutor feedback.

<ul>

 <li>Be sure to complete the final step—click on the <strong>Send for Marking</strong> button to notify your tutor.</li>

</ul>

<strong>Prerequisite:</strong> Read what an API is in the textbook <em>Introduction to Programming Using Java</em> by David J. Eck on pages 142−143.

When solving the problems in this assignment, you must follow the application programming interface (API) expected in each problem. You should implement all the <strong>attributes </strong>and <strong>operations</strong> mentioned in the API.

Note that there is no main method in the APIs. That is, you should not perform any data processing within the main method. You should rather use the main method to test other methods, prompt the user for some inputs, and display the results returned by your methods.




<ol>

 <li>Create a class named AddressBook that has the following field names:</li>

</ol>

firstName, middleName, lastName, homeAddress, businessPhone, homePhone, cellphone, skypeId, facebookId, and personalWebSite.

Use appropriate data types to store the values for these fields in AddressBook objects.

Create appropriate get and set methods to retrieve and assign values to these names. For example, getMiddleName(viveAddressBook) should return the middle name of the person Vive. Similarly, vive.setPersonalWebsite(url) should set the personal website of the person Vive to the specified URL object.

Using the get and set methods, create a comparison method compareNames(name1, name2) that compares the first, middle, and last names of strings name1 and name2. Assume that name1 and name2 follow the following format: “FirstName M. LastName”.

Test your program for correct, partially correct (e.g., name string without the middleName), and incorrect inputs (e.g., phone number containing special characters).




<ol start="2">

 <li>Space Inc. will give a quarterly and annual bonus to its employees only if the savings of the quarter and/or the year are greater than or equal to quarterly minimum (monthly commitment x 3) and/or the annual minimum (monthly commitment x 12) amount, respectively. The quarterly bonus is 3% of eligible quarterly savings, and the annual bonus is 5% of annual savings if eligible. If the annual savings exceeds the committed amount by at least 25%, Space Inc. matches the additional savings (25% or above) as part of the annual bonus.</li>

 <li>An employee has committed to save $2000 per month. Her quarterly savings are as follows: Q1 – $5000, Q2 – $7000, Q3 – $4000, and Q4 – $8000.</li>

 <li>Another employee has committed to save $3000 per month. His quarterly savings are as follows: Q1 – $6000, Q2 – $9000, Q3 – $10000, and Q4 – $17000.</li>

</ol>

Write a program to compute the total bonus amount earned by these two employees in the year.

<ol start="3">

 <li>Write a program that prompts the user to enter two points (x1, y1) and (x2, y2). Calculate and display the distance between the two points using the formula below. Round the answer up to 2 decimal points. You can use pow(a,0.5) to compute the square root of an expression.  Math.pow()  returns a double.</li>

</ol>







For example, the distance between the points (−2, −3) and (−4, 4) is approximately 7.28, as shown below.




<ol start="4">

 <li>A group of AU friends decide to run the Banff, Alberta, Marathon. Their names, times (marathon completion time in minutes), and number of years participated are given below:</li>

</ol>

<table>

 <tbody>

  <tr>

   <td>1</td>

   <td>Elena Brandon</td>

   <td>341</td>

   <td>1</td>

  </tr>

  <tr>

   <td>2</td>

   <td>Thomas Molson</td>

   <td>273</td>

   <td>2</td>

  </tr>

  <tr>

   <td>3</td>

   <td>Hamilton Winn</td>

   <td>278</td>

   <td>5</td>

  </tr>

  <tr>

   <td>4</td>

   <td>Suzie Sarandin</td>

   <td>329</td>

   <td>7</td>

  </tr>

  <tr>

   <td>5</td>

   <td>Philip Winne</td>

   <td>445</td>

   <td>9</td>

  </tr>

  <tr>

   <td>6</td>

   <td>Alex Trebok</td>

   <td>275</td>

   <td>3</td>

  </tr>

  <tr>

   <td>7</td>

   <td>Emma Pivoto</td>

   <td>275</td>

   <td>4</td>

  </tr>

  <tr>

   <td>8</td>

   <td>John Lenthen</td>

   <td>243</td>

   <td>1</td>

  </tr>

  <tr>

   <td>9</td>

   <td>James Lean</td>

   <td>334</td>

   <td>1</td>

  </tr>

  <tr>

   <td>10</td>

   <td>Jane Ostin</td>

   <td>412</td>

   <td>1</td>

  </tr>

  <tr>

   <td>11</td>

   <td>Emily Car</td>

   <td>393</td>

   <td>4</td>

  </tr>

  <tr>

   <td>12</td>

   <td>Daniel Hamshire</td>

   <td>299</td>

   <td>4</td>

  </tr>

  <tr>

   <td>13</td>

   <td>Neda Bazdar</td>

   <td>343</td>

   <td>3</td>

  </tr>

  <tr>

   <td>14</td>

   <td>Aaron Smith</td>

   <td>317</td>

   <td>6</td>

  </tr>

  <tr>

   <td>15</td>

   <td>Kate Hen</td>

   <td>265</td>

   <td>8</td>

  </tr>

 </tbody>

</table>




Extend the AddressBook class from Problem 1 to store the additional data. Now, write a method to find the fastest runner. Print the name, address, and his/her time (in minutes) on three separate lines.

Find the second fastest runner. Print the name, address, his/her time (in minutes), and the difference in time with the fastest runner.

Compute the average time of completion taken by these runners.

Finally, print the name and number of years participated for each runner if the runner’s time of completion is equal to or better than the average time of completion.




<ol start="5">

 <li>Solve the following problem using a program: Suppose you save $100 each month into a savings account with an annual interest rate of 5%. Thus, the monthly interest rate is 0.05/12 = 0.00417.</li>

</ol>

After the first month, the value in the account becomes 100 * (1 + 0.00417) = 100.417

After the second month, the value in the account becomes (100 + 100.417) * (1 + 0.00417) = 201.252

And after the third month, the value in the account becomes (100 + 201.252) * (1 + 0.00417) = 302.507

… and so on.

Write a program that randomly generates monthly savings amounts for the 15 runners in Problem 4. Each monthly saving should be in the range of $100 to $800. Extend the AddressBook class to store the monthly savings generated by the random number generator.

Then, display the final account value for each of the 15 runners.







<ol start="6">

 <li>“The Pythagorean Theorem relates the lengths of the three sides of any right triangle. The legs of a right triangle (the two sides of the triangle that meet at the right angle) are customarily labelled as having lengths “a” and “b”, and the hypotenuse (the long side of the triangle, opposite the right angle) is labelled as having length “c”. The lengths are related by the following equation: a ^2 + b^2 = c ^2.” – refer to <a href="http://www.purplemath.com/modules/pythagthm.htm">http://www.purplemath.com/modules/pythagthm.htm</a> for details.</li>

</ol>

This equation allows you to find the length of a side of a right triangle when they’ve given you the lengths for the other two sides, and, going in the other direction, allows you to determine if a triangle is a right triangle when they’ve given you the lengths for all three sides.

This equation can alternatively be written as c = sqrt of (a^2+b^2).  You can find the square root of a number by calling the standard function Math.sqrt. For example, the statement double y = Math.sqrt(x) sets y to the square root of x.

<ol>

 <li>Given the right triangles described below, write a program to compute the lengths of the remaining sides using a program.</li>

 <li>a = 48 and c = 80</li>

 <li>a = 84 and c = 91</li>

 <li>Determine if the following triangles are right-angled triangles:</li>

 <li>a = 45, b = 55, and c = 75</li>

 <li>a = 28, b = 45, and c = 53</li>

</ol>




<ol start="7">

 <li>Douglas Hofstadter’s Pulitzer-prize-winning book <em>Gödel, Escher, Bach</em> contains many interesting mathematical puzzles. In Chapter XII, Hofstadter mentions a wonderful problem that is well within the scope of the control statements in Java. The problem can be expressed as follows: Pick some positive integer and call it <em>n</em>. If <em>n</em> is even, divide it by two. If <em>n</em> is odd, multiply it by three and add one. Continue this process until <em>n</em> is equal to 1. Hofstadter illustrates this process with the following example, starting with the number <em>n</em> = 15:</li>

</ol>

15 is odd, so I make 3n+1: 46

46 is even, so I take half: 23

23 is odd, so I make 3n+1: 70

70 is even, so I take half: 35

35 is odd, so I make 3n+1: 106

106 is even, so I take half: 53

53 is odd, so I make 3n+1: 160

160 is even, so I take half: 80

80 is even, so I take half: 40

40 is even, so I take half: 20

20 is even, so I take half: 10

10 is even, so I take half: 5

5 is odd, so I make 3n+1: 16

16 is even, so I take half: 8

8 is even, so I take half: 4

4 is even, so I take half: 2

2 is even, so I take half: 1




As you can see from this example, the numbers go up and down, but eventually—at least for all numbers that have ever been tried—come down to end in 1. In some respects, this process is reminiscent of the formation of hailstones, which get carried upward by the winds over and over again before they finally descend to the ground. Because of this analogy, this sequence of numbers is usually called the <em>Hailstone sequence</em>, although it goes by many other names as well.

Write a program that reads in a number from the user and then displays the Hailstone sequence for that number, followed by a line showing the number of steps taken to reach 1.




<ol start="8">

 <li>Google Inc. is looking to recruit three of the Boston runners. The criteria for selection are as follows:</li>

 <li>Average final marks in bachelor’s degree (store up to 2 decimal places). The fifteen candidates have the following grades: 82.30%, 85.10%, 77.77%, 69.93%, 93.03%, 88.61%, 55.99%, 87.49%, 88.00%, 91.20%, 66.79%, 76.65%, 55.89%, 90.01%, and 87.9%.</li>

 <li>Ability to communicate as one of the three values – “excellent”, “average”, and “poor”. The fifteen candidates have the following ability to communicate, respectively: poor, poor, average, average, average, poor, excellent, excellent, excellent, average, excellent, average, excellent, excellent, poor.</li>

</ol>

<ul>

 <li>Innovation as one of the two values – “brilliant” and “average” (store as a Boolean; brilliant = true and average = false). The fifteen candidates have the following innovative abilities: brilliant, average, average, average, brilliant, brilliant, average, brilliant, average, brilliant, average, brilliant, brilliant, average, average.</li>

</ul>

<ol>

 <li>Ability to regulate one’s own skill as a probability value between 0 and 1.0 – 1.0 implies excellent regulatory capabilities and 0.0 implies no skills to regulate (store as a double). The fifteen candidates have the following regulatory abilities: 0.5, 1.0, 0.8, 0.0, 1.0, 0.7, 0.8, 0,9, 0.5, 0.6, 0.3, 0.2,  0.5, 0.3, 0.8.</li>

</ol>

Store these values for the fifteen candidates in an extended AddressBook class. In general, Google will not consider a candidate with average marks of less than 85%. Google will consider a candidate with average marks of less than 85% only if the candidate at least has 0.5 regulatory abilities and at least ‘average’ ability to communicate.  Google will only consider a candidate with poor communication ability if the candidate has a ‘brilliant’ innovation capability. Write a program that will help Google to programmatically determine eligibility of the fifteen candidates for these positions, and print the output on the console.







<ol start="9">

 <li>Write a program that iterates through numbers from 0 to 113 using a loop. Print the numbers, one number per line. As you print each number, say <em>x</em>, also print the following when appropriate, separated by commas:</li>

</ol>




<ol>

 <li>If the number is odd, print “x is odd”</li>

 <li>If the number is divisible by 5, print “hi five”</li>

</ol>

<ul>

 <li>If the total of a number (x) and its subsequent number (x+1) is a value divisible by 7, print “wow”</li>

</ul>

<ol>

 <li>If the number is prime, print “prime”.</li>

</ol>










<ol start="10">

 <li>Modify the following program to the specifications given below:</li>

 <li>Add a new status – SingleParent – where the tax is computed as a SINGLE but with a further reduction of $5000 per child.</li>

 <li>Add a new tax condition – if the income is greater than $249,999 for SINGLE, then add a tax of 25% on income amount above $150,000; if the income is greater than $349,999 for MARRIED, then add a tax of 35% on income amount above $200,000.</li>

</ol>

<ul>

 <li>Unknown status – if the status doesn’t belong to SINGLE or MARRIED or SINGLE_PARENT, then compute a 33% tax on the income.</li>

</ul>




import java.util.Scanner;

public class TaxReturn

{

/**

Constructs a TaxReturn object for a given income and

marital status, and computes the tax.

@param anIncome the taxpayer income

@param aStatus either SINGLE or MARRIED

*/

public TaxReturn(double anIncome, int aStatus)

{

income = anIncome;

status = aStatus;

}




public double getTax()

{

double tax = 0;




if (status == SINGLE)

{

if (income &lt;= SINGLE_BRACKET1)

tax = RATE1 * income;

else if (income &lt;= SINGLE_BRACKET2)

tax = RATE1 * SINGLE_BRACKET1

+ RATE2 * (income – SINGLE_BRACKET1);

else

tax = RATE1 * SINGLE_BRACKET1

+ RATE2 * (SINGLE_BRACKET2 – SINGLE_BRACKET1)

+ RATE3 * (income – SINGLE_BRACKET2);

}

else

{

if (income &lt;= MARRIED_BRACKET1)

tax = RATE1 * income;

else if (income &lt;= MARRIED_BRACKET2)

tax = RATE1 * MARRIED_BRACKET1

+ RATE2 * (income – MARRIED_BRACKET1);

else

tax = RATE1 * MARRIED_BRACKET1

+ RATE2 * (MARRIED_BRACKET2 – MARRIED_BRACKET1)

+ RATE3 * (income – MARRIED_BRACKET2);

}

return tax;

}




public static final int SINGLE = 1;

public static final int MARRIED = 2;

private static final double RATE1 = 0.15;

private static final double RATE2 = 0.28;

private static final double RATE3 = 0.31;

private static final double SINGLE_BRACKET1 = 21450;

private static final double SINGLE_BRACKET2 = 51900;

private static final double MARRIED_BRACKET1 = 35800;

private static final double MARRIED_BRACKET2 = 86500;

private double income;

private int status;




public static void main(String[] args)

{

Scanner in = new Scanner(System.in);

System.out.print(“Please enter your income: “);

double income = in.nextDouble();




System.out.print(“Enter S (single) or M (married): “);

String input = in.next();

int status = 0;




if (input.equalsIgnoreCase(“S”))

status = TaxReturn.SINGLE;

else if (input.equalsIgnoreCase(“M”))

status = TaxReturn.MARRIED;

else

{

System.out.println(“Bad input.”);

return;

}

TaxReturn aTaxReturn = new TaxReturn(income, status);

System.out.println(“The tax is ” + aTaxReturn.getTax());

}

}





