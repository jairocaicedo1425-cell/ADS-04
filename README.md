package sena.ejercicios17;

import java.util.Scanner;

public class Ejercicios17 {

    static Scanner dato = new Scanner(System.in);

    public static void main(String[] args) {
        String sexo, tc;
        int nhc, edad, contU = 0, contC = 0, contG = 0;
        int citas, cont = 0;

        System.out.println("ingrese su numero de citas");
        nhc = dato.nextInt();

        System.out.println("ingrese su edad");
        edad = dato.nextInt();

        System.out.println("ingrese su sexo (M/F):");
        sexo = dato.nextLine();
        dato.nextLine();

        System.out.println("Ingrese tipo de consulta (urgencia,control,general");
        tc = dato.nextLine();

        System.out.println("cuantas citas generales fueron la personas");
        contG = dato.nextInt();

        System.out.println("cuantas citas de urgencia fue la persona");
        contU = dato.nextInt();

        System.out.println("cuantas citas de control fue la persona");
        contC = dato.nextInt();

        while(nhc!=0){
            cont++;
            
           System.out.println("ingrese su citas");
            citas = dato.nextInt();
             System.out.println("ingrese su edad");
        edad = dato.nextInt();
        
        System.out.println("ingrese su sexo (M/F):");
        sexo = dato.nextLine();
        dato.nextLine();

        System.out.println("Ingrese tipo de consulta (urgencia,control,general");
        tc = dato.nextLine();

        System.out.println("cuantas citas generales fueron la personas");
        contG = dato.nextInt();

        System.out.println("cuantas citas de urgencia fue la persona");
        contU = dato.nextInt();

        System.out.println("cuantas citas de control fue la persona");
        contC = dato.nextInt();
             
        
        }

        System.out.println("total de citas Urgencia son" + contU);
             System.out.println("total de citas control son" + contC);
                 System.out.println("total de citas general" + contG);
    }
}
