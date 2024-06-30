
import java.util.Scanner;

public class Main {
    
    public static void main(String[] args) {
         Scanner input=new Scanner(System.in);
        double obtainedValor=0, totalValor=0;
        float Porcento;
        
        System.out.println("Descubra a porcentagem!");
        System.out.println("Digite o Valor atingido:");
        obtainedValor = input.nextDouble();
        System.out.println("Digite o valor meta ");
        totalValor = input.nextDouble();
        
        Porcento = (float) ((obtainedValor*100)/ totalValor);
        
        System.out.println("São" +Porcento+"%");
    }
    
    
}
