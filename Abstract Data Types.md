<strong><h3>Abstract Data Types(ADTs)</h3></strong>
<p>These are mathematical models of a set of data values or information that share similar behavior or qualities and that can be specified and identified independent of specific implementations.</p>
<p>An abstract data type is defined in terms of its data items or its associated operations rather than by its implementation.</p>
<h3><strong>Using abstract data types.<strong></h3>
<p><strong>1.Creating objects</strong>-Each data-type value is stored in an object.To create(instantiate) an individual object, we invoke a constructor by using the keyword <strong>'new'</strong>. Each time that a client uses 'new', the system allocates memory space for the object, initializes its value, and returns a reference to the object. E.g:</p><br>
	
	Counter heads = new Counter("heads");

<p>On the first part,its a declaration to associate the variable with the object reference.While in the second part,it calls on the constructor to create an object.</p><br>
<p><strong>2.Invoking instance methods</strong></p>



