public class Q4
{
    public static void main(int P, int r, int n, int b)
    {
        switch(b)
        {
            case 1:
                   double A= Math.pow(P*1+r/100,n/12);
                   System.out.println("Amount:"+A);
                   System.out.println("Term deposit");
                   break;
            case 2:
                   double Am= P*n +P*n*(n+1)/2 *r/100 *1/12;
                   System.out.println("Amount:"+Am);
                   System.out.println("Recurring deposit");
                   break;
            default: 
                   System.out.println("Invalid number");
        }
    }
}
