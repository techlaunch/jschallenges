# Here is a list of students
Probably any school has a list of students like the following, maybe more extense and comprehensive. 
```
var students = [{
	name: "Salvi",
	gpa: 4.0,
	class: "WEB1100"
},{
	name: "Jeronimo",
	gpa: 1.3,
	class: "WEB1010"
},{
	name: "Cachito",
	gpa: 1.4,
	class: "WEB1010"
},{
	name: "Maria",
	gpa: 2.3,
	class: "WEB1100"
}];
```

For any of the challenges below, your code has to work even if we make any updates to the list of students or add/remove students on the list.

# Challenge #1
Display the name of all students which GPA is lower than 2 in a unordered list. Your code has to result on the example below:

* Jeronimo
* Cachito

# Challenge #2
Create a table with the headers "Student", "GPA" and "Class". Display all the students from the list matching the object field to the three columns of the table. Your code has to result on the example below:

Student  | GPA  | Class
------------- | ------------- | -------------
Salvi  | 4.0  | WEB1100
Jeronimo  | 1.3  | WEB1010
Cachito  | 1.4  | WEB1010
Maria  | 2.3  | WEB1100


# Challenge #3
Display the name of all students in a unordered list grouped by class name. Your code has to result on the example below:

* WEB1100
    * Salvi
    * Maria
* WEB1010
    * Jeronimo
    * Cachito
