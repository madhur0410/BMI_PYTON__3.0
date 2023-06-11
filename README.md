# BMI_PYTON__3.0
name = input("enter your name")
weight = int(input("enter your weight in pounds "))
height = int(input("enter your height in inches "))
bmi = (weight * 703) / (height * height)
print (bmi)
if bmi > 0:
  if (bmi < 18.5):
    print("underweight")
  
  elif ( bmi >= 18.5 and bmi < 24.9):
    print("Healthy")
    
  elif ( bmi >= 24.9 and bmi < 30):
    print("overweight")
  
  elif ( bmi >=30):
    print("Suffering from Obesity") 
else:
  print ("enter valid input")
