import java.util.Scanner;

public class ChatBot {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input;

        System.out.println("Hello! I am a simple chatbot. Type 'bye' to exit.");

        while (true) {
            System.out.print("You: ");
            input = sc.nextLine().toLowerCase();

            if (input.contains("hi") || input.contains("hello"))
                System.out.println("Bot: Hello there!");
            else if (input.contains("how are you"))
                System.out.println("Bot: I'm good, thank you!");
            else if (input.contains("bye")) {
                System.out.println("Bot: Goodbye!");
                break;
            } else
                System.out.println("Bot: Sorry, I don't understand.");
        }
    }
}
