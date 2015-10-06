# Punteros
Actividad numero dos estructura de datos 2015 EDD2015
package arregloporteclado;

import java.util.Scanner;
public class CLASE {
   private Scanner teclado;
   private int[] arreglo;
   
   
   public void cargar(){
      Scanner  rdk = new Scanner (System.in);
       System.out.println("Cantidad de vectores.");
       int cantidad;
       cantidad=rdk.nextInt();
       arreglo=new int [cantidad];
       for(int contador=0; contador<arreglo.length; contador++){
           
          int contador1=0;
            contador1 =arreglo[contador];
           System.out.println("[" +contador +"]");
           
            
           
       }
       //main
package arregloporteclado;

public class Arregloporteclado {

   
    public static void main(String[] args) {
   CLASE a=new CLASE ();
   a.cargar();
           
        
        
    }
    
}

       
       
       
   }

   
   
   
   
}
