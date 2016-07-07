# readme {
_You can put some badges here_
> Here's a short description of my project

I also have a longer summary here so I can provide more details

## Table of Contents
1. [Installation](#installation)
1. [Usage](#usage)
1. [Documentation](#documentation)
  1. [Person](#person)
  1. [Dog](#dog)
1. [Person](#person-1)
1. [Dog](#dog-1)
1. [License](#license)

## Installation
Explain how to install your project. For example (this isn't my package):
```javascript
npm install readme
```

## Usage
Explain how to build/run your project. For example:
```javascript
npm run start
```

## Documentation
If your project has an API, you can include documentation. Let's say for the sake of example, this readme project has two JavaScript classes called `Person` and `Dog`. We could document their public methods as follows.

### Person
- [`sayName`](#sayname) - Logs the Person's name to the console.
- [`sayAge`](#sayage) - Logs the Person's age to the console. 

### Dog
- [`bark`](#bark) - Logs the Dog's bark to the console.

## Person
The Person class contains only non-static methods, so an instance of the class must be created to be used. The constructor takes the following arguments:
```javascript
new Person(name, age)
```
For example:
```javascript
const zack = new Person('Zack', 20);
```

### sayName()
This method logs the name of the Person.
```javascript
zack.sayName();
// < - 'My name is Zack!'
```

### sayAge()
This method logs the age of the Person.
```javascript
zack.sayAge();
// < - 'I am 20 years old!'
```

## Dog
The Dog class contains only non-static methods, so an instance of the class must be created to be used. The constructor takes the following arguments:
```javascript
new Dog(name, barkSound)
```
For example:
```javascript
const millie = new Dog('Millie', 'ruffff');
```

### bark()
This method logs the bark sound of the Dog.
```javascript
millie.bark();
// < - 'ruffff'
```

## License
2016 © [Zack Harley][]
> :fork_and_knife:Fork away!

# }

[]: https://github.com/zackharley
