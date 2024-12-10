import java.util.Scanner;

class SampleArray {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String arr[] = new String[5];
        for (int i = 0; i < 5; i++) {
            System.out.println("Enter the name of employee no: " + (i + 1));
            arr[i] = sc.next(); 
        }
        System.out.println("\nEmployee Names:");
        for (String name : arr) {
            System.out.println(name); 
        }
        
        sc.close();  
  }  
}
