# EqualSumChecker
This project takes the value of three int parameters and returns a boolean true if the sum of parameter 1 and 2 is equal to the third parameter


public class EqualSumChecker {

    public static boolean hasEqualSum(int sum1, int sum2, int sum3) {

        return sum1 + sum2 == sum3;
        
        // another way to solve this probem 
        /* if (sum1 + sum2 == sum3) {
              return true;
            } else 
            
            return false;
        */
    }
        
    public static void main(String[] args) {
        System.out.println(hasEqualSum(-4, -4, -8));
    }
}
