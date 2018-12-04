package gerbilland;

/**
 *
 * @author fgrimme4319
 */
public class GerbilLand {

  
    public static void main(String[] args) {
        int choice1;
        Scanner zoo = new Scanner(System.in);
        choice1 = Bob.nextInt();
        switch(choice1){
             case 1:
                  GWhale();
             break;
             case 2:
                  GRex();
             break;
             case 3:
                  GEagle();
             break;
             default:
                  System.out.println("Insert a valid choice")
                  
        }
    }
    
}
