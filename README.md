# Module_5_Exercises
import random
num_dice = int(input("How many dice would like to roll? "))
total_sum = 0
for i in range(num_dice):
    roll = random.randint(1, 6)
    total_sum += roll
print(f"You rolled {num_dice} dice.")
print(f"The total sum of the rolls is: {total_sum}")
import math
numbers = []
user_number = input("Enter a number: ")
while user_number != "":
    numbers.append(int(user_number))
    user_number = input("Enter a number: ")
    if user_number == "":
        break
print(numbers)
numbers.sort (reverse = True)
print(numbers)
print(numbers[0:5])
number = int(input("Enter an integer: "))
if number <= 1:
    print(number, "is not a prime number")
else:
    is_prime = True
    for i in range(2, number):
        if number % i == 0:
            is_prime = False
            break
    if is_prime:
        print(number, "is a prime number")
    else:
        print(number, "is not a prime number")
cities = []
for i in range(5):
    city = input("Enter the name of a city: ")
    cities.append(city)
print("\nCities you entered:")
for city in cities:
    print(city)
