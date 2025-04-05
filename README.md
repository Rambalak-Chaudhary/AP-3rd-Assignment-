Java Code:

public class CircleAreaCalculator {

    // Method to calculate the area of a circle
    public static double getCircleArea(double radius) {
        return Math.PI * radius * radius;
    }

    public static void main(String[] args) {
        double radius = 5.0;
        double area = getCircleArea(radius);

        System.out.println("Radius: " + radius);
        System.out.println("Area of the circle: " + area);
    }
}
