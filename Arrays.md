<h3><strong>Arrays</strong></h3>
<p>
An array is a collection of variables of the same type.</p>
<p>To declare an array,you need to define the type of the elements with <strong>Square Brackets('[]')</strong>For example, to declare an array of integers:</p>
		int[] arr;
<p>The name of the array is <strong>arr</strong>. The type of elements it will hold is <strong>int</strong>.</p>
<p>You also need to define the array's capacity or the number of elements it holds by using the keyword <strong>'new':</strong></p>
		int[ ] arr = new int[5];
<p>the elements are ordered and each has a specific and constant position called an <strong>index</strong>.E.g:</p>
		arr[2] = 32;
<p>This assigns a value of <strong>32</strong> to the element with <strong>2</strong> as its index.</p>
<p><strong>Note that elements in the array are identified with <em>zero-based index numbers</em>, meaning that the <em>first element's index is 0</em> rather than one. So, the maximum index of the array int[5] is 4.</strong></p><br>
<h3>Initializing Arrays</h3>
<p>You can use an array literal,if you know what values to insert into the array,E.g:</p>
		String[ ] myNames = { "A", "B", "C", "D"};
		System.out.println(myNames[2]);

		// Outputs "C"

<h3>Array Length</h3>
<p>You can access the <strong>length</strong> of an array i.e the number of elements it stores; via its <strong>length property</strong>.Example:</p>
		int[ ] intArr = new int[6];
		System.out.println(intArr.length);

		//Outputs 6
