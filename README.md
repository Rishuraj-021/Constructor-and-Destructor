# Constructor-and-Destructor
## Aim:
To study and implement the concept of constructor and destructor in C++ for automatic object initialization and cleanup.

## Theory:

In C++, object-oriented programming (OOP) allows us to create objects that represent real-world entities. Each object may need initialization at the time of creation and cleanup when it is no longer needed. This is achieved using constructors and destructors.

### 1. Constructor

A constructor is a special member function of a class that is executed automatically whenever an object of the class is created.

The name of the constructor is the same as the class name, and it does not return any value.

It provides a convenient way to initialize data members of a class.

If no constructor is defined, the C++ compiler provides a default constructor automatically.

#### Types of Constructors:

Default Constructor – initializes objects with default values (no arguments).

Parameterized Constructor – takes arguments to initialize objects with specific values.

Copy Constructor – initializes an object as a copy of another object of the same class.

#### Key Features:

Automatically invoked at the time of object creation.

Can be overloaded to provide multiple ways of initializing objects.

### 2. Destructor

A destructor is also a special member function of a class, called automatically when an object goes out of scope, or is deleted.

The name of the destructor is the same as the class name but prefixed with a tilde (~).

It has no arguments and no return type.

It is mainly used to free resources, such as memory or file handles, that were allocated to an object.

Only one destructor is allowed per class, and it cannot be overloaded.

#### Difference Between Constructor and Destructor

Constructor = Initialization of object

Destructor = Cleanup/De-allocation of object



## Conclusion

Constructors and destructors in C++ help in automatic initialization and cleanup of objects.
They improve code efficiency, readability, and memory management by reducing the need for manual function calls during object creation and destruction.
