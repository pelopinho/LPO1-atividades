# LPO1

**TAREFA 1 - 1° slide**

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


**TAREFA 1 - 2° slide**

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


**TAREFA 2 - teams**

**1 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe a sua idade (anos): ");
        int anos = gato.nextInt();

        System.out.println("Informe a sua idade (meses): ");
        int meses = gato.nextInt();

        System.out.println("Informe a sua idade (dias): ");
        int dias = gato.nextInt();

        int anosTotal = anos * 365;
        int mesesTotal = meses * 30;

        int idadeTotal = (anosTotal+mesesTotal+dias);

        System.out.println("O usuário possui "+idadeTotal+" dias de vida");



 **2 -**

        import java.util.Scanner;
        public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Quantos eleitores há no município da FATEC?");
        int eleitor = gato.nextInt();

        System.out.println("Quantos votos brancos?");
        int vtBranco = gato.nextInt();

        System.out.println("Quantos votos nulos?");
        int vtNulo = gato.nextInt();

        System.out.println("Quantos votos válidos?");
        int vtValido = gato.nextInt();

    double percentBranco = vtBranco * 100 / eleitor;
    double percentNulo = vtNulo * 100 / eleitor;
    double percentValido = vtValido * 100 / eleitor;

    int somaVoto = vtBranco + vtNulo + vtValido;

    if (somaVoto > eleitor) {
        System.out.println("Contagem incorreta!");
    } else {

        System.out.println("LEVANTAMENTO\nVotos brancos: " + percentBranco + "%\nVotos nulos: " + percentNulo + "%\nVotos válidos: " + percentValido + "%");


    }

    }
}

**3 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o salário: ");
        double salario = gato.nextDouble();

        System.out.println("Informe a porcentagem de reajuste: ");
        double reajuste = gato.nextDouble();

        double salarioReajustado = salario + (salario*(reajuste*0.01));

        System.out.println("Salário reajustado: "+salarioReajustado);


    }

    }


**4 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o custo de fábrica do carro (R$): ");
        double carroFabrica = gato.nextDouble();

        double custoTotal = carroFabrica + (carroFabrica*0.28) + (carroFabrica*0.45);

        System.out.println("O custo total é de: "+custoTotal);



    }

    }


**5 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o número de carros foram vendidos?");
        int carros = gato.nextInt();

        System.out.println("Informe o valor total das vendas? (R$)");
        double totalVendas = gato.nextDouble();

        System.out.println("Informe o salário fixo (R$): ");
        double salarioFixo = gato.nextDouble();

        System.out.println("Informe o valor de cada carro vendido: (R$)");
        double valorVendaCarros = gato.nextDouble();

        System.out.println("Informe o valor fixo de comissão por carro: ");
        int comissao = gato.nextInt();

       double finalVendas = totalVendas * 0.05;
       double finalCarros = carros * comissao;

       double salarioFinal = finalVendas + finalCarros + salarioFixo;

        System.out.println("Salário total: R$ "+salarioFinal);
        

    }

    }


**6 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe a temperatura em Fahrenheit (°F): ");
        double tempFahrenheit = gato.nextDouble();

        double celsius = (tempFahrenheit - 32) / 1.8;

        System.out.println("A temperatura em celsius é: "+celsius+ "°C");

    }

    }


**7 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe um número: ");
        int num = gato.nextInt();

        if (num > 10) {
            System.out.println("É MAIOR QUE 10!");

        } else if (num == 10) {
            System.out.println("O NÚMERO É IGUAL A 10!");

        } else {
            System.out.println("NÃO É MAIOR QUE 10!");

        }

    }

    }


**8 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe um número: ");
        int num = gato.nextInt();

        if (num >= 0) {
            System.out.println("Positivo!");
        } else if (num < 0) {
            System.out.println("Negativo!");
        }

    }

    }


**9 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe a quantidade de maçãs a serem compradas:");
        int maca = gato.nextInt();

        if (maca < 12) {
            double valor = maca * 1.3;
            System.out.println("O valor total é de R$ "+valor);

        } else if (maca >= 12) {
            double valor = maca * 1;
            System.out.println("O valor total é de R$ "+valor);
        }

    }
}


**10 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe a 1ª nota:");
        double nota1 = gato.nextDouble();

        System.out.println("Informe a 2ª nota:");
        double nota2 = gato.nextDouble();

        double media = (nota1 + nota2) / 2;

        System.out.println("Média = " + media);

        if (media >= 6) {
            System.out.println("Aprovado!");
        } else if (media < 6) {
            System.out.println("Reprovado!");
        }
    }
}


**11 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o ano atual:");
        int ano = gato.nextInt();

        System.out.println("Informe o ano de nascimento:");
        int anoNascimento = gato.nextInt();

        int anoVoto = ano - anoNascimento;

        System.out.println("Você tem "+anoVoto+" anos");

        if (anoVoto >= 16) {
            System.out.println("Você poderá votar este ano!");

        } else {
            System.out.println("Você não poderá votar este ano!");
        }

    }
}

**12 -**
        
        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe um valor: ");
        int num1 = gato.nextInt();

        System.out.println("Informe outro valor (diferente do primeiro informado):");
        int num2 = gato.nextInt();

        double maior = Math.max(num1,num2);

        System.out.println("O maior número é: "+maior);

    }
}


**13 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o primeiro valor:");
        int valor1 = gato.nextInt();

        System.out.println("Informe o segundo valor:");
        int valor2 = gato.nextInt();

        int menor, maior;
        if (valor1 < valor2) {
            menor = valor1;
            maior = valor2;
        } else {
            menor = valor2;
            maior = valor1;
        }

        System.out.println("Valores em ordem crescente: " + menor + ", " + maior);
    }
}


**14 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Digite a hora de início do jogo (apenas horas inteiras):");
        int horaInicio = gato.nextInt();

        System.out.println("Digite a hora de fim do jogo (apenas horas inteiras):");
        int horaFim = gato.nextInt();

        int duracao;
        if (horaInicio < horaFim) {
            duracao = horaFim - horaInicio;
        } else {
            duracao = 24 - horaInicio + horaFim;
        }

        System.out.println("A duração do jogo é de " +duracao+ " horas.");

    }
}


**15 -**

        import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner gato = new Scanner(System.in);

        System.out.println("Informe o n° de horas trabalhadas em um mês:");
        int horasTrabalhadas = gato.nextInt();

        System.out.println("Informe o salário por hora:");
        double salarioPorHora = gato.nextDouble();

        double salarioTotal;
        if (horasTrabalhadas <= 40 * 4) {
            salarioTotal = horasTrabalhadas * salarioPorHora;
        } else {
            int horasExtras = horasTrabalhadas - 40 * 4;
            salarioTotal = (40 * 4 * salarioPorHora) + (horasExtras * salarioPorHora * 1.5);
        }

        System.out.println("O salário total do funcionário é de R$" + salarioTotal);
    }
}
        
        
        
