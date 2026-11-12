
print("OHM'S LAW AND POWER CALCULATOR")

print("1. Calculate Voltage")
print("2. Calculate Current")
print("3. Calculate Resistance")
print("4. Calculate Power")

choice = int(input("Enter your choice: "))

if choice == 1:
    I = float(input("Enter Current (A): "))
    R = float(input("Enter Resistance (Ohms): "))
    V = I * R
    print("Voltage =", V, "Volts")

elif choice == 2:
    V = float(input("Enter Voltage (V): "))
    R = float(input("Enter Resistance (Ohms): "))
    I = V / R
    print("Current =", I, "Amps")

elif choice == 3:
    V = float(input("Enter Voltage (V): "))
    I = float(input("Enter Current (A): "))
    R = V / I
    print("Resistance =", R, "Ohms")

elif choice == 4:
    V = float(input("Enter Voltage (V): "))
    I = float(input("Enter Current (A): "))
    P = V * I
    print("Power =", P, "Watts")

else:
    print("Invalid choice")
