// { Driver Code Starts
//Initial Template for Java

/*package whatever //do not write package name here */

import java.io.*;
import java.util.*;
class Mathematics {
	public static void main (String[] args) {
		Scanner sc=new Scanner(System.in);
		
		int T=sc.nextInt();
		while(T-->0)
		{
		    Divisors obj=new Divisors();
		    int N;
		    N=sc.nextInt();
		    
		    System.out.println(obj.exactly3Divisors(N));
		   
		    
		}
		
	}
}
// } Driver Code Ends


//User function Template for Java


class Divisors
{
    
    public int exactly3Divisors(int N)
    {
        //Your code here
        int i=0;
        int sum=0;
        while(i*i<=N)
        {
            trim k= new trim();
            if(k.prime(i))
            {
                sum++;
                i++;
            }
            else
            {
                i++;
            }
        }
        return sum;
    }
}

class trim
{
    public boolean prime(int n)
    {
        if (n <= 1) 
            return false; 
  
        // Check from 2 to n-1 
        for (int i = 2; i < n; i++) 
            if (n % i == 0) 
                return false; 
  
        return true; 
    }
}
