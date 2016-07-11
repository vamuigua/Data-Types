<strong><h3>Abstract Data Types(ADTs)</h3></strong>
<p>These are mathematical models of a set of data values or information that share similar behavior or qualities and that can be specified and identified independent of specific implementations.</p>
<p>An abstract data type is defined in terms of its data items or its associated operations rather than by its implementation.</p>
<h3><strong>Using abstract data types.<strong></h3>
<p><strong>1.Creating objects</strong>-Each data-type value is stored in an object.To create(instantiate) an individual object, we invoke a constructor by using the keyword <strong>'new'</strong>. Each time that a client uses 'new', the system allocates memory space for the object, initializes its value, and returns a reference to the object. E.g:</p><br>
	
	Counter heads = new Counter("heads");

<p>On the first part,its a declaration to associate the variable with the object reference.While in the second part,it calls on the constructor to create an object.</p><br>
<p><strong>2.Invoking instance methods</strong>- The purpose of an instance method is to operate on data-type values. Instance methods have all of the properties of static methods: arguments are passed by value, method names can be overloaded, they may have a return value and they may cause side effects.They have an additional property that characterizes them: each invocation is associated with an object. E.g:</p><br>
	
	heads.tally() = tails.tally()
<p>The first section invokes an instance method that accesses the object's value.</p>




