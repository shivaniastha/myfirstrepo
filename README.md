# mfirstrepo
class Army
{
   public static void main(String[]args)
    {
      for(int i=0; i<=7; i++)
      {
          for(int k=6; k>=i; k--)
              {
                System.out.print(" "+" ");
               }
          for(int j=0; j<=i; j++)
             {
                System.out.print("*"+" ");
             }
           for(int k=0; k<=1; k++)
             {
                System.out.print(" ");
             }
             for(int j=0; j<=i; j++)
            {
               System.out.print("*"+" ");
            }
           for(int k=6; k>=i; k--)
            {
               System.out.print(" "+" ");
            }
        System.out.println();
      }
     for(int i=0; i<=8; i++)
      {
          for(int j=0; j<=7; j++)
           {
             System.out.print("*"+" ");
           }
             for(int k=0; k<=1; k++)
             {
                System.out.print(" ");
             }
           for(int j=0; j<=7; j++)
           {
             System.out.print("*"+" ");
           }
          System.out.println();
        }
       for(int i=0; i<=7; i++)
         {
            for(int k=1; k<=i; k++)
             {
               System.out.print(" "+" ");
             }
            for(int j=7; j>=i; j--)
             {
               System.out.print("*"+" ");
            }
           for(int k=0; k<=1; k++)
             {
                System.out.print(" ");
             }
          for(int j=7; j>=i; j--)
            {
              System.out.print("*"+" ");
            }
           for(int k=0; k<=i-1; k++)
           {
             System.out.print(" "+" ");
           }
         System.out.println();
        }
        System.out.println();
   }
}
          
