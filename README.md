# Calculos de áreas - Figuras Geométricas Planas. 📍📏

### Esse projeto foi desenvolvido em Java como parte de uma atividade prática de programação. O objetivo é criar programas capazes de calcular a área de diversas figuras geométricas planas, utilizando fórmulas matemáticas. 
### Além do foco matemático, o projeto contém encapsulamento e orientação por classes. 


## 📝 O que tem nesse repositório? 
 * Um pacote (br.edu.formasGeometricasPlanas) para agrupar as classes: Quadrado, Triângulo, Hexagono, Losango, Pentagono, Paralelogramo, Círculo, Trápezio e Retangulo.
* Um pacote (br.edu.principal) para agrupar a classe principal para executar todos os códigos: Principal. 

## 🔒 Encapsulamento 
*  Os atributos das figuras geométricas (como base, altura, lado, raio etc.) são **privados** ('private'), seguindo o princípio de **encapsulamento**.
*  Cada figura pode ter sua própia **classe**, como expliquei acima, contendo métodos responsáveis por calcular sua área.    

## ⬛ Exemplo (classe Quadrado): 

package br.edu.formasGeometricasplanas;

public class Quadrado {

	
	// Atributos 
		private double lado;
		private double area;
		
		// Metodos 
		public Quadrado () {
			lado = 0;
			area = 0; 
		}
		
		public void recebeLado (double pLado) {
			lado = pLado;
		}
		
		public void calcArea () {
			area = (lado * lado);
		}
		
	   public void mostrarArea () {
		   System.out.println(area);
		 }
		
	   public double mostrarAreaComRetorno () {
		 System.out.println("A area do quadrado é: " + area);
			  return area;
		  }
		}

## 😊 Autora 
Projeto desenvolvido por **Júlia**. Feito para aprender, praticar e compartilhar conhecimento. Se quiser acompanhar ou contribuir, será super bem-vindo(a)! bjsss. 

		
	






