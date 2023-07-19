Weight=float(input('enter weight in kgs:')
height=float(input('enter height in mtrs:')
Waist=float(input('enter your waist length in cms:')
BMI=weight/(height*height)
x=input('enter your gender:')
M=['Male']
F=['Female']
if(BMI>=18.5):
  print('The person is overweight')
elif(BMI>18.5 and BMI<=24.9):
  print('The person is healthy')
elif(BMI>25 and BMI<=29.9):
  print('The person is overweight')
else:
  print('The person is obese')
if x in M:
   if(waist>40):
       print('prone to diseases and have to start a healthy diet')
   else:
       print('The person is healthy')
if x in F:
   if(waist>35):
       print('prone to disease and have to start a healthy diet')
  else:
       print('The person is healthy')

