# JavaBuilding

package Building;

import java.awt.Graphics;

import javax.swing.JPanel;

@SuppressWarnings("serial")
public class Building extends JPanel {
	
	@Override
	protected void paintComponent(Graphics g) {
		super.paintComponent(g);
		setBackground(Color.Black);
      
      
      g.drawRect(300,150,200);
      g.fillRect(300,150,200;
      
		// TODO: write code to draw the building
		
	}

}


package Building;

import javax.swing.JFrame;

@SuppressWarnings("serial")
public class BuildingApp extends JFrame {

	public static void main(String[] args) {
		new BuildingApp()).run();
	}
	
	
	    
	    public static void rectangle(int rows, int cols) {
	    	
	    	     
	    	
	    	     for (int i = 0; i < rows; i++) {
	    	
	    	          
	    	
	    	          for (int j = 0; j < cols; j++) {
	    	
	    	               System.out.print("*");
	    	
	    	          }
	    	
	    	 
	    	
	    	          // Go to the next row.
	    	
	    	          System.out.println();
	    	
	    	     }
	    	
	    }
	}


