user_input = input("Enter numbers separated by space: ")
numbers = list(map(int, user_input.split()))
for num in numbers:
    if num % 2 == 0:
        print(num)
