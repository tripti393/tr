import java.util.Scanner;
public class QuizApp {
    private static String[] questions = {
        "What is the capital of France?",
        "Which planet is known as the Red Planet?",
        "What is the largest mammal in the world?",
        // Add more questions here
    };

    private static String[] answers = {
        "Paris",
        "Mars",
        "Blue Whale",
        // Add corresponding answers here
    };

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int score = 0;

        System.out.println("Welcome to the Quiz App!");
        System.out.println("Answer the following questions:");

        for (int i = 0; i < questions.length; i++) {
            System.out.println(questions[i]);
            String userAnswer = scanner.nextLine();
            if (userAnswer.equalsIgnoreCase(answers[i])) {
                System.out.println("Correct!");
                score++;
            } else {
                System.out.println("Wrong! The correct answer is: " + answers[i]);
            }
        }
        System.out.println("Quiz completed!");
        System.out.println("Your score: " + score + " out of " + questions.length);
    }
}
