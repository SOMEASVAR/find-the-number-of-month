# Experiment-2

# Find the numbers of days in a month

# Aim:
  To write a Java program to find the number of days in a month
# Algorithm:

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it NumberDays.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using Switch cases.

Step 5 : Display the operations done the input in the terminal.

# Program:
```
Program developed by: SOMEASVAR.R
Register No: 212221230103
```
```
import java.util.Scanner;
public class fin
{
    public static void main(String[]args)
    {
        Scanner lw= new Scanner(System.in);
        System.out.println("Enter the number of month:");
        int month = lw.nextInt();
        System.out.println("Enter the year:");
        int year = lw.nextInt() ;
        if((month==2) && ((year%4==0) || ((year%100==0)&&(year%400==0))))
            System.out.println("Number of days is 29 and a leap year");
        else if(month==2)
            System.out.println("Number of days is 28");
        else if(month==1 || month==3 || month==5 || month==7 || month==8 || month==10 || month==12)
            System.out.println("Number of days is 31");
        else
            System.out.println("Number of days is 30");
    }
}

```
# Output:
![image](https://github.com/SOMEASVAR/find-the-number-of-month/assets/93434149/ea8daa39-38c5-43df-ad63-1e5637346f89)


# Result:
  We have successfully created a Java program to display the numbers of days in a month
