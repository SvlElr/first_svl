# first_svl
Sure! Here's a simple code for an application that reminds the user to drink 2 liters of water per day:

water_goal = 2  # 2 liters

total_water_consumed = 0

while total_water_consumed < water_goal:

    print(f"Total water consumed today: {total_water_consumed} liters")

    drink_amount = float(input("Enter how much water you drank in liters: "))

    if drink_amount <= 0:

        print("Please enter a valid amount of water.")

    elif total_water_consumed + drink_amount > water_goal:

        print("You have exceeded your daily water limit. Please enter a lower amount.")

    else:

        total_water_consumed += drink_amount

if total_water_consumed >= water_goal:

    print("Congratulations! You have achieved your daily water goal of 2 liters.")

This code will keep track of the total water consumed by the user and remind them to drink water until they reach their daily goal of 2 liters. Feel free to customize or expand on this code to fit your application's needs!
