#Mastering Markdown

[My favorite sub](reddit.com/r/skyrimmods)

![Some Skyrim bug](https://media.giphy.com/media/em6UdqRhuY4Ao/giphy.gif)  
  




	public class Car {
    double mSpeed = 0.0;
    String model;

    public Car(String model) {
        this.model = model;
    }

    public double getSpeed () {
        return mSpeed;
    }

    public void setSpeed(double speed) {
        mSpeed = speed;
    }

    public static void main(String[] args) {
        // creating a new object of type Car
        Car firstCar = new Car ("DeLorean");

        firstCar.setSpeed(7.7d);
        System.out.println("The speed is " + firstCar.getSpeed());
    }}


##A breakfast list

1. Eggs
2. Bacon
3. Hash Browns
4. Waffles

##Aug 3
###Classes/Objects
Most objects are defined by a class

Classes are containers of code, and allow that code to be reusable across the app 

**Constructor methods** do not need to define a return type, and they always share a name with their class

**Setter and getters** allow you to change variables without making changes to the class

