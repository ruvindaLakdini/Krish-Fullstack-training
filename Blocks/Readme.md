Static block

A static block only run once when a class is loaded into the memory.

It doesn't matter what order we put the static block since it is always executed first.

Static block can be executed before executing constructors or empty blocks (instance blocks).

We can have any number of static blocks. They will be executed in the order they are placed in the code.

We can initialize and access static variables inside static blocks but we can't access instance variables inside static blocks.





Instance block

An instance block is executed whenever an instance is created(Ex:- when an object of a class is created)

It is always executed before the execution of constructors so the order of placement doen't matter. We can put them either before or after the constructors.





Constructors


Constructors run each time a new instance of a class is created.

We can create multiple constructors with different argument lists. Then the running constructor is selected by the parameters passed when creating that particular instance.

A particular constructor of an object is executed after the execution of all instance blocks in the code.

