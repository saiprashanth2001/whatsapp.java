import java.util.Scanner;

public class WhatsAppSimulation {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("WhatsApp Simulator");
        System.out.print("Enter your name: ");
        String sender = scanner.nextLine();

        System.out.print("Enter recipient's name: ");
        String recipient = scanner.nextLine();

        System.out.print("Enter your message: ");
        String message = scanner.nextLine();

        System.out.println("\nSending message...");
        System.out.println("--------------------------");
        System.out.println("From: " + sender);
        System.out.println("To: " + recipient);
        System.out.println("Message: " + message);
        System.out.println("--------------------------");
        System.out.println("Message sent successfully!");
    }
}
