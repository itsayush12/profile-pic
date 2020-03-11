import java.util.*;
class profilepic{
    static Scanner scn = new Scanner(System.in);
    public static void main(String []args){
        int l = scn.nextInt();
        int test = scn.nextInt();
        while(test!=0){
            int w = scn.nextInt();
            int h = scn.nextInt();
            if(w>=l && h>=l){
                if(w==h){
                  System.out.println("ACCEPTED"); 
                }else{
                    System.out.println("CROP IT");
                }
            }else{
                System.out.println("UPLOAD ANOTHER");
            }
            test--;
        }
    }
}