print("convert inches to cm: ")
h_ft = int(input("Enter your Feet: "))
h_inch = int(input("Enter your Inches: "))

h_inches += h_ft * 12
h_cm = round(h_inch * 2.54, 1)

print("Your calculated height equals : %d cm." % h_cm)
