# BMI
Weight= int(input("What is your weight?"))
Height= float(input("What is your height?"))
x = Weight/Height**2
if x <=18.5:
    print("Underweight")
elif x >=18.5 and x < 25:
    print("Normal")
elif x >=25 and x < 30:
    print("Overweight")
elif x >30:
    print("Obese")
