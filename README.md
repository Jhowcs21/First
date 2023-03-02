# First
Primeiro programa


import java.util.Scanner;


public class Menu {
	
	public static void main(String[] args) {
		
	
		
		
						//MENU
		  System.out.println("		MENU		");
		  
		  System.out.println();
		  
		  				//Cadastro
		  System.out.println("1. Cadastrar Pessoas");
		  String cadastrar = "1";
		  System.out.println("-------------------");
		  
		  				//Pessoas Cadastradas
		  System.out.println("2. Listar Pessoas Cadastradas");
		  String listar = "2";
		  System.out.println("-------------------");
		  
		  				//Sair
		  System.out.println("3. Sair");
		  String sair = "3";
		  System.out.println();
		  
		  
		  System.out.println("Digite a Opção Desejada!");
		  
		  
		  Scanner sc= new Scanner(System.in);
		  String valor1 = sc.nextLine();
		
		  if (valor1.equals(cadastrar)) {
			  cadastrar ();
			  
		  }
		  else if(valor1.equals(listar)) {
			  listar ();
		  }else if (valor1.equals(sair)) {
			  sair ();
		  }else {System.out.println("Opção invalida!");}
		
		}
					
	
	
					//CADASTRO
	public static void cadastrar () {
		Scanner in = new Scanner (System.in);
		
		String gen;
		int cont = 0;
		
		do
			{
		System.out.println("----------Cadastro----------");
			System.out.println();
		
		
		 System.out.println("Nome");
		 	Scanner sc =new Scanner(System.in);
		 	String nome = sc.nextLine();
		 	
		 	
		 System.out.println("Sobre Nome");
		 	Scanner nome2 =new Scanner(System.in);
		 	String sobreNome = sc.nextLine();
		 	
		 System.out.println("Sexo");
		 	Scanner sexo = new Scanner(System.in);
		 	String sexo2 = sc.nextLine();
		 	
		 System.out.println("Idade");
		 	Scanner idade = new Scanner(System.in);
		 	int idade1 = Integer.parseInt(sc.nextLine());
		 	
		 System.out.println();	
		 System.out.println();	
		 
		
		 
		 System.out.println("Deseja Fazer um novo Cadastro? (Sim  =  1, Não = 2)");
		 cont = in.nextInt();
       
     }while(cont == 1);
		System.out.println();
		
	}
	
	
	
					//LISTA
	public static void listar () {
	}
	
	
	
	
					//SAIR
	public static void sair () {
	}
	
	}
