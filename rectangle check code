import java.util.*;
public class Solution{


    static void rectangleCheck(double xpoint, double ypoint){


        if((xpoint>=2 && xpoint <=5) && (ypoint >=1 && ypoint <=6)){
            if(xpoint == 2 || xpoint == 5 || ypoint == 1 || ypoint == 6){
                System.out.println("\nyou are on the edge\n");
                return;
            }
            System.out.println("\nYou are inside rectangle!\n");
            return;
        }
        System.out.println("\nYou are outside the rectangle\n");
    }

    public static void main(String args[]){


        // assumptions:
        // rectangle is used
        // it's sides are parallel to axes





        try{
            int continueOrNot = 1;
            while(continueOrNot ==1){
                System.out.println("\n____NEW CHECK____");
                Scanner s = new Scanner(System.in);
                System.out.print("type the x coordinate: ");
                double xpoint = s.nextDouble();

                System.out.print("type the y coordinate: ");
                double ypoint = s.nextDouble();

                rectangleCheck(xpoint,ypoint);
                System.out.print("Do you want check again"+"\n(0 - stop, 1 - continue): ");
                continueOrNot = s.nextInt();

            }
        }catch (Exception e){
            System.out.println("You typed something wrong. Please begin the program again.");
        }


        // coordinates of rectangle are below
        /*
        int A_xCoordinate = 2;
        int A_yCoordinate = 1;

        int B_xCoordinate = 5;
        int B_yCoordinate = 1;

        int C_xCoordinate = 5;
        int C_yCoordinate = 6;

        int D_xCoordinate = 2;
        int D_yCoordinate = 6;

        */


    }
}
