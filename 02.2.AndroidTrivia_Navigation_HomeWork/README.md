1. How do you enable your project to use navigation components?
==> Answer: Add dependencies for navigation-fragment-ktx and navigation-ui-ktx
in the build.gradle (module) file.

2. Where are the possible routes through your app defined?
==> Answer: In a file (often called navigation.xml) in the res > navigation folder.

3. Which of the following statements about the NavHostFragment are true? Select all that apply.
==> Answer: 
   - As the user moves between destinations defined in the navigation graph,
the NavHostFragment swaps the fragments in and out as necessary.
   - You must create a single NavHostFragment subclass and implement the 
onNavigate() method to handle different kinds of navigation (such as button clicks).

4. Which of the following statements about the navigation graph are true? Select all that apply.



