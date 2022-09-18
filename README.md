# Sum-of-n-digtis-using-Recursion
public class ABC {
    public static int add(int n)
    {
        if(n==0)
        {
            return 0;
        }
        return(n%10+add(n/10));
    }
    public static void main(String[] args)
    {
         int n=12345;
int k=      add(n);
System.out.println(k);

    }
    
}
