public class App {
    "Driven <METERS> meters"
    "Battery at <PERCENTAGE>%"
    "Battery empty"
    ElonsToyCar.buy(0%)
    ElonsToyCar car = ElonsToyCar.buy(0%);
    ElonsToyCar.distanceDisplay("Driven 0 meters")
car.distanceDisplay("Driven 0 meters");
// => "Driven 0 meters"
ElonsToyCar.batteryDisplay( "Battery at 100%")
// => "Battery at 100%"
car.drive( "Driven 40 meters");
car.distanceDisplay( "Driven 40 meters");
// => "Driven 40 meters"
car.batteryDisplay("Battery at 98%");
// => "Battery at 98%"
// Drain the battery// ...
car.distanceDisplay("Driven 2000 meters");
// => "Driven 2000 meters"
car.batteryDisplay( "Battery empty");
// => "Battery empty"
    }
}
