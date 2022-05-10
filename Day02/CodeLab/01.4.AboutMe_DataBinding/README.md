1 - Why do you want to minimize explicit and implicit calls to findViewById()?

a. Every time findViewById() is called, it traverses the view hierarchy.
b. findViewById() runs on the main or UI thread.
c. These calls can slow down the user interface.
d. Your app is less likely to crash.

==> Answer: d

2 - How would you describe data binding?
For example, here are some things you could say about data binding:

a. The big idea about data binding is to create an object that connects/maps/binds two pieces of distant information together at compile time, so that you don't have to look for the data at runtime.
b. The object that surfaces these bindings to you is called the binding object.
c. The binding object is created by the compiler.


3 - Which of the following is NOT a benefit of data binding?

a. Code is shorter, easier to read, and easier to maintain.
b. Data and views are clearly separated.
c. The Android system only traverses the view hierarchy once to get each view.
d. Calling findViewById() generates a compiler error.
e. Type safety for accessing views.

==> Answer: d

4 - What is the function of the <layout> tag?

a. You wrap it around your root view in the layout.
b. Bindings are created for all the views in a layout.
c. It designates the top-level view in an XML layout that uses data binding.
d. You can use the <data> tag in inside a <layout> to bind a variable to a data class.

==> Answer: c


5 - Which is the correct way to reference bound data in the XML layout?

a. android:text="@={myDataClass.property}"
b. android:text="@={myDataClass}"
c. android:text="@={myDataClass.property.toString()}"
d. android:text="@={myDataClass.bound_data.property}"

==> Answer: a