# RESTAURANTE

import java.awt.Color;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JOptionPane;

public class Restaurante {
	
	static JFrame inicio = new JFrame("RESTAURANTE");
	static JFrame menu = new JFrame("MENU PRINCIPAL");
	static JFrame consulta = new JFrame("CONSULTA");
	static JFrame lista = new JFrame("LISTA DE ESPERA");
	static JFrame mesa = new JFrame("MESA");
	
	static JButton Inicio = new JButton("INICIAR");
	static JButton Sair = new JButton("SAIR");
	static JButton Lista = new JButton("LISTA");
	static JButton Mesa = new JButton("MESA");
	static JButton Consulta = new JButton("CONSULTA");
	static JButton voltarinicio = new JButton("VOLTAR");
	static JButton voltarmenu = new JButton("VOLTAR");
	static JButton voltarlista = new JButton("VOLTAR");
	static JButton voltarmesa = new JButton("VOLTAR");
	static JButton voltarconsulta = new JButton("VOLTAR");
	
	static JButton saidamesa2 = new JButton("LIBERAR MESA 2L");
	static JButton entradamesa2 = new JButton("OCUPAR MESA 2L");
	static JButton saidamesa4 = new JButton("LIBERAR MESA 4L");
	static JButton entradamesa4 = new JButton("OCUPAR MESA 4L");
	static JButton saidamesa6 = new JButton("LIBERAR MESA 6L");
	static JButton entradamesa6 = new JButton("OCUPAR MESA 6L");
	static JButton saidamesa8 = new JButton("LIBERAR MESA 8L");
	static JButton entradamesa8 = new JButton("OCUPAR MESA 8L");
	
	static JButton mesa1 = new JButton("MESA-01");
	static JButton mesa2 = new JButton("MESA-02");
	static JButton mesa3 = new JButton("MESA-03");
	static JButton mesa4 = new JButton("MESA-04");
	static JButton mesa5 = new JButton("MESA-05");
	static JButton mesa6 = new JButton("MESA-06");
	static JButton mesa7 = new JButton("MESA-07");
	static JButton mesa8 = new JButton("MESA-08");
	static JButton mesa9 = new JButton("MESA-09");
	static JButton mesa10 = new JButton("MESA-10");
	static JButton mesa11 = new JButton("MESA-11");
	static JButton mesa12 = new JButton("MESA-12");
	static JButton mesa13 = new JButton("MESA-13");
	static JButton mesa14 = new JButton("MESA-14");
	static JButton mesa15 = new JButton("MESA-15");
	static JButton mesa16 = new JButton("MESA-16");
	static JButton mesa17 = new JButton("MESA-17");
	static JButton mesa18 = new JButton("MESA-18");
	static JButton mesa19 = new JButton("MESA-19");
	static JButton mesa20 = new JButton("MESA-20");
	
	static JLabel Mesa1 = new JLabel("MESA-01");
	static JLabel Mesa2 = new JLabel("MESA-02");
	static JLabel Mesa3 = new JLabel("MESA-03");
	static JLabel Mesa4 = new JLabel("MESA-04");
	static JLabel Mesa5 = new JLabel("MESA-05");
	static JLabel Mesa6 = new JLabel("MESA-06");
	static JLabel Mesa7 = new JLabel("MESA-07");
	static JLabel Mesa8 = new JLabel("MESA-08");
	static JLabel Mesa9 = new JLabel("MESA-09");
	static JLabel Mesa10 = new JLabel("MESA-10");
	static JLabel Mesa11 = new JLabel("MESA-11");
	static JLabel Mesa12 = new JLabel("MESA-12");
	static JLabel Mesa13 = new JLabel("MESA-13");
	static JLabel Mesa14 = new JLabel("MESA-14");
	static JLabel Mesa15 = new JLabel("MESA-15");
	static JLabel Mesa16 = new JLabel("MESA-16");
	static JLabel Mesa17 = new JLabel("MESA-17");
	static JLabel Mesa18 = new JLabel("MESA-18");
	static JLabel Mesa19 = new JLabel("MESA-19");
	static JLabel Mesa20 = new JLabel("MESA-20");
	
	static boolean[] m2 = new boolean [5];
	static boolean[] m4 = new boolean [5];
	static boolean[] m6 = new boolean [5];
	static boolean[] m8 = new boolean [5];
	
	static int m2l = 5;
	static int m2o = 0;
	static int m4l = 5;
	static int m4o = 0;
	static int m6l = 5;
	static int m6o = 0;
	static int m8l = 5;
	static int m8o = 0;
	
	static void inicio() {
		inicio.setTitle("RESTAURANTE");
		inicio.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		inicio.setResizable(false);
		inicio.setLocation(350, 0);
		inicio.setSize(550, 600);
		
		inicio.add(Inicio).setBounds(205, 65, 20, 20);
		inicio.add(Sair).setBounds(205, 65, 20, 20);
	}
	static void menu() {
		menu.setTitle("MENU");
		menu.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		menu.setResizable(false);
		menu.setLocation(350, 0);
		menu.setSize(550, 600);
		
		menu.add(lista).setBounds(205, 65, 20, 20);
		menu.add(mesa).setBounds(205, 65, 20, 20);
		menu.add(consulta).setBounds(205, 65, 20, 20);
		menu.add(voltarinicio).setBounds(205, 65, 20, 20);
	}
	static void consulta () {
		consulta.setTitle("CONSULTA");
		consulta.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		consulta.setResizable(false);
		consulta.setLocation(350, 0);
		consulta.setSize(550, 600);
	}
	static void lista () {
		lista.setTitle("LISTA DE ESPERA");
		lista.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		lista.setResizable(false);
		lista.setLocation(350, 0);
		lista.setSize(550, 600);
	}
	static void mesa() {
		mesa.setTitle("MESA");
		mesa.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		mesa.setResizable(false);
		mesa.setLocation(350, 0);
		mesa.setSize(550, 600);
		
		mesa.add(mesa1).setBounds(205, 65, 20, 20);
		mesa.add(mesa2).setBounds(205, 65, 20, 20);
		mesa.add(mesa3).setBounds(205, 65, 20, 20);
		mesa.add(mesa4).setBounds(205, 65, 20, 20);
		mesa.add(mesa5).setBounds(205, 65, 20, 20);
		mesa.add(mesa6).setBounds(205, 65, 20, 20);
		mesa.add(mesa7).setBounds(205, 65, 20, 20);
		mesa.add(mesa8).setBounds(205, 65, 20, 20);
		mesa.add(mesa9).setBounds(205, 65, 20, 20);
		mesa.add(mesa10).setBounds(205, 65, 20, 20);
		mesa.add(mesa11).setBounds(205, 65, 20, 20);
		mesa.add(mesa12).setBounds(205, 65, 20, 20);
		mesa.add(mesa13).setBounds(205, 65, 20, 20);
		mesa.add(mesa14).setBounds(205, 65, 20, 20);
		mesa.add(mesa15).setBounds(205, 65, 20, 20);
		mesa.add(mesa16).setBounds(205, 65, 20, 20);
		mesa.add(mesa17).setBounds(205, 65, 20, 20);
		mesa.add(mesa18).setBounds(205, 65, 20, 20);
		mesa.add(mesa19).setBounds(205, 65, 20, 20);
		mesa.add(mesa20).setBounds(205, 65, 20, 20);
		
		mesa.add(voltarinicio).setBounds(205, 65, 20, 20);
		mesa.add(voltarconsulta).setBounds(205, 65, 20, 20);
		mesa.add(voltarmenu).setBounds(205, 65, 20, 20);
		mesa.add(voltarlista).setBounds(205, 65, 20, 20);
		
		mesa.add(saidamesa2).setBounds(205, 65, 20, 20);
		mesa.add(entradamesa2).setBounds(205, 65, 20, 20);
		mesa.add(saidamesa4).setBounds(205, 65, 20, 20);
		mesa.add(entradamesa4).setBounds(205, 65, 20, 20);
		mesa.add(saidamesa6).setBounds(205, 65, 20, 20);
		mesa.add(entradamesa6).setBounds(205, 65, 20, 20);
		mesa.add(saidamesa8).setBounds(205, 65, 20, 20);
		mesa.add(entradamesa8).setBounds(205, 65, 20, 20);
	}
	
	static void mesa2lugares() {
		m2[0] = false;
		m2[1] = false;
		m2[2] = false;
		m2[3] = false;
		m2[4] = false;
		mesa();
	}
	static void mesa4lugares() {
		m4[5] = false;
		m4[6] = false;
		m4[7] = false;
		m4[8] = false;
		m4[9] = false;
		mesa();
}
	static void mesa6lugares() {
		m6[10] = false;
		m6[11] = false;
		m6[12] = false;
		m6[13] = false;
		m6[14] = false;
		mesa();
		}
	static void mesa8lugares() {
		m8[15] = false;
		m8[16] = false;
		m8[17] = false;
		m8[18] = false;
		m8[19] = false;
		mesa();

	}
	static void mesa2() {

		if (m2[0] == true) {
			mesa1.setBackground(Color.red);

		} else {
			mesa1.setBackground(Color.green);
		}
		if (m2[1] == true) {
			mesa2.setBackground(Color.red);

		} else {
			mesa2.setBackground(Color.green);
		}
		if (m2[2] == true) {
			mesa3.setBackground(Color.red);

		} else {
			mesa3.setBackground(Color.green);
		}
		if (m2[3] == true) {
			mesa4.setBackground(Color.red);

		} else {
			mesa4.setBackground(Color.green);
		}
		if (m2[4] == true) {
			mesa5.setBackground(Color.red);

		} else {
			mesa5.setBackground(Color.green);
		}
	}

	static void mesa4() {

		if (m4[5] == true) {
			mesa6.setBackground(Color.red);

		} else {
			mesa6.setBackground(Color.green);
		}
		if (m4[6] == true) {
			mesa7.setBackground(Color.red);

		} else {
			mesa7.setBackground(Color.green);
		}
		if (m4[7] == true) {
			mesa8.setBackground(Color.red);

		} else {
			mesa8.setBackground(Color.green);
		}
		if (m4[8] == true) {
			mesa9.setBackground(Color.red);

		} else {
			mesa9.setBackground(Color.green);
		}
		if (m4[9] == true) {
			mesa10.setBackground(Color.red);

		} else {
			mesa10.setBackground(Color.green);
		}
	}
	
	static void mesa6() {

		if (m6[10] == true) {
			mesa11.setBackground(Color.red);

		} else {
			mesa11.setBackground(Color.green);
		}
		if (m6[11] == true) {
			mesa12.setBackground(Color.red);

		} else {
			mesa12.setBackground(Color.green);
		}
		if (m6[12] == true) {
			mesa13.setBackground(Color.red);

		} else {
			mesa13.setBackground(Color.green);
		}
		if (m6[13] == true) {
			mesa14.setBackground(Color.red);

		} else {
			mesa14.setBackground(Color.green);
		}
		if (m6[14] == true) {
			mesa15.setBackground(Color.red);

		} else {
			mesa15.setBackground(Color.green);
		}
	}
	
	static void mesa8() {

		if (m8[15] == true) {
			mesa16.setBackground(Color.red);

		} else {
			mesa16.setBackground(Color.green);
		}
		if (m8[16] == true) {
			mesa17.setBackground(Color.red);

		} else {
			mesa17.setBackground(Color.green);
		}
		if (m8[17] == true) {
			mesa18.setBackground(Color.red);

		} else {
			mesa18.setBackground(Color.green);
		}
		if (m8[18] == true) {
			mesa19.setBackground(Color.red);

		} else {
			mesa19.setBackground(Color.green);
		}
		if (m8[19] == true) {
			mesa20.setBackground(Color.red);

		} else {
			mesa20.setBackground(Color.green);
		}
	}
	
	static void entradamesa2() {
		int x = (int) (Math.random() * 5);

		if (m2[x] == false) {
			m2[x] = true;
			if (m2l > 0) {
				m2l--;
				m2o++;
			}

		} else if (m2[x] == true && m2l > 0) {
			entradamesa2();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 2 lugares estão ocupadas. ");
		}

	}

	static void saidamesa2() {
		int x = (int) (Math.random() * 5);

		if (m2[x] == true) {
			m2[x] = false;
			if (m2o > 0) {
				m2o--;
				m2l++;
			}

		} else if (m2[x] == false && m2o > 0) {
			saidamesa2();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 2 lugares estão livres. ");
		}

	}
	static void entradamesa4() {
		int y = (int) (Math.random() * 5);

		if (m4[y] == false) {
			m2[y] = true;
			if (m4l > 0) {
				m4l--;
				m4o++;
			}

		} else if (m4[y] == true && m4l > 0) {
			entradamesa4();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 4 lugares estão ocupadas. ");
		}

	}

	static void saidamesa4() {
		int y = (int) (Math.random() * 5);

		if (m4[y] == true) {
			m4[y] = false;
			if (m4o > 0) {
				m4o--;
				m4l++;
			}

		} else if (m4[y] == false && m4o > 0) {
			saidamesa4();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 4 lugares estão livres. ");
		}

	}
	
	static void entradamesa6() {
		int z = (int) (Math.random() * 5);

		if (m6[z] == false) {
			m6[z] = true;
			if (m6l > 0) {
				m6l--;
				m6o++;
			}

		} else if (m6[z] == true && m6l > 0) {
			entradamesa6();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 6 lugares estão ocupadas. ");
		}

	}

	static void saidamesa6() {
		int z = (int) (Math.random() * 5);

		if (m6[z] == true) {
			m6[z] = false;
			if (m6o > 0) {
				m6o--;
				m6l++;
			}

		} else if (m6[z] == false && m6o > 0) {
			saidamesa6();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 6 lugares estão livres. ");
		}

	}
	
	static void entradamesa8() {
		int a = (int) (Math.random() * 5);

		if (m8[a] == false) {
			m8[a] = true;
			if (m8l > 0) {
				m8l--;
				m8o++;
			}

		} else if (m8[a] == true && m8l > 0) {
			entradamesa8();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 8 lugares estão ocupadas. ");
		}

	}

	static void saidamesa8() {
		int a = (int) (Math.random() * 5);

		if (m8[a] == true) {
			m8[a] = false;
			if (m8o > 0) {
				m8o--;
				m8l++;
			}

		} else if (m6[a] == false && m8o > 0) {
			saidamesa8();
		} else {
			JOptionPane.showMessageDialog(null, "Todas as mesas com 8 lugares estão livres. ");
		}

	}
	static void acaoBotao() {
		entradamesa2.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				entradamesa2();
				m2();

			}
		});
		saidamesa2.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				saidamesa2();
				m2();

			}
		});
		entradamesa4.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				entradamesa4();
				m4();

			}
		});
		saidamesa4.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				saidamesa4();
				m4();

			}
		});
		entradamesa6.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				entradamesa6();
				m6();

			}
		});
		saidamesa6.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				saidamesa6();
				m6();

			}
		});
		entradamesa8.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				entradamesa8();
				m8();

			}
		});
		saidamesa8.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				saidamesa8();
				m8();

			}
		});
	}


	

	public static void main(String[] args) {
		inicio();
		acaoBotao();

	}

}

