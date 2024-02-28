# atividade1LP

**ATIVIDADE 1 LP - 1° slide**

**1 -** 
        public class Main {
    public static void main(String[] args) {
        System.out.println("Esta mensagem está sendo impressa");

**2 -**

        public class Main {
    public static void main(String[] args) {
        System.out.println("A primeira mensagem está sendo impressa");
        System.out.println("A segunda mensagem está sendo impressa");

**3 -**

        public class Main {
    public static void main(String[] args) {
        System.out.println("A primeira mensagem está sendo impressa\nA segunda mensagem também está sendo impressa");


**ATIVIDADE 1 LP - 2° slide**

**1 -**

        public class Main {
    public static void main(String[] args) {
        int janeiro = 15000;
        int fevereiro = 23000;
        int marco = 17000;

        int soma = janeiro + fevereiro + marco;
        double media = (janeiro + fevereiro + marco) / 3;

        System.out.println("A soma das despesas é igual a "+soma+"\nA média mensal de gastos é igual a "+media);


**2 -**

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);



        System.out.println("Insira a P1: ");
        double p1 = gato.nextDouble();

        System.out.println("Insira a E1: ");
        double e1 = gato.nextDouble();

        System.out.println("Insira a E2: ");
        double e2 = gato.nextDouble();

        System.out.println("Insira a API: ");
        double api = gato.nextDouble();

        System.out.println("Insira o X: ");
        double x = gato.nextDouble();


        double parte1 = (p1*0.6 +((e1+e2)/2)*0.4);
        double media = (p1*0.6 +((e1+e2)/2)*0.4)*0.5+(Math.max(parte1 -5.9,0)/((p1*0.6+(e1+e2)/2)*0.4)-5.9)*(api*0.5)+x;

        if (parte1 > 5.9) {
            System.out.println("A média é: "+media);

        } else if (media < 6 && media > 3.9) {
            System.out.println("Não atingiu a nota!");
        }


    }
}

**2 -**

        
        
