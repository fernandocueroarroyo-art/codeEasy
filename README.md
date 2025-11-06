# codeEasy
un codigo para extensión
package poo2.tin;
import java.util.Scanner;
/**
 *
 * @author ALUMNO#
 */
public class Tin {
      Scanner sc = new Scanner (System.in);
      int numero1, numero2, resultado;
      
      public void setnumero1(){
          System.out.println("ingrese el primer numero");
          numero1=sc.nextInt();
      }
      
      public void setnumero2(){
          System.out.println("ingrese el segundo numero");
          numero2=sc.nextInt();
      }
      
      public int getresultado(){
          resultado = numero1 + numero2;
          return resultado;
      }
           
      
    public static void main(String[] args) {
        Tin tn = new Tin();
        
        tn.setnumero1();
        tn.setnumero2();
            
        System.out.println("El resultado es"+ tn.getresultado());
        
    }
}
