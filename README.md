# HelloWord

public class HelloWord2 {

  public static void main(String[] args) {  
     String ambiente = args [0];
     if (ambiente.equalsIgnoreCase("DEV")){
         System.out.print("Executando em DEV");
     } else if (ambiente.equalsIgnoreCase("TESTE")){
         System.out.print("Ambiente de TESTE");
     }  else {
         System.out.print(ambiente);
     }
     
  }       
}