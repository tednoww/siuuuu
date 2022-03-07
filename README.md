# siuuuu
import java.util.Scanner;

import java.util.Scanner;

public class suuuu 
 {
           static boolean siiiuuu(int eded)  
           {  
                    if(eded== 1) 
                    {  
                            return false;  
                    } 
               for (int i = 2; i*i <= eded; i++) 
               {  
                       if (eded % i == 0)
                       {  
                             return false;  
                       }  
           } 
          return true;  
         }  
     
  
  
  
           static int suiiiiii(int min, int max)   
           {  
                int cem = 0;  
                for (int i = max; i >= min; i--)  {   
                boolean esas = siiiuuu(i);  
                if (esas)
                {   
            	     cem += i;  
                } 
          } 
     return cem;  
 }  
    
    
     public static void main(String args[]){  
    	 Scanner scan= new Scanner(System.in);
    	 int min = 0;
         int max =scan.nextInt();
        

      System.out.println(" " + suiiiiii(min, max));  
     }   
}








public class suiiiiiiiiii {
	public static void main(String[] args) {
		
		
	   /*  int a[] = new int[]{1,2,3,4,5,6,7,8,9,10}; 
		 int b[] = new int[]{1,2,3,4,5,6,7,8,9,10};
		 
		   for(int i=0;i<a.length;i++) {
			  for(int j=0;j<b.length;j++) {
	                 System.out.println(a[i]+b[j]);
                   if(i==j) {
                 	  i++; 
                  }
	            }
          }
	*/
		/* 
		 int cem = 0;
		  int n = 100;
		  for (int i = 1; i <= n; ++i) {
		      cem += i;     // cem= cem + i
		    }
		       
		    System.out.println("cem = " + cem);
		*/
        	
	}
 }
