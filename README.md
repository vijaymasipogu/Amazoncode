# ForLoopcode
ForLoop all the concepts code
public void increasingTriangle() {

		for (int i = 1; i <= 5; i++) {

			for (int j = 1; j <= i; j++) {
				System.out.print("* ");
			}

			System.out.println();
		}

	}

	public void decreasingTriangle() {
		for (int i = 5; i >= 1; i--) {

			for (int j = 1; j <= i; j++) {
				System.out.print("* ");
			}
			System.out.println();
		}
	}
    public void increasingRightTriangle() {
    	 for (int i = 1; i<=5; i++) {
    		 
    		 for (int j = i; j<=5; j++) {
    			 System.out.print("  ");
    			 
    			}
    		 for (int j = 1; j <=i; j++) {
    			 System.out.print("* ");
    			 
			}
			System.out.println();
		}
    	
    }
    public void decreasingRightTriangle() {
    	for (int i = 1; i <=5; i++) {
    		for (int j = 1; j<=i; j++) {
    			System.out.print("  ");
				
			}
    		for (int j = 5; j >=i; j--) {
    			System.out.print("* ");
				
			}
			System.out.println();
		}
    }
    public void triangle() {
    	for (int i = 1; i<5; i++) {
    		
    		for (int j = i; j<=5; j++) {
    			System.out.print("  ");
    	    }
    		
    		for (int j = 1; j<i; j++) {
    			System.out.print("* ");
				
			}
				for (int j= 1; j <=i; j++) {
					System.out.print("* ");
					
				}
				System.out.println();
			}
			
		}
    public void bottomTriangle() {
    	for (int i = 1; i <=5 ; i++) {
    		for (int j = 1; j <= i; j++) {
				System.out.print("  ");
			}
    		for (int j2 = 5; j2 >i; j2--) {
    			System.out.print("* ");
				
			}
    		for (int k = 5; k>=i; k--) {
    			System.out.print("* ");
				
			}
    		System.out.println();
				
			}
			
		}
    public void diamondStar() {
    	for (int i = 1; i <5; i++) {
    		for (int j = i; j<=5; j++) {
    			System.out.print("  ");
				
			}
    		for (int j = 1; j <i; j++) {
    			System.out.print("* ");
				
			}
    		for (int j = 1; j <=i; j++) {
    			System.out.print("* ");
				
			}
    		System.out.println();
    	}
    
    for (int i = 1; i <=5; i++) {
				for (int j = 1; j <=i; j++) {
    			System.out.print("  ");
				
			}
    		for (int j =i; j<5; j++) {
    			System.out.print("* ");
				
			}
    		for (int j = i; j<=5; j++) {
    			System.out.print("* ");
				
			}
    		System.out.println();
			
		}
    }
    
    
	public static void main(String[] args) {
		TriangleForLoop triangle = new TriangleForLoop();
		triangle.increasingTriangle();
		triangle.decreasingTriangle();
		triangle.increasingRightTriangle();
		triangle.decreasingRightTriangle();
		triangle.triangle();
		triangle.bottomTriangle();
		triangle.diamondStar();
	}
}
