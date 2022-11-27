This is the first step towards building our first full web application: the AirBnB clone.


The parent class (called BaseModel) takes care of the initialization, serialization and deserialization of the future instances

A simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file is created

All classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel is created

The first abstracted storage engine of the project: File storage is created

All unittests to validate all our classes and storage engine is created
