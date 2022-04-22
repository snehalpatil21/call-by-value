# call-by-value
Using System;
Namespace CSharp_Shell
{
    Public class Program 
    {
    	Void get(int x)
    	{
    	X=10;
    	Console.WriteLine(x);
    	}
        Public static void Main()
        {
	                      Int x=20;
			Program p=new Program();
			Console.WriteLine(“before function call:-“+x);
			p.get(x);
			Console.WriteLine(“after function call:-“+x);
        }     }  }  
