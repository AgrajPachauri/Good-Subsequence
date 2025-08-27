import java.util.*;
import java.io.*;

class good_subsequence
{
  public static void main(String args[])
  {
    Scanner sc=new Scanner(System.in);
    //System.out.println("Enter Size of Array:-");
    int T=sc.nextInt();
    for(int k=0;k<T;k++)
    {
        int N=sc.nextInt();
        int Ai[]=new int[N];
        //System.out.print("Enter elements of Array");
        for (int i=0; i<N; i++)
        {
          Ai[i]=sc.nextInt();
        }
        boolean flag = (Ai[0]%2==0);
        int count=0;
        for (int i=1; i<N; i++)
        {
          if ((Ai[i]%2==0)!=flag)
            {
              count++;
              flag=!flag;
              
            }
        }
        System.out.println(count+1);
    }
  }
}

