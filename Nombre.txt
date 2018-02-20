import java.util.Scanner;

public class Nombre {
    public static void main(String[] args) {
        String nom1;
        String nom2;
        String ape1;
        String ape2;
        Scanner S = new Scanner (System.in);
        System.out.println("Introduce el primer nombre: ");
        nom1 = S.nextLine();
        System.out.println("Introduce el segundo nombre: ");
        nom2 = S.nextLine();
        System.out.println("Introduce el primer apellido: ");
        ape1 = S.nextLine();
        System.out.println("Introduce el segundo apellido: ");
        ape2 = S.nextLine();
        System.out.println("El nombre completo es: "+nom1+" "+nom2+" "+ape1+" "+ape2); 
    }
}