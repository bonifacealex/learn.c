//program to clculate simple interest
int main() {
    float principal, rate, time, interest;

    #ifdef USE_PREDEFINED_VALUES
        interest = SIMPLE_INTEREST();
        printf("Using predefined values, the Simple Interest is: %.2f\n", interest);
    #else
        printf("Enter the principal amount: ");
        scanf("%f", &principal);
        printf("Enter the rate of interest: ");
        scanf("%f", &rate);
        printf("Enter the time period (in years): ");
        scanf("%f", &time);

        interest = SIMPLE_INTEREST(principal, rate, time);
        printf("The Simple Interest is: %.2f\n", interest);
    #endif

    return 0;
}
