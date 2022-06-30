# ITS-GROUP14-CALCULATOR

import java.awt.*;
import java.awt.event.*;
import javax.swing.*;
import javax.swing.border.EmptyBorder;

public class Caluu {
public static void main(String[] args) {
JFrame frame = new JFrame("Calculator");
// frame.setLayout(new FlowLayout());

JTextField tf = new JTextField("0");

JPanel panel = new JPanel();
panel.setLayout(new GridLayout(4,4,4,4));

	panel.add(new JButton("7"));
	panel.add(new JButton("8"));
	panel.add(new JButton("9"));
	panel.add(new JButton("/"));
	panel.add(new JButton("4"));
	panel.add(new JButton("5"));
	panel.add(new JButton("6"));
	panel.add(new JButton("*"));
	panel.add(new JButton("1"));
	panel.add(new JButton("2"));
	panel.add(new JButton("3"));
	panel.add(new JButton("-"));
	panel.add(new JButton("0"));
	panel.add(new JButton("."));
	panel.add(new JButton("="));
	panel.add(new JButton("+"));


frame.add(panel, BorderLayout.CENTER);
frame.add(tf, BorderLayout.NORTH);
frame.setVisible(true);
frame.setSize(225, 215);
frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	}
}
