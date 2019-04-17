
public class Bricks {
	public boolean checkMethod(int small, int big, int goal) {
	    if (goal <= small + big * 5 && goal >= big * 5) {
	        return true;
	    } else
	        return false;
	}

	public static void main(String args[]) {
	    Bricks brick = new Bricks();
	    System.out.println(brick.checkMethod(3, 2, 10));
	}
	  
  }
