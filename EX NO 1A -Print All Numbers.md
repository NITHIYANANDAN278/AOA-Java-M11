
# EX 1A Print All Numbers 
## DATE: 22/01/2026
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start the program and import the `Scanner` class to take user input.
2. Create a `Scanner` object to read an integer input `N` from the user.
3. Check if `N` is greater than 0; if not, display `"Invalid input. N must be greater than 0."`
4. Use a `for` loop to iterate from 1 to `N`.
5. Print each number separated by a space on the same line.
  

## Program:
```
/*
Program to implement Reverse a String
Developed by:  ENBANATHAN V
Register Number: 212224220027

import java.util.*;
public class vijay{
    public static void main (String[] args){
        Scanner sc=new Scanner (System.in);
        int N=sc.nextInt();
        if(N>0){
            for (int i=1;i<=N;i++)
            {
                System.out.print(i+" ");
            }
        }
        else{
        System.out.print("Invalid input. N must be greater than 0.");
        }
        
    }
}
*/
```

## Output:
<img width="440" height="161" alt="image" src="https://github.com/user-attachments/assets/1b634080-211d-4751-9d13-e367e5ecf3aa" />



## Result:
The program successfully print all the numbers from 1 to N. 
