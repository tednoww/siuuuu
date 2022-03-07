# siuuuu
import java.util.Scanner;

public class suuuu {
  static boolean siiiuuu(int eded)  {  
     if(eded== 1) {  
         return false;  
       } 
     for (int i = 2; i*i <= eded; i++) {  
         if (eded % i == 0){  
            return false;  
                }  
           } 
    return true;  
  }  
  
  
  
  
    static int suiiiiii(int min, int max)   {  
         int cem = 0;  
          for (int i = max; i >= min; i--)  {   
             boolean esas = siiiuuu(i);  
             if (esas){   
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
