# Gra_pies


public class Gra {

	public static void main(String[] args) {
		Pies reksio = new Pies("Azor","owczarek");
		Pies pudel = new Pies("Pusia", "pudel");
		
		System.out.println(reksio); // java automatyczne rzutowanie na string
		System.out.println(pudel.toString());
		
		//spacer Azor
		System.out.println("Spacer z Azorem");
		reksio.wyjdzNaSpacer();
		
		System.out.println(reksio); 
		System.out.println(pudel.toString());
		 
		//karmienie Pusi
		System.out.println("Karmienie Pusi");
		pudel.jedz(1.5);
		
		System.out.println(reksio); 
		System.out.println(pudel.toString());
		
		//karmienie Azora
				System.out.println("Karmienie Azora");
				reksio.jedz(3);
				
				System.out.println(reksio); 
				System.out.println(pudel.toString());

	}

}
