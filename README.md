import java.util.Scanner;

public class lemonade{

     public static void main(String []args){
         
        Scanner scan = new Scanner(System.in);
        
        System.out.println("How much lemonade do you want?");
        
        int cost = 2;
        
        int amount = scan.nextInt();
        
        double total = cost * amount;
        
        if(total <= 0){
            System.out.println("Get out of here!");
        }
        else {
            System.out.printf("Total: %.2f", total);
        }
        
     }
}
