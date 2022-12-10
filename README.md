# suggestion
    import java.util.Scanner;
    public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int temp;

        System.out.print(" Sıcaklık giriniz: ");
        temp = input.nextInt();
        if(temp<5){
            System.out.println("Bu sıcaklıkta kayak yapabilirsiniz");
        }
        if((temp>=5) && (temp<=15)) {
            System.out.println("Bu sıcaklıkta sinemaya gidebilirsiniz");
        }
        if((temp>15) && (temp<=25)){
            System.out.println("Bu sıcaklıkta piknik yapabilirsiniz");
        }
        if(temp>25){
            System.out.println("Bu sıcaklıkta yüzebilirsiniz");
        }


    }
}



