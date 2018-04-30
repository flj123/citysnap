CLASSES
ANONYMOUS FUNCTIONS
(function(window){
	
	function Person(name, address){
		this.name = name;
		this.address = address;
	}

	Person.prototype.sayHello = function(){
		console.log(this.name + " says hello");
	};

	Person.SPECIES = "human";

	window.Person = Person;

}(window));