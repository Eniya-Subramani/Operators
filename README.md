# Operators
import java.util.Scanner;
Public class simpleoperations {
Public static void main(String[]args){
Scanner sc = new Scanner(System.in);
System.out.print(&quot;Enter 1st number:&quot;);
int n1= sc.nextInt();
System.out.print(&quot;Enter 2nd number:&quot;);
int n2= sc.nextInt();
System.out.print(&quot;Enter 3rd number:&quot;);
int n3= sc.nextInt();
// ARITHMETIC OPERATORS
System.out.println(&quot;\n----Arithmetic Operations-----\n&quot;);
System.out.println(&quot;ADDITION = &quot; + (n1+n2+n3));

System.out.println(&quot;SUBTRACTION = &quot; + (n2-n3));
System.out.println(&quot;MULTIPLICATION = &quot; + (n1*n2*n3));
System.out.println(&quot;DIVISION = &quot; + (n1/n3));
System.out.println(&quot;MODULUS = &quot; + (n1%n2));
// RELATIONAL OPERATORS
System.out.println(&quot;\n-----Relational Operations-----\n&quot;);
System.out.println(&quot; Greater than = &quot; + (n1&gt;n2));
System.out.println(&quot; Less than = &quot; + (n2&lt;n3));
System.out.println(&quot; Equal to = &quot; + (n1==n3));
System.out.println(&quot; Not equal to = &quot; + (n1!=n2));
// LOGICAL OPERATORS
System.out.println(&quot;\n-----Logical Operations------\n&quot;);
System.out.println(&quot;And operator = &quot; + ((n1&gt;n2)&amp;&amp;(n1&gt;n3)));
System.out.println(&quot;Or operator = &quot; + ((n1&gt;n2)||(n1&gt;n3)));
System.out.println(&quot;Not operator = &quot; + (!(n1&gt;n2)));
// TERNARY OR CONDITIONAL OPERATOR
System.out.println(&quot;\n-----Ternary Operation----\n&quot;);
String result = (n1&gt; n2)? &quot; n1 is greater than n2 &quot; : &quot; n1 is not greater than n2 &quot;;
System.out.println(&quot;Result : &quot; + result);
}
}
OUTPUT:
Enter 1st number:15
Enter 2nd number:10
Enter 3rd number:5
----Arithmetic Operations-----
ADDITION = 30
SUBTRACTION = 5
MULTIPLICATION = 750
DIVISION = 3
MODULUS = 5
-----Relational Operations-----
Greater than = true
Less than = false

Equal to = false
Not equal to = true
-----Logical Operations------
And operator = true
Or operator = true
Not operator = false
-----Ternary Operation----
Result : n1 is greater than n2
