#include <stdio.h>
#include <math.h>

void menu() {
    printf("\n===== SCIENTIFIC CALCULATOR =====\n");
    printf("1. Addition\n");
    printf("2. Subtraction\n");
    printf("3. Multiplication\n");
    printf("4. Division\n");
    printf("5. Power (x^y)\n");
    printf("6. Square Root\n");
    printf("7. Sine (sin x)\n");
    printf("8. Cosine (cos x)\n");
    printf("9. Tangent (tan x)\n");
    printf("10. Log base 10\n");
    printf("11. Natural Log (ln x)\n");
    printf("12. Exit\n");
    printf("Choose an option: ");
}

int main() {
    int choice;
    double a, b, result;

    while (1) {
        menu();
        scanf("%d", &choice);

        switch (choice) {

        case 1:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &a, &b);
            result = a + b;
            printf("Result = %.4lf\n", result);
            break;

        case 2:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &a, &b);
            result = a - b;
            printf("Result = %.4lf\n", result);
            break;

        case 3:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &a, &b);
            result = a * b;
            printf("Result = %.4lf\n", result);
            break;

        case 4:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &a, &b);
            if (b == 0)
                printf("Error! Division by zero.\n");
            else {
                result = a / b;
                printf("Result = %.4lf\n", result);
            }
            break;

        case 5:
            printf("Enter base and exponent: ");
            scanf("%lf %lf", &a, &b);
            result = pow(a, b);
            printf("Result = %.4lf\n", result);
            break;

        case 6:
            printf("Enter a number: ");
            scanf("%lf", &a);
            if (a < 0)
                printf("Error! Cannot find square root of negative number.\n");
            else {
                result = sqrt(a);
                printf("Result = %.4lf\n", result);
            }
            break;

        case 7:
            printf("Enter angle in degrees: ");
            scanf("%lf", &a);
            result = sin(a * M_PI / 180);
            printf("sin(%.2lf) = %.4lf\n", a, result);
            break;

        case 8:
            printf("Enter angle in degrees: ");
            scanf("%lf", &a);
            result = cos(a * M_PI / 180);
            printf("cos(%.2lf) = %.4lf\n", a, result);
            break;

        case 9:
            printf("Enter angle in degrees: ");
            scanf("%lf", &a);
            result = tan(a * M_PI / 180);
            printf("tan(%.2lf) = %.4lf\n", a, result);
            break;

        case 10:
            printf("Enter a number: ");
            scanf("%lf", &a);
            if (a <= 0)
                printf("Error! Logarithm undefined for zero or negative values.\n");
            else {
                result = log10(a);
                printf("log(%.2lf) = %.4lf\n", a, result);
            }
            break;

        case 11:
            printf("Enter a number: ");
            scanf("%lf", &a);
            if (a <= 0)
                printf("Error! Natural log undefined for zero or negative values.\n");
            else {
                result = log(a);
                printf("ln(%.2lf) = %.4lf\n", a, result);
            }
            break;

        case 12:
            printf("Exiting...\n");
            return 0;

        default:
            printf("Invalid choice! Try again.\n");
        }
    }

    return 0;
}
