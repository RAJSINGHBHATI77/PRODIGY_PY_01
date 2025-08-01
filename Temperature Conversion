def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

def celsius_to_kelvin(celsius):
    return celsius + 273.15

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9

def fahrenheit_to_kelvin(fahrenheit):
    return (fahrenheit - 32) * 5/9 + 273.15

def kelvin_to_celsius(kelvin):
    return kelvin - 273.15

def kelvin_to_fahrenheit(kelvin):
    return (kelvin - 273.15) * 9/5 + 32

print("🔁 Temperature Converter 🔁")
value = float(input("Enter the temperature value: "))
unit = input("Enter the unit (C, F, K): ").strip().upper()

if unit == "C":
    print(f"Fahrenheit: {celsius_to_fahrenheit(value):.2f} °F")
    print(f"Kelvin: {celsius_to_kelvin(value):.2f} K")
elif unit == "F":
    print(f"Celsius: {fahrenheit_to_celsius(value):.2f} °C")
    print(f"Kelvin: {fahrenheit_to_kelvin(value):.2f} K")
elif unit == "K":
    print(f"Celsius: {kelvin_to_celsius(value):.2f} °C")
    print(f"Fahrenheit: {kelvin_to_fahrenheit(value):.2f} °F")
else:
    print("❌ Invalid unit. Please enter C, F, or K.")
