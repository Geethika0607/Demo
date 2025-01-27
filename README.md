# App.java
# This is a test commit
public class App {

    // Method to add two numbers
    public static int add(int a, int b) {
        return a + b;
    }

    // Method to test the add() functionality
    public static void testAdd() {
        // Assertions to check if add() works correctly
        assert add(1, 2) == 3 : "Test Case 1 Failed";
        assert add(1, -1) == 0 : "Test Case 2 Failed";
        System.out.println("All Test Cases Passed!");
    }

    // Main method
    public static void main(String[] args) {
        // Run the test cases
        testAdd();
    }
}


       
