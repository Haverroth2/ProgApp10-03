//pacote Scanner
import java.util.Scanner;
 
//classe Main
class Main {
 
 public static void main(String[] args) {
 
//atributo scanner
 Scanner reader = new Scanner(System.in); 
    System.out.println("Vamos ver qual será sua categoria");
   System.out.println("Qual é a sua idade?");
   double grade1 = reader.nextDouble();
 
//métodos
   if(grade1 <= 10) {
   System.out.println("Sua categoria é Infantil!");
   } if(grade1 == 11) {
   System.out.println("Sua categoria é Infanto Juvenil!");
   }if(grade1 == 12) {
   System.out.println("Sua categoria é Infanto Juvenil!"); }if(grade1 == 13) {
   System.out.println("Sua categoria é Infanto Juvenil!"); }if(grade1 == 14) {
   System.out.println("Sua categoria é Juvenil!");
   }if(grade1 == 15) {
   System.out.println("Sua categoria é Juvenil!");
   }if(grade1 == 16) {
   System.out.println("Sua categoria é Juvenil!");
   }if(grade1 == 17) {
   System.out.println("Sua categoria é Juvenil!");
   }if(grade1 == 18) {
   System.out.println("Sua categoria é Juvenil!");
   }if(grade1 >18) {
     System.out.println("Sua categoria é Adulta!");
   }
 }
}
