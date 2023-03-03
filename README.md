# loops If/else loops practice 

#create a list called 'cars'
cars = ['toyota','mazda','ferrari','bmw','audi']
for car in cars:
  if car == 'bmw': # if a car's name is 'bmw'
    print (car.upper()) #it will print all the name with capital letters 
  else: #otherwise only the first letter will be capital 
    print (car.title())
