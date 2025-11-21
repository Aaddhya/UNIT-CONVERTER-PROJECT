# UNIT-CONVERTER-PROJECT
def kg_to_gram(kg):
    return kg * 1000

def km_to_meter(km):
    return km * 1000

def c_to_f(c):
    return (c * 9/5) + 32

while True:
    print("\n--- UNIT CONVERTER ---")
    print("1. Convert KG to Grams")
    print("2. Convert KM to Meters")
    print("3. Convert Celsius to Fahrenheit")
    print("4. Exit")

    choice = input("Enter your choice (1-4): ")

    if choice == "1":
        kg = float(input("Enter value in kilograms: "))
        print("In grams:", kg_to_gram(kg))

    elif choice == "2":
        km = float(input("Enter value in kilometers: "))
        print("In meters:", km_to_meter(km))

    elif choice == "3":
        celsius = float(input("Enter temperature in Celsius: "))
        print("In Fahrenheit:", c_to_f(celsius))

    elif choice == "4":
        print("Thank you for using the Unit Converter!")
        break

    else:
        print("Invalid choice, please try again.")
