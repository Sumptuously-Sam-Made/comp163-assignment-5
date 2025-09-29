# comp163-assignment-5
step_count = 0
current_number = int(input("Enter starting number: "))
print("Enter starting number:", current_number)
print("Sequence:", end=" ")
# Check if current number is not equal to 1
while current_number != 1:
    # Calculation for Evens
    if current_number % 2 == 0:
        print(current_number, end=" ")
        current_number = int(current_number / 2)
        step_count += 1
    # Calculation for Odds
    elif current_number % 2 == 1:
        print(current_number, end=" ")
        current_number = int(current_number * 3 + 1)
        step_count += 1
print(1, end=" ")
print("\nSteps:", step_count)
