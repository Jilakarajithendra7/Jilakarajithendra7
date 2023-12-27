import java.util.Scanner;

public class BudgetTracker {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Get income details
        System.out.print("Enter income amount: ");
        double incomeAmount = scanner.nextDouble();
        scanner.nextLine(); // Consume newline

        // Get expense details
        System.out.print("Enter expense category: ");
        String expenseCategory = scanner.nextLine();

        System.out.print("Enter expense amount: ");
        double expenseAmount = scanner.nextDouble();

        // Process the entries (you can store them in appropriate data structures)
        System.out.println("Income: $" + incomeAmount);
        System.out.println("Expense Category: " + expenseCategory);
        System.out.println("Expense Amount: $" + expenseAmount);

        // Calculate remaining budget (you may have a separate method for this)
        double remainingBudget = incomeAmount - expenseAmount;
        System.out.println("Remaining Budget: $" + remainingBudget);

        // Close the scanner
        scanner.close();
    }
}
import java.util.Scanner;

public class BudgetTracker {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Get income details
        System.out.print("Enter income amount: ");
        double incomeAmount = scanner.nextDouble();
        scanner.nextLine(); // Consume newline

        // Get expense details
        System.out.print("Enter expense category: ");
        String expenseCategory = scanner.nextLine();

        System.out.print("Enter expense amount: ");
        double expenseAmount = scanner.nextDouble();

        // Process the entries (you can store them in appropriate data structures)
        System.out.println("Income: $" + incomeAmount);
        System.out.println("Expense Category: " + expenseCategory);
        System.out.println("Expense Amount: $" + expenseAmount);

        // Calculate remaining budget (you may have a separate method for this)
        double remainingBudget = incomeAmount - expenseAmount;
        System.out.println("Remaining Budget: $" + remainingBudget);

        // Close the scanner
        scanner.close();
    }
}


<!---
Jilakarajithendra7/Jilakarajithendra7 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
