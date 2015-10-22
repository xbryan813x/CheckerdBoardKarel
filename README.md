# CheckerdBoardKarel
Stanford CS106A: The goal of this algorithm is to have "Karel the Robot" create a checker board from scratch. 
Created by BRYAN PACHECO
/*
 * File: CheckerboardKarel.java
 * ----------------------------
 * When you finish writing it, the CheckerboardKarel class should draw
 * a checkerboard using beepers, as described in Assignment 1.  You
 * should make sure that your program works for all of the sample
 * worlds supplied in the starter folder.
 */

import stanford.karel.*;

public class CheckerboardKarel extends SuperKarel {

	// You fill in this part
	
	public void run() {
		putBeeper();
		placeBeeper();
		move();
		turnLeft();
		move();
		turnLeft();
		
		/* Beggining of second row */
		
		putBeeper();
		placeBeeper();
		move();
		turnRight();
		move();
		putBeeper();
		turnRight();
		
		/* third row */
		
		placeBeeper();
		move();
		turnLeft();
		move();
		turnLeft();
		
		/* fourth row */
		
		putBeeper();
		placeBeeper();
		move();
		turnRight();
		move();
		putBeeper();
		turnRight();
		
		/* fifth row*/
		
		placeBeeper();
		move();
		turnLeft();
		move();
		turnLeft();
		
		/* sixth row */
		
		putBeeper();
		placeBeeper();
		move();
		turnRight();
		move();
		turnRight();
		
		/* Seventh row */
		
		putBeeper();
		placeBeeper();
		move();
		turnLeft();
		move();
		turnLeft();
		
		/* eigth row */
		
		putBeeper();
		placeBeeper();
		move();
		turnAround();
		
			
		}
		
	
	/* this shows how to place beeper on the the first row */
	
			private void placeBeeper() {
		
				for (int i=0; i<3; i++)
					FillRow();
				}
		
			public void FillRow() {
				move();
				move();
				putBeeper();
			}
			
}
