# How-many-unattempted-problems
# Problem
CodeChef recently revamped its practice page to make it easier for users to identify the next problems they should solve by introducing some new features:

Recent Contest Problems - contains only problems from the last 2 contests Separate Un-Attempted, Attempted, and All tabs Problem Difficulty Rating - the Recommended dropdown menu has various difficulty ranges so that you can attempt the problems most suited to your experience Popular Topics and Tags Our Chef is currently practicing on CodeChef and is a beginner. The count of ‘All Problems’ in the Beginner section is X. Our Chef has already ‘Attempted’ Y problems among them. How many problems are yet ‘Un-attempted’?

# Input Format

The first and only line of input contains two space-separated integers X and Y — the count of 'All problems' in the Beginner's section and the count of Chef's 'Attempted' problems, respectively.

# Output Format

Output a single integer in a single line — the number of problems that are yet 'Un-attempted'

# CODE

    /* package codechef; // don't place package name! */
    
    import java.util.*;
    import java.lang.*;
    import java.io.*;
    
    /* Name of the class has to be "Main" only if the class is public. */
    class Codechef
    {
    	public static void main (String[] args) throws java.lang.Exception
    	{
    		// your code goes here
    		Scanner sc=new Scanner(System.in);
    		int x=sc.nextInt();
    		int y=sc.nextInt();
    		System.out.println(x-y);
    	}
    }

