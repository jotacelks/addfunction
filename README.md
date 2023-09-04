# addfunction

package javaapplication20;

import javax.swing.JOptionPane;

public class JavaApplication20 {

    static void ImprimirOla() {
        JOptionPane.showMessageDialog(null, "Olá World ");
    }

    public static void imprimir() {
        System.out.println("Aprendendo Linguagem java");
    }

    public static void imprimirTexto(String texto) {
        System.out.println(texto);
    }

    public static void somar(int a, int b) {
        System.out.println("soma" + (a + b));
    }

    public static void quadrado(int a) {
        System.out.println(Math.pow(a, 2));
    }

    public static void maior(int a, int b, int c) {
        System.out.println(Math.max(a, Math.max(a, b)));
    }

    public static void sexo(char a) {
        switch (a) {
            case 'F' ->
                System.out.println("Feminino ");
            case 'M' ->
                System.out.println("Masculino ");
            default ->
                System.out.println("Desconhecido ");

        }
    }

    public static void main(String[] args) {

        ImprimirOla();
        ImprimirOla();
        ImprimirOla();
      
        
    }

}


----------------




package javaapplication20;

import javaapplication20.JavaApplication20;

public class JavaApplication21 {

    public static void main(String[] args) {
        
        JavaApplication20.ImprimirOla();
        JavaApplication20.imprimir();
        JavaApplication20.imprimirTexto("Professora");
        JavaApplication20.maior(3, 5, 8);
        JavaApplication20.quadrado(6);
        JavaApplication20.sexo('F');
        JavaApplication20.somar(2, 4);
        
        
    }
    
}
