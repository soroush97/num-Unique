# num-Unique
package qu7;

public class QU7 {

    public static void main(String[] args) {
             System.out.println("unique : " + numUnique(18, 3, 4));
		System.out.println("unique : " + numUnique(6, 7, 7));
	}
	
	public static int numUnique(int a , int b, int c) {
		int k = 0;
		//similar with triangle type check
                        if (a == b && a == c) {
                            k = 1;
		}
		else if ( (a == b && b != c) || (a == c && c != b)|| (b == c && a != c)) {
		      
                            k = 2;
                //if temple = 2
		}
		else {
                            k = 3;
                //if temple = 3
            }
                            return k;
        }
    
}
