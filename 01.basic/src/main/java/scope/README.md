# Define the scope of variables 

Scope of variables:
* class, instance, local, and method parameters.
* Local variables: definidas dentro método. Variables definidas dentro de bucle son locales.
* Scope variable local es menor scope de varibae método method si definido en sub bloqueen un método.
* Local variables no pueden ser accesibles desde fuera de método en el cual están definidas 
* In a method, a local variable can’t be accessed before its declaration.
* Instance variables are defined and accessible within an object. They’re accessible to all the instance methods of a class.
* Class variables are shared by all the objects of a class—they can be accessed even
if there are no objects of the class.
* Method parameters are used to accept arguments in a method. Their scope is
limited to the method where they’re defined.
* A method parameter and a local variable can’t be defined using the same name.
* Class and instance variables can’t be defined using the same name.
* Local and instance variables can be defined using the same name. In a method,
if a local variable exists with the same name as an instance variable, the local
variable takes precedence