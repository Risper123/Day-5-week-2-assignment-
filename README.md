# Day-5-week-2-assignment-
Assignment for week 2 day 5
Create a class representing anything you like (a Smartphone, Book, or even a Superhero!).
Add attributes and methods to bring the class to life!
Use constructors to initialize each object with unique values.
Add an inheritance layer to explore polymorphism or encapsulation.
Activity 2: Polymorphism Challenge! 🎭

class Superhero:
    def __init__(self, name, superpower, origin, alter_ego):
        self.name = name
        self.superpower = superpower
        self.origin = origin
        self.alter_ego = alter_ego
    
    def display_info(self):
        print(f"Superhero Name: {self.name}")
        print(f"Alter Ego: {self.alter_ego}")
        print(f"Superpower: {self.superpower}")
        print(f"Origin: {self.origin}")
    
    def perform_action(self):
        print(f"{self.name} is using their superpower, {self.superpower}!")
        
    def save_the_day(self):
        print(f"{self.name} is saving the day from danger!")

# Example of creating a superhero object
spiderman = Superhero(name="Spider-Man", superpower="Web-slinging and wall-crawling", origin="Radioactive Spider Bite", alter_ego="Peter Parker")

# Displaying superhero information
spiderman.display_info()
spiderman.perform_action()
spiderman.save_the_day()

Create a program that includes animals or vehicles with the same action (like move()). However, make each class define move() differently (for example, Car.move() prints "Driving" 🚗, while Plane.move() prints "Flying" ✈️).

class Animal:
    def move(self):
        print("Moving")

class Dog(Animal):
    def move(self):
        print("Running 🐕")

class Fish(Animal):
    def move(self):
        print("Swimming 🐟")

class Vehicle:
    def move(self):
        print("Moving")

class Car(Vehicle):
    def move(self):
        print("Driving 🚗")

class Plane(Vehicle):
    def move(self):
        print("Flying ✈️")

class Boat(Vehicle):
    def move(self):
        print("Sailing 🚤")
        
