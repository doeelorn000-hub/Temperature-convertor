#include <iostream>

int main() {
    double celsius, fahrenheit;

    // 1. Ask the user to input a temperature in Celsius
    std::cout << "Enter temperature in Celsius: ";
    std::cin >> celsius;

    // 2. Convert it to Fahrenheit using the formula: F = (C * 1.8) + 32
    fahrenheit = (celsius * 1.8) + 32;

    // 3. Output the result
    std::cout << "The temperature in Fahrenheit is: " << fahrenheit << "°F" << std::endl;

    // 4. Bonus: Logical checks for Freezing or Hot conditions
    if (celsius < 0) {
        std::cout << "Freezing!" << std::endl;
    } 
    else if (celsius > 30) {
        std::cout << "Hot!" << std::endl;
    }

    return 0;
}
