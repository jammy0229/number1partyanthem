import java.util.Scanner;

public class t {
    public static void main(String[] args) throws InterruptedException {
        Scanner scanner = new Scanner(System.in);
        String[] lyrics = {
            "I text a postcard, sent to you",
            "Did it go through?",
            "Sending all my love to you",
            "You are the moonlight of my life",
            "every night",
            "Giving all my love to you"
        };
        System.out.println("nyarks");
        for (String line : lyrics) {
            scanner.nextLine();  
            printSlowly(line, 50);  
            System.out.println();  
        }

        scanner.close();
    }
    public static void printSlowly(String text, int charDelay) throws InterruptedException {
        for (char c : text.toCharArray()) {
            System.out.print(c); 
            Thread.sleep(charDelay); 
        }
    }
}
