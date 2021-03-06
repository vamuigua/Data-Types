<strong><h3>Abstraction</h3></strong>
<p>This is the necessary process of reducing an object to its essesences so that only the necessary elements are represented without including implementation details..</p>
<p>Abstraction defines an object interms of its:</p>
<ul>
<li>Properties(attributes)</li>
<li>Behaviour(functionality)</li>
<li>Interface</li>
</ul>
<p>This is done to reduce complexity by providing the neccesary information and increase efficiency</p>
<p>Example of real case scenario:You (the object) are arranging to meet a blind date and are deciding what to tell them so that they can recognize you in the restaurant. You decide to include the information about where you will be located, your height, hair color, and the color of your jacket. This is all data that will help the procedure (your date finding you) work smoothly. You should include all that information. On the other hand, there are a lot of bits of information about you that aren't relevant to this situation: your social security number, your admiration for obscure films, and what you took to "show and tell" in fifth grade are all irrelevant to this particular situation because they won't help your date find you.</p>
<p>In Java, abstraction is achieved using <strong>abstract classes</strong>and <strong>interfaces</strong>.</p>
<p>An abstract class is defined using the<strong>'abstract'</strong> keyword.
<p>- If a class is declared abstract it cannot be instantiated (you cannot create objects of that type).</p>
<p>- To use an abstract class, you have to inherit it from another class.</p>
<p>- Any class that contains an abstract method should be defined as abstract.</p>
<p>An abstract method is a method that is declared without an implementation (without braces, and followed by a semicolon):<strong>abstract void walk();</strong><p>
<strong><h3>Abstract Class</h3></strong>
<p>Example:</p>
	abstract class Animal {
	  int legs = 0;
	  abstract void makeSound();
	}
<p><strong>The Animal class</strong> and <strong>makeSound</strong> are abstract.</p>
