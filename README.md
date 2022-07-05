/*
</br>
Paste following dsa question into the online compiler. </br>
https://www.interviewbit.com/online-java-compiler/
</br>
Question : </br>

Write a program that, given an array A[] of n numbers and another number x, determines whether or not there exist two elements in A[] whose sum is exactly x. </br>

Examples: </br>

<pre>
Input: arr[] = {0, -1, 2, -3, 1}
        x= -2
Output: Pair with a given sum -2 is (-3, 1)
              Valid pair exists
Explanation:  If we calculate the sum of the output,1 + (-3) = -2

Input: arr[] = {1, -2, 1, 0, 5}
       x = 0
Output: No valid pair exists for 0
</pre>

Time Complexity: </br>
Space Complexity: </br>

*/
class Main {

public static void main(String [] args) {

  int A[] = {0, -1, 2, -3, 1}; 
  int x = -2; 
  int size = A.length; 

  if (chkPair(A, size, x)) { 
      System.out.println("Valid pair exists"); 
  } 
  else { 
      System.out.println("No valid pair exists for " + x ); 
  } 
}

// Implement your method here

}
