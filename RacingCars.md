# Welcome to the races

Imagine we have the following array of Car objects:

```
var car = [{
	model: "Camry",
	torque: 24,
	speed: 25.4
},{
	model: "Focus",
	torque: 21,
	speed: 15.8
},{
	model: "Thunderbird",
	torque: 15,
	speed: 45.3
},{
	model: "Fusion",
	torque: 25,
	speed: 40.1
},{
	model: "Al camino",
	torque: 49,
	speed: 10.8
},{
	model: "Tundra",
	torque: 10,
	speed: 12.6
}];
```

First, let's understand the concept of seed. A seed for this example will be a random number between 0.8 and 1.2. We will use the seed to account to account for human errors, weather or other unexpected changes on the environment. 

In a race circuit, a formula to estimate the changes for a car to win is to multiple the torque of a car by the aproximate degree of each curve and by the seed, and then the speed of the car by the aproximate lenght of each straight road and by the seed. Cars with more torque will do better on curvy circuits, and cars with great speed will perform on straight circuits.

![clasic circuit](https://www.clipartmax.com/png/small/120-1200419_race-clipart-flag-png-race-track-clipart-transparent.png|width=100)

For a circuit above, with 4 courves of aproximate 45 degress, 2 roads of 300 meters and 2 small roads of 10 meters, the formula could be:

```
45 * torque * seed + 
45 * torque * seed + 
45 * torque * seed + 
45 * torque * seed + 
300 * speed * seed + 
300 * speed * seed + 
10 * speed * seed + 
10 * speed * seed
```

# Challenge #1
Implement the following funcion checkCarChanges() that receives a Car object, an array of courves and an array of roads and return the car changes.

```
funcion checkCarChanges(car, curves, roads) {
	// your code here
	return chance;
}
```
For the above circuit, the arrays of curves and roads will be as follows:
```
var curves = [45,45,45,45];
var rods = [300,10,300,10];
```

# Challenge #2
Using the circuit shown above, run the funcion for each car on the initial array and display the model on an ordered list, starting by the ones with smaller changes. Add the button "Race!" to start and re-do the races.

# Challenge #3

Create the arrays of curves and roads from the circuit below. Use approximate values. Now run your funcion for each car on the initial array and display the model on an ordered list, starting by the ones with smaller changes. Add the button "Race!" to start and re-do the races. Make sure your interface looks simple but appealing to the user.

![curvy circuit](https://autobahnspeed.com/wp-content/uploads/2016/12/Jessup-Le-Mans.png|width=100)


