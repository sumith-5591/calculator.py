def additon(x,y):
  return x+y
def subtraction(x,y):
  return x-y
def multiplication(x,y):
  return x*y
def division(x,y):
  if y!=0:
    return x/y
  else:
    return "Error: Division by zero"

def calculator():
  print("Simple Calculator")
  print("Choose Operation:")
  print("1.Additon")
  print("2.Subtraction")
  print("3.Multiplication")
  print("4.Division")

  while True:
    choice = input("Enter choice (1/2/3/4): ")

    if choice in ('1','2','3','4'):
      num1 = float(input("Enter first number: "))
      num2 = float(input("Enter second number: "))

      if choice == '1':
        print("Result:", additon(num1,num2))
      elif choice=='2':
        print("Result:", subtraction(num1,num2))
      elif choice=='3':
        print("Result:", multiplication(num1,num2))
      elif choice=='4':
        print("Result:", division(num1,num2))

      next_calculation=input("Do you want to perform another calculation? (yes/no):")
      if next_calculation.lower()!='yes':
        break
    else:
      print("Invalid input")

calculator()
