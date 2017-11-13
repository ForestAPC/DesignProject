package dasher;
import java.awt.Color;
import java.awt.Font;
import java.awt.Graphics;

import javax.swing.JPanel;

public class FinishMonsters extends JPanel
{
	private long Time;
	
	public FinishMonsters(long Time)
    {
    	setLayout(null);
    	setSize(800,700);
    	setOpaque(true);
    	setVisible(true);
    }
	
	public void paint(Graphics g) 
	{	
		g.setColor(Color.BLACK);
		g.fillRect(0, 0, 800, 700);
		g.setColor(Color.YELLOW);
	    g.setFont(new Font("TimesRoman", Font.PLAIN, 80)); 
	    g.drawString("Nice! You got the monsters!", 100, 350);
	    g.setFont(new Font("TimesRoman", Font.PLAIN, 30)); 
	    System.out.println(Time);
	}
	
	public void SetTime(long temp) 
	{	
		Time = temp;
	}

}
