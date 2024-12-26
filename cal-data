#include <stdio.h>
#include <math.h>

void calculateOtp(int productSerNum, int otpPin) {
    // Calculate OTP
    int otp4 = 999999 - (((productSerNum * 2) + (((otpPin % 100) * 10000) + (otpPin / 100) + (((otpPin % 100) + (otpPin / 100)) % 100) * 100)) % 1000000);

    // Display the result
    printf("OTP 4: %d\n", otp4);
}

int main() {
    int productSerNum, otpPin;

    // Get user input
    printf("Enter Product Serial Number: ");
    scanf("%d", &productSerNum);

    printf("Enter OTP Pin: ");
    scanf("%d", &otpPin);

    // Calculate and display OTP
    calculateOtp(productSerNum, otpPin);

    return 0;
}
